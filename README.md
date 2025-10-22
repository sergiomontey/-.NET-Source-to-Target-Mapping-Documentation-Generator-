# 🗺️ Source-to-Target Mapping Documentation Generator (STTM Gen)
![.NET MAUI](https://img.shields.io/badge/.NET_MAUI-CrossPlatform-purple.svg)
![C#](https://img.shields.io/badge/C%23-10%2B-512BD4.svg)
![MVVM](https://img.shields.io/badge/Architecture-MVVM-green.svg)
![Status](https://img.shields.io/badge/Status-In_Development-yellow.svg)

> **A professional desktop application for ETL consultants** - Eliminate hours of manual Excel work by providing an intuitive GUI for documenting complex data mappings.

---

## 🎯 Overview

STTM Gen is a **.NET MAUI** desktop application designed specifically for **ETL (Extract, Transform, Load)** and **Data Migration** consultants. It provides a structured, guided, and persistent way to document the source-to-target mapping process, transforming the usual error-prone manual Excel task into a streamlined, professional workflow.

### 🌟 Key Features

* **✅ Visual Mapping Form**: Intuitive form entry for documenting `Source Table/Column` $\to$ `Target Table/Column`.
* **💡 Transformation Logic Capture**: Dedicated multi-line entry for documenting complex business logic and SQL/code transformations.
* **📑 Business Rule Documentation**: Capture and link specific data quality or business validation rules to each mapping.
* **🔢 Data Type Selection**: Dropdown selectors for defining and confirming target data types.
* **💾 JSON Project Persistence**: **Save** and **Load** entire mapping projects to a single, readable `.sttm.json` file.
* **📊 Real-time Table View**: A live, interactive DataGrid/CollectionView displaying all documented mappings.
* **📄 Professional Excel Export**: Generate a highly formatted, client-ready **Excel** document (using **ClosedXML**) with clear headings, borders, and text wrapping.
* **🗑️ Delete & Clear**: Simple functionality for managing (editing, deleting, clearing) mapping entries.

---

## 🎬 Screenshots

| Mapping Entry Form | Real-time Mapping Grid |
| :---: | :---: |
| ** | ** |
| *Intuitive entry fields for source, target, and logic* | *Live, scrollable table view of all mappings* |

---

## 🚀 Quick Start (Development)

STTM Gen is built with **.NET MAUI** and C\#.

### Prerequisites

* **.NET 8 SDK** (or newer)
* **Visual Studio 2022** (Community or higher) with the **.NET Multi-platform App UI development** workload installed.

### 1. Clone the Repository

```bash
git clone [https://github.com/yourusername/sttm-documentation-generator.git](https://github.com/yourusername/sttm-documentation-generator.git)
cd sttm-documentation-generator
