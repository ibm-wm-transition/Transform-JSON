# Transform-JSON

## Getting Started
The transform feature lets you perform various operations on the input data in order to help you customize your workflow output or the data you send to the next action. This feature is available in all actions supported by webMethods.io Integration. 
Following instructions will get you a copy of the specific JSON transform in your webMethods.io Integration tanent.
List of JSON transform available in the webMethods.io Integration are:
1. <b> Parse : </b>This operation lets you parse the given object.
2. <b> Stringify: </b>This operation lets you stringify the given object.

### Prerequisites
1. An account in [webmethod.io](https://www.softwareag.cloud/site/product/webmethods-io-integration.html) with webMethods.io Integration access.

### Importing the recipie to your webMethods.io Integration tanent:
1. Download the zip file from this github page.
2. Log in to your webmethod.io account then go to `webMethods.io Integration`.
3. Select `Reciepes` the click on `Import`.
![image](https://user-images.githubusercontent.com/60179170/88805095-5d798500-d1cc-11ea-97de-dec146247ecc.png)
4. Then select the downloaded file and click on `open`.
![image](https://user-images.githubusercontent.com/60179170/88921620-72b5e880-d28c-11ea-99ed-e4b24fe0e1fd.png)
5. After that you will be able the workflow in your recipie list.<br/>
![image](https://user-images.githubusercontent.com/60179170/88921699-96792e80-d28c-11ea-8471-4c46f4e25c02.png)
6. Click on that workflow and then select the project name where you want to import the workflow and click on `Done`.
![image](https://user-images.githubusercontent.com/60179170/88805882-5737d880-d1cd-11ea-8414-17324e86dcd6.png)
7. After that you will see a short description about that transform along with the workflow name. Click on `Import` here.
![image](https://user-images.githubusercontent.com/60179170/88921762-b3156680-d28c-11ea-8d2f-7ce4c4284ef1.png)<br/>
Yeee now you have succesfully imported the work flow.

### Run the workflow:
1. Go to that specific project where you have imported the workflow. Hover over the workflow that you have imported and click on `edit`.
![image](https://user-images.githubusercontent.com/60179170/88921888-e526c880-d28c-11ea-9e54-7ed9f1a34de4.png)
2. Click on the `edit` icon present in the top left corner.
![image](https://user-images.githubusercontent.com/60179170/88808530-a29fb600-d1d0-11ea-90e1-d4efeebfe853.png).
3. Now go to the workflow description and coppy the requested body. `only the JSON part`. And click `Done`.
![image](https://user-images.githubusercontent.com/60179170/88921945-012a6a00-d28d-11ea-824a-fc9547c90725.png)
4. Now `double click` on the start .
![image](https://user-images.githubusercontent.com/60179170/88809305-9700bf00-d1d1-11ea-91a2-235dfaf46578.png).
5. From the list click on webhook.<br/>
![image](https://user-images.githubusercontent.com/60179170/88810663-49855180-d1d3-11ea-914e-09f501278c2f.png)
6. Click `Next`.<br/>
![image](https://user-images.githubusercontent.com/60179170/88910377-05995780-d27a-11ea-99cc-b472dac0f0ef.png)
7. Now paste the coppied data in to the body and click `Next` and then `Done`.
![image](https://user-images.githubusercontent.com/60179170/88922065-35058f80-d28d-11ea-8017-19d77adbc959.png)
8. Now run the workflow it will give you output in the logger. 
![image](https://user-images.githubusercontent.com/60179170/88922165-60887a00-d28d-11ea-9abd-9ec776f6e0a9.png)

### Test With other input:
1. Open the weebhook and change the data inside the body. <b> Donot change the formte of the data. ie. "data1" is the formate of the data is JSON</b>.<br/>
![image](https://user-images.githubusercontent.com/60179170/88922381-a6454280-d28d-11ea-9ae9-cab58d4b1b55.png)
2.  Now run the workflow it will give you output in the logger. Here you can see the new array after a pop.<br/>

