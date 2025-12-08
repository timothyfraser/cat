<!-- CAT Platform Navigation Bar -->
<link rel="stylesheet" href="assets/css/navbar.css">

<nav class="cat-navbar">
  <div class="cat-navbar-container">
    <div class="cat-navbar-logo">
      <a href="https://cat-apps.com/" title="CAT Platform">
        <img src="assets/images/cat_logo.svg" alt="CAT Platform" height="50px">
      </a>
    </div>
    <div class="cat-navbar-links">
      <a href="https://cat-apps.com/">Dashboard</a>
      <a href="index.html">Documentation</a>
      <a href="https://cat-apps.com/">Sign In</a>
    </div>
  </div>
</nav>

# Aggregator Guide

Learn how to use the Aggregator to compare emissions data across multiple counties side-by-side.

## What is the Aggregator?

The **Aggregator** is a tool that lets you:
- Select multiple counties at once
- Compare emissions data across different geographic areas
- Filter by pollutant, aggregation level, and metrics
- View aggregated data in tables and charts
- Analyze regional patterns and differences

This is useful for:
- Regional planning: Comparing multiple counties in your region
- MPO analysis: Analyzing emissions across your planning area
- State-level analysis: Comparing counties within a state
- Identifying patterns: Finding which areas have higher/lower emissions

## Accessing the Aggregator

1. Click **"AGGREGATOR"** in the sidebar (TOOLS section)
2. The Aggregator page will load with toggleable sidebars

## Understanding the Interface

The Aggregator has a unique layout with toggleable sidebars:

- **Left Sidebar (County Panel)**: List of counties you can select
- **Right Sidebar (Selection Panel)**: Filters and options
- **Main Content Area**: Data table and comparison charts
- **Toggle Buttons**: Show/hide the sidebars

### Toggle Buttons

At the top, you'll see buttons to show/hide sidebars:
- **"☰ County Panel"**: Toggle the left sidebar (county selection)
- **"☰ Selection Panel"**: Toggle the right sidebar (filters)

Click these buttons to show or hide the sidebars as needed.

## Step-by-Step: Using the Aggregator

### Step 1: Select Counties

1. In the **left sidebar (County Panel)**, you'll see a table of available counties
2. **Select counties** by clicking the checkboxes on the left of each row
3. You can select multiple counties at once
4. Use **"Select All"** to select all counties, or **"Deselect All"** to clear selections

> **Note**: The county list shows available data files. Currently, this may include sample data. Future versions will show your actual orders.

### Step 2: Choose Pollutant

1. In the **right sidebar (Selection Panel)**, find **"Pollutant"**
2. Select the pollutant you want to analyze:
   - **CO2e**: Carbon dioxide equivalent
   - **CO**: Carbon monoxide
3. Available options depend on the data

### Step 3: Select Aggregation Level

1. In the **right sidebar**, find **"Aggregation Level"**
2. Choose how you want data grouped:
   - **Overall**: No sub-grouping, total emissions
   - **By Vehicle Type**: Group by source type (motorcycles, cars, trucks, buses, etc.)
   - **By Fuel Type**: Group by fuel (gasoline, diesel, CNG, electric, etc.)
   - **By Road Type**: Group by road classification (rural/urban, restricted/unrestricted)
   - **By Regclass**: Group by regulatory class (light duty, medium/heavy duty, etc.)

### Step 4: Select Group Type (if applicable)

1. If you selected an aggregation level other than "Overall", a **"Select Group"** dropdown will appear
2. Choose the specific group you want to analyze:
   - **By Vehicle Type**: Select specific vehicle type (e.g., "Passenger Cars")
   - **By Fuel Type**: Select specific fuel (e.g., "Gasoline")
   - **By Road Type**: Select specific road type (e.g., "Urban Unrestricted Access")
   - **By Regclass**: Select specific regulatory class (e.g., "Light Duty Vehicles")
3. If "Overall" is selected, this dropdown won't appear

### Step 5: Select Metrics

1. In the **right sidebar**, find **"Metrics"**
2. Select one or more metrics to display:
   - **Emissions**: Total emissions values
   - **VMT**: Vehicle miles traveled
   - **Vehicles**: Vehicle counts
3. You can select multiple metrics to compare

### Step 6: View Results

The **main content area** will automatically update showing:

- **Emissions Data Table**: Pivot table with aggregated data
  - Rows: Years and counties
  - Columns: Selected metrics
  - Values: Aggregated emissions/VMT/vehicles
- **Comparison Plot**: Bar chart comparing counties
  - Separate panels (facets) for each metric
  - Color-coded bars for each county
  - Easy visual comparison

## Understanding the Results

### Data Table

The table shows:
- **Rows**: Each row represents a year-county combination
- **Columns**: Each column represents a metric (Emissions, VMT, Vehicles)
- **Values**: Aggregated totals based on your filters
- **Sorting**: Click column headers to sort

### Comparison Chart

The bar chart shows:
- **X-axis**: Counties being compared
- **Y-axis**: Values for the selected metrics
- **Facets**: Separate panels for each metric (if multiple selected)
- **Colors**: Different colors for visual distinction
- **Bars**: Height represents the value

**Reading the Chart:**
- Taller bars = higher values
- Compare bars across counties to see differences
- Each metric has its own panel for clarity

## Tips for Using the Aggregator

1. **Start with Overall**: Begin with "Overall" aggregation to see total emissions, then drill down
2. **Select Multiple Metrics**: Compare emissions, VMT, and vehicles together to understand relationships
3. **Use Filters Strategically**: Filter by specific vehicle types or fuel types to focus your analysis
4. **Toggle Sidebars**: Hide sidebars when you want more space for the charts
5. **Compare Gradually**: Start with 2-3 counties, then add more as needed

## Common Scenarios

### Scenario 1: Compare Total Emissions Across Counties

1. Select 3-5 counties in County Panel
2. Choose pollutant (e.g., CO2e)
3. Select "Overall" aggregation level
4. Select "Emissions" metric
5. View table and chart to see which county has highest emissions

### Scenario 2: Compare Vehicle Types

1. Select counties
2. Choose pollutant
3. Select "By Vehicle Type" aggregation
4. Select a specific vehicle type (e.g., "Passenger Cars")
5. Select "Emissions" metric
6. See how passenger car emissions compare across counties

### Scenario 3: Multi-Metric Analysis

1. Select counties
2. Choose pollutant and aggregation
3. Select all three metrics: Emissions, VMT, Vehicles
4. View separate panels for each metric
5. Understand relationships: high VMT doesn't always mean high emissions (depends on vehicle mix)

### Scenario 4: Fuel Type Comparison

1. Select counties
2. Choose pollutant
3. Select "By Fuel Type" aggregation
4. Select a fuel type (e.g., "Electric")
5. Compare electric vehicle usage across counties

## Understanding Aggregation Levels

### Overall

- Shows total emissions without breakdown
- Best for: High-level comparisons
- Use when: You want to see which county has most total emissions

### By Vehicle Type

- Breaks down by vehicle categories
- Best for: Understanding which vehicle types drive emissions
- Use when: Analyzing fleet composition impacts

### By Fuel Type

- Breaks down by fuel categories
- Best for: Understanding fuel mix impacts
- Use when: Analyzing alternative fuel adoption

### By Road Type

- Breaks down by road classifications
- Best for: Understanding geographic distribution
- Use when: Analyzing urban vs. rural patterns

### By Regclass

- Breaks down by regulatory classes
- Best for: Regulatory and compliance analysis
- Use when: Working with regulatory frameworks

## Troubleshooting

### No Data Showing

If the table or chart is empty:
1. Make sure you've selected at least one county
2. Verify you've selected a pollutant, aggregation level, and metric
3. Check that the selected group type (if applicable) exists in the data
4. Try selecting "Overall" aggregation to see if data appears

### Counties Not Available

If you don't see the counties you need:
1. Currently, the Aggregator may use sample data
2. Future versions will show your actual orders
3. Create orders for the counties you need first
4. Contact support if you need specific counties

### Chart Not Updating

If the chart doesn't change when you adjust filters:
1. Wait a moment for the chart to recalculate
2. Make sure you've clicked to save your filter selections
3. Try toggling a sidebar off and on
4. Refresh the page if needed

## Future Enhancements

The Aggregator is being enhanced to:
- Show your actual order data (not just sample data)
- Allow selecting orders directly from your orders table
- Load data from your order buckets automatically
- Support more counties and data sources

## Next Steps

After using the Aggregator:

1. **[Create Orders](creating-orders.md)** - Create orders for counties you want to compare
2. **[Visualize Data](visualizer-guide.md)** - Use Visualizer for more detailed exploration
3. **[Generate Reports](reporter-guide.md)** - Create reports comparing counties
4. **[Download Data](data-hub-guide.md)** - Use Data Hub for bulk downloads

## Related Topics

- **[Creating Orders](creating-orders.md)** - Create orders for counties to compare
- **[Visualizer Guide](visualizer-guide.md)** - Detailed visualization of individual counties
- **[Data Hub Guide](data-hub-guide.md)** - Bulk download data for analysis
- **[Reporter Guide](reporter-guide.md)** - Generate reports with comparisons

---

**Ready to download data in bulk?** See [Data Hub Guide](data-hub-guide.md) for bulk download capabilities.




