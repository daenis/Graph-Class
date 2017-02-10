# Graph-Class
JavaScript code for a Graph class. Graph objects possess two properties - x and y, which are to be assigned array values that contain x and y coordinates, respectively. The stipulation is that the program needs at least three sequential coordinates to properly execute methods and return mathematically correct values (ex: x = 3, x = 4, x = 5). 
Note: Program operates under the quadratic equation model, f(x) = Ax^2 + Bx + C
Methods:
- takeDerivativeA() : Returns the derivative of the first term, led by coefficient A.
- formLeading() : Returns the value of the leading coefficient.
- takeDerivativeB() : Returns the derivative of the second term, led by coefficient B. Because B is paired with only base x with no exponential value, the returned value from this method will also be the value of B. For linear equations, the derivative is also the slope.
- takeYInt() : Returns the value of the function when x values are set to 0 (Also known as coefficient C, or the Y Intercept).
- formEq() : Returns a string value representing the equation in the form of the quadratic equation model. 
  ***Still needs optimization. In the process of creating a more aesthetically pleasing return value for linear functions. As of right now, return values for linear functions read in the syntax as follows: f(x) = 0x^2 + Bx + C. Aiming to eliminate A coefficient term altogether.***
- predict(n) : Returns f(n), n being a number specified by the user.
- formDerivativeEq() - Returns a string value representing the derivative of the original equation.
  ***Still needs optimization, much like the formEq() method***
- predictDerivative(n) : Similar to the predict method. Return a value for f'(n).
Future functionality will include integration methods, min / max detection methods and root detection methods. In addition, test cases will be provided with the class. 
