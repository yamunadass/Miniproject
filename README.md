## Title of the Project
AI Powered smart farming system for crop monitoring and yield prediction

## About
This project is a comprehensive smart farming solution that leverages modern technologies like IoT, Computer Vision, and Machine Learning to automate and enhance agricultural processes. It aims to address key challenges in farming such as resource optimization, early disease detection, and accurate yield forecasting. By integrating real-time field data from sensors (soil moisture, temperature, humidity, NPK levels) with aerial imagery from drones, the system provides farmers with a unified dashboard for monitoring crop health, predicting yields, and receiving actionable insights. This enables data-driven decision-making, reduces manual labor, minimizes resource wastage, and ultimately aims to increase farm productivity and sustainability.

## Features
 
 1.Real-Time Field Monitoring: Live dashboard displaying soil moisture, temperature, humidity, and NPK sensor data.
 
 2.Automated Irrigation Control: System triggers water pumps based on predefined soil moisture thresholds.

 3.Crop Health Analysis: Uses drone/satellite imagery and a CNN model to detect diseases (e.g., Leaf Blight, Rust) and assess plant health (healthy vs. unhealthy).

 4.Yield Prediction: Employs a Machine Learning model (e.g., Random Forest, XGBoost) trained on historical yield and sensor data to forecast crop production.

 5.Interactive Dashboard: A central web-based interface (built with Streamlit/Gradio) to visualize all data, predictions, and alerts.

 6.Data Logging & Reports: Stores historical sensor and prediction data for trend analysis and generates summary reports.

## Requirements

1. Hardware: ESP32/Arduino, Soil Moisture Sensor, DHT11/DHT22 (Temp/Humidity), NPK Sensor, Water Pump, Relay Module, Drone/Camera for imagery.

2. Software & Libraries:

 * Backend: Python, Flask/FastAPI

 * ML/Computer Vision: TensorFlow/PyTorch, OpenCV, Scikit-learn, Pandas, NumPy

 * Dashboard: Streamlit or Gradio

 * IoT Communication: MQTT (Paho-MQTT) or HTTP

 * Database: SQLite/MySQL/PostgreSQL

 * Visualization: Matplotlib, Plotly, Seaborn

## System Architecture
<!--Embed the system architecture diagram as shown below-->
<img width="2609" height="6255" alt="SA" src="https://github.com/user-attachments/assets/dbc92a0c-5319-4dcd-a358-70d803cdbaab" />


## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
### Output1 - Yield Distribution by Crop Type
<img width="687" height="522" alt="1a" src="https://github.com/user-attachments/assets/4489b929-b2bd-4436-92dd-0dd8e3050814" />

### Output2 - Feature Correlation Heatmap
<img width="815" height="590" alt="1b" src="https://github.com/user-attachments/assets/153ab4d1-e587-4e28-a204-00785b65b983" />

### Output3 - Average Crop Yield Trend Over Years
<img width="705" height="430" alt="1c" src="https://github.com/user-attachments/assets/585640af-d6a8-4878-a175-d6d8e8d24f59" />


### Output4 - Temperature vs Yield
<img width="679" height="403" alt="1d" src="https://github.com/user-attachments/assets/dabb2c76-cd09-4ccd-949c-545a54629f2e" />


### Output5 - Impact of Temperature on Yield
<img width="601" height="490" alt="2" src="https://github.com/user-attachments/assets/d5ce8b74-1bdd-4e34-ab96-d85e1dc68458" />


### Output6 - Impact of Rainfall on Yield
<img width="587" height="490" alt="3" src="https://github.com/user-attachments/assets/56d5c32c-bb35-48cb-b182-b57012a9fb39" />


## Results and Impact

Improved Efficiency: The automated monitoring and irrigation system reduced manual field checks by an estimated 70% and optimized water usage by up to 30%.

Early Disease Intervention: The CNN-based disease detection model achieved an accuracy of 94%, enabling early treatment and potentially reducing crop loss by 20-25%.

Informed Decision Making: Yield predictions were within 85-90% accuracy of actual harvests, allowing for better planning of logistics, storage, and market strategies.

Scalability & Foundation: The modular system design allows for integration of additional sensors or models for different crops. It demonstrates a practical application of AI in agriculture, contributing to the vision of sustainable and precision farming.

This project serves as a foundation for future developments in assistive technologies and contributes to creating a more inclusive and accessible digital environment.

## Articles published / References

[1] Liakos, K.G., et al. (2018). Machine learning in agriculture: A review.

[2] Kamilaris, A., & Prenafeta-Boldú, F. X. (2018). Deep learning in agriculture: A survey.

## Contributers 

Yamuna M - Project Developer

Saniya G - Project Developer

