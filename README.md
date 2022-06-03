**Courier Management System
(Ashutosh Aswani)**

**Abstract:**
Our project is basically a courier system and we have two entities in this courier system. When we see the login panel, we see there is an option for admin and another one for the customer in the login panel. The admin can actually change the details of the delivery executives and also update the delivery related details like delivery person name and expected delivery date for each and every order ID and in the customer panel, we have different options like track order, wallet, my orders, help, and pick up also. In the track order panel we can enter the courier ID and track our courier, in my order section we can enter our name and see all the courier orders placed by us, then in the wallet, we can add or withdraw money and when we place an order for pick up of a courier the money is directly withdrawn from the wallet itself and in the pickup panel, we can place a request to pick up the parcel from a particular address and deliver it to a particular address.

**Software Used:**
MySQL , Netbeans IDE 

**Programming Language Used: **
Java

**OOPs concepts used:**

**Method Overloading**

Method overloading has been used while taking the wallet initial balance when a new customer registers and thus there are two methods which are overloaded and one of them takes 4 parameters and the other takes 5 parameters. If the wallet balance is given then 5 parameters would be passed or else only 4 and default value of wallet would be 0 in the sql query executed.

**Constructor Overloading**

Constructor overloading has been used in the pickup panel where the mobile number field has been kept optional and so thus the number of parameters passed varies depending upon if the mobile was entered.

**Multiple Inheritance using interface implementation**

Multiple inheritance has been implemented by creating an fetchMobileNumber interface and then in the pickup class it has been inherited and the fetchMobileNumber1 method to fetch customer mobile has been overridden.

**this keyword**

this keyword has been used to refer to the current instance of the class and thus close it by using setVisible as false and create an object of other class to open and make it visible by using setVisible - true.

**Exception handling using try-catch block**

Exception handling has been used at several places for ensuring that if any error occurs while establishing a connection with the database then the exception is caught and to ensure that the wallet balance and the mobile number are always entered numeric so they have been parsed into integer and if any exception occurs in parsing that means some other character instead of an integer has been entered into a mobile number or wallet balance and there is a number format exception and that exception would be caught by the catch block.

**Method Overriding for methods in interface**

Method overriding has been used while giving the definition to the fetchMobileNumber1 method of the fetchMobileNumber interface and it is used for to autofill mobile number of customer by name in the pickup panel.

**Final keyword**

The final keyword has been used in the customer registered panel in the sqlQuery method of the query class so as to prevent it from being overridden in some other class.

**Static keyword**

Static keyword has been used in the sqlQuery method of the query class in customer register panel so that it can be called without the creation of an object as it belongs to the whole class and no meaning for it to be specific for every instance of the class.

**Protected keyword**
Protected keyword has been used in the sqlQuery method of the query class so that it is not accessible from other packages.

**Encapsulation**

Encapsulation has been used while overriding the fetchMobileNumber1 method as it takes the input parameter of name and returns the mobile number and is thus similar to get and set methods as we use while encapsulation for read and write operations.

**Issues faced**

Another problem we faced was the simultaneous working of multiple team members on the project as some had installed the Oracle NetBeans and after sometime it was removed from the web and only Apache netbeans was available which was very similar but had a few changes like we were not getting the Libraries option in it and we had to import a MySQL jar file in the Libraries folder to establish connection with the database and so working was getting difficult at initial stage though later the issue was solved.

**Screenshots:**

![image](https://user-images.githubusercontent.com/78266562/171876199-2859e2e1-84f5-4993-ac4d-c2a3624302d2.png)
![image](https://user-images.githubusercontent.com/78266562/171876720-03674b32-9c81-4463-995d-97cc705ef8e2.png)
![image](https://user-images.githubusercontent.com/78266562/171877000-2c144804-e8aa-46b5-8e6e-e22148249a7e.png)
![image](https://user-images.githubusercontent.com/78266562/171877020-611a59ba-aba6-4fd8-90a4-437479b82d8d.png)
![image](https://user-images.githubusercontent.com/78266562/171877186-84e66cf0-403d-446b-9411-643815d4b379.png)
![image](https://user-images.githubusercontent.com/78266562/171877213-38ccd866-4b8f-4cfa-9a1b-72a88a11b730.png)
![image](https://user-images.githubusercontent.com/78266562/171877280-11960415-ed3c-4217-bd89-a1aaa8ab7b5d.png)
![image](https://user-images.githubusercontent.com/78266562/171877309-b26be7aa-20b1-4742-8ecb-b55a853804ae.png)
![image](https://user-images.githubusercontent.com/78266562/171877347-954cf5ba-b173-4089-8034-a074219e09f3.png)

**UML Diagrams**

<img width="623" alt="Screenshot 2022-06-03 at 8 15 46 PM" src="https://user-images.githubusercontent.com/78266562/171877515-8e1b4350-0f31-466c-b418-54f4c78fe2c1.png">
<img width="417" alt="Screenshot 2022-06-03 at 8 16 00 PM" src="https://user-images.githubusercontent.com/78266562/171877557-9a83b663-3181-438c-809a-aae9fba85f19.png">
<img width="427" alt="Screenshot 2022-06-03 at 8 16 11 PM" src="https://user-images.githubusercontent.com/78266562/171877592-76b0fdd5-973a-47af-b5a8-f5874d07de23.png">
<img width="427" alt="Screenshot 2022-06-03 at 8 16 21 PM" src="https://user-images.githubusercontent.com/78266562/171877612-bea3381d-2477-4a45-9e43-90e74604878e.png">
<img width="427" alt="Screenshot 2022-06-03 at 8 16 30 PM" src="https://user-images.githubusercontent.com/78266562/171877636-fb3ed8a9-059d-41a4-9e74-694f1b3fca7a.png">
