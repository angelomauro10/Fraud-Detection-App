This Fraud Detection App has a purpose to predict fraudulent transactions according its data analysis and modeling predict process, and the construction of this fraud detection as app with various fields for manipulating a wide of options in the UI.

This repository has the following docs:

1. fraud_detection_app.ipynb : Starting this notebook, we look the notebook architecture. In this file we find all the data analysis, modeling and web app contruction.

2. fraud_app.png : An image with the UI app view.

3. fraudulent_1.png : Image as example with the first fraud completition brackets altering the following fields:

            Transaction Type: purchase
            Value: 'purchase' has been selected.
            
            Transaction Amount: USD 200,000.00
            Value: 200000.00 has been entered.
            
            Account Balance: USD 0.00
            Value: 0.00 has been entered.
            
            Customer Risk Score (0-1):
            Value: (Default) 0.5.
            
            Merchant Risk Score (0-1):
            Value: (Default) 0.5.
            
            Merchant Category: travel
            Value: 'travel' has been selected.
            
            Number of Transactions in Last 7 Days:
            Value: (Default) 5.
            
            Is International Transaction?:
            Value: Checked (True).
            
            Failed Transactions in Last 24 Hours:
            Value: (Default) 3.

4. fraudulent_2.png : Image as example with the second fraud completetion brackets altering the following fileds:

            Distance From Last Transaction (km):
            Value: (Default) 5.0.
            
            Debt to Income Ratio:
            Value: (Default) 0.5.
            
            Hour of Day:
            Value: (Default) 12.
            
            Credit Limit:
            Value: (Default) 5000.0.
            
            Country:
            Value: (Default) 'USA'.
            
            CVV Match?:
            Value: (Default) checked (True).
            
            IP Reputation Score (0-1):
            Value: (Default) 0.75.
            
            Calculated Balance Difference: transaction_amount - account_balance
            Value: 200000.00 - 0.00 = 200000.00.

            Prediction
            Value: Transaction is Fraudulent

5. legitimate_1.png: Image as example with the first legitimate completition brackets altering the following fields:

            Transaction Type: purchase
            Value: 'purchase' has been selected.
            
            Transaction Amount: USD 200,000.00
            Value: 200000.00 has been entered.
            
            Account Balance: USD 1000,000.00
            Value: 10000000.00 has been entered.
            
            Customer Risk Score (0-1):
            Value: (Default) 0.5.
            
            Merchant Risk Score (0-1):
            Value: (Default) 0.5.
            
            Merchant Category: travel
            Value: 'travel' has been selected.
            
            Number of Transactions in Last 7 Days:
            Value: (Default) 5.
            
            Is International Transaction?:
            Value: Checked (True).
            
            Failed Transactions in Last 24 Hours:
            Value: (Default) 3.

6. legitimate_1.png: Image as example with the second legitimate completition brackets altering the following fields:

            Distance From Last Transaction (km):
            Value: (Default) 10.0.

            Distance From Last Transaction (km):
            Value: (Default) 5.0.
            
            Debt to Income Ratio:
            Value: (Default) 0.5.
            
            Hour of Day:
            Value: (Default) 12.
            
            Credit Limit:
            Value: (Default) 300000.0.       
            
            Country:
            Value: (Default) 'USA'.
            
            CVV Match?:
            Value: (Default) checked (True).
            
            IP Reputation Score (0-1):
            Value: (Default) 0.75.
            
            Calculated Balance Difference: transaction_amount - account_balance
            Value: 200000.00 - 10000000.00 = -800000.00.

            Prediction
            Value: Transaction is Legitimate
