# 💊 Pharmacy Inventory and Drug-Expiry Intelligence using Smart Shelves

<p align="center">
  <strong>Smart Inventory. Intelligent Expiry Management. Cloud-Powered Pharmacy.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Cloud-AWS-orange?style=for-the-badge&logo=amazonaws" />
  <img src="https://img.shields.io/badge/IoT-AWS%20IoT%20Core-blue?style=for-the-badge&logo=amazonaws" />
  <img src="https://img.shields.io/badge/Database-DynamoDB-purple?style=for-the-badge&logo=amazondynamodb" />
  <img src="https://img.shields.io/badge/Architecture-Cloud%20Native-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Project-Academic-red?style=for-the-badge" />
</p>

---
## 👥 Team Members

| S. No. | Name | Student ID |
|---|---|---|
| 1 | K. Hemanth | 2520030230 |
| 2 | D. Siri Reddy | 2520030126 |
| 3 | M. Yashwanth | 2520030369 |

### 👩‍🏫 Faculty Guide

Y. Harika  
Professor, CSE Department

---

## 🎓 Academic Information

| Detail | Information |
|---|---|
| Project Title | Pharmacy Inventory and Drug-Expiry Intelligence using Smart Shelves |
| Course | Cloud Infrastructure and Services |
| Course Code | 25CS2206E |
| Academic Year | 2026–2027 |
| Team Number | 8 |
| Section | 1 |
| Faculty Guide | Y. Harika |
| Department | Computer Science and Engineering |

---
## 📌 Project Overview

Pharmacy Inventory and Drug-Expiry Intelligence using Smart Shelves is a cloud-based pharmacy inventory management system designed to monitor medicine stock in real time, track batch-level expiry dates, identify low-stock items, and support intelligent inventory management.

The proposed system integrates smart shelves equipped with weight sensors and RFID or barcode readers to collect inventory data. Shelf events are transmitted through MQTT to AWS IoT Core, where cloud-based processing updates inventory records, evaluates expiry and stock conditions, and generates alerts.

The system uses AWS cloud services for data processing, storage, analytics, notification delivery, forecasting, security, and dashboard hosting.

---

## 🚨 Problem Statement

Traditional pharmacy inventory management systems often rely on manual stock counting or systems that update inventory only when staff manually scan or enter information.

These approaches can lead to:

- Medicines expiring unnoticed.
- Accidental dispensing of expired medicines.
- Frequently used medicines running out of stock.
- Slow-moving medicines accumulating unnecessarily.
- Inefficient purchasing and stock management.
- Incomplete inventory and compliance records.
- Limited real-time visibility into pharmacy stock.

### 💡 Proposed Solution

The proposed system uses smart shelves and AWS cloud infrastructure to automate inventory tracking and drug-expiry intelligence.

It continuously monitors medicine inventory, associates stock with batch expiry information, identifies low-stock and near-expiry medicines, provides reorder suggestions using historical sales data, and supports First-Expiry-First-Out (FEFO) dispensing.

---

## 🎯 Objectives

- Monitor pharmacy inventory in real time.
- Integrate weight sensors and RFID/barcode readers.
- Track medicine batches and expiry dates.
- Detect near-expiry medicines automatically.
- Generate low-stock alerts.
- Recommend reorder quantities using historical sales data.
- Support First-Expiry-First-Out (FEFO) dispensing.
- Provide a cloud-hosted inventory dashboard.
- Maintain historical inventory and audit records.
- Build a scalable cloud-native pharmacy inventory prototype.

---

## ✨ Key Features

- 📦 Real-Time Inventory Monitoring – Track medicine stock through smart shelf events.
- 🏷️ RFID and Barcode Integration – Identify medicine products and inventory items.
- ⚖️ Weight Sensor Integration – Detect stock changes using shelf weight measurements.
- 📅 Expiry Tracking – Maintain batch-level medicine expiry information.
- 🚨 Expiry Alerts – Identify medicines approaching their expiry dates.
- 📉 Low-Stock Detection – Automatically identify products requiring replenishment.
- 📊 Inventory
