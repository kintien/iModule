iModule
=======



1. Write two functions to generate fibonacci series. Function specs are as follows:

   Function name = fib1()
    number of arguments = 1
        argument_1 = integer value N where N = number up to which fibonacci series is generated
    return value = list of fibonacci numbers up to N

   Function name = fib2()
    number of arguments = 1
        argument_1 = integer value N where N = length of fibonacci series to generate
    return value = list of first N fibonacci numbers

2. Make sure your functions are well commented

3. Create a new folder on your computer. Call it 'iFibonacci'

4. Create a text file using notepad(Windows) or textpad(Mac). Add your functions to this file
    and save it as 'iFibonacci.py' in the folder your created earlier.

5. Create another empty file in the folder 'iFibonacci'. Save it as 'setup.py'.

6. Add the following text to setup.py file.

###################################################

from distutils.core import setup

setup(
    name = 'iFibonacci',
    version = '1.0.0',
    py_modules = ['iFibonacci'],
    author = 'Your name',
    author_email = "yourmail@you.com",
    url = 'http://website.com',
    description = 'Fibonacci series generator'
)

####################################################

7. Save the file.

8. Open Command Prompt(Windows) or Terminal(Mac).

9. Navigate to iFibonacci folder.

10. Run the command: python3 setup.py sdist

11. To install the distribution to your local copy of python, run the command: python3 setup.py install

12. Now your module is ready to be imported into your code!

13. Create a new project in PyCharm and try using import iFibonacci !!!