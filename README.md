# <pre> IE314-Software Engineering 
## Lab-5_202001444

### Name       :Parmar Gaurang Gajendrabhai
### Student ID :202001444
### Group      :32

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
![image](https://user-images.githubusercontent.com/97961910/227491460-7f567f45-6639-4700-8923-cf31d03395e4.png)
<br/><br/>

2. https://github.com/TheAlgorithms/Python/blob/master/ciphers/base16.py

<br/>
tool output
<br/>
![image](https://user-images.githubusercontent.com/97961910/227492463-d8ef1111-5c71-4b8e-be45-32d642eded4b.png)
<br/><br/>

3. https://github.com/TheAlgorithms/Python/blob/master/ciphers/bifid.py

<br/>
tool output
<br/>
![image](https://user-images.githubusercontent.com/97961910/227492691-e01999ad-d070-4551-9a07-7b5b22cad31d.png)
<br/><br/>

4. https://github.com/TheAlgorithms/Python/blob/master/ciphers/hill_cipher.py

<br/>
tool output
<br/>
![image](https://user-images.githubusercontent.com/97961910/227493911-3107c6a8-5e98-4ef5-8394-ef397a57b9e3.png)
<br/><br/>

5. https://github.com/TheAlgorithms/Python/blob/master/ciphers/rabin_miller.py

<br/>
tool output
<br/>
![image](https://user-images.githubusercontent.com/97961910/227493828-ba21384d-cca1-455d-b071-4529918779fa.png)
<br/><br/>

#### Understanding of errors: 
1) C0114: This message recommends that the user add a module-level docstring to describe the purpose of the module.<br/>
2) C0116: This message suggests that the user add a docstring for the "generate_public_key" function to describe what it does, what its parameters are, and what it returns.<br/>
3) C0103: This message suggest that the user follow the snake_case naming convention for variable and function names. Specifically, the variables "n", "r", "li", and "x" should be renamed to "n_value", "random_value", "list_of_values", and "private_key", respectively.<br/>
4) C0115: This message suggests that the user should include a class-level docstring to describe the purpose of the class.
5) W0621 : The variable name 'num' used in the function definition is also defined in the outer scope, which could cause confusion.
6) R1705 : The "else" statement after "return" is unnecessary and can be removed.
7) E0401 : The module is unable to import 'numpy'.
