Test_Helper_Function

Requirements:
Python 3
Pandas 1.3.5
Pytest 7.2.1

Project Description:
This project does unit testing on a few of the functions from the helper file. 

test_random_float checks the make sure that the function returns a number of type float.

test_random_bowling_score checks to make sure that the function returns a number of type int.

test_silly_tuple checks to make sure that the function returns an object of type tuple.


How to Run the project:
The run the project you need to download helper_function.py and test_helper_function.py. Next run test_helper_function.py


Example Output
jdwat@JeffComputer MINGW64 ~/OneDrive/desktop/sprint9/bloomdata_jdwatson08
$ pytest test_helper_function.py --verbose

============================= test session starts =============================
platform win32 -- Python 3.11.1, pytest-7.2.1, pluggy-1.0.0 -- C:\Users\jdwat\.virtualenvs\sprint9-drJZjINu\Scripts\python.exe
cachedir: .pytest_cache
rootdir: C:\Users\jdwat\OneDrive\desktop\sprint9\bloomdata_jdwatson08
plugins: Faker-16.6.1
collecting ... collected 3 items

test_helper_function.py::test_random_float PASSED                        [ 33%]
test_helper_function.py::test_random_bowling_score PASSED                [ 66%]
test_helper_function.py::test_silly_tuple PASSED                         [100%]

============================== 3 passed in 3.74s ==============================


License:
MIT License
