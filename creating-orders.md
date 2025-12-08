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

# Creating Orders

Learn how to submit new emissions modeling orders through the Cloud MOVES system on the CAT Platform.

## What is an Order?

An **order** is a request to run emissions modeling for a specific geographic area (county) and year through the **Cloud MOVES** system. Cloud MOVES is the distributed computing infrastructure that processes MOVES emissions calculations. When you submit an order:

1. Cloud MOVES runs the MOVES (Motor Vehicle Emission Simulator) model for your selected county and year
2. Processing typically takes 5-10 minutes
3. Results include emissions data, vehicle miles traveled (VMT), vehicle counts, and more
4. You can download the results, visualize them, and use them for analysis

## Accessing the New Order Page

1. Click **"New Order"** in the sidebar (MENU section)
2. Or click **"New Order"** from the Welcome page under "Customize Your Scenarios"

## Step-by-Step: Creating an Order

### Step 1: Select Geographic Area

You can choose a county in two ways:

**Option A: By County Name**
1. In the "Choose Type" dropdown, select **"By Name"**
2. In the "Geoid" dropdown, search for or select your county
   - Example: "Tompkins County, NY"
   - The system will show counties in a searchable list

**Option B: By FIPS Code**
1. In the "Choose Type" dropdown, select **"By Geoid"**
2. In the "Geoid" dropdown, select or enter the 5-digit FIPS code
   - Example: "36109" for Tompkins County, NY
   - FIPS codes are standardized county identifiers

> **Tip**: If you know the FIPS code, using "By Geoid" is often faster. If you're not sure, "By Name" is easier to search.

### Step 2: Select Year

1. In the "Year" dropdown, select the year you want to model
2. You can select multiple years if needed (up to 5 years at a time for non-admin users)
3. Available years typically range from historical data to future projections

> **Note**: You can select multiple counties and multiple years. The system will create a separate order for each combination (county × year).

### Step 3: Upload Custom Files (Optional)

If you have custom MOVES input files, you can upload them to customize the modeling:

**Supported File Formats:**
- **Excel (.xlsx)**: Single Excel workbook with multiple sheets
- **ZIP file (.zip)**: Archive containing multiple CSV files
- **CSV file (.csv)**: Single CSV file (will be converted to ZIP automatically)

**What Are MOVES Input Files?**

MOVES input files contain activity data such as:
- Vehicle miles traveled (VMT) by vehicle type
- Vehicle counts
- Vehicle starts
- Operating hours
- Vehicle type distributions
- Fuel type distributions
- Road type distributions

If you don't upload custom files, the system uses default MOVES activity data for your selected county.

**How to Upload:**
1. Click **"Choose File"** or **"Browse"**
2. Select your file(s)
3. The file name will appear once selected
4. You can upload one file per order

> **Note**: If you upload a CSV file, it will be automatically converted to a ZIP file. Excel files are also converted to ZIP format for processing.

### Step 4: Check Your Limits

Before submitting, check your order limits:

- **Orders This Month**: Shows how many orders you've created this month vs. your monthly limit
- **Total Orders**: Shows your total orders vs. your account limit
- **Remaining**: How many orders you can still create this month

If you're approaching your limit, you may want to:
- Wait until next month
- Upgrade your subscription
- Delete old orders you no longer need

### Step 5: Submit Your Order

1. Review your selections:
   - Geographic area(s)
   - Year(s)
   - Uploaded files (if any)
2. Click **"Submit Order"**
3. You'll see a success message
4. A modal will confirm your order submission

**What Happens Next:**
- Your order appears in the "View Orders" table within 1-2 minutes
- Order status will show "Processing" initially
- Processing typically takes 5-10 minutes
- Once ready, status changes to "Ready" and you can download results

## Understanding Order Limits

### Subscription Limits

Each subscription tier has different limits:

- **Free**: Typically 5 orders per month, limited total orders
- **Basic**: More orders per month
- **Premium**: Even more capacity
- **Institutional**: Custom limits based on contract

### Multiple Selections

If you select:
- 3 counties and 2 years = 6 orders will be created (3 × 2 = 6)
- 1 county and 5 years = 5 orders will be created

**Important**: The system creates one order per county-year combination. Make sure you don't exceed your limits!

### Non-Admin Limits

If you're not an admin user:
- Maximum 5 counties per submission
- Maximum 5 years per submission
- This prevents accidentally creating too many orders at once

## Order Processing

Orders are processed by the **Cloud MOVES** system, which uses distributed cloud computing to run MOVES emissions calculations efficiently.

### Processing Time

- **Initial Registration**: 1-2 minutes (order appears in table)
- **Data Processing**: 5-10 minutes (Cloud MOVES runs MOVES model)
- **Total Time**: Typically 6-12 minutes from submission to ready

### Processing Status

You can check order status in "View Orders":
- **Processing**: Order is being calculated
- **Ready**: Order is complete, data available
- **Error**: Something went wrong (check details or contact support)

### What Gets Calculated

Each order generates:
- Emissions by pollutant (CO2e, CO, NOx, PM, etc.)
- Vehicle miles traveled (VMT) by category
- Vehicle counts by type
- Data broken down by:
  - Vehicle type (cars, trucks, buses, motorcycles, etc.)
  - Fuel type (gasoline, diesel, electric, CNG, etc.)
  - Road type (rural/urban, restricted/unrestricted)
  - Regulatory class

## Tips for Creating Orders

1. **Start Simple**: For your first order, select one county and one year without custom files
2. **Check Limits First**: Always review your order limits before submitting multiple combinations
3. **Use FIPS Codes**: If you work with specific counties regularly, learn their FIPS codes for faster entry
4. **Plan Ahead**: If you need many orders, consider upgrading your subscription or spreading orders across months
5. **Custom Files**: Only upload custom MOVES input files if you have specific activity data to use

## Common Scenarios

### Scenario 1: Single County, Single Year
- Select: 1 county, 1 year
- Result: 1 order
- Use case: Quick analysis for a specific area and year

### Scenario 2: Multiple Counties, Single Year
- Select: 3 counties, 1 year
- Result: 3 orders (one per county)
- Use case: Comparing multiple counties for the same year

### Scenario 3: Single County, Multiple Years
- Select: 1 county, 5 years
- Result: 5 orders (one per year)
- Use case: Time series analysis for one county

### Scenario 4: Multiple Counties, Multiple Years
- Select: 3 counties, 3 years
- Result: 9 orders (3 × 3 = 9)
- Use case: Comprehensive regional analysis
- ⚠️ **Warning**: Make sure you have enough order capacity!

## Troubleshooting

### "Out of Space" Error

If you see an "Out of Space" message:
- You've reached your monthly or total order limit
- Options:
  - Wait until next month (for monthly limits)
  - Upgrade your subscription
  - Delete old orders you no longer need

### File Upload Errors

If file upload fails:
- Check file format (must be .xlsx, .zip, or .csv)
- Ensure file isn't corrupted
- Try converting Excel to CSV if having issues
- Contact support if problems persist

### Order Not Appearing

If your order doesn't appear in "View Orders":
- Wait 1-2 minutes (there's a slight delay)
- Refresh the page
- Check that submission was successful (you should have seen a success message)

## Next Steps

After creating an order:

1. **[View Your Orders](viewing-orders.md)** - Check status and download results
2. **[Visualize Your Data](visualizer-guide.md)** - Explore results with interactive charts
3. **[Generate a Report](reporter-guide.md)** - Create a Word document report
4. **[Publish Your Data](publishing-data.md)** - Share verified results publicly (if verified)

## Related Topics

- **[Viewing Orders](viewing-orders.md)** - Managing and downloading your orders
- **[Account Management](account-management.md)** - Understanding your subscription and limits
- **[Publishing Data](publishing-data.md)** - Publishing verified orders to public database
- **[Glossary](glossary.md)** - Definitions of terms like FIPS code, geoid, etc.

---

**Ready to view your orders?** See [Viewing Orders](viewing-orders.md) for how to check status and download results.




