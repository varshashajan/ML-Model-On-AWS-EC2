# ML-Model-On-AWS-EC2
Completion of my portfolio project on building an end-to-end machine learning model deployment on an AWS EC2 instance for predicting student placement.
Brief overview of project:
1. Build the model : Started by cleaning the dataset and identifying the key features. Accuracy of the model is a crucial part and finally collecting the various insights.
2. Export the model using Pickle : The model was then saved and loaded using pickle
3. Build a Flask website to serve the model : To making it easy for anyone to interact with the predictive tool i initially hosted it as a web application using Flask.
4. Deploy the website on AWS EC2
   -- Create an AWS account
   -- Create an EC2 instance
   -- Edit the security group
   -- Download keygen(pem file)
   -- Download and install Putty and WinSCP
   -- Upload Flask website to EC2 using WinSCP
   -- Install packages on EC2 using Putty
