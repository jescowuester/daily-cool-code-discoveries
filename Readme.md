# Cool code discoveries 
![scraa](https://emojis.slackmojis.com/emojis/images/1521814450/3718/dabbing_unicorn.png?1521814450)

 - [JavaScript](#JavaScript)
 - [React](#React)
 - [css](#css)
 - [html](#html)
 
 
 
## JavaScript

- `({text})=><div>{text}</div> ` is the same as `function(props){return <div>{props.text}</div>}`

 - `+false` becomes 0 and `+true` becomes 1
 
 - `+"1"` becomes `1`

 - `new Set()` is similar to an array but has unique values
 
 - you can cache the array length in a for loop like this `for (let i = 0, length = array.length; i < length; i++){...`
 
 - if you want to cut off part of  `const arr = [1,2,3,4,5]`  you can do `arr.length = 3` and `arr` will be `[1,2,3]` 
 
  - long conditional chains like this `name === 'foo' || name === 'bar' || etc..` can be simplified like this `['foo','bar',etc...].includes(name)`

 - you can destructure nested objects: `const { object: {nestedProp, nestedObj: {deeperNestedProp}}} = parentObj`

 - `a === 5 ? true : false` is the same as just writing `a=== 5`. This can be combined with the tips before to shorten some code `+(a===5) //1 : 0` (in production the ternary operator is prob. a better idea tho)

## React

 - `<> ... </>` can be used in React instead of `<Fragment>...</Fragment>`

 - you can use the `useReducer` hook with just simple arrow function `const [toggle, setToggle] = useReducer(toggle=>!toggle, true)` (more of a shift in mindset than a hack)

 ## css
 
 - `place-content: flex-start center;` is a shorthand for `align-item` / `justify-content` 
 
 ## html
 
  - there is a `<picture>` tag that lets you create responsive images.
