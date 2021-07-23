# Kairos
#### Cut the line, and safe your life.
Intelligent crowd-managing platform to decrease establishments closing rate.
<!--![Kairos Logo](/Extra_docs/Images/logo-kairos-white.png =10x20)-->
​
<!--<a name="Short_Description"></a>-->
# Short Description
### Challenge we ran into
The COVID-19 pandemic has a high infection rate, leading governments to close borders and order lockdown measures to protect the citizens. As a result, there is a high decrease in sales, leading to the closure of establishments. Hence, the unemployment rate has increased.
### Techonology into action
Establishments can safely open if they have the ability to track client’s health, and users can go out and avoid queues or the exposure to crowds if they can know in advance the amount of people that will be in the establishment.
### The idea
Development of a mobile app that lets the user make reservations, know the capacity of the store at a specific time, and predicts the people that will be in that establishment at that hour. This makes for a safer, more efficient visit. 
​
# Contents
1. Short Description<!--(#Short_Description)-->
2. [Kairos Demo Video](#video)
3. [Kairos Architecture](#Architecture)
4. [Complete Description](#Long_Description)
5. [Kairos RoadMap](#roadmap)
6. [Getting Started](#Getting_Started)
7. [Machine Learning Model](#machine)
8. [Live Demo](#Live_Demo)
9. [Buld With](#Technologies)
10. [Authors](#Authors)
11. [Acknolwedgemnts](#ackwoledgments)
​
​
<a name="video"></a>
# Kairos Demo Video
Watch the video below to understand Kairo's solution!
[![Kairos Video](/Extra_docs/Images/front_Image.jpg)](https://youtu.be/18CiVdAl5rw)
​
<a name="Architecture"></a>
# Kairos Architecture
![Architecture](/Extra_docs/Images/Architecture_Kairos.jpg)
1. User/admin registers to Kairos developed with Flutter.
2. Flutter connects with Backend for authentification. 
3. Backend does requests to IBM APIs for predictions.
4. IBM APIs return corresponding values to backend.
5. Backend does requests to external APIs for predictions.
6. External APIs return corresponding values to backend.
7. Backend requests Firebase Cloud Messaging for notifications.
8. Firebase Cloud Messaging sends notifications to devices.
​
​
<a name="Long_Description"></a>
# Complete Description
See [Kairos Complete Description.md](/Extra_docs/Files/long-description-1.md)
​
​
<a name="roadmap"></a>
# Kairos Roadmap
See [ROADMAP.md](/Extra_docs/Files/road-map.md)
<!--![RoadMap](/Images/RoadMap_Kairos.jpg)-->
​
​
<a name="Getting_Started"></a>
# Getting Started
## Installing
Download the APK for Android from [here](https://drive.google.com/drive/folders/1cY_6llZol1PjC79GOs7SEujZjAYNRZKY?usp=sharing)
## Admin Login 
* **User:** zaraCol@yopmail.com
* **Password:** 123456
## Client Login
* Please register (do not use special characters). Check [Live Demo](#Live_Demo) for further details. (Since the app uses your location, no places will be shown)
If you want to fully test our app, please use the following client.
* **User:** sandra@gmail.com
* **Password:** 123456
​
<a name="machine"></a>
# Machine Learning Model
See [Kairos Machine Learning Model](/Extra_docs/Files/kairos-ml-model.md)
​
​
<a name="Live_Demo"></a>
# Live Demo ��
1. Check the flow of the user and administrator [here](https://www.youtube.com/watch?v=itsDZXL9YgQ)
​
​
​
<a name="Technologies"></a>
# Build With ��️
​
* [Flutter](https://flutter.dev/)- Used for app development.
* [Nodejs](https://nodejs.org/en/) - Used to build the Heroku backend. Manages authentification, API calls, turns and queues management, usar entrance to establishments logic.
* [Firebase](https://firebase.google.com/) - Used for notifications and external authentification. 
* [PostgreSQL](https://www.ibm.com/cloud/databases-for-postgresql) - Used to storage all the app data. 
* [Watson Machine Learning](https://www.ibm.com/cloud/machine-learning#:~:text=Deploy%20and%20run%20AI%20models,at%20scale%20across%20any%20cloud.) - Used to train the Machine Learning model.
* [Globalization Pipeline](https://www.ibm.com/cloud/globalization-pipeline) - API used to translate the application to 9 different languages.
* [The Weather Company](https://www.ibm.com/weather) - API to get weather predictions. 
* [HERE](https://www.here.com/) - API used to know distance between user and establishment.
* [Avuxi](https://www.avuxi.com/) - API used to get places popularity.
* [Calendarific](https://calendarific.com/) - API used to get holidays.
* [Position Stack](https://positionstack.com/) - API used to get person's geolocation. 
 
<a name="Authors"></a>
# Authors ✒️
​
* [**Francisco Javier Gonzalez Rey**](https://www.linkedin.com/in/franciscogonzalez17/) - Full Stack Developer
* [**Carlos Fernando Infante Montoya**](https://www.linkedin.com/in/carlosinfante98/) - Frontend Developer
* [**Santiago Forero**](https://www.linkedin.com/in/dasafodev/) - Frontend Developer
* [**Manuela Mariño**](https://www.linkedin.com/in/manuela-marino-844229186/) - Product Manager
* [**Alvin David Gregory Tatis**](https://www.linkedin.com/in/alvin-david-gregory-tatis-484052199/) - Data Scientist
​
<a name="ackwoledgments"></a>
# Acknowledgements
​
* [Walter Torres](https://www.linkedin.com/in/walter-torres-90b862180/) for his video, annimations skills, and user interface experience.
​
