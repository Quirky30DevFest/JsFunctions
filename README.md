# JsFunctions
You should:
* fork this repo
* link your forked copy of the repo to the upstream repo to get changes easily 
* To see how to do that have a look here: https://help.github.com/articles/syncing-a-fork/
* regularly update from upstream to check for changes
* use TDD
	* start looking at [Qunit](http://qunitjs.com/) 
	* From now on use Qunit 
	* Setup a [Travis](https://travis-ci.org) and start monitoring your tests
* commit to GIT regularly

# These things count:
* regular commits
* testable code
* passing test
# The functions

The function name and the file name should be the same

For example for hello.js the function should look like this:

```
function hello(){
	// your code goes here
}
```

Each function should have a test file called functionname_test.js

For ```hello.js``` it should be called ```hello_test.js```


> If any of these function specifications don't make sense, let's discuss, clarify and change it. 

Create a function that:

 #|File name & function name | Write a function that?
---|----------|-------------------------------------------------------------------------------------
1| hello.js | return "hello world"
2| hello_uppercase.js| takes a username as parameter and returns "Hello, < USERNAME parameter >!"
3| hello_joe.js | takes a username as parameter and returns as "Hello, < USERNAME parameter >!" if the username is Joe or Bob only say "Hello!"
4| number_list.js |takes a number as a parameter (n) and return a list of number from 1 to n
5| sum_numbers.js| takes a number as a parameter (n) and return the sum of numbers from 1 to n
6| length.js|takes a string parameter and return the length of the supplied parameter
7| upper.js |takes a string parameter and return the supplied parameter in uppercase
8 |reverse.js|takes a string parameter and return the reversed string parameter
9 |hello_list.js| takes a number as parameter and return a list of "hello world" entries equal to the number supplied
10 |high_low.js| given a list of numbers returns the highest and lowest numbers in the list
