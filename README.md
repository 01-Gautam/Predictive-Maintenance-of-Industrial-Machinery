# 🏭 Predictive Maintenance of Industrial Machinery Using Machine Learning

[![IBM Watson Studio](https://img.shields.io/badge/IBM-Watson%20Studio-blue.svg)](https://www.ibm.com/cloud/watson-studio)
[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Machine Learning](https://img.shields.io/badge/ML-Random%20Forest-green.svg)](https://scikit-learn.org/)
[![Accuracy](https://img.shields.io/badge/Accuracy-99.5%25-brightgreen.svg)]()

## 🎯 Project Overview

This **capstone project** demonstrates a cutting-edge **Predictive Maintenance System** for industrial machinery using IBM Watson Studio's automated machine learning capabilities. The system achieves **99.5% accuracy** in predicting equipment failures before they occur, enabling proactive maintenance scheduling and significantly reducing operational downtime.

### ✨ Key Achievements
- 🎯 **99.5% Accuracy** using Random Forest Classifier
- ⚡ **Real-time Failure Prediction** with multi-class classification
- 🔧 **Proactive Maintenance** scheduling capabilities
- ☁️ **Cloud Deployment** on IBM Watson Studio
- 🚀 **Automated ML** using IBM's AutoAI technology
- 📊 **9 Pipeline Models** generated and compared

## 🚨 Problem Statement

Industrial machinery failures result in:
- **Significant downtime** and production losses
- **High maintenance costs** due to reactive repairs
- **Safety risks** for workers
- **Reduced operational efficiency**

**Solution**: Develop a predictive maintenance model that analyzes sensor data to identify patterns preceding failures, enabling proactive maintenance scheduling.

## 💡 Proposed Solution

### Core Objective
Develop a **predictive maintenance model** capable of anticipating machine failures before they occur, assisting organizations in:
- 📅 Scheduling timely maintenance
- 💰 Reducing downtime and associated costs
- ⚡ Improving operational efficiency

### Classification Approach
- **Multi-class Classification**: Predicts specific failure types
- **Binary Classification**: Fail/Not Fail scenarios

## 🏗️ System Architecture

### Technology Stack
- **Platform**: IBM Watson Studio & Watsonx.ai Studio
- **Algorithm**: Random Forest Classifier (Primary)
- **Alternative**: Decision Tree Classifier
- **Automation**: IBM AutoAI for automated model selection
- **Deployment**: IBM Watson Studio API endpoints

### Key Components
1. **Data Collection**: Kaggle Predictive Maintenance dataset
2. **Automated Preprocessing**: IBM Watson Studio handles data cleaning
3. **Model Training**: AutoAI generates 9 optimized pipelines
4. **Model Evaluation**: Cross-validation with multiple metrics
5. **Deployment**: Real-time prediction API

## 📊 Dataset & Features

### Source
- **Dataset**: [Kaggle Predictive Maintenance Dataset](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification)
- **Features**: 9 sensor parameters
- **Target**: Failure type classification

### Input Features
| Feature | Description |
|---------|-------------|
| UDI | Unique Device Identifier |
| Product ID | Product identification |
| Type | Machine type (L, M, H) |
| Air temperature [K] | Ambient temperature |
| Process temperature [K] | Process temperature |
| Rotational speed [rpm] | Machine rotational speed |
| Torque [Nm] | Applied torque |
| Tool wear [min] | Tool wear duration |

## 🤖 Algorithm & Results


### Pipeline Comparison (Top 4)
| Rank | Algorithm | Accuracy | Enhancements | Build Time |
|------|-----------|----------|--------------|------------|
| 🥇 | Batched Tree Ensemble Classifier | 99.5% | HPO-1, FE, HPO-2, BATCH | 00:00:45 |
| 🥈 | Snap Random Forest Classifier | 99.5% | HPO-1, FE, HPO-2 | 00:00:42 |
| 🥉 | Snap Random Forest Classifier | 99.5% | HPO-1, FE | 00:00:35 |
| 4️⃣ | Snap Decision Tree Classifier | 99.4% | HPO-1, FE, HPO-2 | 00:00:03 |

### Failure Type Classification
The model successfully classifies multiple failure types:
- **Overstrain Failure**
- **Random Failures** 
- **Power Failure**
- **Tool Wear Failure**
- **Heat Dissipation Failure**
- **No Failure**

*Note: The model was tested with randomly provided sample data and achieved consistent high accuracy across all failure types.*

## 🚀 Implementation Highlights

### IBM Watson Studio Workflow
1. **Data Import**: Uploaded Kaggle dataset to IBM Cloud Object Storage
2. **AutoAI Experiment**: Configured for multiclass classification
3. **Model Generation**: AutoAI created 9 optimized pipelines
4. **Performance Analysis**: Compared models using accuracy metrics
5. **Model Deployment**: Deployed best model as REST API
6. **Real-time Testing**: Validated predictions using test interface

### Key Features Implemented
- ✅ **Automated Feature Engineering**
- ✅ **Hyperparameter Optimization**
- ✅ **Ensemble Model Creation**
- ✅ **Batch Processing Capabilities**
- ✅ **Real-time API Endpoints**

## 🔮 Future Scope

The system can be extended by incorporating:
- **Additional Sensor Parameters**: Vibration levels, electrical current
- **Real-time Data Streaming**: IBM Cloud pipelines integration
- **User-friendly Dashboard**: Monitoring interface for maintenance teams
- **IoT Integration**: Direct sensor data ingestion
- **Multi-machine Support**: Scalable architecture for various machine types

## ✅ Conclusion

This project successfully demonstrates a **machine learning-based predictive maintenance system** with exceptional performance:

- ✅ **99.5% Accuracy** achieved using Random Forest model
- ✅ **Multi-failure Support** for various failure types
- ✅ **Cloud Deployment** fully operational on IBM Watson Studio
- ✅ **Proactive Maintenance** enabling timely scheduling
- ✅ **Cost Reduction** through reduced unplanned downtimes

The solution effectively addresses industrial challenges through comprehensive preprocessing, automated model tuning, and cloud-based deployment, ultimately enhancing operational efficiency.

<div align="center">
## 👨‍💻 Author

**Gautam Tripathi**

---


</div>
