# OneWeekHackathon2020

 Our inspiration came from an idea of leveraging scenarios where we can join two Azure services Azure Sentinel and Azure Data Explorer (ADX) together. 
 
 Why Sentinel and ADX, what scenario is behind: 
 
 - Data scientists who are perhaps more used to working out of machine learning modelling specific tools such as Azure Data Explorer, Kusto explorer can easily import the necessary logs to aid their activity and also push back their results to augment the fraud detection workflows that are available out of the box in Sentinel. 
 
 - Customers are also currently facing issues related to Sentinel pricing in some regions of the world, where it has become more cost effective to purchase custom solutions that help filtering out most of the ‘non critical’ logs using alternate and cheaper Azure data lake and only stream in high fidelity logs to Sentinel such as in the picture below. Our project will continue to explore the feasibility of such cost-effective architectures and if they have an impact on the quality of the incidents detected or in the effectiveness of the hunting queries. The product could greatly benefit if such recommendations can be provided early in the evolution phase. 
 
 Besides such solutions also reveal how multiple azure solutions can be brought into serve the common purpose of SIEM and security and thereby more thought can be invested on the integration points between such components. 
 
 In short words: We are focusing on a solution to filter the log data before ingesting into LA and leveraging the ML. The outcome from the Hackathon will be IT and ML architecture and further steps for creating RNN for log anomaly detection.
 
 During this hackathon we would like focus on following steps divided into two segments: 
 
 Segment 1 - infrastructure (Azure Sentinel) 
 - present optimal way how data can be exported/imported from/to LA  
 - testing approach where we can aggregate log data and speed up in data preprocessing (aggregate the alerts based on rules we can create on the Sentinel site and make them available on the ADX site) 
 
 Segment 2 - ML 
 - plan for data preprocessing for RNN 
 - plan for test and build models 
