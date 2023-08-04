# Remote-Test-Harness
* Test Harness is a console application that would automate the testing process, it has three executables Repository, Client, and Test Harness Server.
* Repository maintains all the test code files to be tested, Client is a WPF application from which the user can send the test request in the form of XML to Test Harness and displays the test result in the WPF window and Test Harness executes the test request received from multiple clients. Downloads the test code and test driver from the repository server and sends the result back to the client.
* All the communication between the three executables is established using WCF communication
