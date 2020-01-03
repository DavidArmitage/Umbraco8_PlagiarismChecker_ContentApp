-----------------------------------------------
Umbraco8 Plagiarism Checker ContentApp
-----------------------------------------------
This is a content app to assist content writers checking their content is not Plagiarised and duplicated on other websites. This makes use of Copyscape API which is a very cheap paid API service. Users are required to create an API key. Information how to do this can be found in the documentation.

For trial purposes I have added an API key with some credits. Once you have reviewed the app please create your own API key.

-------------------------------------
CONFIGURATION INSTRUCTIONS
-------------------------------------

COPYSCAPE API 
-------------------------------------
Please note this content app utilises copyscape API. You can find more information regarding the API here.
https://www.copyscape.com/api-guide.php


CREATE AN API KEY
-------------------------------------
You are required to create your own API Key to use within this content app. You can create an API Key for Copyscape here.
https://www.copyscape.com/signup.php?pro=1 - first register
https://www.copyscape.com/apiconfigure.php - then get your API key here


ADD THE USERNAME AND API KEY TO YOUR WEB.CONFIG
-------------------------------------
Once you have created an API Key you are required to add this and your username to your web.config file within the <appSettings> section.
EG.

<appSettings>
  <add key="CopyscapeAppUsername" value="YOUR USER NAME HERE" />
  <add key="CopyscapeAppApiKey" value="YOUR API KEY TO GO HERE" />-->
</appSettings> 


PURCHASE CREDITS
-------------------------------------
Copyscape is a paid service. When creating this app I had a good look around at all the options available. Some were free and some not. I tried and tested a few and decided this to be the best option.

This was based on quality and price. The API worked very well and the price was very cheap. You can find information regarding the pricing here.
https://www.copyscape.com/propurchase.php

Here are the prices the last time I checked.
https://www.copyscape.com/faqs.php#procost

Searches cost 3c for the first 200 words plus 1c for each additional 100 words or part thereof.


IMPORTANT! WHAT IS TEST MODE?
-------------------------------------
For the purpose of evaluating this content app I have added my own username and API Key. This is encrypted and compiled within a dll so you wont be able to see this in your web.config. 

If you don’t add an API key in your <appSettings> then this content app will assume you are using it for evaluation purposes. You will still have full functionality but there will be a red message at the top of the app reminding you that you’re still in ‘TestMode’. Once you add your API Key into your <appSettings> file then this message will disappear.

I’m happy for everyone to use my API Key for evaluation purposes but please do not abuse it. I have added $20 worth of credits and I may top up from time to time as long as people are not abusing the service and eating up all the credits. 

Once you have reviewed the app then please try and create your own API Key as soon as possible.

If you need help with this, please don’t hesitate to drop me an email at.
david@recsitedesign.com


PLEASE SUPPORT THIS APP MY UP VOTING 
-------------------------------------
If you like this content app then please feel free to show your appreciation by voting.


WHERE TO REPORT ISSUES
-------------------------------------
You can either drop me an email at david@recsitedesign.com or you can log a issue at the following URL.
https://github.com/DavidArmitage/Umbraco8_PlagiarismChecker_ContentApp/issues


LATEST VERSION
-------------------------------------
The latest version of the app can be found here
https://github.com/DavidArmitage/Umbraco8_PlagiarismChecker_ContentApp
