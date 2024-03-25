# Excel Tips and Shortcuts

This README file contains a list of Excel shortcuts and formulas for various tasks.

## Shortcuts

### Currency Formatting Shortcut
- **Shortcut:** Ctrl+Shift+4

### Format Cells
- **Shortcut:** Ctrl+1

### Add Filters
- **Shortcut:** Ctrl+Shift+L

## Formulas

### 1. Greater Than Condition
- **Steps:**
  1. Select column.
  2. Go to Conditional Formatting.
  3. Choose "Greater Than" and set the value.

### 2. Sum in a Column
- **Steps:**
  1. Go to a new row.
  2. Enter `=SUM(Select column)`.
  3. Press Enter.

### 3. Sum of One Category
- **Formula:** `=SUMIF(Select Category column, category(food), the amount column)`

### 4. Sum Values in a Table
- **Formula:** `=SUM(Table_Name[Column Name])`

### 5. Create Table Shortcut
- **Shortcut:** Select any cell, then press Ctrl+T.

### 6. Quartile of Data
- **Formula:** `=PERCENTILE.EXC(data[Amount], 0.25 or 0.75)`

### 7. Total Count of Products
- **Formula:** `=COUNTA(UNIQUE(Data[Product]))`

### 8. Sales by Country (Through Formulas)
- **Formula:** `=SUMIFS(data[Amount], data[Geography], Row of the country(B3))`

## Additional Information

### Changing Column Widths of a Table
- **Steps:**
  1. Go to Home > Cells > Format.
  2. Under Cell Size, select AutoFit Column Width.

### Sales by Country (Through Pivot)
- **Steps:**
  1. Insert a pivot table.
  2. Choose the appropriate table name.

### $ Per Unit
- **Steps:**
  1. Select a row in the pivot table.
  2. Go to the data model in pivot table fields.
  3. Right-click on data.


