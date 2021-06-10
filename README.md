# BLANK-DataAnalysis_SCDFXIBM

**Short Description**



Designed to filter information from both trusted and non trusted news and journalism sites, this programme will be used to filter out the information to help the SCDF. Thus ensuring that they have the most vast and accurate data to act upon.



Ideally, this programme can also assist in analysing the various news sites across the world and cross reference the various informations to provide the most accurate data for SCDF to use. This is done through a pyramid structure as there are 3 stages, the top most important are the various news outlets we trust the most with the middle being the moderate trust and the lowest level being the various unknown journalist and news outlets. This system will allow the info obtained by the news outlets to be referenced and compiled to form the most accurate info to be given while at the same time allowing lesser known but just as important info to be surfaced should it be needed. However due to the lack of resources and time we are only able to create a mock version of the programme and hence with limited functions.





[Pitch Video](https://youtu.be/GMuAYAmlAYI)
  
  
  
  
**The architecture of our proposed solution**
![SolutionArhitecture](https://user-images.githubusercontent.com/85574822/121530902-7da2e300-ca30-11eb-8972-e741b0713dc9.JPG)




**How our application will work.**

Our team will be able to retrieve the data through a custom search engine that will be able to search related news by keywords, phrases or questions. These group of websites will be transmitted to the web server. Then the web server will submit a database request (keywords or question) to our database server via SQL with python. This will then prompt a database reply back to the web server with the results via SQL as well. Hence the web server will send the files, via PHP server processing, that can be in html, jpg, css or js to the browser displays page. The related websites will be shown through the next following page. The unreliable news will be indicated in the display, along with the reliable news. 


We will need to use SQL with Python to create the database and ensuring its able to be use in phone apps. PHP and MySQL will be use to create a custom search engine. 


Multiple news outlets and trusted journalist sites act as trusted sites to build a pyramid structure where non-trusted sites are at the bottom and trusted sites are at the top. Large trusted news outlets may have alot of sourced info but sometimes, the smaller sites may be able to obtain trusted info that we can trust that the bigger ones missed out


![latest3tier](https://user-images.githubusercontent.com/85574822/121569283-3548ec80-ca53-11eb-8617-32e2f96ba563.JPG)



With this idea, our team will be focusing on news in relations to SCDF as there are a number of websites (credible and non-credible sources) with relation to a specific news or updates related to SCDF. This system will be accessible through an application that users can download in their android or ios smartphone.







**Our Application will be as follows**



![MockApp](https://user-images.githubusercontent.com/85574822/121566189-d59d1200-ca4f-11eb-9308-fd4d873f8647.JPG)



