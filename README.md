# Bug-Samples
___
Below are some Bug samples that I wrote from my experience.
___

_Title:_ Invalid card number <br/>
_Description:_ We should not be able to make an order with an invalid card number <br/>
_TestCaseId:_ TC2 <br/>
_Status:_ OPEN <br/>
_Raised By:_ Kinga <br/>
_Application Version:_ - <br/>
_Steps to Reproduce:_<br/>
1. Open https://demo.guru99.com/payment-gateway/purchasetoy.php
2. Choose: Quantity 1
3. Press Buy
4. Fill all information for card (invalid card)
5. Press Buy

_Expected Results:_ We should receive an error message <br/>
_Actual Result:_ We receive Payment successful and an Order ID <br/>
_Priority:_ 1 <br/>
_Severity:_ 1 <br/>
_Files attached:_ <br/>

![image](https://github.com/DeeKinga/Bug-Samples/assets/131695090/65b10639-b229-4759-8ced-6c813acc2113)
![image](https://github.com/DeeKinga/Bug-Samples/assets/131695090/c0a1f8a5-42fc-4058-ba94-74ab63320ea6)

___

_Title:_ Responsive  <br/>
_Description:_ Responsive in all devices from the developer tools <br/>
_TestCaseId:_ TR1 <br/>
_Status:_ OPEN <br/>
_Raised By:_ Kinga <br/>
_Application Version:_ - <br/>
_Steps to Reproduce:_ <br/>
1. Open https://demo.guru99.com/payment-gateway/purchasetoy.php
2. Go to More tools-developer tools
3. Dimension: Responsive

_Expected Results:_ Should be responsive in all devices shown in the developer tool <br/>
_Actual Result:_ The menu bar doesn’t appear in all the devices <br/>
_Priority:_ 1 <br/>
_Severity:_ 3  <br/>

![image](https://github.com/DeeKinga/Bug-Samples/assets/131695090/3614d454-2999-46c1-9603-b956dff39bc6)

___

_Title:_ Back button <br/>
_Description:_ After we purchased the product we shouldn’t be able to return to the page with the card details by pressing the back button <br/>
_TestCaseId:_ TB1 <br/>
_Status:_ OPEN <br/>
_Raised By:_ Kinga <br/>
_Application Version:_ - <br/>
_Steps to Reproduce:_ <br/>
1. Open https://demo.guru99.com/payment-gateway/purchasetoy.php
2. choose: Quantity 9
3. press Buy
4. fill in all information for the card
5. Press Buy
6. press the back button

_Expected Results:_ We should receive an error message <br/>
_Actual Result:_ We can go back to the purchase page which contains the card details <br/>
_Priority:_ 1 <br/>
_Severity:_ 1 <br/>

![image](https://github.com/DeeKinga/Bug-Samples/assets/131695090/5afc3996-beb4-436d-9d60-961f7b2c5303)

___

_Title:_ Quantity with a negative value <br/>
_Description:_ We should not be able to complete an order with a quantity with a negative value. This value is modified in the code source to a negative value. <br/>
_TestCaseId:_ MC3 <br/>
_Status:_ OPEN <br/>
_Raised By:_ Kinga <br/>
_Application Version:_ - <br/>
_Steps to Reproduce:_ <br/>
1. Open https://demo.guru99.com/payment-gateway/purchasetoy.php
2. Choose: Quantity -15
3. Press Buy
4. Fill in all information for the card
5. Press Buy

_Expected Results:_ We should receive an error message <br/>
_Actual Result:_ We receive Payment successfully and an Order ID <br/>
_Priority:_ 1 <br/>
_Severity:_ 1 <br/>

![image](https://github.com/DeeKinga/Bug-Samples/assets/131695090/37377c68-058c-4302-a85d-6dae67a3b888)
![image](https://github.com/DeeKinga/Bug-Samples/assets/131695090/acfb891f-f93b-405f-9d34-c241398d5508)



