# Assignment
1. Postman was used to write tests for 5 different API methods (POST, GET, PUT, PATCH and DETELE).
Test were written without authentication.

2. External test data source is used in PUT test. There are 2 types of external data files provided, 
however the data examples are the same in both files:
    1. DataStackExchangeforPUT.csv, 
    2. DataStackExchangeforPUT.json,


3. Json Schema validation example is added to GET test.

4. To perform CI integration Jenkins was used to run the test automatically. The command to run the test was used:
newman run https://www.getpostman.com/collections/37f95a508f5adc4300a2.

5. We can set up Jenkins or other Ci integration tool that our automated test would run after every new version of 
software is compiled/build/packaged and is ready for testing. 

6. We can also set up the automated test sequence and conditions under which test should be run (previous test is passed/failed etc.).

7. Test scenarios and test cases are placed in document: Test cases for StackExchangeAPITest.xlsx.

Thank you for your time.
