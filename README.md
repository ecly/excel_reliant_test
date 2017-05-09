# How to test:

 - First run both the tests without Code Coverage *(NUnit 2 Test Adapter needed for NUnit test)*
 	+ Observe them both executing just fine.
 - Run one of them with Code Coverage
 	+ Hangs indefinitely and never closes instance.
 - To prepare for second test, restart Visual Studio and ensure that the background Excel instance is closed manually. Do this through Task Manager and merely look for EXCEL.EXE
 - Now attempt to run the second test and observe the same behavior as seen in first test.