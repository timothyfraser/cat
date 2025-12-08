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

# Reporter Guide

Learn how to use the Reporter to generate professional Word document reports with emissions data, charts, and analysis.

## What is the Reporter?

The **Reporter** is a tool that generates downloadable Word (.docx) reports containing:
- Emissions data for selected geographic areas
- Professional charts and graphs
- Formatted text and analysis
- Ready-to-use documents for presentations and documentation

This is useful for:
- Creating press releases with emissions data
- Generating reports for planning documents
- Preparing materials for public meetings
- Documenting analysis results

## Accessing the Reporter

1. Click **"REPORTER"** in the sidebar (MENU section)
2. Or click **"Reporter"** from the Welcome page under "Share & Report"
3. The Reporter page will load

## Understanding the Interface

The Reporter has a sidebar layout:

- **Left Sidebar**: Selection controls (table, year, pollutant)
- **Main Area**: Report configuration and preview

## Step-by-Step: Generating a Report

### Step 1: Select Geographic Area

1. In the **"SEARCH"** dropdown (left sidebar), select a table:
   - **Granddata tables**: Public data (e.g., "granddata.d36109")
   - **Orderdata tables**: Your custom order data (e.g., "orderdata.d36109_u8_o1")
2. The table name includes the FIPS code for the county

### Step 2: Select Year

1. In the **"YEAR"** dropdown, select the year for your report
2. Available years depend on the selected table

### Step 3: Select Pollutant

1. In the **"POLLUTANT"** dropdown, select the pollutant:
   - **CO2e**: Carbon dioxide equivalent
   - **CO**: Carbon monoxide
   - **NOx**: Nitrogen oxides
   - And others

### Step 4: Choose Report Type

1. In the main area, find **"Report Type"**
2. Currently, **"Press Release"** is the available option
3. Select your desired report type

### Step 5: Select Graph Type

1. Find **"Graph Type"** in the main area
2. Choose between:
   - **Bar**: Bar chart visualization
   - **Donut**: Donut/pie chart visualization
3. A preview image will update to show the graph style

### Step 6: Choose Aggregation Level

1. Find **"Aggregation"** in the main area
2. Select how you want data grouped:
   - **By Vehicle Type**: Groups by source type (motorcycles, cars, trucks, buses, etc.)
   - **By Fuel Type**: Groups by fuel (gasoline, diesel, CNG, electric, etc.)
   - **By Road Type**: Groups by road classification (rural/urban, restricted/unrestricted)
   - **By Regulatory Class**: Groups by regulatory class (light duty, medium/heavy duty, etc.)

### Step 7: Preview Your Report

1. A preview image shows the graph style you selected
2. The image updates when you change graph type
3. This gives you an idea of what the report will look like

### Step 8: Download Report

1. Click the **"DOWNLOAD"** button
2. A loading modal will appear: "Downloading... Will take a moment..."
3. The system generates your report via the Reporter API
4. After a few seconds, the report will download as `report.docx`
5. The modal will close automatically

## Understanding Report Types

### Press Release

The **Press Release** report type generates:
- Formatted Word document with emissions data
- Charts showing emissions breakdowns
- Text suitable for public release
- Professional formatting

This is useful for:
- Public announcements
- Media releases
- Public meeting materials
- Documentation for stakeholders

## Understanding Graph Types

### Bar Chart

- **Visualization**: Vertical or horizontal bars
- **Best for**: Comparing categories side-by-side
- **Example**: Comparing emissions by vehicle type

### Donut Chart

- **Visualization**: Circular chart with center hole
- **Best for**: Showing proportions and percentages
- **Example**: Showing distribution of emissions by fuel type

## Understanding Aggregation Levels

### By Vehicle Type

Groups emissions by:
- Motorcycles
- Passenger Cars
- Light Trucks
- Medium/Heavy Duty Trucks
- Buses
- And other vehicle types

**Use when**: You want to see which vehicle types contribute most to emissions.

### By Fuel Type

Groups emissions by:
- Gasoline
- Diesel
- Electric
- CNG (Compressed Natural Gas)
- Ethanol
- And other fuels

**Use when**: You want to see the impact of different fuel types.

### By Road Type

Groups emissions by:
- Off-Network
- Rural Restricted Access
- Rural Unrestricted Access
- Urban Restricted Access
- Urban Unrestricted Access

**Use when**: You want to see where emissions occur geographically (rural vs. urban).

### By Regulatory Class

Groups emissions by:
- Motorcycles
- Light Duty Vehicles
- Medium Duty Vehicles
- Heavy Duty Vehicles
- Buses

**Use when**: You want regulatory/classification-based analysis.

## Tips for Using the Reporter

1. **Preview First**: Check the preview image to ensure the graph type looks good
2. **Choose Appropriate Aggregation**: Select the aggregation level that best shows what you want to highlight
3. **Try Different Options**: Generate multiple reports with different settings to see what works best
4. **Use Public Data**: Granddata tables work well for public-facing reports
5. **Customize After Download**: You can edit the Word document after downloading to add your own text

## Common Tasks

### Task 1: Generate Press Release

1. Select a granddata table (public data)
2. Select current or recent year
3. Select CO2e (most common for press releases)
4. Choose Press Release report type
5. Select Donut chart (visually appealing)
6. Choose By Fuel Type aggregation
7. Download and review

### Task 2: Create Analysis Report

1. Select your orderdata table (your custom data)
2. Select the year you modeled
3. Select the pollutant of interest
4. Choose Press Release report type
5. Select Bar chart (good for comparisons)
6. Choose By Vehicle Type aggregation
7. Download and customize

### Task 3: Compare Scenarios

1. Generate report for baseline scenario
2. Generate report for alternative scenario
3. Compare the two reports side-by-side
4. Use in presentations or documentation

## Understanding the Report Content

### What's Included

The generated report typically includes:
- **Title/Header**: Report identification
- **Introduction**: Context about the data
- **Data Summary**: Key statistics
- **Chart/Graph**: Visual representation based on your selections
- **Analysis**: Text describing the findings
- **Conclusion**: Summary and implications

### Report Format

- **File Format**: Microsoft Word (.docx)
- **Compatibility**: Opens in Word, Google Docs, and other word processors
- **Editable**: You can edit the document after downloading
- **Professional**: Formatted for presentations and publication

## Troubleshooting

### Download Not Starting

If the report doesn't download:
1. Check your browser's download settings
2. Ensure pop-up blockers aren't preventing the download
3. Wait a bit longer (generation can take 10-30 seconds)
4. Try again if it times out

### Report Generation Error

If you see an error:
1. Verify your table selection has data for the selected year
2. Check that the year is available for that table
3. Try a different year or table
4. Contact support if problem persists

### Report Content Issues

If the report doesn't look right:
1. Try a different graph type
2. Try a different aggregation level
3. Verify your table/year/pollutant selections
4. Generate again with different settings

## Tutorial Feature

The Reporter includes an interactive tutorial:

1. Click **"Start Tutorial"** button (if available)
2. Follow the step-by-step guide
3. Learn about each feature as you go
4. Complete the tutorial to understand all options

## Next Steps

After generating a report:

1. **Review the Report**: Open the downloaded .docx file
2. **Customize**: Edit the document to add your own text or analysis
3. **Use in Presentations**: Include charts and data in your presentations
4. **Share**: Distribute the report to stakeholders or the public

## Related Topics

- **[Visualizer Guide](visualizer-guide.md)** - Explore data before generating reports
- **[Creating Orders](creating-orders.md)** - Create custom data for reports
- **[Viewing Orders](viewing-orders.md)** - Access your order data for reports
- **[Calculator Guide](calculator-guide.md)** - Analyze scenarios before reporting

---

**Ready to explore your data first?** See [Visualizer Guide](visualizer-guide.md) to view interactive charts before generating reports.




