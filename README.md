# Inventory-Gun
RFID Based Inventory Management System

## Introductions
Radio Frequency Identification (RFID) is a technology that uses electromagnetic fields to identify and track objects via tags. Unlike traditional barcodes, RFID does not require direct line-of-sight and can process multiple items simultaneously, making it highly efficient.
RFID has been widely implemented in various industries such as retail, healthcare, and logistics. It is used for inventory tracking, patient identification, and electronic toll systems, among others. The adoption of long-range high-frequency RFID systems enables tracking over significant distances, making them ideal for real-time inventory management.
This project develops a cost-effective inventory management system using an Impinj RFID reader. By integrating IoT technology, the system automates item tracking and monitoring. A web-based interface built with Laravel and MySQL allows users to manage inventory and generate reports efficiently.

## Use Cases
For this project, we are simulating a clothing store equipped with RFID technology that can automate inventory tracking by dividing the store into zones such as "Entrance," "Men’s Clothing," "Women’s Clothing," and "Fitting Room." RFID antenna readers placed in each zone track item movement and send real-time data to the cloud, enabling staff to monitor item locations through a web interface.
To support real-time inventory tracking, we designed a custom antenna suited for RFID-based zone detection. After evaluating various antenna types using Antenna Magus, we selected and modeled a truncated patch antenna in CST Studio. The design demonstrated circular polarization, which is essential for maintaining reliable tag detection regardless of orientation. It achieved a strong axial ratio (~2.1), good gain, and effective impedance matching. These features make it highly suitable for tracking items across all designated areas, ensuring robust coverage, accurate detection, and seamless integration into our inventory management system.
 


## Objectives
- To implement a real-time inventory tracking system for a clothing store using RFID technology.
- To enhance operational efficiency by automating item location tracking and reducing manual effort.
- To utilize long-range high-frequency RFID readers for accurate and reliable data collection.
- To integrate IoT technology for seamless data transfer and cloud-based processing.
- To offer a cost-effective solution for small and medium-sized businesses seeking to optimize their inventory management processes.

## Requirements
Hardware: Impinj r420  RFID reader, patch antennas, RFID tags
Software: Python,Laravel and MYSQL

## Scope
- The device contains RF-ID Reader and patch-type antennas with a web-based user interface for the owner to utilize the data.
- This system is using zone-based location tracking rather than precise location of the object.

## System Working Flow
![Image](https://github.com/user-attachments/assets/15448d56-50b2-4863-a1f1-1e8e22d92ae8)

## List of Features
- Real-Time Inventory Tracking: Automatic identification and tracking of items using RFID tags.
- Search and Locate Items based on zone : Quickly locate items using RFID scans or search functionality.
- Inventory Reporting: Generate reports on stock levels and usage trends.
- Integration with User Interface: Web-based dashboard to monitor inventory in real-time.

## Learning Goals
- To understand and implement RFID technology with IoT concepts.
- To learn to integrate hardware (RFID reader) with software systems.
- To gain experience in designing a user-friendly web interface.
- To understand real-time data processing and reporting for inventory systems.

## Weekly Update 
**Week-1** 
 1/6/2025
- Team formation and role distribution  
- Discussed initial direction of the project

**Week-2**
 1/20/2025
- Posted on GitHub  
- Studied various antenna types suitable for RFID  
- Selected tools for simulation and design

**Week-3**
 1/27/2025
- Finalized Truncated Patch Antenna as the best fit  
- Began initial antenna modeling in CST
- ![sketches (1)](https://github.com/user-attachments/assets/c3532035-8ee2-40de-9180-7f3a9fdc7e1c)


**Week-4**
 2/10/2025
- **Proposal Presentation delivered**
   
**Week-5**
 2/17/2025
- Faced High S11 value problem in the antenna ( shoud be less than at least -10 dB)
- ![image](https://github.com/user-attachments/assets/15a99e80-942e-489e-abbe-a53b5625f6b3)

- Researched APIs for cloud interaction  
- Started setting up Impinj RFID reader
- Tested reader–software connection

**Week-6**
 2/24/2025
- Solved S11 issues by adjusting antenna parameters (-32 dB, -14 dB)
- ![image](https://github.com/user-attachments/assets/0454e1c6-2dd3-4d2d-87f3-7b29aaabc14e)
- facing problem on achieving circular polarization 
- Started developing cloud database
- Continued reader integration  
- Built initial database structure

**Week-7**
 3/10/2025
- Achieved circular polarization but faced high AR (>3 dB)
-  ![ARthetaPhi](https://github.com/user-attachments/assets/5904ffe2-3bd4-4c70-8e72-655f11fe25e3)
-  ![image](https://github.com/user-attachments/assets/ac2d1313-7095-45bd-a8da-2818ed124705)
- Connected cloud to the database  

**Week-8**
 3/17/2025
- Optimized antenna design and achieved AR = 2.1
![image](https://github.com/user-attachments/assets/d66acfc5-d1e6-4ad2-a856-50bfea81a6e6)
- Started building user interface

**Week-9**
  3/24/2025
- Found narrow bandwidth – antenna is sensitive to tolerance
  ![image](https://github.com/user-attachments/assets/f9271082-8182-4960-ab4d-5f6c4cb0b28b)
- Continued database reprogramming for use-case fit

**Week-10**
  3/31/2025
- Sent antenna design for fabrication  
- UI and RFID data testing in progress

**Week-11**
  4/7/2025
- Fabrication completed
- ![IMG20250403154350](https://github.com/user-attachments/assets/03510e1e-b4ba-41c9-89c3-68c8e7a1b5ee)
![IMG20250403154342](https://github.com/user-attachments/assets/d6223944-eaff-4a4d-b179-d6b9df799d3f)
![WhatsApp Image 2025-04-06 at 02 42 03_cea164de](https://github.com/user-attachments/assets/6da8ee50-af40-44b0-931e-6eb734eb9753)
- System integration setup

**Week-12**
  4/14/2025 
- End-to-end system test with cloud and reader
- Antenna testing completed

**Week-13**
  4/21/2025
- Verified complete IoT pipeline



