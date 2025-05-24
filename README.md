# Where's My Ride?

**A datathon project by Code Blooded**  
This application addresses a common question faced by many transit users: “Did I just miss the bus?” 

The goal of this project is to provide users with real-time predictions of bus travel times, suggest alternative transportation options if they miss their bus, and offer personalized mobility recommendations by leveraging machine learning techniques and transit data.

---

## Overview

Where's My Ride allows users to enter their starting point, destination, desired departure time, and day of the week. Using this input, the system predicts expected bus travel duration based on historical and live transit data. If the user is unlikely to catch their intended bus, the app provides alternative options such as walking, biking, or scooter use, aiming to simplify urban mobility and reduce wait times.

---

## Features

- **User Input Interface:** Simple form to enter trip details including origin, destination, time, and day.  
- **Predictive Modeling:** Utilizes machine learning to forecast bus travel times by analyzing historical trip data combined with real-time updates.  
- **Missed Bus Alerts:** Provides clear indications if the user will miss the bus based on current schedules and predicted arrival times.  
- **Multi-Modal Recommendations:** Suggests other transportation modes such as scooters, walking, or biking, depending on distance and availability.  
- **Fast and User-Friendly:** Designed to be intuitive with minimal input required for quick decision-making.

---

## Technical Approach

The system architecture includes:  

- **Data Sources:** Integration of live transit data from local transportation authorities along with micro-mobility datasets (bike and scooter share systems).  
- **Machine Learning Model:** Developed using scikit-learn, trained on variables including bus stop sequences, GPS coordinates, trip durations, and day/time features.  
- **Model Validation:** Conducted correlation analysis and visual comparisons between predicted and actual travel times to evaluate accuracy and reliability.  
- **Recommendation Engine:** Combines predicted travel times with contextual information such as weather conditions and transit availability to suggest the most efficient travel options.

For a comprehensive explanation of the methods and results, please refer to the full project report:  
[Where's My Ride.pdf](./Where%27s%20My%20Ride.pdf)

---

## Screenshots

![App UI sample](https://github.com/your-username/your-repo/raw/main/screenshots/ui.png)

You may update this section by placing your own screenshots in a `/screenshots` directory and updating the image links accordingly.

---

## Future Development

Planned enhancements include:  

- **Dynamic Re-routing:** Implementing real-time updates to suggest alternate routes if delays or missed connections occur.  
- **Notification System:** Adding push notifications to remind users when to leave or alert them of schedule changes.  
- **User Preferences:** Allowing users to create profiles to customize transportation preferences and save frequent routes.  
- **Monetization Strategies:** Exploring sustainable revenue models through partnerships or premium features to support ongoing development.

---

## Full Project Report

The project report provides detailed information on data preprocessing, modeling techniques, evaluation metrics, and strategic recommendations:  
[Where's My Ride.pdf](./Where%27s%20My%20Ride.pdf)

---

## References and Data Sources

- Greensboro Transit Authority: [ridegrtc.com](https://ridegrtc.com)  
- Bike and Scooter Share Data: [BTS Bikeshare Data](https://data.bts.gov/Bicycles-and-Pedestrians/Bikeshare-Docked-and-Dockless-and-E-scooter-System/cqdc-cm7d/about_data)  
- Virginia Datathon 2025: [Virginia Datathon](https://data.virginia.gov/organization/datathon-2025)  
- Jupyter Project: [jupyter.org](https://jupyter.org)

---

## Technologies Used

- **Python** for core programming and data manipulation  
- **Pandas, Matplotlib, Seaborn** for data analysis and visualization  
- **Scikit-learn** for machine learning modeling  
- **Jupyter Notebooks** as the development environment

---

## Team Members

- Margaret Shepard — Data Scientist and Project Lead  
- Jotham Zvikonyaukwa — Machine Learning Engineer  
- Preciouc Ndunduri — Data Analyst and Visualization Specialist

---

Thank you for your interest in our project. We hope this tool will contribute to improving urban mobility and transit experiences.
