<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">

<head>

<meta charset="utf-8">
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />


<div class="container-fluid main-container">

<div id="header">
<h1 class="title">Vehicle Insurance Fraud Detection Using Machine Learning- Capstone Project</h1>
<h4 class="date"><em><ol start="10" style="list-style-type: decimal">
</ol></em></h4>
</div>


<div id="synopsis" class="section level2">
<h2>Overview</h2>
<p>Vehicle insurance fraud detection using machine learning involves the development of algorithms and models to analyze large volumes of data related to insurance claims, policyholders, and service providers to identify potential fraudulent activities. By leveraging advanced machine learning techniques such as anomaly detection, classification, and regression, insurance companies can accurately detect and prevent fraud, thereby reducing financial losses and improving customer satisfaction. The process involves data preparation, feature engineering, model selection, training, and testing, followed by deployment and monitoring of the system. This approach can provide a cost-effective and efficient solution for detecting and preventing fraudulent insurance claims.
</p>
</div>
<div id="Objective" class="section level2">
<h2>Objective</h2>
<p>Vehicle insurance fraud is a significant problem that affects insurance companies, policyholders, and society as a whole. Fraudulent activities can lead to financial losses for insurance companies, higher premiums for policyholders, and even put innocent people at risk by allowing unsafe drivers to remain on the road. Machine learning-based fraud detection systems can help identify and prevent fraudulent claims by analyzing vast amounts of data and identifying patterns and anomalies that may indicate fraudulent activity. This can help insurance companies reduce their losses, minimize the impact on honest policyholders, and ultimately improve the overall integrity and sustainability of the insurance industry.</p>
</div>

<div id="DESCRIPTIONS" class="section level3">
<h2>Information about DataSet</h2>
<p>For our analysis, total <b>27</b> variables, where</p>
<li>the <b>RESPONSE VARIABLE(Y)</b> is <b>FraudFound_P</b> </li>
<p>and the <b>26 EXPLANATORY VARIABLES</b> are </p>
<li><b>WeekOfMonth</b></li> 
<li><b>WeekOfMonthClaimed</b></li>
<li><b>AccidentArea</b></li>
<li><b>Sex</b></li>
<li><b>MaritalStatus</b></li>
<li><b>Age</b></li>
<li><b>Fault</b></li>
<li><b>PolicyType</b></li>
<li><b>VehicleCategory</b></li>
<li><b>VehiclePrice</b></li>
<li><b>Deductible</b></li>
<li><b>DriverRating</b></li>
<li><b>Days_Policy_Accident</b></li>
<li><b>Days_Policy_Claim</b></li>
<li><b>PastNumberOfClaims</b></li>
<li><b>AgeOfVehicle</b></li>
<li><b>AgeOfPolicyHolder</b></li>
<li><b>PoliceReportFiled</b></li>
<li><b>WitnessPresent</b></li>
<li><b>AgentType</b></li>
<li><b>NumberOfSuppliments</b></li>
<li><b>AddressChange_Claim</b></li>
<li><b>NumberOfCars</b></li>
<li><b>Year</b></li>
<li><b>BasePolicy</b></li>
<li><b>ClaimSize</b></li>
</div>
<div id="conclusion" class="section level3">
<h2>Conclusion</h2>
<p>In the comparison of the five models based on the given AUC and accuracy scores, we can conclude that the Random Forest (RF) model has the highest prediction performance with an AUC score of 0.79, while KNN, RF, and SVM have the same accuracy score of 0.94, which is the highest among all models. Therefore, choosing the best model depends on the specific requirements of the task at hand, and both AUC and accuracy should be considered together while selecting a model.
Based solely on the AUC scores, the Random Forest (RF) model has the highest prediction performance among the models you listed with an AUC score of 0.79</p>
</div>
</body>
</html>
