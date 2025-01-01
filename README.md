Preclip data:
![image](https://github.com/user-attachments/assets/29af177b-e6c1-4bc8-b7e1-3638b9598a95)
![image](https://github.com/user-attachments/assets/91ecae4c-b8bf-4951-8cb5-26d9077c1bd3)

post clip data:

![image](https://github.com/user-attachments/assets/dc22eb23-44f0-4cc6-8c96-824af6a0f582)


post scaling data:

![image](https://github.com/user-attachments/assets/7964f208-1577-4b09-9d42-df5b638c99ff)


Analyzing pair: feature_00 and feature_02
R² between feature_00 and feature_02: 0.8924
Mean: -0.0000, Std Dev: 0.0679
![image](https://github.com/user-attachments/assets/2e8f05fa-2e32-42f2-a036-9dc64c604b97)
![image](https://github.com/user-attachments/assets/dbd6e39c-b496-4a20-bd3e-9eb5ac891b83)
![image](https://github.com/user-attachments/assets/9fcf2712-d0a7-4964-87eb-6fa786cf8674)

final cleaned data:
![image](https://github.com/user-attachments/assets/cd6aded8-419e-4adc-84a3-0e3c86709a2e)

top 10 important features determined by xgboost:
Top important features: [('responder_3', 108.0), ('responder_0', 80.0), ('responder_7', 33.0), ('responder_5', 20.0), ('responder_8', 18.0), ('responder_4', 13.0), ('feature_24', 11.0), ('feature_24_lag_1', 10.0), ('weight', 7.0), ('responder_2', 7.0)]

initial R-score(self determined):

![image](https://github.com/user-attachments/assets/a928aea6-1c6a-4ec5-a0f3-25acff94333e)

R-Score using only top relevant features:

20: 0.8409
25: 0.8426
30: 0.8397
35: 0.8349
40: 0.8386

Then, I used Binary search to find the actual max: 

correlation filtered(0.1):

![image](https://github.com/user-attachments/assets/30355066-0f34-4a1a-a665-5277b17fe165)

correlation filtered(0.3):

![image](https://github.com/user-attachments/assets/eaebeffe-94a2-4389-afc5-817429ae9cf4)
