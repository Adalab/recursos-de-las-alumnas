# CSS

1. If you have a `<p>` element with font-size: 10rem, will the text be responsive when the user resizes / drags the browser window?

* Yes
* No

2. the pseudo class :checked will select inputs with type radio or checkbox, but not <option> elements.

* True
* False

3. In a HTML document, the pseudo class :root always refers to the <html> element.

* True
* False

4. The translate() function can move the position of an element on the z-axis.

* True
* False


5. What will happen to the position of #example?
```
<p id="example">Hello</p>
#example {
      margin-bottom: -5px;
}
```
* It will move 5px downwards
* All elements succeding #example will move 5px upwards
* Neither

6. Are unused style resources still downloaded by the browser?
```
<div id="test1">
  <span id="test2"></span>
</div>

#i-am-useless {
    background-image: url('mypic.jpg');
}
```
* Yes
* No
* Sometimes

7. On page load, will mypic.jpg get downloaded by the browser?
```
<div id="test1">
  <span id="test2"></span>
</div>

#test1 {
    display: none;
}
#test2 {
    background-image: url('mypic.jpg');
    visibility: hidden;
}
```
* Yes
* No

8. What is the use of the only selector?

```
@media only screen and (max-width: 1024px) {
    margin: 0;
}
```
* Apply the style for screen only and ignore the device max-width
* Stops older browsers from parsing the remainder of the selector
* It does nothing

9. Does ***overflow: hidden*** create a new block formatting context?
```
<div>
    <p>I am floated</p>
    <p>So am I</p>
</div>

div {
    overflow: hidden;
}
p {
    float: left;
}
```
* Yes
* No

# HTML

1. Is `<keygen>`a valid HTML5 tag?

* Yes
* No

2. Is the following HTML valid?
```
<figure>
      <img src="myimage.jpg" alt="My image">
      <figcaption>
              <p>this is my self portrait.</p>
      </figcaption>
</figure>
```
* Yes
* No

3. In what situation should you use the `<small>`tag?

* When you want to create subheading after a `<h1>`element
* When you want to add copyright information inside a `<footer>`
* Both situations

4. If you have a page of search results and want to highlight the search term, what HTML tag would you use?

* `<strong>`
* `<mark>`
* `<rem>`
* `<highlight>

5. What does the scoped attribute do?
```
<article>
    <h1>Hello world</h1>
    <style scoped>
         p {
            color: #FF0;
         }
    </style>
    <p>This is my text</p>
</article>
```
* Applies style rules to elements succeeding it, but with the same parent element
* Applies style rules to all children of the scoped parent element
* Applies style rules to IE browsers only
* None of the above

6. Does the following HTML trigger a http request when the page first loads?
```
<img src="mypic.jpg" style="visibility: hidden" alt="My picture">
```
* Yes
* No

7. Does the following HTML trigger a http request when the page first loads?
```
<div style="display: none;">
    <img src="mypic.jpg" alt="My photo">
</div>
```
* Yes
* No

8. Does main1.css have to be downloaded and parsed before Hello World is alerted?
```
<head>
    <link href="main1.css" rel="stylesheet">
    <script>
        alert('Hello World');
    </script>
</head>
````
* Yes
* No

9. Does main1.css have to be downloaded and parsed before main2.css can be fetched?
```
<head>
    <link href="main1.css" rel="stylesheet">
    <link href="main2.css" rel="stylesheet">
</head>
```
* Yes
* No

# JAVA-SCRIPT

1. What does the following statement evaluate to?
```
"1" + 2 + "3" + 4;
```
* 10
* 1234
* 37

2. What does the following statement evaluate to?
```
4 + 3 + 2 + "1"
```
* 10
* 4321
* 91

3. What is alerted?
```
var foo= 1;
function bar() {
      foo = 10;
      return;
      function foo() {}
}
bar();
alert(foo);
```
* 1
* 10
* Function
* undefined
* Error

4. What is the order of values alerted?
```
var x= 3;
var foo = {
      x: 2,
      baz: {
          x: 1,
          bar: function() {
                return this.x;
          }
      }
 }
 var go = foo.baz.bar;
 aler(go());
 alert(foo.baz.bar());
 ```
 * 1,2
 * 1,3
 * 2,1
 * 2,3
 
 5. What value is alerted?
 ```
 var x = 4,
    obj = {
        x: 3,
        bar: function() {
            var x = 2;
            setTimeout(function() {
                  var x = 1;
                  alert(this.x);
            }, 1000);
        }
     };
 obj.bar();
 ```
 * 1
 * 2
 * 3
 * 4
 * undefined
 
 6. what value is alerted?
 ```
 x = 1;
 function bar() {
      this.x = 2;
      return x;
 }
 var foo = new bar();
 alert(foo.x);
 ```
 * 1
 * 2
 * undefined
 
 7. What value is alerted?
 ```
 function foo(a) {
      alert(arguments.length);
 }
 foo(1, 2, 3);
 ```
 * 1
 * 2
 * 3
 * undefined
 
 8. What value is alerted?
 ```
 var foo = function bar() {};
 alert(typeof bar);
 ```
 * function
 * object
 * undefined
 
 9. What value is alerted?
 ```
 var arr = [];
 arr[0] = 'a';
 arr[1] = 'b';
 arr.foo = 'c';
 alert(arr.length);
 ```
 * 1
 * 2
 * 3
 * undefined
 
 10. What value is alerted?
 ```
 function foo(a) {
    arguments[0] = 2;
    alert(a);
}
foo(1);
```
* 1
* 2
* undefined

11. What value is alerted?
```
function foo(){}
delete foo.length;
alert(typeof foo.length);
```
* number
* undefined
* object
* Error

 






