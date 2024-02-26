1. Check out the project
2. Open the project in IntelliJ(preferred)
3. Enable Gradle Auto-import and select Java 1.8 as SDK
4. Once Gradle import in done open database window and select H2
5. Please change configuration as mentioned in below picture
6. Please check public schema if tables are created
7. Username and password is manju and make sure it matches application.Properties
      file. (this is in memory db.)
8. Please open h2 console in IntelliJ and run the script from /bin/main/script.sql
9. Once tables are created please run RewardPointsCalculatorApplication.java
      from java/com/retailer/rewards
10. Open postman or any similar application and click
    

    http://localhost:8080/customers/1001/rewards

    http://localhost:8080/customers/1002/rewards

    http://localhost:8080/customers/1003/rewards

    http://localhost:8080/customers/1004/rewards