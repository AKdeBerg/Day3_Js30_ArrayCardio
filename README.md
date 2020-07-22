# <h1 align="center"> 💪🏼Get Ready for Array Cardio💪🏼 </h1>
You think you know all about Js array? Alrighty, take these challenges from Wes Bos <a href="https://javascript30.com/">JavaScript30</a> to put your claim in test.
I have done my part; boy!! it was one good workout session. 
Let me share my experiece here-

## What did I solve?
Wes Bos posed some of the very interesting and real-life problems which can be solved by various array methods i.e. **Array.prototype.filter(), Array.prototype.map(), Array.prototype.sort(), Array.prototype.reduce()**

## The Challenge & My Learnings
Given Data:
```javascript
    const inventors = [
      { first: 'Albert', last: 'Einstein', year: 1879, passed: 1955 },
      { first: 'Isaac', last: 'Newton', year: 1643, passed: 1727 },
      { first: 'Galileo', last: 'Galilei', year: 1564, passed: 1642 },
      { first: 'Marie', last: 'Curie', year: 1867, passed: 1934 },
      { first: 'Johannes', last: 'Kepler', year: 1571, passed: 1630 },
      { first: 'Nicolaus', last: 'Copernicus', year: 1473, passed: 1543 },
      { first: 'Max', last: 'Planck', year: 1858, passed: 1947 },
      { first: 'Katherine', last: 'Blodgett', year: 1898, passed: 1979 },
      { first: 'Ada', last: 'Lovelace', year: 1815, passed: 1852 },
      { first: 'Sarah E.', last: 'Goode', year: 1855, passed: 1905 },
      { first: 'Lise', last: 'Meitner', year: 1878, passed: 1968 },
      { first: 'Hanna', last: 'Hammarström', year: 1829, passed: 1909 }
    ];
```

<details>
<summary>Filter the list of inventors for those who were born in the 1500</summary>
<p>
  
```JavaScript
const earlyInventors = inventors.filter((inventor) => inventor.year >= 1500 && inventor.year < 1600)
console.table(earlyInventors)
```
</p>
</details> 


<details>
<summary>Give us an array of the inventors first and last names</summary>
<p>
  
```JavaScript
const inventorsName = inventors.map((inventor) => `${inventor.first} ${inventor.last}`)
console.table(inventorsName)
```
</p>
</details> 

For full details of my learning & what you can learn from this challenge, plz see my blog post-
<a href="https://dev.to/akdeberg/javascript30-day-4-solve-real-life-challenges-using-array-methods-4m2i">JavaScript30: Day 4 - Solve Real Life challenges using Array Methods
</a>
