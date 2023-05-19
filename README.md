# CS682
Java Interoperability Unit Tests

Setting up the project:

Initially we create an atSign and place it in a keys folder containing the downloaded atKeys.

For Java client:
•	Pull the at_java repository from this link into your local machine with an IDE installed such as Eclipse/Visual Studio Code.
•	Install Maven dependencies by running the pom.xml file provided in the pulled repository.


For Dart client:
•	Pull the at_client_sdk repository from this link into your local machine with an IDE installed such as Eclipse/Visual Studio Code.
•	Install Maven dependencies by running the pubspec.yaml file present in at_client_sdk>tests.

Running the Project:
  Sending keys from:
   1.	Dart client to Java client: 
    a.	Open terminal/command line in Mac/Windows.
    b.	Type ./dartToJava.sh to run the script to send keys from dart client to java client.
    c.	The terminal should display the sent and received keys and namespace.
    
   2.	Java client to Dart client:
    a.	Open terminal/command line in Mac/Windows.
    b.	Type ./javaToDart.sh to run the script to send keys from dart client to java client.
    c.	The terminal should display the sent and received keys and namespace.

   

