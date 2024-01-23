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
                  
 **output of result1** will be **true** and output of result2 will be **false** because when num1 is compared with num2 due to strict inequality operator it will check both number and datatype as num1 is Number and num2 is string so they are not equal so **true** will be shown in console while **output of result2** will display **false** in console because != will not check data type it only checks value of num1 and num2.

           =============================================================================
**Question # 6 :  Guess the Output and explain Why?**<br/>
`let str = 'Hello Programmers';`<br/>
`let result = str.includes('r');`<br/>
`console.log(result);`

**Answer # 6: Output of result**<br/>
   Output of result is **true** because .includes() is string method which returns true if string contains a specified string otherwise it returns false

        =================================================================================
**Question # 7: Guess the Output and Explain Why?**<br/>
`let num1 = 2;`<br/>
`let num2 = 5;`<br/>
`let result = num1 ** num2 * 2;`<br/>
`console.log(result);`

**Answer # 7: Output of result**<br/>
     Output of result is **64** .** in javascript is power (exponentiation) operator * is used as multiplication operator so first it will calculate 2^5 which is equal to 32 and then 32 will be multiplied by 2 so 64 will be displayed in console.

      ===================================================================================
**Question # 8: Guess the Output and Explain Why?**<br/>

`let num1 = [1, 2, 4, 5];`<br/>
`let num2 = [6, 5, 8, 0];`<br/>
`let result = num1.concat(num2);`<br/>
`console.log(result);`

**Answer # 8 : Output of result**<br/>
             output of result is [1,2,4,5,6,5,8,0] .concat() is array method and it joins two or more strings or arrays it does not change existing string

        ==================================================================================
**Question # 9 : Guess the Output and Explain Why?**<br/>

`let a = 5;`<br/>
`let b = 7;`<br/>
`let c = 8;`<br/>
`let result = a < b > c;`<br/>
`console.log(result);`

**Answer # 9 : Output of result**<br/>
         output of result is **false** when result expression is executed it first compare a < b means 5 < 7 so ans is true as true is 1 so further 1 will be calculated with c so 1 > 8 so ans is false so **false** will be shown in console.

         ==================================================================================
**Question #  10 :  If your State is split into four equal parts such that in each part there are 1/4 number of people live. You have to find how many people would live in each part? which operators will you use ?**

**Answer # 10 :** To find the number of people living in each of the four equal parts when the state is split, we can  use the division operator
    **Example with Code Snippet**

    const totalPeople = 100;
    const peopleInEachPart = totalPeople / 4;
    console.log(`Each part would have ${peopleInEachPart} people.`);   //output Each part would have 25 people

         =========================================================================================
**Question # 11: Guess the Output And Explain Why?**

	let i = 4;
	for (let j = 0; i < 10; i++) {
	  if (j === 1 || i === 6) {
	    continue;
	  } else {
	    console.log(i, j);
	
	    if (i === 7) {
	      break;
	    }
	  }
	}

 **Answer # 11 **output of above code is <br/>
    4 0 <br/>
    5 0  <br/>
    7 0 <br/>
 when program start execution at start i = 4 when loop start executed value of j=0 and i < 10 condition is true so control falls inside block of loop in block first<br/>  The loop continues as long as i is less than 10.<br/>
In each iteration, it checks if j is equal to 1 or i is equal to 6. If true, it uses continue to skip the rest of the loop body and jumps to the next iteration.<br/>
If the condition is false, it prints the values of i and j.<br/>
It checks if i is equal to 7. If true, it uses break to exit the loop.

          ==========================================================================
**Question # 12:  Guess the Output and Explain Why?**

	let i = 0;
	for (i; i < 5; i++) {
	  console.log(i);
	}

 **Answer # 12 : Output** <br/>
           0 <br/>
	   1 <br/>
           2  <br/>
	   3  <br/>
           4  <br/>
        at start i is 0.<br/>
	when for loop start executed loop variable i initialized to 0.<br/>
	The loop continues as long as i is less than 5.<br/>
	In each iteration, it prints the value of i.<br/>
	After each iteration, it increments i by 1.

         =======================================================================
**Question # 13 : Write a simple Program in which You have to print first 10 numbers in descending order (10...1)**

**Answer # 13 :**<br/>
             for (let i=10; i >0 ; i--) {<br/>
		  console.log(i);
		}

           ======================================================================
**Question # 14 :  Lets say John is looking a new country to live in. He want to live in a country that speaks English, has less than 10 million people. One of the food option between these two must present Spanish food OR English food.
Write an if/else if statement to help john figure out Your country is right for him?**

**Answer # 14 :**<br/>

			let lang="English"
			let pop = 500
			let food = "Spanish"
			if (lang === "English" && pop <=100000 && food ===( "Spanish" ||  "English")){
			    console.log("john can live here")
			}
			else {
			    console.log("john cannot live here")
			}

              =========================================================================
**Question # 15 :  Guess the Output And Explain Why?**

	for (let i = 0; i < 10; i++) {
	  console.log(i);
	}
	console.log(i);

 **Answer # 15 : Output**

       0
       1
       2
       3
       4
       5
       6
       7
       8
       9
       Refernce Error : i is not defined

       first console.log(i) statement  print value from 0 to 9 
       second console.log(i) give reference error i is not defined because i is not defined globally

              ======================================================================
**Question # 16 :  use nested-if statement to check your age>18<br/>
         than check your height height > 5.10.<br/>
        If both true show any message(I can sit in exam) in the console?**

**Answer # 16 :**

	const age = 20;
	let height = 5.11;
	if (age > 18)
	{
	  if(height> 5.10)
	  {
	      console.log("I can sit in exam")
	  }
	  else {
	      console.log("I cannot sit in exam")
	  }
	}

	         ======================================================================
**Question # 17 : Create two variables grade and passingYear.Check if your grade == "A" and passingYear < 2020 with the help of ternary operator(Not allowed to use any logical operator).If both condition true print on console Qualify. Otherwise Fail**

**Answer # 17 :**

		let grade = "A"
		let passingYear = 2019
		grade === "A" ? (passingYear < 2020 ? console.log("Qualify") : console.log("Fail")) : console.log("Fail");

                 ======================================================================
**Question # 18 : Create a function Declaration called describeYourState Which take three parameters Population, traditional food and historical place. Based on this input function should return a String with this format.
My state population is ** Its traditional food is ** and historical place name is ___**

**Answer # 18 :**

	     function describeYourState(pop,food,place)
              {
	        console.log(`My state population is ${pop} Its traditional food is ${food} and historical place name is ${place}`)
	       }
	     describeYourState("10,000" ,"biryani","Islamabad")

              =========================================================================
**Question # 19 :Create a function expression which does the exact same thing as defined in Question 18**

**Answer # 19 :**
	
	            const describeYourState = (pop,food,place) =>
	           {
	                console.log(`My state population is ${pop} Its traditional food is ${food} and historical place name is ${place}`)
	           }
	       describeYourState("10,000" ,"biryani","Islamabad")

              =========================================================================
**Question # 20 : Create function addition which takes two numbers as an argument And return the result of sum of two numbers
Important Note: In the function call you are not passing any parameter. You can modify function to achieve this.
Example;**
		
		function addition(num1, num2) {
		  return num1 + num2;
		}
		console.log(addition()); //You are not allowed to modify this line any more

  **Answer # 20 :**

       By assigning default values to parameters we can solve this like
		
		function addition(num1 =10 , num2 =26 ) {
		  return num1 + num2;
		}
		console.log(addition());

         
