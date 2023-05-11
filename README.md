# JavaScript Lesson #1
## JavaScript is a well language for FrontEnd developers*
___
**_it is good for it framework that name is React & Angular & Vue it can be your best friend to create the sites_**
___

## **JAVASCRIPT VARIABLES & CONSTANTS**
<br>

## Variables

>### var 
>`used in older versions of JavaScript`
>>```javascript
>>function globalVareable() {
>>console.log(a)
>>let a = 5       
>>}
>>globalVareable()
>>```
>### let
>`used in new versions of JavaScript`
>>```javascript
>>function localVareable() {
>>    console.log(a)
>>    let a = 5
>>    
>>}
>>localVareable()
>>```
>### const
>`used like constant which you can't change after first using`
>>```javascript
>>let txt2 = "text"
>>txt2 = "bye"
>>console.log(txt2);
>>
>>const TXT = "hello world";
>>TXT="hello";
>>console.log(TXT);
>>```
<br>
<br>


## **OBJECTS AND PRIMITIVES**
___
<br>

## Value

>+ Primitve
>   + Number
>   + String
>   + Boolean
>   + Undefined
>   + Null
>   + Symbol
>   + BigInt
>+ Object 
>   + Object literals
>   + Array
>   + Functions
>   + Many more...
>
>
<br>
<br>

## **ARIPHMETICS OPERATORS**
___
<br>

>| Operators    |   Meaning       | 
>|:------------:|:-------------:|
>| +            | Addition        |
>| -            | Substraction    |
>| *            | Multiplication  |
>| /            | Division        |
>| %            | Part of piece   |
>| ++           | Increment       |
>| --           | Decrement       |

<br>
<br>

## **LOGIC OPERATORS**
___
<br>

>| Operators    |   Meaning       |
>|:------------:|:---------------:|
>| &&           | Logical and     |
>| ||           | Logical or      |
>| !            | Logical not     |

<br>
<br>

## **COMPARISON OPERATORS**
___
<br>

>| Operators    | Meaning                              |
>|:------------:|:-------------------------------------|
>| >            | Less than                            |
>| <            | Greater than                         |
>| >=           | Less than or equal to                |
>| <=           | Greater than or equal to             |
>| ==           | Equal to                             |
>| !=           | Not Equal to                         |
>| ===          | Equal to value and same type         |
>| !==          | Not Equal to value and Not same type |

<br>
<br>

# **Conditions**

## **TERNARY OPERATORS**

`The ternary operator if, we say that the abbreviated if we will not be mistaken.`

```javascript
let result = condition ? value1 : value2;
```

+ The number 0, the empty string "", null, undefined and NaN become false. Because of this, they are called "false" values.

+ The remaining values become true, so they are called "truthy".
___

# **Loop**

>## **FOR**
>>```javascript
>>let str = '';
>>let cnt = 0;
>>
>>for(let i=0;i<9;i++){
>>    str += 1;
>>    cnt++;
>>}
>>console.log(str);
>>console.log(cnt);
>>```
>## **WHILE**
>>```javascript
>>let n = 0;
>>let x = 0;
>>
>>while(n < 3){
>>    n++;
>>    x += n;
>>}
>>console.log(n);
>>console.log(x);
>>```
>## **FOR**
>>```javascript
>>let result = '';
>>let i = 0;
>>
>>do{
>>    i += 1;
>>    result += i;
>>} while(i < 5)
>>console.log(result);
>>```
>>___
