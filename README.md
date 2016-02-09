# perl_test

Test cases in perl using the perl Test::Simple module which has the basic functionality for testing.

As shown in the above sample code-snippet, its a simple program that has two functions; one to print a statement, and another to return random number within 1000.

Ok() is the function to test a given test case

ok( actual-testcase, testcase-name );

Let us take the first one, it calls the function(i.e:hello_world()) and matches the return value with a string(i.e: “Hello world!”). On success, it says “ok 1″ otherwise “not ok 1″ along with the test case name (i.e: My Testcase 1).

Similarly the second one, it calls the function get_number() and checks the return value is greater than 0. On success, it says “ok 2″ otherwise “not ok 2″ along with the test case name (i.e: My Testcase 2).
