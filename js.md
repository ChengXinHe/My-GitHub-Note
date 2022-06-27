# JavaScript

* **常见函数**
  >console.log("learn")
  >alert("miao")
  >prompt("age")
* **variables**
* **const**
  >const不能reassignment，不能redeclaration
* **let**
  > let x=2声明变量
  >let可以reassignment，不能redeclaration

* **var**
   
* **String和Number**
  >String+String会直接连接concat
  >n1=20;n2=30;name=Xinhe;n3=10;n4=15
  n1+n2+n3+n4+n5=50Xinhe1015
* **Window and Document**
  >是js中两个重要的object
  >HTML DOM 的 document 也是 window 对象的属性之一：
  `window.document.getElementById("header");`
* **DOM**
  >HTML DOM (文档对象模型)当网页被加载时，浏览器会创建页面的文档对象模型（Document Object Model）。
  >HTML DOM 模型被构造为对象的树：
![alt 属性文本](https://www.runoob.com/images/pic_htmltree.gif)
  >javascrpit get elemnent from html by
  `document.querySelector(h1.second)` 只会抓到遇见的第一个符合标准的
  `document.querySelectorAll(.second)`返回一个nodeList

* **Arrow Function Experssion 和 function declaration**
  >arrow没有this这个keyword，arrow中的this指的是window这个object
  >arrow不能先调用再声明
  >`let Wilson ={`
    `name:'wilson Ren',`
  `greeting(){`
        `console.log("Hi"+this.name);`
        `},`
        `walk:()=>{`
        `console.log(this.name);}`
        `}`

* **for each**
  >`const numbers = [65, 44, 12, 4];`
  >`numbers.forEach(myFunction)`
  >`function myFunction(item, index, arr) {`
  `arr[index] = item * 10;`
`}`
  >这function叫callback function

* **Array, HTML Collection,NodeList**
  >Array:有length，index
  >push，pop，shift，unshift
  >HTML Collection:document.getelementsbyclassName返回一个的
  >不能push,pop等
  >NodeList:document.querySelectorAll(.second)返回
  >Array和Nodelist可以用forEach, collection不行

* **The Element Object**
  >https://www.w3schools.com/jsref/dom_obj_all.asp
* **
* **
* **
* **

* **
* **
* **
* **
* **
* **
* **
* **

* **
* **
* **
* **

