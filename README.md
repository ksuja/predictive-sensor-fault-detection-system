Predictive Sensor Fault Detection:  
This project uses time-series machine learning to predict and detect faults in industrial temperature sensors (PT100 etc.), supporting smart farming and industrial automation tasks. It processes large datasets, detects outliers, and produces actionable alerts for preventive maintenance.

Dataset:  
- Source: sensor-fault-detection.csv  
- Columns:  
  - Timestamp (datetime, UTC)  
  - SensorId (integer)  
  - Value (float; temperature readings)

Installation:
- Clone the repository (or download the notebook).
- Install Python packages:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn

Results:
- You’ll get metrics like test MSE, test MAE, and visual anomaly flags.
- Maintenance alerts can be exported or visualized.

Notes:
- Designed for temperature sensor data but adaptable for other IoT sensors.
- Requires time-ordered historical data for best results.



[1](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/71949113/31ad7d03-a821-45c3-b3aa-cec9ecc7dcae/Predictive_Sensor_Fault_Detection.ipynb)
