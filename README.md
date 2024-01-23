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

**Answer # 3 : Output of result**<br/>
                   output of result will be **24** because **lastIndexOf** method returns index or position of last occurence of specified substring. The function returns -1 if the value is not found in the string or array

            =========================================================================
**Question # 4 : Guess the Output and Explain Why?**<br/>
`let variable = 'hello programmers';`<br/>
`let result = Number(variable);`<br/>
`console.log(result);`

**Answer # 4 : Output of result**<br/>
                 output of result will be **NaN** because Number() method takes variable or expression as argument and convert it into number. If variable cannot be converted to valid number then the result will be NAN(Not a Number) so here variable is string which cannot be converted into number so result displayed **NaN** in console.

            ===========================================================================
**Question # 5: Guess the Output and Explain Why?**<br/>
`let num1 = 32;`<br/>
`let num2 = '32';`<br/>
`let result1 = num1 !== num2;`<br/>
`let result2 = num1 != num2;`<br/>
`console.log(result1, result2);`

**Answer # 5 : Output of result1 and result2**<br/>
               **Output of result1 = true**<br/>
	       **Output of result2 = false**
                  
 **output of result1** will be **true** and output of result2 will be **false** because when num1 is compared with num2 due to strict not equality operator it will check both number and datatype as num1 is Number and num2 is string so they are not equal so **true** will be shown in console while **output of result2** will display **false** in console because != will not check data type it only checks value of num1 and num2
