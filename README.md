# AgroNet 🌱🚀

AgroNet is a web application created by our team for the hackathon **NASA Space Apps Challenge Athens**. The project focuses on providing farmers in Evoia, Greece with vital information about the risk level of green bollworm infestations in their cotton fields.

By leveraging satellite data and local sensor inputs, AgroNet helps farmers make informed decisions on when to check their fields and optimize pesticide use, reducing the environmental impact while protecting crops from pests.

# 🚜 Project Overview

Cotton farmers need to monitor the presence of green bollworms in their fields regularly. While pesticides can be used to manage these pests, excessive use can harm the plants and ecosystem. Farmers must balance between early detection and limited pesticide application.

AgroNet addresses this challenge by creating a bollworm danger level indicator based on:

    NASA Satellite Temperature Data: Bollworm populations increase within a specific temperature range.
    NASA NDVI Data: Areas with denser flora tend to attract more pests.
    Local Farm Sensor Data (optional): Additional sensors can be deployed across farms to improve the resolution of the indicator, measuring parameters like temperature and soil moisture.

By using machine learning, AgroNet can dynamically adjust the weights of these factors (temperature, flora, sensor data) based on real-world field data.

Farmers can also contribute by pressing a Worm Alert Button, which will increase the danger level in their area, refining the indicator for nearby farms.

# 🌟 Features

    Bollworm Danger Level Indicator: A calculated risk score using satellite data, sensor inputs, and user alerts.
    User-Driven Alerts: Farmers can send alerts if they notice increased bollworm activity in their fields, enhancing community awareness.
    Fire Alerts: Real-time fire alerts to help farmers protect their crops from sudden fires.
    Machine Learning for Accuracy: A simple machine learning model is proposed to adjust the weighted sum of data layers based on real-world field data.

# 🛠️ Future Improvements

    Sensor Integration: Add support for IoT-based sensors to track real-time environmental factors like temperature and humidity.
    Advanced Machine Learning: Implement a robust machine learning model using field-specific data for more accurate predictions.
    Mobile App: Develop a mobile version of AgroNet for on-the-go access by farmers.


# 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

# 📷 Screenshots

Coming soon!

# 📞 Team

For any questions or suggestions, feel free to reach out to the team at:

    Email: agronet.team@example.com
    GitHub Issues: AgroNet Issues
    
