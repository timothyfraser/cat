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

# Visualizer Guide

Learn how to use the Visualizer to explore your emissions data with interactive charts, maps, and visualizations.

## What is the Visualizer?

The **Visualizer** is an interactive tool that lets you:
- View emissions data as charts, maps, and tables
- Compare different scenarios and time periods
- Explore data by vehicle type, fuel type, road type, and more
- Combine your custom order data with public CAT Grand Database data
- Export visualizations for presentations and reports

## Accessing the Visualizer

1. Click **"VISUALIZER"** in the sidebar (MENU section)
2. Or click **"Visualizer"** from the Welcome page under "Explore Your Data"
3. The Visualizer page will load with several sections (accordions)

## Understanding the Interface

The Visualizer is organized into sections that you expand and collapse:

1. **SELECT CUSTOM ORDER DATA**: Choose your own order data to include
2. **CHOOSE YOUR SCENARIO**: Select what data to visualize (geographic area, year, pollutant, etc.)
3. **PROFILE**: Summary statistics and overview
4. **TOOLBOX**: Multiple visualization types (charts, maps, etc.)

## Step-by-Step: Using the Visualizer

### Step 1: Select Custom Order Data (Optional)

If you want to visualize data from your own orders:

1. Expand the **"SELECT CUSTOM ORDER DATA"** section
2. You'll see a table listing your orders
3. Select one or more orders by clicking the checkboxes
4. Selected orders' data will be loaded and used in visualizations

> **Note**: You can skip this step to view only public CAT Grand Database data. Your custom order data will override public data for the same county/year if both are available.

### Step 2: Choose Your Scenario

Expand the **"CHOOSE YOUR SCENARIO"** section to configure what you want to visualize:

#### Search (Table Selection)

1. In the **"SEARCH"** dropdown, select a table:
   - **Granddata tables**: Public data (e.g., "granddata.d36109" for Tompkins County, NY)
   - **Orderdata tables**: Your custom order data (e.g., "orderdata.d36109_u8_o1")
2. The table name includes the FIPS code (geoid) for the county

#### Year

1. Select the **year** you want to visualize
2. Available years depend on the selected table

#### Pollutant

1. Select the **pollutant** you want to analyze:
   - **CO2e** (code 98): Carbon dioxide equivalent
   - **CO** (code 2): Carbon monoxide
   - **NOx** (code 3): Nitrogen oxides
   - And others
2. Different pollutants show different aspects of emissions

#### Highlight

1. Select what to **highlight** in visualizations:
   - Options vary but may include vehicle types, fuel types, road types, etc.
2. This affects how data is grouped and displayed

#### Options (Metrics)

1. Select one or more **metrics** to display:
   - **Emissions**: Total emissions values
   - **VMT**: Vehicle miles traveled
   - **Vehicles**: Vehicle counts
2. You can select multiple metrics to compare

### Step 3: View Profile

The **"PROFILE"** section shows:
- Summary statistics for your selected scenario
- Key metrics and totals
- Overview of the data

This gives you a quick summary before diving into detailed visualizations.

### Step 4: Explore Toolbox Visualizations

The **"TOOLBOX"** section contains multiple visualization types. Click the tabs (pills) at the top to switch between them:

#### FACTSHEET

- Summary statements and key metrics
- Text-based overview of the data
- Good for quick reference

#### MAP

- Geographic visualizations
- Shows emissions by sub-jurisdiction or geographic area
- Color-coded maps showing spatial patterns
- Interactive: hover or click for details

#### DONUT

- Pie/donut charts showing distribution
- Displays how emissions are divided by category (e.g., by vehicle type, fuel type)
- Interactive: hover for values, click to highlight segments

#### TIME TREND

- Line charts showing emissions over time
- Useful for seeing trends across years
- Can show single or multiple series

#### TIME TREND BY TYPE

- Multi-series line charts
- Shows trends for multiple categories on the same chart
- Compare different vehicle types, fuel types, etc. over time

#### RANK

- Ranking visualizations
- Compares different areas or categories
- Shows which areas have highest/lowest emissions
- Bar charts or similar ranking displays

## Understanding the Visualizations

### Reading Charts

- **X-axis**: Usually time (years) or categories
- **Y-axis**: Usually emissions values, VMT, or vehicle counts
- **Colors**: Different colors represent different categories (vehicle types, fuel types, etc.)
- **Hover**: Move your mouse over chart elements to see exact values
- **Click**: Some charts allow clicking to filter or highlight

### Reading Maps

- **Colors**: Different colors or shades represent different emission levels
- **Legend**: Shows what colors/shades mean
- **Click/Hover**: Interact with map areas to see details
- **Zoom**: Some maps allow zooming in/out

### Comparing Data

You can compare:
- **Different years**: Select different years to see trends
- **Different pollutants**: Switch pollutants to see different aspects
- **Different areas**: Select different tables (counties) to compare
- **Custom vs. Public**: Your order data vs. public granddata

## Tips for Using the Visualizer

1. **Start Simple**: Begin with one table, one year, one pollutant to understand the interface
2. **Explore Gradually**: Add complexity (multiple years, custom orders) as you get comfortable
3. **Use Custom Orders**: Include your own order data to see your specific modeling results
4. **Try Different Visualizations**: Each visualization type shows data differently - explore them all
5. **Compare Scenarios**: Use the Visualizer to compare different years, areas, or scenarios

## Common Tasks

### Task 1: View Your Order Results

1. Go to Visualizer
2. Expand "SELECT CUSTOM ORDER DATA"
3. Select your order(s)
4. Configure scenario (year, pollutant, etc.)
5. Explore visualizations in Toolbox

### Task 2: Compare Two Counties

1. Select first county's table in "SEARCH"
2. Note the data
3. Switch to second county's table
4. Compare the visualizations side-by-side (or switch back and forth)

### Task 3: See Trends Over Time

1. Select a table (county)
2. Select a pollutant
3. Go to "TIME TREND" or "TIME TREND BY TYPE" in Toolbox
4. View the line chart showing trends

### Task 4: Understand Distribution

1. Select your scenario
2. Go to "DONUT" in Toolbox
3. See how emissions are distributed (e.g., by vehicle type or fuel type)
4. Hover over segments for exact percentages

## Data Sources

The Visualizer combines data from:

- **Your Custom Orders**: Data from orders you've created and selected
- **CAT Grand Database**: Public data from published orders
- **Default Data**: Standard MOVES data when custom data isn't available

When you select custom order data, it takes priority over public data for the same county/year combination.

## Troubleshooting

### No Data Showing

If visualizations are empty:
1. Check that you've selected a table, year, and pollutant
2. Verify your custom orders (if selected) are "Ready" (not "Processing")
3. Try a different year or pollutant
4. Check that the table has data for your selections

### Custom Order Data Not Appearing

If your order data doesn't show:
1. Verify the order status is "Ready" in View Orders
2. Make sure you selected the order in "SELECT CUSTOM ORDER DATA"
3. Check that the order's county/year matches your scenario selection
4. Wait a moment for data to load

### Visualizations Not Loading

If charts don't appear:
1. Wait a few seconds for data to load
2. Refresh the page
3. Try selecting different options
4. Check your internet connection

## Next Steps

After exploring your data in the Visualizer:

1. **[Generate a Report](reporter-guide.md)** - Create a Word document with your visualizations
2. **[Use the Calculator](calculator-guide.md)** - Estimate how emissions change with different scenarios
3. **[Compare Counties](aggregator-guide.md)** - Use Aggregator to compare multiple counties side-by-side
4. **[Download Data](data-hub-guide.md)** - Use Data Hub for bulk downloads

## Related Topics

- **[Creating Orders](creating-orders.md)** - Create orders to visualize
- **[Viewing Orders](viewing-orders.md)** - Check order status before visualizing
- **[Calculator Guide](calculator-guide.md)** - Estimate emissions changes
- **[Reporter Guide](reporter-guide.md)** - Generate reports from visualizations

---

**Ready to estimate emissions changes?** See [Calculator Guide](calculator-guide.md) to adjust activity measures and see projected emissions.




