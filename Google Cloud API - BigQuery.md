
How to Configure Google BigQuery API?
========

### 1. Authentication Error
```
Could not automatically determine credentials. 
Please set GOOGLE_APPLICATION_CREDENTIALS or explicitly create credentials and re-run the application. 
For more information, please see [https://cloud.google.com/docs/authentication/getting-stted]
```

### Solution
If you get this erroor, you should first follow the instruction on [Getting Started with Authentication](https://cloud.google.com/docs/authentication/getting-started).

1. Please make sure that a **service account** has been created and a **JSON file** containing your key has been downloaded.

2. Please check if you have [authenticated to your Cloud API Services](https://cloud.google.com/video-intelligence/docs/common/auth).

3. Please check if authentication credentials have been provided to your application code. 
  
      **The recmondeded way to realize it is to set an environment variable**. 
      
      > For Windows users, you can do it **with PowerShell** or **with command prompt**.
      >
      > However, this variable only applies to your current shell session, so if you open a new session, set the variable again.
      
      **So, a better way is to set your ***GOOGLE_APPLICATION_CREDENTIALS*** by adding a new variable form "This PC/Property"**

![Google_Cloud_API_Environment_Variable](https://github.com/kathy9980/Install-Software-Python-Packages/blob/master/Google_Cloud_API_Environment_Variable.png?raw=true)
