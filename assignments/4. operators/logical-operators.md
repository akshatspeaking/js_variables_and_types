# Logical Operator

1. 🥇What's the output of the following, write the output next to the code as comment.

* [ ] Logical AND operation

```js
true  && true; //true
true  && false;   //false
false && true;    //false
false && false;   //false
"foo" && "bar";   //bar
"bar" && "foo";   //foo
"foo" && "";      //""
""    && "foo";   //""
" "   && "John" && "" && false //""
false && "Hey" && undefined      //false
"undefined" && false && 42    //false
```

* [ ] Logical OR operation
```js
true  || true;    //true
true  || false;   //true
false || true;    //true
false || false;   //false
"foo" || "bar";   //foo
"bar" || "foo";   //bar
"foo" || "";      //foo
""    || "foo";   //foo
" "   || "John" || "" || false //" "
false || "Hey" || undefined   //"Hey"
"undefined" || false || 42    //"undefined"
```

2. 🥈You have two variables i.e `isGuestOneVeg` and  `isGuestTwoVeg` according to the value using logical && and || opeartor do the following.

* [ ] If both are veg "Only offer up vegan dishes."
* [ ] At least one veg  "Make sure to offer up some vegan options."
* [ ] Else, "Offer up anything on the menu"
```js
let isGuestOneVeg = false;
let isGuestTwoVeg = false;
if (isGuestOneVeg==true && isGuestTwoVeg==true) {
   alert("Only offer up vegan dishes")
}
else if (isGuestOneVeg==true || isGuestTwoVeg==true) {
   alert("Make sure to offer up some vegan option")
}
else {
   alert("Offer up anything on the menu")
}
```


3. 🎖Using the variable `temperature` and logical operators do the following
* [ ] If temperature is less then 32 alert "It is freezing outside"
* [ ] If the temperature is greater then 110 alert "It is hot outside"
* [ ] else 'Go for it. It is pretty nice out'
```js
let temperature = 4;
if (temperature<32) {
   alert("It is freezing outside");
}
else if (temperature>110) {
   alert("It is hot outside");
}
else {
   alert("Go for it. It is pretty nice out.")
}




```

4. 🎖 Output of this and the reason behind the output.
```js
alert( alert(1) || 2 || alert(3) );

//1
//2

On running first alert function, because of the OR (||) operator, it looks for first truthy value. alert(1) is a function and runs as it is, and the statement continues looking for first truth value, which is 2. It displays 2 and stops before going to alert(3).
```