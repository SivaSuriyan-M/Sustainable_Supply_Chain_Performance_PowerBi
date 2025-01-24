# Sustainable Supply Chain Performance – Week 1

## Objectives
- Load the provided CSV file into Power BI.
- Use Power Query to transform the data by creating multiple separate tables:
  - Inventory Table
  - Manufacturing Table
  - Supplier Table
  - Supply Chain Table
- Perform data transformations by duplicating the original table and retaining only the relevant columns for each table.

---

## Steps Performed

### 1. Loading the Data into Power BI
1. Open **Power BI Desktop**.
2. Navigate to **Home > Get Data > Text/CSV**.
3. Select the file `Sustainable Supply Chain Performance.csv`.
4. Preview the data in the import window and click **Load** to bring it into Power BI.

---

### 2. Creating Separate Tables with Power Query
The following transformations were performed for each table:

#### **A. Inventory Table**
1. Open **Power Query Editor** (`Transform Data`).
2. Right-click the original table and select **Duplicate**.
3. Rename the duplicated table to **Inventory Table**.
4. Retain the following columns:
   - `SKU`
   - `Product type`
   - `Availability`
   - `Stock levels`
   - `Lead times`
   - `Order quantities`
5. Remove all other columns using the **Remove Other Columns** option.
6. Review and apply the changes.

#### **B. Manufacturing Table**
1. Duplicate the original table and rename it to **Manufacturing Table**.
2. Retain the following columns:
   - `Production volumes`
   - `Manufacturing lead time`
   - `Manufacturing costs`
   - `Inspection results`
   - `Defect rates`
3. Remove all other columns and review the data for accuracy.
4. Apply the changes.

#### **C. Supplier Table**
1. Duplicate the original table and rename it to **Supplier Table**.
2. Retain the following columns:
   - `Supplier name`
   - `Location`
   - `Lead time`
3. Remove all other columns.
4. Apply the changes.

#### **D. Supply Chain Table**
1. Duplicate the original table and rename it to **Supply Chain Table**.
2. Retain the following columns:
   - `Transportation modes`
   - `Routes`
   - `Shipping costs`
   - `Shipping times`
   - `Costs`
3. Remove all other columns.
4. Apply the changes.

---

### 3. Data Validation
- Each table was reviewed to ensure the correct columns were retained.
- Missing or incomplete data (if any) was identified, but no cleaning was performed as part of the Week 1 task.

---

### 4. Insights and Observations
- The original dataset was successfully divided into four separate tables:
  - **Inventory Table**: Focused on stock and product details.
  - **Manufacturing Table**: Highlighted production and quality metrics.
  - **Supplier Table**: Contained supplier and location data.
  - **Supply Chain Table**: Focused on logistics and transportation.
- These tables will be used for further analysis and visualization in subsequent tasks.

---

### Challenges
- Identifying relevant columns for each table required careful attention.
- Ensuring no accidental data loss during transformations.

---

## Tools Used
- **Power BI Desktop**: For data transformation and modeling.
- **Power Query**: For duplicating tables and removing unnecessary columns.

---

## Screenshot

![Screenshot 2025-01-24 111141](https://github.com/user-attachments/assets/1c87fe8e-a069-4158-8a37-e5d57043a2a1)

---

Feel free to reach out if you have questions or suggestions!

