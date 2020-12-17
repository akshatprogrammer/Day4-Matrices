# Day4-Matrices

## What are matrices in programming?
     A matrix is a grid used to store or display data in a structured format.
     In computing, a matrix may be used to store a group of related data.
     For example, some programming languages support matrixes as a data type that offers more flexibility than a static array.
     
## Declaration
 <b>Data_type</b> <b>array_name</b> [rows]  [coulumns];</br>
 eg -> int mat[3]  [3];
 
## Initialization
  int mat[3]   [3] = {{1,2,3},{4,5,6},{7,8,9}};  (compile time)</br>
  for(i=0;i<row;i++)</br>
  {</br>
    for(j=0;j<col;j++)</br>
    {</br>
      cin >> a[i]  [j];</br>
    }</br>
  }</br>(Run Time)</br>
  ![image](https://github.com/akshatprogrammer/Day4-Matrices/blob/main/Microsoft%20Whiteboard%2012_17_2020%2012_19_12%20PM%20(2).png?raw=true)
  
  
## Row Major and Column Majaor
  ### Row Major
   ![image](https://github.com/akshatprogrammer/Day4-Matrices/blob/main/Microsoft%20Whiteboard%2012_17_2020%2012_19_12%20PM.png?raw=true)
   
  ### Coloumn Major
   ![image](https://github.com/akshatprogrammer/Day4-Matrices/blob/main/Microsoft%20Whiteboard%2012_17_2020%2012_19_55%20PM.png?raw=true)
 
 
## Address Calculation of Element in Matrix.
   ### For Row Major
  Add = Base Add + (col x i + j)*sizeof(datatype);</br>
  Here i and j representing row and column of particular element</br>
### For Column Major
  Add = Base Add + (row x j + i)*sizeof(datatype);</br>
  Here i and j representing row and column of particular element</br>
    
## Dynamic Memory Allocation
   ### Using malloc()
   ![image](https://github.com/akshatprogrammer/Day4-Matrices/blob/main/Microsoft%20Whiteboard%2012_17_2020%2012_43_51%20PM.png?raw=true)
   ### Using malloc() with pointer array
   ![image](https://github.com/akshatprogrammer/Day4-Matrices/blob/main/Microsoft%20Whiteboard%2012_17_2020%2012_56_15%20PM.png?raw=true)
   
   **Note -> arr[i]  [j] = * ( * (arr + i) + j);**
# Connect With Me
LinkedIn : https://www.linkedin.com/in/akshat-jain-a24baa18a/<br/>
Email : akshat.kodia@gmail.com<br/>
Twitter : www.twitter.com/akki_aj89<br/>

# Personal
Name : Akshat Jain<br/>
University : Graphic Era University, Dehradun(UK)

If any problem with this program reach me at Telegram<br/>
Here is the link -> https://t.me/akki_aj89

# Gratitude
Thank You, if you like it please leave a Star.
