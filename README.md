# AsmlAssignmentSpiralMatrix
 Spiral Matrix for ASML Assignent
 
 SpiralMatrix.java contains main method which will print the output as sugested in the question..
 Method spiralPrint(int[][] arr) will take array as the argument and will print the result 
 The logic is explained below and is also present in the comments section of the API :
 
	  * 1) four pointers are taken which will be initially pointing to 
	  *    starting coloumn Index, ending coloumn index, top row index and 
	  *    Bottom row index...
	  *  2) The logic will run until all the squares of the loop and are printed
	  *  3) NullPointerException is handled , If the arr is null
	  *  4) ArrayIndexOutOfBoundException is handled, If the array elements are not 
	  *     provided properly
	  *  5) Time complexity is m*n and space complexity is 1..
	  *  
	  *  The logic used is : 
	  *  First the top row will be added to stringJoiner and then , the top row pointer will be 
	  *  incremented by 1 
	  *  Then the right most coloumn is stringJoiner from the topRow pointer value to the
	  *  BottomRowPointer value and then the right most coloumn value is decremented
	  *  by 1 
	  *  Then the Bottom most row is stringJoiner from the RightMostColoumn pointer to the 
	  *  LeftMost coloumn pointer and then the value of Bottom Most row pointer is
	  *  Decremented 
	  *  Then the left most coloumn is stringJoiner from the BottomRow to the TopRow
	  *  Taking the coloumn value as constant and then increase the left pointer to one
	  *  All these logic is will execute until the 
	  *  topRowPointer<=bottomRowPointer && leftColoumnPointer<=rightColoumnPointer
	  *  Finally the value of stringJoiner will be printed 
   
   JUNIT test cases are writterned which covers mostly all the scenarios of the API like Nullpointer exception , ArrayIndexOutOfBoundException and 
   properly printing the array..
   
