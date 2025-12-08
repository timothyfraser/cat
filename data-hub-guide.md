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

# Data Hub Guide

Learn how to use the Data Hub to download large datasets in bulk from the CAT Grand Database.

## What is the Data Hub?

The **Data Hub** is a bulk download tool that lets you:
- Download emissions data for multiple counties at once
- Select multiple years and pollutants
- Export data as CSV files
- Access public CAT Grand Database data
- Get large datasets for offline analysis

This is useful for:
- Regional analysis: Downloading data for multiple counties
- Time series analysis: Getting data for multiple years
- External analysis: Exporting data for use in Excel, R, Python, etc.
- Reporting: Getting comprehensive datasets for reports

## Accessing the Data Hub

1. Click **"DATAHUB"** in the sidebar (TOOLS section)
2. The Data Hub page will load with selection controls

## Understanding the Interface

The Data Hub has a sidebar layout:

- **Left Sidebar**: Selection controls (years, pollutants, metrics, aggregation, file upload)
- **Main Area**: Download button and instructions

## Step-by-Step: Downloading Data

### Step 1: Select Years

1. In the **"YEAR"** dropdown (left sidebar), select one or more years
2. You can select multiple years (up to 60 years maximum)
3. Hold Ctrl (Windows) or Cmd (Mac) to select multiple years
4. Selected years will be included in your download

### Step 2: Select Pollutant

1. In the **"POLLUTANT"** dropdown, select the pollutant:
   - **CO2e**: Carbon dioxide equivalent
   - **CO**: Carbon monoxide
   - **NOx**: Nitrogen oxides
   - And others
2. **Note**: You can only select one pollutant per download

### Step 3: Select Metric

1. In the **"METRIC"** dropdown, select what you want to download:
   - **Emissions**: Emissions values
   - **VMT**: Vehicle miles traveled
   - **Vehicles**: Vehicle counts
2. You can select one metric per download

### Step 4: Select Aggregation Level

1. In the **"AGGREGATION"** dropdown, select how data should be grouped:
   - **Overall**: No sub-grouping
   - **By Vehicle Type**: Group by source type
   - **By Fuel Type**: Group by fuel type
   - **By Road Type**: Group by road classification
   - **By Regclass**: Group by regulatory class

### Step 5: Upload Geographic Areas

1. You need to provide a list of counties (geoids) to download
2. Click **"Download Sample File"** to get a template CSV file
3. Open the sample file in Excel or a text editor
4. Edit the file to include the FIPS codes (geoids) you want:
   - One geoid per row
   - Format: 5-digit FIPS code (e.g., 36109)
   - Maximum 100 geoids per download
5. Save the file as CSV
6. Click **"Choose File"** or **"Browse"** in the Data Hub
7. Select your edited CSV file

**Sample CSV Format:**
```
geoid
36109
36023
36107
```

### Step 6: Download Data

1. Review your selections:
   - Years selected
   - Pollutant selected
   - Metric selected
   - Aggregation level
   - Geographic areas file uploaded
2. Click the **"DOWNLOAD"** button
3. A loading spinner will appear: "Processing your request..."
4. The system will generate your CSV file
5. After processing (may take 30-60 seconds), the file will download automatically

## Understanding the Limits

### Input Limits

- **Years**: Maximum 60 years per download
- **Pollutants**: Maximum 1 pollutant per download
- **Geographic Areas**: Maximum 100 counties (geoids) per download
- **File Format**: CSV file with geoid column

### File Size Considerations

Large downloads (many years × many counties) may:
- Take longer to process (30-60 seconds or more)
- Result in large CSV files (several MB)
- Require more time to download

## Tips for Using the Data Hub

1. **Start Small**: Test with a few years and counties first
2. **Use Sample File**: Always use the sample file template to ensure correct format
3. **Check Geoid Format**: Ensure FIPS codes are 5 digits (add leading zeros if needed)
4. **Plan Your Downloads**: Consider splitting very large requests into multiple downloads
5. **Save Your Files**: Downloaded CSV files can be large - make sure you have space

## Common Tasks

### Task 1: Download Single County, Multiple Years

1. Select multiple years (e.g., 2020-2025)
2. Select pollutant (e.g., CO2e)
3. Select metric (e.g., Emissions)
4. Select aggregation (e.g., Overall)
5. Create CSV with one geoid
6. Upload and download

### Task 2: Download Multiple Counties, Single Year

1. Select one year
2. Select pollutant and metric
3. Create CSV with multiple geoids (up to 100)
4. Upload and download
5. Get data for all counties in one file

### Task 3: Regional Analysis

1. Create CSV with all counties in your region
2. Select years of interest
3. Download emissions data
4. Use in Excel or other tools for analysis

## Understanding the Downloaded Data

### CSV File Structure

The downloaded CSV will contain:
- **Geographic identifiers**: geoid, county name, state
- **Year**: The year for each record
- **Pollutant**: The pollutant code
- **Aggregation fields**: Depending on aggregation level (vehicle type, fuel type, etc.)
- **Metric values**: The selected metric (emissions, VMT, or vehicles)

### Data Format

- **Rows**: Each row represents a unique combination of geoid, year, and aggregation category
- **Columns**: Geographic info, year, pollutant, aggregation fields, metric value
- **Format**: Standard CSV (comma-separated values)

## Troubleshooting

### "Invalid File Format" Error

If you get a file format error:
1. Make sure you're using the sample file template
2. Check that the file is saved as CSV (not Excel .xlsx)
3. Verify the geoid column header is exactly "geoid"
4. Ensure geoids are 5-digit numbers (add leading zeros if needed)

### "Too Many Geoids" Error

If you exceed the 100 geoid limit:
1. Split your request into multiple downloads
2. Create separate CSV files with up to 100 geoids each
3. Download each file separately
4. Combine results in Excel or other tools if needed

### Download Not Starting

If the file doesn't download:
1. Check your browser's download settings
2. Ensure pop-up blockers aren't preventing the download
3. Wait longer (large downloads can take 60+ seconds)
4. Try again if it times out

### Processing Takes Too Long

If processing seems stuck:
1. Very large requests (many years × many counties) can take 1-2 minutes
2. Wait at least 2 minutes before assuming it failed
3. Try a smaller request first to test
4. Contact support if it consistently fails

## Next Steps

After downloading data:

1. **Open in Excel**: Import the CSV for analysis
2. **Use in R/Python**: Load CSV for statistical analysis
3. **Create Visualizations**: Use the data in your own charts
4. **Generate Reports**: Include data in your reports

## Related Topics

- **[Creating Orders](creating-orders.md)** - Create custom modeling orders
- **[Viewing Orders](viewing-orders.md)** - Access your order results
- **[Visualizer Guide](visualizer-guide.md)** - Interactive data exploration
- **[Aggregator Guide](aggregator-guide.md)** - Compare counties side-by-side

---

**Ready to compare counties?** See [Aggregator Guide](aggregator-guide.md) for side-by-side comparisons.




