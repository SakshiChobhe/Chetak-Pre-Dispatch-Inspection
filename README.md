
# Chetak EV Pre-Dispatch Inspection (PDI) Dashboard

## Overview

This project was developed during my internship at Bajaj Auto Ltd., Akurdi, Pune, under the Process Engineering – Digital Manufacturing Team.

The objective of the project was to support the Pre-Dispatch Inspection (PDI) process for Chetak Electric Vehicles by developing a vision-based inspection dashboard that enables quality engineers to monitor vehicle inspection checkpoints, visualize captured images, and track inspection results in real time.

The system integrates computer vision, database management, and web technologies to improve quality assurance, reduce manual inspection effort, and enhance traceability within the manufacturing process.

---

## Problem Statement

Pre-Dispatch Inspection is the final quality verification stage before a vehicle is dispatched to dealerships or customers.

Traditional inspection methods involve significant manual effort and are prone to:

* Human errors
* Inconsistent inspections
* Delayed defect identification
* Limited traceability

To address these challenges, Bajaj Auto implemented a digital inspection system using cameras, databases, and automated dashboards.

---

## Key Features

### Real-Time Inspection Dashboard

* Display inspection status for Left-Hand (LH) and Right-Hand (RH) checkpoints
* Visual pass/fail indicators using color-coded statuses
* Dynamic loading of inspection data

### Vehicle Traceability

* Search inspections using VIN number
* Filter records by model and inspection dates
* Access historical inspection records

### Visual Quality Control

* Display images captured from multiple inspection cameras
* Link captured images to inspection checkpoints
* Support defect verification and quality analysis

### Database Integration

* Store inspection metadata
* Manage checkpoint results
* Track image storage locations
* Maintain complete inspection history

### Manufacturing Data Analytics

* Inspection status tracking
* Historical defect analysis
* Quality monitoring support

---

## System Architecture

```text
Vehicle Inspection Line
        │
        ▼
 PLC Trigger System
        │
        ▼
 Industrial Cameras
        │
        ▼
 Image Capture
        │
        ▼
 MySQL Database
        │
        ▼
 Flask Backend APIs
        │
        ▼
 Inspection Dashboard
        │
        ├── Check Sheet
        ├── Visual QC
        ├── Inspection History
        └── Reports
```

---

## Technologies Used

### Backend

* Python
* Flask
* REST APIs
* JSON

### Frontend

* HTML5
* CSS3
* JavaScript
* AJAX

### Database

* MySQL

### Computer Vision

* YOLO Object Detection
* OpenCV

### Development Tools

* Visual Studio Code
* Jupyter Notebook
* Anaconda
* XAMPP
* Makesense.ai

### Version Control

* Git
* GitHub

---

## Hardware Components

* Basler acA2440-20gc Industrial Camera
* NVIDIA Jetson AGX Orin Developer Kit
* Mitsubishi FX5U PLC
* Industrial Sensors
* PoE Network Infrastructure
* LED Vision Lighting System

---

## Dashboard Modules

### Check Sheet Module

Displays inspection results for:

* Left-Hand Side Checkpoints
* Right-Hand Side Checkpoints
* Pass/Fail Status Indicators

### Visual QC Module

Provides:

* Multi-camera image display
* Real-time visual verification
* Defect monitoring support

### History Module

Supports:

* VIN-based search
* Model-based filtering
* Date range filtering
* Historical inspection review

### Reports Module

Provides:

* Inspection summaries
* Checkpoint analysis
* Traceability records

---

## Database Structure

### Master Data Table

Stores:

* Vehicle Identification Number (VIN)
* Model Information
* Vehicle Color
* Inspection Timestamp
* Shift Information
* Image Storage Paths
* LH Checkpoint Results
* RH Checkpoint Results

Example Fields:

```sql
vin
model
color
timestamp
shift
images_path

lh_checkpoint_1 ... lh_checkpoint_28
rh_checkpoint_1 ... rh_checkpoint_28
```

---

## Benefits of the Solution

* Improved inspection accuracy
* Reduced manual effort
* Faster defect identification
* Better manufacturing traceability
* Enhanced quality assurance process
* Support for Industry 4.0 initiatives

---

## Learning Outcomes

During this internship project, I gained hands-on experience in:

* Industrial Digital Manufacturing
* Quality Assurance Systems
* Computer Vision Applications
* Database Design
* Flask Web Development
* Manufacturing Process Engineering
* Dashboard Development
* Real-Time Data Management

---

## Future Enhancements

* Automated YOLO-based defect detection
* Real-time alert notifications
* Defect trend analytics
* Predictive quality monitoring
* Cloud-based inspection reporting
* AI-powered defect classification

---

## Internship Details

**Organization:** Bajaj Auto Ltd.

**Department:** Process Engineering – Digital Manufacturing Team

**Location:** Akurdi, Pune, Maharashtra, India

**Project:** Chetak EV Pre-Dispatch Inspection (PDI) Dashboard

**Duration:** Internship Project

---

## Author

**Sakshi Chobhe**

Aspiring AI Engineer | Python Developer | Computer Vision Enthusiast

LinkedIn: Add your LinkedIn profile

GitHub: https://github.com/SakshiChobhe

