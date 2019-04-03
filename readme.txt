python -m unittest -v xk_unittest_Person.Testing


How to run python unittest module
If you’re using PyCharm IDE, you can simply press ctrl+shift+F10 to run unittest module. Otherwise you can use command prompt to run this module. For example, we named the file for unit-testing as Basic_Test.py. So the command to run python unittest will be:


$python3.6 -m unittest Basic_Test.Testing

If you want to see the verbose, then the command will be;


$python3.6 -m unittest -v Basic_Test.Testing


Note that the unittest module executes the test functions in the order of their name, not in the order they are defined. And since we want our set_name test to execute first, we have named our test case functions as test_0_set_name and test_1_get_name.

test_: function to test
