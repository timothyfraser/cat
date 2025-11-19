# Translators Guide

Learn how to use the Translators tool to edit MOVES input tables for custom emissions modeling scenarios.

## What is the Translators Tool?

The **Translators** tool lets you:
- View and edit MOVES (Motor Vehicle Emission Simulator) input tables
- Customize activity data for emissions modeling
- Save your edited tables for future use
- Download edited tables as CSV files
- Load previously saved tables

This is an **advanced feature** for users who need to customize MOVES input data beyond the default values.

> **Note**: This tool is for advanced users familiar with MOVES input table formats. If you're new to emissions modeling, you may want to start with the Calculator or create orders with default values.

## Accessing the Translators Tool

1. Click **"TRANSLATORS"** in the sidebar (TOOLS section)
2. The Translators page will load

## Understanding MOVES Input Tables

MOVES uses various input tables that define:
- **Activity Data**: VMT, vehicle counts, starts, hours
- **Vehicle Distributions**: Percentages by vehicle type
- **Fuel Distributions**: Percentages by fuel type
- **Road Type Distributions**: Percentages by road classification
- **Other Parameters**: Various modeling parameters

Common table types include:
- SourceTypeYear: Vehicle type distributions
- FuelTypeYear: Fuel type distributions
- RoadTypeYear: Road type distributions
- And many others

## Step-by-Step: Using the Translators Tool

### Step 1: Select a Table

1. In the **"Table"** dropdown, select the MOVES input table you want to edit
2. Available tables depend on what's available in the system
3. The table will load and display in an editable format

### Step 2: Review the Table

1. The table will show columns and rows of data
2. Review the structure and current values
3. Understand what each column represents
4. Note any default values that are already set

### Step 3: Edit Values

1. **Click on a cell** to edit it
2. **Enter a new value**
3. **Press Enter** or click elsewhere to save
4. The table will update with your changes

**Editing Tips:**
- Be careful with data types (numbers vs. text)
- Ensure percentages add up correctly (if applicable)
- Maintain data consistency across related fields
- Save your work frequently

### Step 4: Save Your Table

1. Click the **"Save"** button
2. Your edited table will be saved to your account
3. You can load it later for use in orders or further editing
4. Saved tables are associated with your user account

### Step 5: Download Your Table

1. Click the **"Download"** button
2. Your edited table will download as a CSV file
3. You can use this file when creating orders (upload as custom file)
4. Or use it in other tools for analysis

### Step 6: Load Saved Tables

1. Click **"View History"** or similar button
2. You'll see a list of previously saved tables
3. Select a saved table to load it
4. Continue editing or use it as-is

## Using Edited Tables in Orders

After editing and saving a table:

1. **Download the table** as CSV
2. **Go to New Order** page
3. **Upload your edited table** (or ZIP containing multiple tables)
4. **Submit the order** with your custom inputs
5. The order will use your edited values instead of defaults

## Understanding Table Formats

### Common Columns

Depending on the table type, you may see:
- **Year**: The year for the data
- **Geographic identifiers**: County, state, etc.
- **Category codes**: Vehicle type codes, fuel type codes, etc.
- **Activity values**: VMT, vehicles, starts, hours
- **Percentages**: Distributions by category
- **Other parameters**: Various modeling inputs

### Data Validation

The system may validate:
- Required fields are filled
- Data types are correct
- Ranges are reasonable
- Relationships between fields are consistent

## Tips for Using the Translators Tool

1. **Start with Defaults**: Load default tables first to understand the structure
2. **Make Small Changes**: Test with small edits before making major changes
3. **Document Changes**: Note what you changed and why
4. **Save Frequently**: Save your work regularly
5. **Download Backups**: Download edited tables as backups
6. **Test in Calculator**: Use the Calculator to test your edited values before creating orders

## Common Tasks

### Task 1: Adjust Vehicle Type Distribution

1. Select SourceTypeYear or similar table
2. Find vehicle type percentages
3. Adjust percentages (ensure they add to 100%)
4. Save and download
5. Use in an order

### Task 2: Modify Fuel Mix

1. Select FuelTypeYear table
2. Adjust fuel type percentages
3. Increase electric vehicle percentage, decrease gasoline
4. Save and use in orders

### Task 3: Customize Activity Data

1. Select activity-related table
2. Edit VMT, vehicle counts, or other activity measures
3. Save and download
4. Upload when creating orders

## Troubleshooting

### Table Won't Load

If a table doesn't load:
1. Check your internet connection
2. Try selecting a different table
3. Refresh the page
4. Contact support if problem persists

### Can't Edit Cells

If cells aren't editable:
1. Make sure you've selected a table
2. Wait for the table to fully load
3. Try clicking directly on a cell
4. Check if the table type allows editing

### Save Failed

If saving fails:
1. Check that all required fields are filled
2. Verify data formats are correct
3. Ensure you're logged in
4. Try again or contact support

## Advanced Usage

### Working with Multiple Tables

For complex scenarios:
1. Edit multiple related tables
2. Save each one
3. Download all edited tables
4. Create a ZIP file containing all tables
5. Upload ZIP when creating an order

### Integrating with Other Tools

1. Download edited tables as CSV
2. Import into Excel for further editing
3. Use in R or Python for analysis
4. Re-upload when ready for orders

## Related Topics

- **[Creating Orders](creating-orders.md)** - Use edited tables when creating orders
- **[Calculator Guide](calculator-guide.md)** - Test scenarios before editing tables
- **[Viewing Orders](viewing-orders.md)** - Check results from orders using custom tables

## Next Steps

After editing tables:

1. **[Test in Calculator](calculator-guide.md)** - See how changes affect emissions
2. **[Create an Order](creating-orders.md)** - Use edited tables in a full modeling order
3. **[View Results](viewing-orders.md)** - Check how your custom inputs affected results

---

**Need to test your changes?** See [Calculator Guide](calculator-guide.md) to estimate emissions with your edited values.

