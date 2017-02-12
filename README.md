# Graph-Class
JavaScript code for a Graph class. Graph objects possess two properties - x and y, which are to be assigned array values that contain x and y coordinates, respectively. The stipulation is that the program needs at least four sequential coordinates to properly execute methods and return mathematically correct values (ex: x = 3, x = 4, x = 5, x = 6). 
Note: Program operates under the cubic equation model, f(x) = Ax^3 + Bx^2 + Cx + D
Methods:
- takeDerivativeA() : Returns the derivative of the first term, led by coefficient A.
- formLeading() : Returns the value of the leading coefficient.
- takeDerivativeB() : Returns the derivative of the second term, led by coefficient B. 
- formB() : Returns the value of the coefficient B.
- takeDerivativeC() : Returns the value of the coefficient C. This is the same as the derivative, as C is associated with the x term.
- takeYInt() : Returns the value of the function when x values are set to 0 (Also known as coefficient D, or the Y Intercept).
- formEq() : Returns a string value representing the equation in the form of the cubic equation model. 
  ***Still needs optimization. In the process of creating a more aesthetically pleasing return value for functions that contain the value 0 in place of A, B, C or D. As of right now, for example, return values for linear functions read in the syntax as follows: f(x) = 0x^2 + Bx + C. Aiming to eliminate A coefficient term altogether.***
- predict(n) : Returns f(n), n being a number specified by the user.
- formDerivativeEq() - Returns a string value representing the derivative of the original equation.
  ***Still needs optimization, much like the formEq() method***
- predictDerivative(n) : Similar to the predict method. Return a value for f'(n).
Future functionality will include integration methods, min / max detection methods and root detection methods. In addition, test cases will be provided with the class. 
