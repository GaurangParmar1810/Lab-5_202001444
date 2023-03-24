# <pre> IE314-Software Engineering 
## Lab-5_202001444

### Name       :Parmar Gaurang Gajendrabhai
### Student ID :202001444
### Group no      :32

<br/><br/>
####  selected tool and github repo

I am using 'pylint' tool for python.<br/>
Github repo : https://github.com/TheAlgorithms/Python/tree/master/ciphers
<br/><br/>

#### Performing static Analysis and error understanding
1. https://github.com/TheAlgorithms/Python/blob/master/ciphers/diffie.py

<br/>
tool output
<br/>
C:\Users\student\Desktop\Lab-5_202001444\Python-master\ciphers>python -m pylint diffie.py<br/>
************* Module ciphers.diffie<br/>
diffie.py:1:0: C0114: Missing module docstring (missing-module-docstring)<br/>
diffie.py:4:0: C0116: Missing function or method docstring (missing-function-docstring)<br/>
diffie.py:4:19: C0103: Argument name "n" doesn't conform to snake_case naming style (invalid-name)<br/>
diffie.py:5:8: C0103: Variable name "r" doesn't conform to snake_case naming style (invalid-name)<br/>
diffie.py:6:8: C0103: Variable name "li" doesn't conform to snake_case naming style (invalid-name)<br/>
diffie.py:7:12: C0103: Variable name "x" doesn't conform to snake_case naming style (invalid-name)<br/>
<br/>
-----------------------------------<br/>
Your code has been rated at 7.50/10<br/>



<br/><br/>

2. https://github.com/TheAlgorithms/Python/blob/master/ciphers/base16.py

<br/>
tool output
<br/>
C:\Users\student\Desktop\Lab-5_202001444\Python-master\ciphers>python -m pylint base16.py<br/>
************* Module ciphers.base16<br/>
base16.py:1:0: C0114: Missing module docstring (missing-module-docstring)<br/>
<br/>
-----------------------------------<br/>
Your code has been rated at 9.09/10<br/>

3. https://github.com/TheAlgorithms/Python/blob/master/ciphers/bifid.py

<br/>
tool output
<br/>
C:\Users\student\Desktop\Lab-5_202001444\Python-master\ciphers>python -m pylint bifid.py<br/>
************* Module ciphers.bifid<br/>
bifid.py:10:0: E0401: Unable to import 'numpy' (import-error)<br/>
bifid.py:21:0: C0115: Missing class docstring (missing-class-docstring)<br/>
bifid.py:23:8: C0103: Attribute name "SQUARE" doesn't conform to snake_case naming style (invalid-name)<br/>
bifid.py:72:8: C0200: Consider using enumerate instead of iterating with range and len (consider-using-enumerate)<br/>
bifid.py:98:8: C0200: Consider using enumerate instead of iterating with range and len (consider-using-enumerate)<br/>
<br/>
-----------------------------------<br/>
Your code has been rated at 8.00/10<br/>
<br/><br/>

4. https://github.com/TheAlgorithms/Python/blob/master/ciphers/hill_cipher.py

<br/>
tool output
<br/>

C:\Users\student\Desktop\Lab-5_202001444\Python-master\ciphers>python -m pylint hill_cipher.py<br/>
************* Module ciphers.hill_cipher<br/>
hill_cipher.py:40:0: E0401: Unable to import 'numpy' (import-error)<br/>
hill_cipher.py:43:28: C0103: Argument name "a" doesn't conform to snake_case naming style (invalid-name)<br/>
hill_cipher.py:43:36: C0103: Argument name "b" doesn't conform to snake_case naming style (invalid-name)<br/>
hill_cipher.py:57:0: C0115: Missing class docstring (missing-class-docstring)<br/>
hill_cipher.py:203:0: C0116: Missing function or method docstring (missing-function-docstring)<br/>
hill_cipher.py:204:4: C0103: Variable name "n" doesn't conform to snake_case naming style (invalid-name)<br/>
hill_cipher.py:212:4: C0103: Variable name "hc" doesn't conform to snake_case naming style (invalid-name)<br/>
<br/>
-----------------------------------<br/>
Your code has been rated at 8.71/10<br/>
<br/><br/>

5. https://github.com/TheAlgorithms/Python/blob/master/ciphers/rabin_miller.py

<br/>
tool output
<br/>
C:\Users\student\Desktop\Lab-5_202001444\Python-master\ciphers>python -m pylint rabin_miller.py<br/>
************* Module ciphers.rabin_miller<br/>
rabin_miller.py:1:0: C0114: Missing module docstring (missing-module-docstring)<br/>
rabin_miller.py:6:0: C0116: Missing function or method docstring (missing-function-docstring)<br/>
rabin_miller.py:6:17: W0621: Redefining name 'num' from outer scope (line 221) (redefined-outer-name)<br/>
rabin_miller.py:7:4: C0103: Variable name "s" doesn't conform to snake_case naming style (invalid-name)<br/>
rabin_miller.py:8:4: C0103: Variable name "t" doesn't conform to snake_case naming style (invalid-name)<br/>
rabin_miller.py:11:8: C0103: Variable name "s" doesn't conform to snake_case naming style (invalid-name)<br/>
rabin_miller.py:12:8: C0103: Variable name "t" doesn't conform to snake_case naming style (invalid-name)<br/>
rabin_miller.py:15:8: C0103: Variable name "a" doesn't conform to snake_case naming style (invalid-name)<br/>
rabin_miller.py:16:8: C0103: Variable name "v" doesn't conform to snake_case naming style (invalid-name)<br/>
rabin_miller.py:20:16: R1705: Unnecessary "else" after "return", remove the "else" and de-indent the code inside it (no-else-return)<br/>
rabin_miller.py:24:20: C0103: Variable name "v" doesn't conform to snake_case naming style (invalid-name)<br/>
rabin_miller.py:28:0: C0116: Missing function or method docstring (missing-function-docstring)<br/>
rabin_miller.py:28:21: W0621: Redefining name 'num' from outer scope (line 221) (redefined-outer-name)<br/>
rabin_miller.py:213:0: C0116: Missing function or method docstring (missing-function-docstring)<br/>
rabin_miller.py:215:8: W0621: Redefining name 'num' from outer scope (line 221) (redefined-outer-name)<br/>
<br/>
-----------------------------------<br/>
Your code has been rated at 5.95/10<br/>
<br/><br/>

#### Understanding of errors: 
1) C0114: This message recommends that the user add a module-level docstring to describe the purpose of the module.<br/>
2) C0116: This message suggests that the user add a docstring for the "generate_public_key" function to describe what it does, what its parameters are, and what it returns.<br/>
3) C0103: This message suggest that the user follow the snake_case naming convention for variable and function names. Specifically, the variables "n", "r", "li", and "x" should be renamed to "n_value", "random_value", "list_of_values", and "private_key", respectively.<br/>
4) C0115: This message suggests that the user should include a class-level docstring to describe the purpose of the class.
5) W0621 : The variable name 'num' used in the function definition is also defined in the outer scope, which could cause confusion.
6) R1705 : The "else" statement after "return" is unnecessary and can be removed.
7) E0401 : The module is unable to import 'numpy'.
