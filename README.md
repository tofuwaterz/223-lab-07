# Laboratory 7
  
## Program Instructions
1. Write a Python package with sub-packages, modules, and functions using keyword arguments.  Use the following mathematics within your lab05-username directory):

mathematics/
		__init__.py
		whoami.py
numbers/
			__init__.py
			whoami.py
			series.py
			simple.py
geometry/
			__init__.py
			whoami.py
			rectangle.py
			circle.py
			cube.py

. Create a mathematics package.
       . Initialize the __all__ variable to the whoami module.
       . Create a whoami module.
          . Create a function named getname which returns the __name__ variable.
     .
      Create a numbers sub-package.
          . Initialize the __all__ variable to the whoami and series modules.
          . Create a whoami module.
               . Create a function named getname which returns the __name__ variable.
          . Create a series module.
               . Create a function named sum which receives a keyword parameter list and returns the sum of all the values in the list.
               . Create a function named average which receives a keyword parameter list and returns the average of all the values in the list.
          . Create a simple module.
               . Create a function named addition which receives the keyword parameters left and right and returns left plus right.
               . Create a function named subtraction which receives the keyword parameters left and right and returns left minus right.
               . Create a function named multiplication which receives the keyword parameters left and right and returns left multiplied by right.
               . Create a function named division which receives the keyword parameters left and right and returns left divided by right.
     . Create a geometry sub-package.
          . Initialize the __all__ variable to the whoami, circle, and cube modules.
          . Create a whoami module.
               . Create a function named getname which returns the __name__ variable.
          . Create a rectangle module.
               . Create a function named perimeter which receives a keyword parameters length and width and returns (2l + 2h).
               . Create a function named area which receives a keyword parameters length and width and returns (l * h).
          . Create a circle module.
               . Create a function named circumference which receives the keyword parameter radius and returns (2 * pi * r).
               . Create a function named area which receives the keyword parameter radius and returns (pi * r * r).
          . Create a cube module.
               . Create a function named surface_area which receives the keyword parameter side and returns (s * s * 6).
               . Create a function named volume which receives the keyword parameter side and returns (s * s * s).
. Create your own main.py file to test all the modules and functions and run the program using the command below and repeat the steps above until you are satisfied your program output meets the above requirements. I will not grade this file - it is for your use to test the package.