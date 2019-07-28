1. We are planning to build an Android Application with the following features:
2. Main Components of our app

   a) **Voter Account Management** :  
        Registering a New User and verifying his details, while login from user credentials and using OTP *two-factor-        authentication*.
        Passwords shall be stored in encrypted form in the database.
        Information Regarding the current election status in the user's constituency, as well as the parties manifesto, will be provided.
        
   b) **Blockchain-Based Voting Manager** : 
   
      **Double Voting Prevention** : This submodule safeguards the system against double voting, by associating it with a flag. This verification is deployed on the blockchain.
        
     **Vote Transaction** : The presence of user shall be verified by his fingerprint and vote cast by this user is recorded in the blockchain.
        
   c) *Unique feature* to attract the voters is by providing them some credits after casting the votes. These credits can be used for the discount in government services such as Electricity bill, Telephone bill, Adhaar update, etc.
   
3. User can save their time and energy spent in standing in the queue. It is also beneficial for *senior citizens* and *physically disabled people*. People who are not present in their constituencies like *students and job professionals* can also cast their vote using the same application. Special securities given to *famous personalities* can also be avoided.

4. Database will store details about voters like voter-id number, Name, Password, Phone number, City, State, etc.
5. We will build the app interface using Android studio and will write the code in `JAVA` and `XML`.The database will be managed using `MySQL` and deployed in `Azure`. Voting will be handled using `blockchain`.
