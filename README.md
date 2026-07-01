# Enterprise Asset Management and CMDB Implementation

## Project Overview

Rex Medical Research Pty Ltd is a medium-sized healthcare research organisation with approximately 250 employees operating across two office locations. The company relies on a range of IT assets including Windows workstations, laptops, Windows and Linux servers, network devices, and business applications to support research, finance, human resources, and daily operations.

During an internal audit, it was identified that the organisation's asset inventory was incomplete and maintained through an outdated spreadsheet containing inconsistent and missing information. Several assets lacked ownership details, business criticality classifications, and status, making it difficult for the IT department to accurately identify, manage, and secure organisational assets.

As a Cyber Asset Management consultant, I was tasked with designing a practical asset management process to improve asset visibility, establish a central Configuration Management Database (CMDB), and implement procedures to ensure asset information remains accurate and up to date.

This project demonstrates the design of a simple Cyber Asset Management process based on industry best practices. The solution focuses on discovering assets, validating inventory information, classifying business assets, assigning ownership, and maintaining an accurate CMDB using a structured review process.

## Project Objectives

1. Review the existing asset register.
2. Identify deficiencies in the current asset inventory.
3. Improve the spreadsheet-based CMDB.
4. Assign ownership and business criticality.
5. Develop a CMDB maintenance process.
6. Recommend migration to a dedicated asset management platform.

## 1. Reviewing the Existing Spreadsheet and Identifying Deficiencies

### Current State Assessment

The client currently maintains IT assets using a single Microsoft Excel spreadsheet. While it provides a basic inventory of hardware, the spreadsheet contains missing and inconsistent information, including asset owners, serial numbers, IP addresses, business criticality, and review dates. As a result, the organisation cannot accurately track assets or maintain an effective Configuration Management Database (CMDB).

### Missing Information

- Missing hostnames
- Missing asset owners
- Missing departments
- Missing IP addresses
- Missing serial numbers
- No asset classification
- No business criticality
- No review dates
- No asset custodian
- No lifecycle status

**Screenshot 1 – Legacy Asset Spreadsheet**

<img width="1877" height="648" alt="image" src="https://github.com/user-attachments/assets/de363c90-bc8f-45d9-9af2-52eb141de8b7" />

---

## 2. Recommendations

Based on the assessment, the following improvements are recommended:

1. Validate all existing asset records with the IT department.
2. Update missing asset information such as owner, serial number, IP address, and location.
3. Assign a business criticality rating to each asset.
4. Standardise asset naming and data entry.
5. Create a structured CMDB using the existing spreadsheet as the initial repository.
6. Establish a regular review process to ensure the CMDB remains accurate and up to date.

---

## 3. Improved CMDB Design

| Field | Purpose |
|--------|---------|
| Asset ID | Unique identifier for each asset |
| Hostname | Device name |
| Asset Type | Desktop, Laptop, Server, Network Device, Printer |
| Manufacturer | Device manufacturer |
| Model | Hardware model |
| Serial Number | Manufacturer serial number |
| Assigned User | Person responsible for the asset |
| Department | Business department |
| Location | Physical location |
| Operating System | Installed operating system |
| IP Address | Network address |
| Business Criticality | Low, Medium or High |
| Asset Status | Active, In Storage, Retired |
| Purchase Date | Date acquired |
| Warranty Expiry | Warranty end date |
| Last Review Date | Date the record was last verified |
| Comments | Additional notes |

---

## 4. Asset Discovery and Validation

Following the review of the existing asset register, an asset discovery exercise was conducted to identify hardware currently connected to the organisation's network. The results were compared with the existing spreadsheet to identify missing, duplicate, and outdated asset records.

The discovered assets were then reviewed with the IT department to validate technical information, including device names, operating systems, IP addresses, serial numbers, and asset status. Any discrepancies identified during the review were corrected before updating the CMDB.

Following the technical validation, meetings were held with business stakeholders from each department to confirm asset ownership and determine the business criticality of each asset. This ensured that every asset had an assigned owner and an appropriate business classification, improving accountability and supporting future risk management activities.

---

## 5. CMDB Maintenance Process

Once the CMDB was populated with validated asset information, a maintenance process was established to ensure the asset inventory remained accurate and current.

- All new IT assets must be recorded in the CMDB before being deployed.
- Asset changes, including hardware replacements, user transfers, and location changes, must be updated by the IT department.
- Asset owners are responsible for notifying IT of any changes affecting assigned equipment.
- The IT department will perform a quarterly review of the CMDB to verify asset information and remove retired or disposed assets.
- An annual audit will be conducted to validate the CMDB against the physical asset inventory and identify any discrepancies.

---

## Spreadsheet CMDB Improvement Summary

The original asset register was reviewed and updated to create a more structured CMDB. Missing information was added where possible, and new fields were introduced to improve asset tracking, ownership, and review processes.

The improved CMDB now includes asset type, manufacturer, model, serial number, assigned user, department, location, operating system, IP address, business criticality, asset status, warranty expiry, and last review date.

The improved spreadsheet provides the organisation with a clearer view of its IT assets and creates a stronger foundation for future migration into a dedicated CMDB tool such as Snipe-IT.

**Screenshot 2 – Improved Spreadsheet CMDB**

<img width="1834" height="596" alt="image" src="https://github.com/user-attachments/assets/d4ce458e-4b98-4963-ad1a-1813406d4651" />

---

## 6. Migration to Snipe-IT

As the organisation grows, maintaining the CMDB in Microsoft Excel becomes increasingly difficult. Manual updates increase the risk of inaccurate records, duplicate entries, and inconsistent asset information.

To improve efficiency and provide a centralised asset management solution, the organisation recommended migrating the spreadsheet-based CMDB to Snipe-IT, an open-source IT asset management platform.

The migration would preserve the existing asset information while providing additional features such as:

- Centralised asset inventory
- Asset assignment to users
- Asset categories and locations
- Improved search and reporting
- Asset history and audit trail
- Role-based access control

Following the migration, the spreadsheet would be retained as a backup, and all future asset updates would be managed within Snipe-IT.

The following screenshots demonstrate the Snipe-IT asset management platform after the migration from the spreadsheet-based CMDB.

### Snipe-IT Dashboard

**Figure 1.** Snipe-IT Dashboard – Displays an overview of the organisation's asset management system, providing a summary of managed assets and quick access to key asset management functions.

<img width="940" height="811" alt="image" src="https://github.com/user-attachments/assets/df2217ad-06a9-4846-9c68-8cb02bc0fec8" />

### Asset Inventory

**Figure 2.** Asset Inventory – Displays the centralised asset register containing hardware assets, assigned users, locations, asset status, and other inventory information maintained within the CMDB.

<img width="940" height="634" alt="image" src="https://github.com/user-attachments/assets/00024e1e-a939-4c17-97b8-8b6203cdbd72" />

### Asset Details

**Figure 3.** Asset Details – Displays detailed information for an individual asset, including hardware specifications, assigned owner, location, asset status, and lifecycle information used to support ongoing asset management.

<img width="940" height="556" alt="image" src="https://github.com/user-attachments/assets/de3929b5-0d03-42e5-8ee3-1370101191a3" />

---

## Project Outcome

The project successfully improved the organisation's asset management process by transforming an incomplete and inconsistent spreadsheet into a structured Configuration Management Database (CMDB). Asset information was reviewed, validated, and enhanced with business and technical data, including ownership, department, location, operating system, business criticality, and lifecycle information.

A formal maintenance process was established to ensure the CMDB remains accurate through regular reviews and updates by the IT department. This provides the organisation with a reliable inventory of IT assets, improving accountability, operational efficiency, and support for future security and compliance activities.

As the organisation continues to grow, the spreadsheet-based CMDB may become increasingly difficult to maintain. To support future growth, the organisation recommended migrating to Snipe-IT. This provides a centralised asset management platform capable of managing the asset lifecycle more efficiently while maintaining accurate and up-to-date asset information.
