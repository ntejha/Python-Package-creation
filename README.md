
# Step 01 : Account in PyPi

Just follow this :
1. go to : https://pypi.org/account/register/
2. Verify your email
3. Enable 2FA
4. Create a token

# Step 02 : Twine and pytest

just do pip install twine and keep it and also pip install pytest also.


# Step 03 : Project setup

In side the main folder create these files:
- __init__.py
- functions.py files
- setup.py
- README.md
- LICENSE
- requirements.txt
- 
Create a foldersand it create these two folders:
- examples : this should have the example of that function
- tests : this should have the same function files with test output

Inside the __init__.py file there should be the import all the py functions

Inside the ecample folder there should be one example .py file which call the functions and implement and check if it works.

Inside the test for each function test has to be created and kept inside.

In the LICENSE just put the MIT license content and put name front of name

Explain the whole package in readme.md file.

in requirements.txt file put the requirements for this function

in setup.py file do pip install setuptools and do the necessary, sample would like

![[Pasted image 20250316042126.png]]


# Step 04 : Test

Go in terminal navigate to test folder and put pytest and check if all gets passed.

# Step 05 : Build

Now just go to the main folder and pip install build and then python -m build, this will cause two files to appear tar.gz and .whl

# Step 06 : Test you tar file

locally test the package, pip install dist/location

and check the required if it works 

# Step 07 : Final touches

Once your confident it works, go to terminal and put twine upload dist/location

it will ask api key copy paste it then 


Once all is done go and check if everything is reflecting in the pypi file and all is well,



















