##Cascade the 'C' in CSS
### 1. Highest Importance
1. User marked with !importance
2. Author marked with !importance
3. Author declaration
4. User declaration
5. Browser declaration
### 2. Specificity
 1. Inline
 2. Id
 3. Classes, pseudo classes, attributes
 4. Element , pseudo element 
* `But value to calculate specicity is (inline,id,classes,element)` <br>
    `eg (1,1,0,0) > (0,2,1,1)`
### 3. Source Order

## NOTE
* `Never use !important keyword it doesnt help you in wrong run`
* `Never use inline stylesheet code is not maintainable and scalable`
* `Universal selector has specificity value of (0,0,0,0)`
* `When using 3rd party sylesheet include your stylesheet al last. Order is very Important !`
 