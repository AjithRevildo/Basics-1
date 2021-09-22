# day2-js-assesment

1.Browser JS(console) vs Nodejs

Node js :

Node doesn’t have a predefined “window” object cause it doesn’t have a window to draw anything.
“location” object is related to a particular url; that means it is for page specific. 
So, node doesn’t require that.
Ofcourse Node doesn’t have “document” object also, cause it never have to render anything in a page.
Node has “global”, which is a predefined global object. 
It contains several functions that are not available in browsers, cause they are needed for server side works only.
“require” object is predefined in Node which is used to include modules in the app.
In Node everything is a module. You must keep your code inside a module.


Browser js(Console) :


“window” is a predefined global object which has functions and attributes, that have to deal with window that has been drawn.
“location” is another predefined object in browsers, that has all the information about the url we have loaded.
“document”, which is also another predefined global variable in browsers, has the html which is rendered.
Browsers may have an object named “global”, but it will be the exact one as “window”.
Browsers don’t have “require” predefined. You may include it in your app for asynchronous file loading.
Moduling is not mandatory in client side JavaScript, i.e. in browsers.
As both of them are JavaScript executor, and Node uses the JavaScript engine of a browser (Chrome), so differences are not much there. It is just the Node wrapper which has been written on top of JavaScript V8 Runtime engine, which is deleting few objects and also including some according to the requirement of Node.


4.excute the below code and write your discription.

a)typeof(1) //number

it is a number normally ,js also take 1 as the number.

b)typeof(1.1)//number

1.1 these also taken as a number in js

c)typeof('1.1')//string

these 1.1 is a string because these 1.1 inside the '' so it take as string in js

d)typeof(true)//boolean

boolean in js is true or false (or) yes or no (or) on or off ........here the type of () is true .....so these type is boolean.

e)typeof(null)//object

null is often used to signify an empty reference to an object. When Brendan Eich created JavaScript, he followed the same paradigm, and it made sense (arguably) to return "object". In fact, the ECMAScript specification defines null as the primitive value that represents the intentional absence of any object value (ECMA-262, 11.4.11).

f)typeof(undefined)//undefined

the typeof(undefined) is also a undefined .undefined is a property of the global object. That is, it is a variable in global scope. The initial value of undefined is the primitive value undefined.

g)typeof([])//object

empty array [] it can be taken as object in js ..normally array contain some values or object.but here array is empty,it can be taken as object

h)typeof({})//object

its can be taken as the object,to differentiate regular objects from arrays

i)typeof(NaN)//number

In js NaN is not a number or not a valid number,but it take NaN as number.

<script>
  console.log(typeof(1));

 //number -it is a number normally ,js also take 1 as the number.

console.log(typeof(1.1));

//number-1.1 these also taken as a number in js

console.log(typeof('1.1'));

//string-these 1.1 is a string because these 1.1 inside the '' so it take as string in js

console.log(typeof(true));

//boolean in js is true or false (or) yes or no (or) on or off //........here the type of () is true .....so these type is boolean.

console.log(typeof(null));

/*null is often used to signify an empty reference to an object. When Brendan Eich created JavaScript, he followed the same paradigm, and it made sense (arguably) to return "object". In fact, the ECMAScript specification defines null as the primitive value that represents the intentional absence of any object value (ECMA-262, 11.4.11).*/

console.log(typeof(undefined));

/*the typeof(undefined) is also a undefined .undefined is a property of the global object. That is, it is a variable in global scope. The initial value of undefined is the primitive value undefined.*/

console.log(typeof([]));

/*empty array [] it can be taken as object in js ..normally array contain some values or object.but here array is empty,it can be taken as object*/

console.log(typeof({}));

/*its can be taken as the object,to differentiate regular objects from arrays*/

console.log(typeof(NaN));

/*In js NaN is not a number or not a valid number,but it take NaN as number.*/
</script>
[day2execution.txt](https://github.com/AjithRevildo/day2-js-assesment/files/7212976/day2execution.txt)










