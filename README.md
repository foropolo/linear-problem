# linear-problem
Take a linear problem and give us back the info as arrays

You insert into the programm a file as LP02.LTX 
such as
max	-x1 + x2 + 6x3 - x4 	

subject	 4x1 + x2 + 2x3 + 3x4  => 	12

-x1 - 2x2 +   x3 - 5x4  =<  34
	
 2x1 + 7x2 - x3  -  x4   >=  8		 
	
-3x1 +  x2 +  6x3 - 2x4  =   0
  
end

and give us back the info in array

MinMAx=1
C=[[-1, 1, 6, -1]]

A=[[4, 1, 2, 3], 
  
  [-1, -2, 1, -5],
  
  [2, 7, -1, -1],
  
  [-3, 1, 6, -2]]

B=[12, 34, 8, 0]

Eqin=[1, -1, 1, 0]
