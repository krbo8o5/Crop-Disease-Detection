# Introduction
This project focuses on developing an affordable, efficient, and portable system for the early detection of crop diseases using deep learning and IoT technologies.
The system basically makes use of Convolutional Neural Networks (CNNs), which have transformed picture categorization by learning complicated visual properties straight from raw photos. 
Compared to classic machine learning approaches that involve human feature extraction, CNNs provide improved accuracy and automation.
The training process begins with a public dataset encompassing five key crops—Corn, Rice, Potato, Wheat, and Sugarcane—and various disease types.
In addition to this, we have prepared a new real-time dataset collected using a portable IoT device equipped with a camera and GPS sensor. The collected data is stored on the cloud server, from where the dataset is acquired that is used for testing.
These devices are deployed in actual agricultural fields, continuously capturing images of crop leaves under natural, variable field conditions. Environmental data such as humidity, temperature, and light intensity is also recorded, providing valuable context that can improve model accuracy and decision-making.

# Technologies Used

- **Deep Learning:** TensorFlow / PyTorch (CNNs)
- **IoT:** ESP32 / Raspberry Pi + camera & sensors
- **Cloud Services:** Firebase / AWS / Azure Blob Storage
- **Web Interface:** Flask / Streamlit / React (optional)
- **Dataset Management:** Pandas, NumPy, OpenCV

![image](https://github.com/user-attachments/assets/fbd67643-cc7f-4cfe-a285-1a349c1b649b)
