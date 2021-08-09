### Read: Class 03
-------------------------------------------------------------------------------------------------------------------------------

## Passing Functions as Props

In **React**, the map() function is most commonly used for rendering a list of data to the DOM. To use the map() function, attach it to an array you want to iterate over. The map() function expects a callback as the argument and executes it once for each element in the array

![react](https://d585tldpucybw.cloudfront.net/sfimages/default-source/blogs/templates/social/reactt-light_1200x628.png?sfvrsn=43eb5f2a_2)

###  loop through an array and display each value in JSX

![react1](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTDn4EUwnhxgiAal8TgZ-a8TzeaBKw7k21fl2sp4hI15mIij538gjWJoicZUaFrgdaUCcE&usqp=CAU)


> You can basically use the same structure when working with JSX: var rows = []; for (var i = 0; i < numrows; i++) { // note: we are adding a key prop here to allow react to uniquely identify each // element in this array.


### the purpose of a key

> A “key” is a special string attribute you need to include when creating lists of elements in React. Keys are used to React to identify which items in the list are changed, updated, or deleted. In other words, we can say that keys are used to give an identity to the elements in the lists
---------------------------------------------------------------------------------------------------------------

## spread operator

##### The Spread operator lets you expand an iterable like an object, string, or array into its elements while the Rest operator does the inverse by reducing a set of elements into one array


##### spread operator can do

![react2](https://livecodestream.dev/post/how-to-use-the-spread-operator-in-javascript/featured_hu552373e3dd9cfa7192fd6d6eeac47a64_53660_680x0_resize_q75_box.jpg)

The Spread operator lets you expand an iterable like an object, string, or array into its elements while the Rest operator does the inverse by reducing a set of elements into one array.

EX:

`const arr1 = [1,2,3]
const arr2 = [4,5,6]
const arr3 = [...arr1, ...arr2] //arr3 ==> [1,2,3,4,5,6]`

