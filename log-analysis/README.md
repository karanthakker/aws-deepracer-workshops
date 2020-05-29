## Contents

The notebook, `DeepRacer Log Analysis.ipynb`, steps through several analysis of data available after Deepracer training and evaluation jobs including the simulation trace data found in cloudwatch, the csv files found in the exported models, and even runs sample images through the network and shows the resulting activation nodes.

## How to use the notebook

1. Login to your AWS account - SageMaker service ([SageMaker Link](https://us-east-1.console.aws.amazon.com/sagemaker/home?region=us-east-1#/dashboard))
2. On the left tab select `Notebook instances`
3. Select `Create notebook instance`
4. Fill up the notebook instance name. In the Additional configuration select atleast 25 GB. This is because docker gets installed and takes up space.
5. Create a new IAM role. Give root permission.
6. Select the git repository and clone this repository (https://github.com/barberd/aws-deepracer-workshops.git).
7. Then click create notebook instance button at the button
8. This takes like 2 min to create your notebook instance. Then click on the newly created instance and click on the juypter notebook.
9. You will see all the github files.  Browse into log-analysis and start 'DeepRacer Log Analysis.ipynb'
10. Update the 'simulation_name' with your training and evaluation simulation job names.




