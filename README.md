# Bubble-Sorting
Bubble sorting algorithm with javascript
[preview](https://editor.p5js.org/Sulay35/present/Mrtc-9-D)

**Using P5.js library:**
  https://p5js.org/
  
##### The sorting algorithm works like that:
   
   The dataset is created from an existing array and it shuffle it with `shuffle(array)` function. 
  
  dataset --> array of random values between 0 and 100
  
  `for x in dataset:
    if dataset[x] > dataset[x+1]:
      swap dataset[x] and dataset[x+1] values
   `   
      
      
javascript
    
    var temp; // temporary variable for a value
    if(array[x] > array[x+1]){// if the next value is lower then the actual
      fill(255,0,0);// color of the working tile
      rect(x*10, 210, 10, -array[x]*2);//draw the evaluate value 
      
      comparisons += 1;
      
      temp = array[x];// keep the value to swap
      array[x] = array[x+1];// change the values of the lower 
      array[x+1] = temp; // the next tile has the value of the working tile
    }

---
      
**TO DO**
  - feature 1 : 
    changeable array length
  - add cocktail sort and merge sort to the repo 
# Insertion-Sorting

# Merge-Sorting

# Cocktail-Sorting
