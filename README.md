# Inventory-Gun
RFID Based Inventory Management System

## Introductions
Radio Frequency Identification (RFID) is a technology that uses electromagnetic fields to identify and track objects via tags. Unlike traditional barcodes, RFID does not require direct line-of-sight and can process multiple items simultaneously, making it highly efficient.
RFID has been widely implemented in various industries such as retail, healthcare, and logistics. It is used for inventory tracking, patient identification, and electronic toll systems, among others. The adoption of long-range high-frequency RFID systems enables tracking over significant distances, making them ideal for real-time inventory management.
This project develops a cost-effective inventory management system using an Impinj RFID reader. By integrating IoT technology, the system automates item tracking and monitoring. A web-based interface built with Laravel and MySQL allows users to manage inventory and generate reports efficiently.

## Use Cases
For this project, we are simulating a clothing store equipped with RFID technology that can automate inventory tracking by dividing the store into zones such as "Entrance," "Men’s Clothing," "Women’s Clothing," and "Fitting Room." RFID antenna readers placed in each zone track item movement and send real-time data to the cloud, enabling staff to monitor item locations through a web interface. To optimize the system, we are conducting studies using Antenna Magus to evaluate antenna patterns and select the design that provides the best performance for the intended zones. The chosen antenna design will ensure robust coverage and accurate tracking across all designated areas.These features make it a perfect choice for our inventory tracking system.
 


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
![Image](https://github.com/user-attachments/assets/8027eab3-f732-422c-aecd-11e6e770677a)

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
