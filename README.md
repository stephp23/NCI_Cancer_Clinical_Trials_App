# Ctrials
## A NCI Cancer Clinical Trials API Based Application

![](./Ctrials_app_banner.png)

## Description

This is a web application that allows users to gather specific information about National Cancer Institute supported clinical trials. Users will be able to look at information regarding clinical trials, based on diffferent parameters, such as : disease, disease progression, interventions, age of study participant, and location of clinical trials. The Ctrials application takes it a step further, by allowing users to see clinical trials that are conducted nearby, in the context of an interative Google map. It has desktop, mobile, and tablet responsive capabilities. 


## User Interfaces

### Homepage Search Tabs and Dropdown menus give user the ability to narrow down by the main parameters.
-     Health Condition patient is experiencing. 
-     Key Words and Phrases related to health condition or treatments.
-     Disease Porgression including cancer stages and reccurent health conditions.
-     Age of Prospective Study Participant

![](./cancer_app_Desktop_page_1.png)


### Second page of the application will provide further clinical trial search breakdown.
-     User will be able to narrow down search results by different types of clinical trials by checking off and selecting all the different trial types to include.
-     User will have the choice to further narrow down results based on geolocation of the clinical trials, by selecting a country (from a dropdown menu), US state (from a dropdown menu), or actively inputing into a search bar for cities (needed for locations outside the United States). The user will also be able to input a desired distance away from their given location, to look for clinical trials. 
-     The results yeilded from based search will then be shown on Google Map with markers symbolozing each clinical trial in its location, near the user's given location. A list of the clinical trials shown on the map will be displayed below the map, with buttons that allow the user to click individual trials for further information.

![](./cancer_app_Desktop_page_2.png)


### Third page of the application will provide detailed information on the chosen trial user has selected from the yeilded results. 

![](./cancer_app_Desktop_page_3.png)

### Mobile Interface

![](./cancer_app_iPhone8_mobile_correct.png)

### Tablet Interface

![](./cancer_app_tablet_correct.png)

## API Usage

### NCI Clinical Trials Search API

![](./NCI_API.png)

-API enpoints used: Clinical Trials, Disease, Terms, and Interventions.

-  https://clinicaltrialsapi.cancer.gov/
  
### Google Maps Javascript API

- https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY

## Requirements:

- The Ctrials web application will be developed using HTML, CSS, and Javascript.
- The data will be retrieved from an external source (the National Cancer Institute's Clinical Trials API and Google Maps API) and rendered into the DOM by using Axios. 
- Flexbox will be used to efficently lay out, align, and distribute elements on the application pages. 
- An API Key will be utilized to access the Google Maps API, with its corresponding ENV file. 
- National Cancer Institutue's API does not require an API Key.
- Ctrials will be an application designed and built to be responsive on three different screen sizes: desktop, mobile, and tablet. Application will be hosted on Netlify.


## Inspiration

As developers, who were previously in the biology and science fields, we wanted to create an application that could be useful for people who need breakthrough clinical health services and scientific researchers conducting clinical trials. The Ctrials application provides is an easy to use tool for individuals looking for readily accessible cancer clinical research trials information, along with location proximity, to better connect possible participants to clinical trials.  

Thank you to the National Cancer Institute for the development of their clinical trials API. We sought out inspiration from their current search website: https://www.cancer.gov/about-cancer/treatment/clinical-trials/search/advanced . 

## Contact

### Developed by: Stephanie Pena and David Espinal 

#### Want to know more? Feel free to reach us at: 

- [LinkedIn - Stephanie Pena](https://www.linkedin.com/in/stephanie-a-pe%C3%B1a-1132bb16a/)
- [LinkedIn - David Espinal](https://www.linkedin.com/in/david-espinal-28b91a1b7/)
- [Email](mailto:stephp23@gmail.com)

##### Disclaimer: We do not own the rights to any of the images included in this repository. All images were pulled from standard Google searches. 
