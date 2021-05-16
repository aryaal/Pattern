# Pattern
Pattern of equilateral triangle.
In this program outer for loop is for printing the rows.
             for(int i=n;i>=1;i--)
		           {
             }
Inside the for loop one more for loop is taken to print the space.Here we take a variable space and assign the value i-1.The  loop begins from i-1 and the loop execute till it is less than 1.
              for(int space=i-1;space>=1;space--)
		           	{
			               	System.out.print(" ");
		            	}
One more for loop is taken to print star.Here we take  variables j and s and it is initialize to 1 and j execute till it is greater than s.
               for(int j=1;j<=star;j++)
	            	{
			              System.out.print("*");
		            }
 After every iteration of outer for loop a new line is print
              System.out.println();
              
  And the value of star is incremented by 2.
  Iteration happens till value of i is less than 1.
	
