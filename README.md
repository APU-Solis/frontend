# NASA API Frontend - Solis

This application. Solis, is built as a part of "You are my sunshine" Challenge for Nasa Space Apps Challenge 2021.

## Screenshots
![image](https://user-images.githubusercontent.com/54048682/135761614-2dab39a5-cb33-4fb3-9e76-5dbaa2cc491d.png)
![image](https://user-images.githubusercontent.com/54048682/135761652-4d8a3f3a-5829-4aae-afcb-e3898c76c454.png)
![image](https://user-images.githubusercontent.com/54048682/135761665-c9e4be77-9b25-4a64-9583-08696e0d7c98.png)
![image](https://user-images.githubusercontent.com/54048682/135761680-c73b68cb-c2b6-4c5e-80d2-3ae7914c93e1.png)
![image](https://user-images.githubusercontent.com/54048682/135761695-d5805f9b-77f5-492d-a9e6-f6e564133465.png)

## Description
Our project is helping to find better locations to set up the solar panels as well as to configure them to meet the perfect solar exposure. The application is allowing users to choose specific locations where they are interested to set up their solar panels or it will accept the user’s current location. The selected place will contain details about the sky conditions, also the solar Irradiance for the equator which is presented in graphs, where users can choose different time periods. For ease of use, the averages of the values are calculated with a formula to grade the location on the solar panel compatibility allowing the user to get a general idea. Moreover, we decided to include the data that assists to set panel angles to exact direction to better capture the energy. The 3D model is used to pinpoint the location of the sun so that users can easily understand the preferred angle for their solar panels. We are helping people to install the panels on their own, knowing and analyzing the locations that have better conditions for solar panels by providing essential information for both, general users and power users. As a result, our app will assist the public to use renewable and sustainable energy with less hassle.



In order to build the application we utilized Angular in combination with Ionic and Capacitor allowing us to use one codebase for many platforms such as web, iOS, or Android, saving the cost and time for development. We also use our own backend system using Python Flask deployed as a serverless function to AWS Lambda. In order to make deployment simpler Zappa, AWS CLI wrapper was used. For designing, we used Figma, a cross-platform UI prototyping tool. In order to collaborate remotely, Microsoft Teams and Discord were utilized. Lastly, our code versioning system is Git and the code repository is hosted on Github.



The application is complete and production ready with few limitations including caching, data analysis performance and potential low security exploits. The application was tested on iOS and Android, Google Chrome, Firefox.


## Intrcutions to run
1. Clone this project
2. Run `npm install`
3. Run `ionic capacitor add ios/android`
4. Run `ionic capacitor run ios/android`

### Remarks
1. Please note that the 3D Model will not work in web browser mode as it requires native device orientation api
2. You would need to have an ionic 5 version installed globally on your system
