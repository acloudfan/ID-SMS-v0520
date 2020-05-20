## 1. Create the Studio

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