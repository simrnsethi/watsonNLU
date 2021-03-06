
Getting Started with watsonNLU
==============================

J. Harmse, T. Haley, S. Sethi, V. Mulholland 2018-04-15

Installation
------------

### Sign up with IBM and download R package

To use the Watson NLU API you must create an account with the IBM developper cloud.

1.  Follow the link to the [Natural Language Understand](https://www.ibm.com/watson/developercloud/natural-language-understanding/api/v1/) page and follow the *Sign in to IBM Cloud* link or click ["Get Started Free"](https://console.bluemix.net/registration?target=%2Fcatalog%2Fservices%2Fnatural-language-understanding%3FhideTours%3Dtrue%26cm_mmc%3DOSocial_Tumblr-_-Watson%2BCore_Watson%2BCore%2B-%2BPlatform-_-WW_WW-_-wdc-ref%26cm_mmc%3DOSocial_Tumblr-_-Watson%2BCore_Watson%2BCore%2B-%2BPlatform-_-WW_WW-_-wdc-ref%26cm_mmca1%3D000000OF%26cm_mmca2%3D10000409_). Check your inbox to complete registration.

    ![](../doc/pictures/readme/1_addservice.png)

2.  Use your credentials to log in and add the [Natural Language Understanding services](https://console.bluemix.net/catalog/services/natural-language-understanding) and click "Create".

3.  Go to [Service credentials](https://console.bluemix.net/services/natural-language-understanding/3464cdba-a428-4934-945e-3dfd87d4e49c/?paneId=credentials&new=true&env_id=ibm:yp:us-south&org=89ae7f05-90ac-4efa-a089-e0a83704a79e&space=24853127-1fa6-4544-9835-e230bed91e8e) and create "New credentials". You may need to perform this step every time your credentials need to be updated.

    ![](../doc/pictures/readme/2_newcredentials.png)

4.  Use these credentials as the username and password within the R wrapper authentication function `auth_NLU`.

    ![](../doc/pictures/readme/3_viewcreds.png)

You can install watsonNLU in R from GitHub with:

``` r
# install.packages("devtools")
devtools::install_github("johannesharmse/watsonNLU")
```

Now you are ready to use [`watson_NLU`]()
