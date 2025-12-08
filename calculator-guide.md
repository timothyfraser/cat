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

# Calculator Guide

Learn how to use the Calculator to estimate how emissions change when you adjust transportation activity measures like vehicle miles traveled (VMT), vehicle counts, and other factors.

## What is the Calculator?

The **Calculator** is an interactive tool that lets you:
- Adjust activity measures (VMT, vehicles, starts, hours, etc.)
- See how emissions change in real-time
- Compare baseline emissions vs. adjusted scenarios
- Estimate the impact of transportation changes
- Visualize emissions changes with interactive charts

This is useful for:
- Scenario planning: "What if we increase VMT by 10%?"
- Policy analysis: "How do emissions change with more electric vehicles?"
- Conformity analysis: Estimating emissions for transportation plans

## Accessing the Calculator

1. Click **"CALCULATOR"** in the sidebar (MENU section)
2. Or click **"Calculator"** from the Welcome page under "Explore Your Data"
3. The Calculator page will load

## Understanding the Interface

The Calculator has several main sections:

1. **Selection Panel**: Choose geographic area, pollutant, and activity measure
2. **Data Table**: Editable table showing activity measures
3. **Results Display**: Shows emissions estimates and comparisons
4. **Charts**: Visual displays of emissions changes

## Step-by-Step: Using the Calculator

### Step 1: Select Geographic Area

1. In the **"Table"** dropdown, select a geographic area (county)
   - Options include counties from the CAT Grand Database
   - Example: "Tompkins County, NY"
2. The system will load default MOVES activity data for that area

### Step 2: Select Pollutant

1. In the **"Pollutant"** dropdown, select the pollutant you want to analyze:
   - **CO2e**: Carbon dioxide equivalent
   - **CO**: Carbon monoxide
   - **NOx**: Nitrogen oxides
   - And others
2. Different pollutants will show different emission factors

### Step 3: Select Activity Measure

1. In the **"Activity Measure"** dropdown, select what you want to focus on:
   - Options may include vehicle types, fuel types, road types, etc.
2. This determines which columns are most relevant in the data table

### Step 4: Review Baseline Data

The **Data Table** will automatically populate with default MOVES values for your selected area and pollutant. You'll see columns like:

- **Year**: The year being modeled
- **VMT**: Vehicle miles traveled
- **Vehicles**: Vehicle count
- **Starts**: Number of vehicle starts
- **Hours**: Operating hours
- **Vehicle Type Percentages**: % Bus, % Car/Motorcycle, % Light Truck, etc.
- **Fuel Type Percentages**: % Gas, % Diesel, % Electric, etc.
- **Road Type Percentages**: % Rural Restricted, % Urban Unrestricted, etc.

> **Note**: These are default values from the MOVES model. You can edit them to create custom scenarios.

### Step 5: Adjust Activity Measures

To create a scenario, edit values in the table:

1. **Click on a cell** in the table to edit it
2. **Enter a new value**
3. **Press Enter** or click elsewhere to save
4. The Calculator will automatically recalculate emissions

**Example Adjustments:**
- Increase VMT by 10%: Multiply current VMT by 1.1
- Add more electric vehicles: Increase % Electric, decrease % Gas
- Change vehicle mix: Adjust vehicle type percentages
- Modify road usage: Change road type percentages

### Step 6: View Results

The **Results Display** shows:

- **Baseline Emissions**: Original emissions based on default values
- **Adjusted Emissions**: New emissions based on your edits
- **Difference**: How much emissions changed (absolute and percentage)
- **Comparison Charts**: Visual displays comparing baseline vs. adjusted

### Step 7: Explore Charts

Interactive charts show:
- Emissions by category (vehicle type, fuel type, etc.)
- Comparison between baseline and adjusted scenarios
- Breakdowns showing where changes occurred

**Interacting with Charts:**
- **Hover**: See exact values
- **Click**: Filter or highlight categories
- **Zoom**: Some charts allow zooming

## Understanding the Calculations

### How It Works

The Calculator uses the MOVES (Motor Vehicle Emission Simulator) model to estimate emissions:

1. **Activity Data**: Your edited values (VMT, vehicles, etc.)
2. **Emission Factors**: Standard MOVES emission rates
3. **Calculation**: Activity × Emission Factors = Emissions
4. **Real-time Updates**: As you edit, calculations update automatically

### Key Concepts

**VMT (Vehicle Miles Traveled)**
- Total miles driven by all vehicles
- Increasing VMT generally increases emissions
- Can be adjusted by vehicle type, road type, etc.

**Vehicle Counts**
- Number of vehicles in the fleet
- Affects total activity and emissions

**Vehicle Type Distribution**
- Percentage of different vehicle types (cars, trucks, buses, etc.)
- Different types have different emission rates
- Changing the mix changes total emissions

**Fuel Type Distribution**
- Percentage of different fuels (gasoline, diesel, electric, etc.)
- Electric vehicles have lower/no tailpipe emissions
- Changing fuel mix significantly affects emissions

**Road Type Distribution**
- Percentage of travel on different road types
- Urban vs. rural, restricted vs. unrestricted
- Affects speed and emission rates

## Common Scenarios

### Scenario 1: Increase VMT

**Question**: "What if vehicle miles traveled increases by 15%?"

1. Select your area and pollutant
2. Find the VMT column in the table
3. Multiply current VMT values by 1.15 (or add 15%)
4. View results to see emissions increase

### Scenario 2: Add Electric Vehicles

**Question**: "How do emissions change if 20% of vehicles are electric?"

1. Select area and pollutant
2. Increase % Electric to 20%
3. Decrease % Gas (or other fuel) by 20% to maintain 100% total
4. View results to see emissions decrease

### Scenario 3: Change Vehicle Mix

**Question**: "What if we have more trucks and fewer cars?"

1. Select area and pollutant
2. Increase % Light Truck, % Heavy Truck
3. Decrease % Car/Motorcycle
4. View results to see how emissions change

### Scenario 4: Modify Road Usage

**Question**: "What if more travel is on urban roads?"

1. Select area and pollutant
2. Increase % Urban Restricted, % Urban Unrestricted
3. Decrease % Rural Restricted, % Rural Unrestricted
4. View results to see impact

## Tips for Using the Calculator

1. **Start with Defaults**: Review default values before making changes
2. **Make Small Changes First**: Test with small adjustments to understand the tool
3. **Maintain Totals**: When adjusting percentages, ensure they add up to 100%
4. **Compare Scenarios**: Use the comparison features to see differences clearly
5. **Document Your Changes**: Note what you changed and why for your analysis

## Understanding Results

### Baseline vs. Adjusted

- **Baseline**: Emissions using default MOVES values
- **Adjusted**: Emissions using your edited values
- **Difference**: Shows the impact of your changes

### Percentage Changes

- **Positive %**: Emissions increased
- **Negative %**: Emissions decreased
- **Large %**: Significant impact
- **Small %**: Minor impact

### Category Breakdowns

Results show emissions by:
- Vehicle type (where changes occurred)
- Fuel type (which fuels contribute most)
- Road type (where travel happens)
- Other categories depending on your selections

## Troubleshooting

### Table Not Editable

If you can't edit the table:
1. Make sure you've selected a table (geographic area)
2. Wait for data to load completely
3. Try clicking directly on a cell
4. Refresh the page if needed

### Results Not Updating

If results don't change after editing:
1. Make sure you pressed Enter or clicked elsewhere to save
2. Wait a moment for calculations to complete
3. Check that your edits are valid numbers
4. Try refreshing the page

### Values Don't Make Sense

If results seem incorrect:
1. Verify your edits are reasonable (e.g., percentages add to 100%)
2. Check that values are in correct units
3. Review default values to understand expected ranges
4. Try resetting and making smaller changes

## Next Steps

After using the Calculator:

1. **[Create an Order](creating-orders.md)** - Use your scenario to create a full modeling order
2. **[Visualize Results](visualizer-guide.md)** - View your order data with interactive charts
3. **[Generate a Report](reporter-guide.md)** - Create a document with your analysis
4. **[Compare Counties](aggregator-guide.md)** - Compare your area with others

## Related Topics

- **[Creating Orders](creating-orders.md)** - Create full modeling orders based on your scenarios
- **[Visualizer Guide](visualizer-guide.md)** - Visualize your order results
- **[Reporter Guide](reporter-guide.md)** - Generate reports from your analysis
- **[Glossary](glossary.md)** - Definitions of terms like VMT, emission factors, etc.

---

**Ready to create an order based on your scenario?** See [Creating Orders](creating-orders.md) to submit a full modeling request.




