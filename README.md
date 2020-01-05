# mobileapplication
Mobile Application

INFO 4302 SEMESTER 1 2019/2020


                  

INFO 4302 MOBILE APPLICATION
(FINAL PROJECT PROPOSAL)


PROJECT TITLE:
JomGombak - Your Local Food Explorer



GROUP MEMBERS:
 EIZZAH AQILAH BT ABDUL HALIM (1629250 )
ANIS AQILAH BT BORHANUDDIN (1628812)
AISYAH MARDHIAH BT AZURA (1621890 )
SITI HAJAR BT KHAZURIN (1622120)






a. Introduction

'JomGombak' is a mobile application acts as your explore guide aims to give the user exposure of good Malaysia cuisines in Gombak. The application is able to search for restaurants, desserts, ‘Pasar Malam’, ‘Mamak’ or whatever else the user’s tongue desires at the moment. This application will provide quick categories for the user to choose and it will display the best results near your current location which is Gombak. Results appear in order of what's closest to the user, and they can view by the default list or a map. 

People travel in hoping that they found good places with trusted reviews from the community about those specific places, especially on places to eat. Some of the locals themselves do not know any good suggestions to offer to the outsider on which place is a good food stop. The suggestions on websites and information scattered around on social media instead of one platform. Sometimes these good places went viral, but some people might miss it and forgot the names. Thus, there is no specific platform within easy reach for them.

b. The objectives

The main objectives for this mobile application project are:

To develop a mobile application that allows users to know various places to eat around Gombak
To help ease users to search for places to eat with good reviews and ratings
To able user to contribute giving a review of the restaurant


c. Features and functionalities

Our features and functionalities are:-
 List out good foods around Gombak (with descriptions)
 Estimate distance between current live location and venue chosen. 
Add reviews of the particular restaurant.

d. Screen navigation (routing) and components (presentational and container) diagram


Figure 1. Screen Navigational Flow


Figure 2. Component Diagram

e. Sequence diagram


				Figure 3. Sign up Sequence Diagram


				Figure 4. JomGombak Sequence Diagram
f. References
Native Base, Retrieved from https://nativebase.io/
Expo Documentation, Retrieved from https://docs.expo.io/versions/latest/
Restaurants near Gombak Station, Retrieved from https://www.tripadvisor.com.my/RestaurantsNear-g3198092-d9578234-Gombak-Batu_Caves_Selangor.html
The code implementation and completed functionalities


Group member (Developers)
Functionalities
Main code implementation
Anis Aqilah Binti Borhanuddin (1628812)
SignUp and Login Page
Enable users to register as a member and authenticate the user to use the application.
Firebase 
Store the details of the user after sign up.
Retrieve the user’s email and password to authenticate the login process.

Aisyah Mardhiah Binti Azura (1621890)
Home Page
Provide an interface using tabs to display the mealtime for the user to choose and displaying lists of suggested restaurants according to the mealtimes tabs.
Native Base
Use the UI components for React Native from the native base which is ‘Advanced Tab’ to display the lists of mealtimes.

Eizzah Aqilah Binti Abdul Halim (1629250)
Restaurant Page (Map)
Displaying map and details of restaurants (the descriptions, image, location, opening and closing time) selected by the user.
Mapview API
Use Mapview API to display back the map accordingly to the latitude and longitude of the selected restaurants.

Siti Hajar Binti Khazurin (1622120)
Restaurant Page (Review)
Add a review button on top of the map for the user to give their opinion about the selected restaurant.
Firebase
Store the reviews added by the user.
Retrieve and display back all the user’s reviews by listing them out on the different pages.

