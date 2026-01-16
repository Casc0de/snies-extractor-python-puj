# snies-extractor-python-puj

## README Summary

### **Project: SNIES Extractor**

**Purpose**: Tool to manage and process academic data from Colombia's National Higher Education Information System (SNIES), automating the loading, processing, and exporting of information about academic programs.

---

### **Main Objective**
Facilitate the management of educational data (enrolled, admitted, graduated students) by reducing manual errors and improving efficiency in processing academic information.

---

### **System Architecture**

**3 Main Layers:**

1. **User Interface (Streamlit)**
   - Load predefined or new Excel files
   - Filter by keywords and year ranges
   - Visualize and download results

2. **SNIES Controller** 
   - Core business logic
   - Manages file loading and processing
   - Coordinates between interface and file manager

3. **File Manager**
   - Reads Excel files with Pandas
   - Processes and transforms data
   - Consolidates and exports results

---

### **Workflow**

1. **Load** → Upload Excel files with academic data
2. **Process** → Organize by academic program and year
3. **Export** → Generate consolidated files (Excel/JSON)

---

### **Technologies**
- **Streamlit** - Interactive web interface
- **Pandas** - Data processing
- **OpenPyXL** - Excel read/write
- **Plotly** - Visualizations

---

### **Key Features**
- Multiple file loading
- Advanced filtering by keywords and years
- Data transformation and cleaning
- Multi-format export
- Processed results visualization
