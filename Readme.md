# 🌍 Navarro Streams Analysis — ArcGIS Pro Project

## 📌 Project Overview

This project demonstrates a complete introductory GIS workflow using **ArcGIS Pro**, focusing on data acquisition, visualization, and spatial analysis. The objective was to extract and analyze stream networks within the Navarro watershed boundary using the NHD Flowline dataset.

This project reflects real-world GIS practices such as working with geodatabases, applying symbology for interpretation, and performing spatial queries to isolate meaningful subsets of data.

## 🛠️ Tools & Technologies

### Software

* ArcGIS Pro *(access provided via UC Davis)*

### GIS Tools Used

* **Explore Tool** — used to inspect spatial features and attribute data
* **Select By Location** — used to identify features based on spatial relationships
* **Export Features** — used to create a new dataset from selected features
* **Symbology Panel** — used to modify visual representation of spatial data

---
## 🗂️ Datasets

### 1. NHD Flowline Dataset

* **Type:** File Geodatabase Feature Class
* **Source:** National Hydrography Dataset (NHD)
* **Description:**
  Represents linear water features such as rivers, streams, and flow paths.
  Attribute data includes feature names and classifications, allowing verification of real-world water systems.

---

### 2. Navarro Boundary Dataset

* **Type:** Polygon Feature Class
* **Description:**
  Defines the geographic boundary of the Navarro watershed, used to spatially constrain the analysis.

---

### 🧠 Data Structure: File Geodatabase

Both datasets are stored within a **File Geodatabase (.gdb)**, which functions as:

i. A structured container for spatial datasets
ii. A system for managing relationships between geographic features
iii. An efficient format for storing and querying large geospatial data

### 🔑 Key Insight: Authentication in ArcGIS Pro

Access to institutional resources in ArcGIS Pro requires connecting to the correct ArcGIS Online organization. This is done by entering the organization URL during sign-in, which links the user to shared datasets, licenses, and cloud-based tools.

---

## 🗂️ Data Management & Geodatabases

Data was imported and organized using ArcGIS Pro’s Catalog system.

* Opened the **Catalog Pane**
* Connected to the folder containing extracted course data
* Located and accessed `source.gdb`
* Added the **NHD Flowline** dataset to the map

### 🧠 Understanding Geodatabases

A geodatabase is best understood as a **structured, folder-like database** designed to store and organize spatial data. It supports multiple datasets, preserves relationships, and enables efficient data management within GIS workflows.

---

## 🔍 Exploring the Data

Initial exploration helps build familiarity with spatial and attribute data.

* Used zoom tools to examine spatial distribution at different scales
* Applied the **Explore Tool** to inspect individual features
* Accessed attribute tables to review feature-level information

### 🌊 Understanding the NHD Flowline Dataset

The NHD Flowline dataset represents **surface water features**, including rivers, streams, and flow paths. This can be confirmed by:

* Inspecting the attribute table (e.g., stream names and classifications)
* Reviewing metadata within layer properties

---

## 🎨 Symbology & Data Visualization

Symbology was adjusted to improve interpretability of spatial features.

* Modified line color to reflect real-world representation (e.g., blue for water features)

### 🎯 Why Symbology Matters

Effective symbology bridges the gap between raw data and human understanding. By aligning map visuals with real-world expectations (e.g., blue for rivers), users can quickly interpret spatial information. For example, changing stream lines to blue makes them immediately recognizable, improving clarity during analysis.

---

## 📍 Spatial Analysis: Focusing on Navarro Watershed

To refine the analysis, the dataset was constrained to a specific geographic region.

* Added the **Navarro boundary** layer
* Used **Select By Location** to identify streams intersecting the boundary
* Exported the selected features as a new dataset: `navarro_streams`

### 🧠 Why Subset Data by Boundary?

Subsetting data allows analysts to:

* Focus on a specific area of interest
* Reduce data complexity
* Improve processing efficiency

In this case, isolating streams within the Navarro watershed enables targeted environmental or hydrological analysis relevant to that region.

---

## 🔄 Workflow Diagram

```
Data Acquisition → Project Setup → Data Import → Exploration → Symbology → Spatial Selection → Export → Final Dataset
```

---

## 📊 Results & Outcome

* Successfully extracted stream features within the Navarro boundary
* Created a new dataset (`navarro_streams`) for focused analysis
* Improved data visualization through effective symbology
* Demonstrated the use of spatial queries in GIS workflows

---

## 📷 Visual Documentation

* NHD Flowline dataset visualization - Insert GitHub link
* Select By Location results Insert GitHub link


---

## 🧾 Conclusion

This project demonstrates foundational GIS skills including data management, visualization, and spatial analysis. By extracting and analyzing streams within a defined watershed, the workflow highlights how GIS enables focused, location-based insights. These techniques are essential for real-world applications such as environmental monitoring, resource management, and spatial decision-making.

---
