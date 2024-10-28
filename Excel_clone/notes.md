

## Resume 
Excel clone                    
* Created a web version of excel using vanilla Javascript ,HTML and CSS.
* All the features such as 2d grid, rows ,columns,sheets, formula and address bar  were build using vanilla js and css.
* it contains feature like changing font size ,font type ,alignments and other styling for text(optional)
*  Formula is implemented using `DFS algorithm` and evaluation of that `formula is done via infix stack evaluation`


```js
function initDB() {
    for (let i = 0; i < 100; i++) {
        let row = [];
        for (let j = 0; j < 26; j++) {
            //i j
            let name = String.fromCharCode(j + 65) + (i + 1) + "";
            let cellObject = {
                name: name,
                value: "",
                formula: "",
                childrens: [],
                parents: [],
            }
            row.push(cellObject);
        }
        newDB.push(row);
    }
}
let db=[[{name:A1
value:"",
 formula: "",
 isItalic:false,
 isBold:false,
 color:
 background

}]]
```
 * How multiple sheets are handled 
   * Dat storage :there is a 3d array of db -> that contains sheet's 2d array 
   * UI level 
```js
let row1=[{name:"A1",value:""},{name:"A2"}]
let row2=[{name:"A1"},{name:"A2"}]
let sheet1=[row1,row2]
let sheet2=[row1,row2]
let db =[sheet1, sheet2]
```
* formula ->
  * what formula is 
    * it should replace the variables and give you the value after evaluation
    * if any of the cell's value changes the formula should automatically 
    *  
  * constraints


