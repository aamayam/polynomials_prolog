# polynomials_prolog
Basic operations with polynomials using Prolog language and recursive methods.

The project is a .pl (prolog file) script that allows to perform basic operations 
with polynomials. i.e. addition, substraction, scalar multiplication, multiplying 
polynomials, evaluation, composition, first derivative and an additional method 
to print the polynomial in a "friendly" format (similar to Java toString()).

Every single method in the script is commented with the I/O format and an example
of its use. 

To characterize a polynomial expression we use a List that includes the coefficients 
of each term in the polynomial, ordered by the degree (in increasing order). 
For instance, the polynomial 

  - p(x) = x^3 + 2*x^2 - x + 5

is represented with the next list

  - [5 -1 2 1]
  
