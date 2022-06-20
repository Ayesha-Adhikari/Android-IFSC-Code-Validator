# Android-IFSC-Code-Validator
Indian Financial System Code or more popularly known as IFSC is a unique code assigned to each bank branch and used for online money transfers. 

This Android application provides an API that helps in the reverse lookup to search bank and branch details for a given IFSC code.

The Application displays the following information about the bank and its branch:
•	General bank information Name of the bank, bank code, branch IFSC code, branch MICR code
•	Branch location Name of branch, address, city, district and state


About the project:
This android application is basically a demonstration of the Volley library.
Volley is an HTTP library, developed by Google to provide a networking class capable of working without interfering with the user experience. 
It manages the processing and caching of network helps in Request queuing and prioritization, 
effective memory management, and allows customization of the library as per our needs.

In this application, I first designed a simple layout.

![image](https://user-images.githubusercontent.com/64662434/174663389-b463f240-ca3b-4ad5-a656-e7d1004b1fc3.png)

 
After that, I initialized the components of the Main Activity and also created a new Request Queue using Volley library to fetch the data from the IFSC API provided by Razorpay.


Then, using the JSONObjectRequest class, a request is made to the specified URL and a JSONObject response is received. Using this response object, the details of the bank is extracted from the JSON file and displayed in the Application.



