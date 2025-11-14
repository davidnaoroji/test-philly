# SOP Philly

1. Go to Maola Philly Orders group and find new order email(s). Open up order form.

2. Go to SAP, Create Sales Orders. Enter ZOR7 in Order Type:, 1000 in Sales Organization:, 10 in Distribution Channel:, 20 in Division:, hit Continue.

<img width="673" height="450" alt="image" src="https://github.com/user-attachments/assets/c8710ad5-fec5-4147-b5ad-866144c6466b" />

* Login screen for creation of SAP

3. Evaluate the order form. Each order form will be different. Look for the PO Number, the Ship to Address, and the Delivery Date. 

<img width="800" height="494" alt="image" src="https://github.com/user-attachments/assets/60472524-36fc-49b8-b557-b333cb8efc36" />

* Order Sheet

4. In the Philly sheet, go to Philly Details, enter the date that the order form came in Order Date. Go to the Cust List sheet and look for the DC Name associated with the Ship To Address. (In this case, the DC Name is Ingles-1).

<img width="975" height="461" alt="image" src="https://github.com/user-attachments/assets/9d94691e-d26e-4cc0-9caa-9300d97b2445" />

* Phildephia Orders Excel Sheet - Shows different vendor and distinctions between vendors and orders

5. Go back to Philly Details and in Customer enter the DC Name. Drag the Ship To #, Sold To #, Street Address, City, and Sate from the previously entered order down to the row you are on. In Cust Ref PO#, enter the PO Number. Leave the SO# blank for now. Drag the previously entered Day down to the row you are on (the correct day will automatically be added in). In Del Date, enter the delivery date. Type in YES or NO if the order is in SAP (this is used to track the orders you are working on). Keep in mind the OTD which shows the days between the day the order form was sent to the delivery date. 

<img width="975" height="102" alt="image" src="https://github.com/user-attachments/assets/374a35b9-62d8-4723-82bf-f98c54f6baaf" />

* Philly details tab containing orders and vendor information

6. In SAP, you will only need to enter the following details. 

<img width="1087" height="508" alt="image" src="https://github.com/user-attachments/assets/c8fecc06-13bf-4641-8913-09924310bfcc" />

* SAP Orders Screen

7. Enter the Sold-To Party, the Ship-To Party, the Cust. Reference, and Req. Deliv. Date (See the Philly Details sheet) into SAP. 

<img width="822" height="577" alt="image" src="https://github.com/user-attachments/assets/53bda991-3264-4b03-8b8f-e1c6b953d439" />

* SAP Order details filled

8. View the order form to find the items and the cases needed for each item. 

<img width="975" height="194" alt="image" src="https://github.com/user-attachments/assets/f1846efd-5fed-4230-9956-0f6ba87eb0fa" />

* Order form details view only product and case count

9. In the Philly Details sheet, find the SKU based on the items on the order form. 

<img width="749" height="372" alt="image" src="https://github.com/user-attachments/assets/37cb5434-5e70-489a-bb27-dcc75ddc73ed" />

* Philly details tab that contains products by SKU where you manually enter case quantity

10. Once you are done entering the item quantities, go to the very first SKU and highlight from the first SKU to the last SKU (including the cells you entered quantities in). In the Home tab, go to Find & Select, Go To Special, select Blanks, Click OK. This will highlight only the cells that do not contain quantities. Type 0 and then press Ctrl + Enter. This will automatically fill the blanks with 0.

11.	Enter the quantities in SAP. Examine what the SKU number is and the quantity. After inputting the SKU number and  the quantity, hit enter to enter each item. The Item, Un, Item Description, ItCa, D.., First Date, Plnt get automatically filled in. Once the order(s) have been entered, click Save.

<img width="1117" height="109" alt="image" src="https://github.com/user-attachments/assets/f5a0d98f-cd28-4088-8ff7-845723b36187" />

* Enter products and quantites into SAP

12. At the bottom of the screen, the SO# appears. Record it in the Philly Details sheet.

<img width="567" height="89" alt="image" src="https://github.com/user-attachments/assets/2814e3ef-d037-4fd4-8047-24b6911e1a6e" />

* SO is created

<img width="975" height="107" alt="image" src="https://github.com/user-attachments/assets/2006a945-5320-43dc-945e-294e2416a013" />

* Manually enter SO into Philly Details tab

13. Go to Philly Compliance sheet. This sheet mirrors whats in Philly Details. The Details sheet focuses on what was ordered and the Compliance page focuses on what we set the order to. Copy the row(s) you worked on and paste values. This gets rid of formulas and pastes the data as numbers.


14.	Open up the Philadelphia Delivery Confirmation Sheet and go to the bottom. Copy the Order Date, Customer Name, Street Address, City, State, PO Number, Cases, SO Number, and Delivery Date into the sheet.


15.	For the Pick Up Date and the Load Out Date, refer to the Cheat Sheet tab based on the Customer Name. (In this case, the Customer is Ingles). View the chart and to see what the Pick Up Date and Load Out Date is supposed to be. (In this case, it’s 1 day before the Delivery Date). 

<img width="975" height="368" alt="image" src="https://github.com/user-attachments/assets/518e5489-8a0f-4932-a2fd-4c7683b6fd88" />

* Philly deliver date scheduled

16. Enter the date(s) in the Pick Up Date and Load Out Date.

<img width="1082" height="109" alt="image" src="https://github.com/user-attachments/assets/e8db986d-f8b4-4c42-b609-013e6fd630c5" />

* Order details for delivery

17.	Go back to the Philly Order Sheet and go to the Philly Compliance page. Set the row(s) you worked on to match the rows above in formatting. Highlight the row above that is not in dark blue (up until you see the total quantity of cases across all SKUs), go to the Home tab and click on Format Painter. Highlight the row(s) you worked on. 

<img width="1403" height="68" alt="image" src="https://github.com/user-attachments/assets/02bccb5e-6b35-411f-a128-6b6982e99c08" />

<img width="1131" height="65" alt="image" src="https://github.com/user-attachments/assets/93beb42d-050f-4cfd-a266-9efc6b1f4b7c" />
