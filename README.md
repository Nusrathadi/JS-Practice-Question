# JS-Practice-Question
**Question # 1: Write a code to check difference between null and undefined data type. Also check their type using typeof**<br/>

**Answer # 1 : **Concept Explanation**** <br/>
**Null data type** means empty value or blank value whereas **undefined data type** mean variable has been declared but it's value has not been assigned. <br/>
**typeof** operator checks type of variable e.g string ,Number ,Boolean ,object etc
 <br/> **_Example of null data type_** <br/>
	` // let x = null; `<br/>
`// console.log(typeof x)  //output object` <br/>
typeof null returns object as output <br/>
**_Example of undefined data type_** <br/>
` // let x ; `<br/>
`// console.log(typeof x)  //output undefined` <br/>
typeof undefined is undefined

             ====================================================================
**Question # 2:  Which type of variables (var, let or const) must be initialized at the time of declaration?**

**Answer #2 : **Concept Explanation****<br/>
**var** and **let** can be declared without intialization and both of them shows undefined in log but **const** must be intialized at time of declaration otherwise it shows SyntaxError: Missing initializer in const declaration <br/>
` var x` <br/>
`console.log(x)  // output undefined ` <br/>

` let x` <br/>
` console.log(x) // output undefined `<br/>

`const x` <br/>
`console.log(x) //output SyntaxError: Missing initializer in const declaration `

           =========================================================================
**Question # 3 : Guess the Output and Explain Why?**

`let languages = 'java javaScript python cSharp';` <br/>
`let result = languages.lastIndexOf('S');` <br/>
`console.log(result);`


