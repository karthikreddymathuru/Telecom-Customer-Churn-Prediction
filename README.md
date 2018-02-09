# Telecom-Customer-Churn-Prediction

To predict the telecom customers who are likely to exit the contract and also to generate patterns
of Churn and non-churn to assist the management to take appropriate decisions to limit churn.

Most telecom companies suffer from voluntary churn. Churn rate has strong impact on the life
time value of the customer because it affects the length of service and the future revenue of the
company. It is estimated that 75 percent of the 17 to 20 million subscribers signing up with a new
wireless carrier every year are coming from another wireless provider, which means they are
churners. 


Attribute Information:  The dataset depicts the details of the telecom customer, like, services that each customer has signed for, customer account information , and their demographic info etc.

Information about attributes:

Demographics Data :

	•	HouseholdID : Each Household id
	• 	Country : Country. ( For this attribute, missing values are denoted as “?”)
	•	State : State ( For this attribute, missing values are denoted as “?”)
	•	Retired : Whether retired
	•	HasPartner : Demographic information - whether the customer has partner ( 1-Yes; 2-No)
	•	HasDependents : Demographic information - whether the customer has dependents ( 1-Yes; 2-No)
	•	Education : Education qualification
	•	Gender : Demographic information – gender

Account Information :

	•	CustomerID : CustomerID
 	• 	BaseCharges : Customer account information (Charges for Base plan)
	•	DOC : Date of data collection
	•	TotalCharges : Customer account information (Total). ( For this attribute, missing values are denoted as “MISSINGVAL” 					also)
	•	DOE : Date of entry as customer
	•	ElectronicBilling : Customer account information - whether electronic billing
	•	ContractType : Contract type ( For this attribute, 	missing values are denoted as “NA”)
	•	PaymentMethod : payment method

Data of ServicedOptedFor : 

	•	CustomerID : CustomerID
	•	TypeOfService : Service signed for    
	•	SeviceDetails : 

Churn Data : 	

	•	CustomerID : Customer ID
	•	Churn : Whether the customer churns  (Target)
  
  
Error Metric :  "Recall" maintaining accuracy.
