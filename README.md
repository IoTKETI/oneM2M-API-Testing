## **Introduction**

 A suite of Postman script is provided to familitate the use of oneM2M complied server platform - [Mobius](https://github.com/IoTKETI/Mobius). 
 - The Postman scripts covers operations of CREATE, UPDATE, RETRIEVE, and DELETE for following resources:
    + **AE**,
    + **accessControlPolicy**, 
    + **CSEBase**,
    + **container**,
    + **contentInstance**,   
    + **group**,
    + **locationPolicy**,  
    + **mgmtObj including Battery, firware, DeviceCapacity, DeviceInfo, and Reboot**,   
    + **node**, 
    + **remoteCSE**,
    + **semanticDescriptor**,
    + **subscription**,
    + **timeSeries**, and
    + **timeSeriesInstance**.
 - Discovery function is also demonstrated with applied filter criteria conditions as following:
    + **resourceType**,
    + **limit**,
    + **stateTagBigger** and **stateTagSmaller**,
    + **createdBefore** and **createdAfter**,
    + **sizeBelow** and **sizeAbove**,
    + **modifiedSince** and **unmodifiedSince**,
    + **expiredBefore** and **expiredAfter** 
    
 ## **Get Started** 
 
 The API script is developed via Postman. The Postman is a powerful API development tool, and if you have not yet install it in your machine, you can download it from [here](https://www.getpostman.com/). 
 You can download or clone the Mobius API script from [here](https://github.com/IoTKETI/oneM2M-API-Testing/blob/master/Mobius_API_Release2.postman_collection.json).
 
 - Import the downloaded Postman script into your Postman collections via "import" feature of Postman.
 - Configure the management environment of your postman in terms of configuration of the CSEBase (cb) and the Mobius server URL (mp_url). You can create a new **Manage Environment** in the Setting of Postman.
 - Select any one script from a list of script, and click "Send" to try sending a request to Mobius.
 
 
 
 
 
