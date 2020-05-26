## These notebooks are part of the Amazon workshop
## "Applied Machine Learning with SageMaker"


### Hypothetical Situation
You are Data Scientist working for a Mid-Size Cellphone povider - "Atizen". Market for cellphone services have become extremely competitive and your employer has started to lose out the customers to competition. An internal analysis has indicated that in the hyper-competitive *Atizen* MUST pro actively work on retaining the customers as once the customer has left it is virtually impossible to get them back due to the one year contracts they sign.

Business leadership has come up with a strategy that requires pro active customer reach out to prevent them from leaving *Atizen*. The customer care team was given the owner ship of the task to reach out to customers who are at a high risk of separation from *Atizen*. 

*Atizen* has roughly 7 Million customers. The customer care team is a 50 member team. It is practically impossible to call every customer to understand their risk of separation. A better strategy is needed!!!

You are given the task of understanding the historical data to come up with a report that will identify the current customers who have a high risk of separation. Here is how the data looks like.


## Common Issues
1. The Notebook Markdown sections are un readable (green ones)
   *Fix:* Change the Theme for Jupyter Notebooks
        * Click on Settings
        * Select JupyterLab Theme
        * Select either 'JupyterLab Light' or 'JupyterLab Dark'

2. My notebook has become unresponsive 
   *Fix:* Reload the notebook using the browser reload

3. I am getting permissions issue on S3 bucket
   *Fix:* You MUST create an S3 buck for use from the notebooks
   Scripts require you to change the name of the bucket. If you missed that step then you would get a "permissions error on S3"

4. I messed up when creating the "Studio" - what do I do?
   *Fix:* No worries - we will need to recreate the studio
   1. Click on the gear in the user section
   2. Delete the "App"
   3. Delete the "User"
   4. Come to the studio screen & delete the studio
   5. Now follow the instructions to recreate the studio



### Info on setup
- Jupyter 101
https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook

- Use this as the guide
https://gitlab.com/juliensimon/aim307/-/blob/master/aim307.ipynb

- Data Analysis
https://github.com/awslabs/amazon-sagemaker-examples/blob/master/introduction_to_applying_machine_learning/xgboost_customer_churn/xgboost_customer_churn.ipynb

- Companion video
https://www.youtube.com/watch?v=D04dxTiDO3E&feature=youtu.be


[[https://github.com/acloudfan/ID-SMS-V0520/blob/master/images/create-new-experiment.png|alt=octocat]]