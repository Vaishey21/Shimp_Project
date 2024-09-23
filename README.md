# shrimp-monitoring-system

# Problem Statement

Traditional shrimp farming methods involve manually inspecting shrimp for diseases, which is labor-intensive and time-consuming. Additionally, farmers often rely on PCR tests to diagnose diseases, but these tests take up to three days to yield results, during which time up to 60% of the shrimp may die. This approach leads to significant losses and inefficiencies in shrimp farming.

# Solution

We developed a Shrimp Disease Monitoring System that leverages the YOLOv8 model for real-time detection of shrimp diseases. This system is implemented on a Jetson Nano, utilizing a thermal camera to accurately identify whether shrimp are diseased or healthy, providing instant feedback to farmers.

# Key Features:

Real-time Disease Detection: Uses YOLOv8 for efficient and accurate disease identification.
Jetson Nano Deployment: Optimized for low-power devices, making it suitable for on-site usage in shrimp farms.
Thermal Imaging: Employs a thermal camera to enhance disease detection capabilities, allowing for non-invasive monitoring.

# Hardware Requirements

Jetson Nano
Thermal Camera compatible with Jetson Nano

# Model Inference

The YOLOv8 model processes input from the thermal camera and identifies diseased shrimp in real-time, providing immediate alerts.

# Model Performance

Accuracy: The YOLOv8 model has shown high accuracy in detecting shrimp diseases based on our testing dataset.
Efficiency: The system operates efficiently on Jetson Nano, making it viable for continuous monitoring in shrimp farms.
