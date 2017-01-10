# 面试题整理

## 简答题
1. 行内元素有哪些?块级元素有哪些?
> 常用块级元素:  p , div , h1~h6 , form , hr , dl , ol , ul , table <br>
> 常用行内元素: span , a , br , code , i , em , img , input ,label , select , textarea

2. split()和join()的区别
> split(): 一个数组调用这个方法,传入一个String参数,会返回由参数拼接而成的字符串;<br>
> join(): 一个字符串调用这个方法,传入一个String参数,会返回由参数分割的数组;

3. js的typeof()返回哪些数据类型
> number , string , boolean , object , function , undefined

4. 数组方法pop() push() unshift() shift()的区别
> pop(): 删除数组最末尾的值,返回值是被删除的值;<br>
push(): 在数组末尾添加传的参数,返回值是添加进去的值;<br>
unshift(): 在数组最前端插入传的参数,返回值是添加进去的值;<br>
shift(): 删除数组最前端的值,返回值是被删除的值;

5. ajax请求的时候get和post方式的区别
> get: 参数会在url中显示,GET方式传送数据量小，处理效率高，安全性低，会被缓存;<br>
post: 浏览器会把所有表单字段作为参数发送给服务器,并不会显示在url中,可传送数据量大,安全性较好,不会被缓存;

6. call和apply的区别
> call(): 两者相同点在于都是可以借用另一个对象的方法,从而改变方法的this指向.区别在于call向方法传递确定数量的参数<br>
apply():而apply需要传递一个数组参数,并且会自动遍历数组里的参数一一传入借用的方法,当不确定参数数量时用apply

7. ajax请求时如何解析json数据
> json.parse()方法可以把json字符串解析为对象

8. document.ready事件和document.load事件的区别
> 两者都是页面加载完成后触发的事件,区别在于ready表示文档结构加载完成,但是不包括图片等,而load则包括图片在内页面中所有的东西都加载完成后才触发


## 程序题
1. 排序算法(任选一种用js实现)