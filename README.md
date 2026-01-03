# Papollo Hospital Performance Tracker
 This README file is based on the **Apollo Healthcare Data Analysis** project detailed in the sources, which focuses on building an end-to-end analytics solution for a hospital chain.

---

# Apollo Healthcare Data Analysis Project

## Project Overview
This project involves the process of **examining, cleaning, transforming, and interpreting** a healthcare dataset to discover useful information and support data-driven decision-making for hospital administrators. By analyzing patient records, billing, and operational metrics, this project provides a comprehensive look at how a hospital chain manages its leads and workflow.

## Core Objectives
*   Provide a **breakdown of bed occupancy** to monitor hospital capacity.
*   Analyze **billing and insurance information** to understand revenue streams and patient costs.
*   Track **patient feedback** for assigned doctors to ensure high standards of care.
*   Identify **trends in diagnoses** (e.g., viral infections, malaria, typhoid) to prepare for seasonal disease spikes.

## Technologies Used
*   **MS Excel / Google Sheets:** Used for initial reading, loading, and pre-cleaning of the dataset.
*   **Power BI:** Utilized for creating the primary **interactive and attractive dashboard**.
*   **Power Query Editor:** Essential for **data preprocessing**, including promoting headers, handling missing values, and ensuring correct data types (e.g., converting billing amounts to integers and dates to calendar format).

## Dataset Information
The dataset contains **7,157 rows** of patient records with several key attributes:
*   **Patient Identity:** Patient ID.
*   **Temporal Data:** Admit Date, Discharge Date, and Follow-up Date.
*   **Clinical Data:** Diagnosis, Bed Occupancy Type (Private, General, ICU), and Test Type (e.g., MRI).
*   **Administrative Data:** Assigned Doctor, Feedback (out of 5), and Insurance Type.
*   **Financial Data:** Billing Amount and Health Insurance Amount.

## Project Workflow
1.  **Requirement Gathering:** Defined a "blue-print" based on client needs, identifying that **Patient ID** and **Billing** were the most critical metrics to track.
2.  **Data Connection:** Linked the Google Sheets dataset directly to Power BI.
3.  **Preprocessing:** Cleaned raw data in **Power Query**, verifying that numeric values for billing and ratings were correctly formatted for calculation.
4.  **UI/UX Design:** Applied a custom background (designed in tools like Canva) and integrated the hospital logo to make the report **professional and attractive** for a resume portfolio.
5.  **Deployment:** The dashboard can be **published to the web**, creating a live link where managers or peers can interact with the data in real-time.

---
