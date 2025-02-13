# Belly Button Biodiversity Dashboard

## 📌 Overview

This project is part of my **University of Toronto Data Analytics Bootcamp (Module 14 Challenge)**. The goal is to create an **interactive dashboard** using **JavaScript, D3.js, and Plotly.js** to explore the **Belly Button Biodiversity dataset**. The dataset catalogs microbial species found in human navels and reveals that a small number of species are commonly present in most individuals, while the rest are rare.

---

## 🎯 Objectives

- **Develop an Interactive Dashboard** to visualize the dataset.
- **Create a Horizontal Bar Chart** to display the top 10 OTUs for each individual.
- **Generate a Bubble Chart** to represent microbial diversity across samples.
- **Display Demographic Metadata** for each selected individual.
- **Ensure the Dashboard Updates Dynamically** when selecting a new individual.
- **Deploy the Application** using **GitHub Pages**.

---

## 📂 Project Deliverables

### **1️⃣ Project Setup**
- Create a new GitHub repository: `belly-button-challenge`.
- Clone the repository and add the provided starter files.
- Push changes to GitHub and deploy via GitHub Pages.

### **2️⃣ Interactive Visualizations**
- **Bar Chart:**
  - Displays the **Top 10 OTUs** for a selected individual.
  - Uses `sample_values` as values.
  - Uses `otu_ids` as labels.
  - Uses `otu_labels` for hover text.
- **Bubble Chart:**
  - Uses `otu_ids` for the x-axis.
  - Uses `sample_values` for the y-axis and marker size.
  - Uses `otu_ids` for marker colors.
  - Uses `otu_labels` for hover text.
- **Demographic Info Panel:**
  - Displays metadata for the selected individual.
  - Dynamically updates with new selections.

### **3️⃣ Deployment**
- Publish the project to **GitHub Pages**.
- Ensure all plots update dynamically.
- Submit the repository and live deployment link.

---

## 🛠️ Technologies Used

### **Libraries & Tools**
- **JavaScript & D3.js**: Data fetching and manipulation.
- **Plotly.js**: Interactive visualizations.
- **HTML & CSS**: Structuring and styling the dashboard.
- **GitHub Pages**: Deployment.

### **Key Concepts & Techniques**
- Fetching external JSON data using `d3.json()`.
- Creating interactive charts with **Plotly.js**.
- Dynamically updating visualizations with event listeners.
- Deploying web applications using **GitHub Pages**.

---

## 📖 Steps to Reproduce

### **1️⃣ Setup Repository & Environment**
1. Clone the repository:
   ```sh
   git clone git@github.com:Oceanpro00/belly-button-challenge.git
   ```
2. Navigate into the project folder:
   ```sh
   cd belly-button-challenge
   ```
3. Open the project in **VS Code**.

### **2️⃣ Run the Dashboard Locally**
1. Open `index.html` in a web browser.
2. Ensure `samples.json` is accessible via the provided URL.
3. Use the dropdown menu to select different individuals and observe updates.

### **3️⃣ Deploy the Project**
1. Push all changes to GitHub:
   ```sh
   git add .
   git commit -m "Initial commit with dashboard files"
   git push origin main
   ```
2. Enable **GitHub Pages** in the repository settings.
3. Verify the deployment link.

---

## 📊 Data Visualizations & Functionality

### **1️⃣ Horizontal Bar Chart**
- Displays the **Top 10 OTUs** for each individual.
- Updates when a new sample is selected.
- Uses `sample_values` for the bar lengths.
- Uses `otu_ids` for labels and `otu_labels` for tooltips.

### **2️⃣ Bubble Chart**
- Displays all microbial species in a sample.
- Uses `otu_ids` (x-axis) and `sample_values` (y-axis).
- Marker size represents `sample_values`.
- Marker color represents `otu_ids`.
- Hover text displays `otu_labels`.

### **3️⃣ Demographic Information Panel**
- Shows key metadata for each individual.
- Updates dynamically based on the selected sample.

---

## 🚀 Deployment & Submission

- **Deployed Application:** [Belly Button Biodiversity Dashboard](https://oceanpro00.github.io/belly-button-challenge/)
- **Ensure all visualizations work correctly** when interacting with the dropdown.
- **Submit both**:
  - **GitHub repository link**
  - **Deployed app link**

---

## 📁 Repository Breakdown

The repository is structured as follows:

```
belly-button-challenge/
│-- index.html  # Main HTML file for the dashboard
│-- app.js  # JavaScript file handling data fetching and visualization
│-- samples.json  # Dataset containing microbiome information
│-- README.md  # Documentation for the project
│-- static/
│   │-- css/
│   │   └── style.css  # Styling for the dashboard
│   └── js/
│       └── plots.js  # JavaScript file for Plotly visualizations
```

- **index.html:** Main webpage structure.
- **app.js:** Handles data retrieval and interactivity.
- **samples.json:** Dataset with microbiome details (included for reference but not directly used in the dashboard). The data is instead imported dynamically from the external source: [Belly Button Biodiversity Dataset](https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json).
- **static/css/style.css:** Stylesheet for layout and design.
- **static/js/plots.js:** Generates visualizations using Plotly.
- **README.md:** Project documentation and setup instructions.

---

- **Deploy to GitHub Pages** for public access.
- **Ensure all visualizations work correctly** when interacting with the dropdown.
- **Submit both**:
  - **GitHub repository link**
  - **Deployed app link**

---

## 🏆 Acknowledgments

This project was developed as part of the **University of Toronto Data Analytics Bootcamp**.

---
