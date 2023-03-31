# Amazon SageMaker

- Amazon SageMaker is one of cloud based machine learning platform.
- It has been launched by AWS in November 2017.
- It lets us create, train and deploy machine learning models quickly in the cloud by using Amazon Sagemaker.
- It uses number of languages such as Python, Ruby, Java, JavaScript, Go.

# Amazon SageMaker Notebook Instance

- It is machine learning compute instance.
- It is used to create instances and related resources.
- These instances let us run Jupyter Notebook Applications and JupyterLab.
- While creating notebook instances, we need to attach or create S3 bucket for the storage purpose of these notebooks.
- We have been provided with sample notebooks as well for reference.

## Now, let's have look at how to create AWS SageMaker Notebook Instance

1. First search for Amazon SageMaker Service on AWS dashboard after signing in to console.

2. Next, you will be able to see many options in the left side bar.
   From there, select *Notebook* option
   ![image](https://user-images.githubusercontent.com/66831307/229079382-a1111715-ca7e-44df-9916-27c5cc42e3f1.png)

3. In Notebook, there are two options available as shown below-
   ![image](https://user-images.githubusercontent.com/66831307/229079663-4a0126d3-9e3a-4c45-8cfe-de47278cf7b7.png)
   
4. If we opt for Notebook Instance.. Let's see what next?
   - We will get an option to create notebook instance
     ![image](https://user-images.githubusercontent.com/66831307/229080730-5ec8d914-3059-4a60-96e6-9a288d1ebe51.png)

  i. Now, let's create a new notebook instance
     ![image](https://user-images.githubusercontent.com/66831307/229081083-28e753c7-f563-4485-be7d-55d062e85630.png)
     As shown in the figure, add instance name, type and platform identifier.
     Then need to add permissions(IAM Role)
     ![image](https://user-images.githubusercontent.com/66831307/229082142-cdb0c64f-6a43-45a2-bfbd-89104badf78c.png)
     We can keep other settings as default.
     
  ii. Now, my notebook instance is ready, let's have look at it-
      ![image](https://user-images.githubusercontent.com/66831307/229082952-2f32471f-a0e4-43ca-9f9b-0ce4664efd63.png)
      From here we can go with either Jupyter or JupyterLab.I have opted for Jupyter.
      ![image](https://user-images.githubusercontent.com/66831307/229083571-1289c28c-80fb-4f92-b094-382d93542921.png)
      And here is the newly created Jupyter Notebook.
      
  iii. We are having these many option available to create a notebook-
       ![image](https://user-images.githubusercontent.com/66831307/229084139-a9679b21-42c8-40ff-95ad-0d47db486e2b.png)
       
       I am opting to upload my previously availabe dataset and python code file for house price prediction
       ![image](https://user-images.githubusercontent.com/66831307/229085264-5486c56e-f6f3-48b6-aae3-0bb06c19ea49.png)
       My files has been uploaded. We can run it like usual jupyter notebook and can train our model.
       
 5. If we choose Git Repositories in place of Notebook Instances,
    We just need to add Git Repository
    ![image](https://user-images.githubusercontent.com/66831307/229086200-2b206040-848e-490c-b5e4-26a1e42a2f4e.png)
    ![image](https://user-images.githubusercontent.com/66831307/229086542-871bb7b9-07bd-421a-bc32-1700964ff427.png)
    I have added a git repository as shown below-
    ![image](https://user-images.githubusercontent.com/66831307/229087837-3036a0a6-3bb9-4c43-9126-83459a497e7c.png)
    We can associate these repositories as default or additional repositories to notebook instances.
    
    And here we have covered Notebook section of Amazon SageMaker.
    
    Thank You!
    
    See you soon with next interesting blog.👋







     
