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

# Viewing Orders

Learn how to view, manage, and download your emissions modeling orders from the Cloud MOVES system.

## Accessing Your Orders

1. Click **"View Orders"** in the sidebar (MENU section)
2. Or click **"View Orders"** from the Welcome page under "Customize Your Scenarios"
3. You'll see a table with all your orders

## Understanding the Orders Table

### Table Columns

The orders table displays:

- **ID**: Unique order identifier
- **CREATED**: Date and time when you submitted the order
- **GEOID**: FIPS code for the county (e.g., 36109)
- **COUNTY**: County name (e.g., Tompkins County)
- **STATE**: State abbreviation (e.g., NY)
- **YEAR**: Year that was modeled
- **STATUS**: Current order status (see below)
- **DETAILS**: Button to view full order information

### Order Status

Orders can have different status messages:

- **Processing**: Order is being calculated (typically 5-10 minutes)
- **Ready**: Order is complete and data is available for download
- **Error**: Something went wrong - check details or contact support
- **Published**: Order has been published to the public CAT Grand Database

### Filtering and Searching

Use the search box and filters at the top of the table to:
- Search by county name, state, year, or status
- Filter by specific columns
- Sort by clicking column headers

## Viewing Order Details

### Opening Order Details

1. Find the order you want to view in the table
2. Click the **"Details"** button in that row
3. A modal window will open showing comprehensive order information

### Information Shown

The details modal displays:
- Order ID and creation date
- Geographic information (county, state, FIPS code)
- Year modeled
- Order status and processing information
- Bucket information (storage location)
- Any custom files that were uploaded
- Additional metadata

## Downloading Order Results

### When Data is Available

Once an order status shows **"Ready"**, the data is available for download. You can access it through:

1. **Visualizer**: View and explore data with interactive charts
2. **Data Hub**: Download in bulk (if you have multiple orders)
3. **Direct Download**: Access the data through the bucket link (advanced)

### Using the Visualizer

The easiest way to view and work with your order data:

1. Go to **"Visualizer"** in the sidebar
2. In the "SELECT CUSTOM ORDER DATA" section, select your order(s)
3. The data will be loaded and available for visualization
4. See **[Visualizer Guide](visualizer-guide.md)** for detailed instructions

### Downloading via Data Hub

For bulk downloads of multiple orders:

1. Go to **"Data Hub"** in the sidebar (TOOLS section)
2. Select years and pollutants
3. Upload a CSV with geoids you want to download
4. Click download
5. See **[Data Hub Guide](data-hub-guide.md)** for details

## Managing Your Orders

### Refreshing the Table

To update order statuses:

1. Click the **"Refresh"** button (if available)
2. Or navigate away and back to the View Orders page
3. The table will reload with current statuses

### Deleting Orders

If you no longer need an order:

1. Select one or more orders by clicking the checkboxes on the left
2. Click **"DELETE"** button
3. A confirmation modal will appear
4. Review the warning message
5. Click **"CONFIRM DELETE"** to proceed
6. The order(s) and associated data will be permanently deleted

> **Warning**: Deleting an order is permanent and cannot be undone. Make sure you've downloaded any data you need before deleting.

### Publishing Orders

If you're verified for a county, you can publish orders to the public CAT Grand Database:

1. Select the order(s) you want to publish
2. Click **"PUBLISH"** button
3. A confirmation modal will appear
4. Click **"CONFIRM PUBLISH"** to proceed
5. Your data will be available publicly within 5-10 minutes

> **Note**: You must be verified for the order's county (geoid) to publish. See **[Publishing Data](publishing-data.md)** for details.

### Sharing Orders

You can share access to your order data with colleagues:

1. Select **one** order (sharing works for single orders only)
2. Click **"SHARE"** button
3. A modal will open showing:
   - People who currently have access
   - A field to add email addresses
   - A bucket URL link
4. To add someone:
   - Enter their email address
   - Click **"Add"**
   - They'll receive access to view the order data
5. To remove someone:
   - Enter their email address
   - Click **"Remove"**
   - Their access will be revoked

> **Note**: You can only share one order at a time. If you select multiple orders, you'll see an error message.

## Understanding Order Data

Orders processed through Cloud MOVES generate comprehensive emissions data for your selected county and year.

### What Data is Included

Each order contains emissions data organized by:

- **Pollutants**: CO2e, CO, NOx, PM, and others
- **Vehicle Types**: Cars, trucks, buses, motorcycles, etc.
- **Fuel Types**: Gasoline, diesel, electric, CNG, etc.
- **Road Types**: Rural/urban, restricted/unrestricted
- **Regulatory Classes**: Light duty, medium/heavy duty, etc.
- **Metrics**: Emissions, VMT (vehicle miles traveled), vehicle counts

### Data Format

Order data is stored as CSV files with columns for:
- Geographic identifiers (geoid, county, state)
- Year
- Pollutant codes
- Aggregation levels (by vehicle type, fuel type, etc.)
- Category codes (specific vehicle types, fuel types, etc.)
- Metric values (emissions, VMT, vehicles)

## Tips for Managing Orders

1. **Regular Cleanup**: Delete old orders you no longer need to stay within limits
2. **Monitor Status**: Check processing orders periodically to know when data is ready
3. **Use Filters**: Use the search and filter features to find specific orders quickly
4. **Download Early**: Download or visualize data you need before deleting orders
5. **Share Strategically**: Only share orders with colleagues who need access

## Common Tasks

### Task 1: Check if Order is Ready

1. Go to View Orders
2. Look at the STATUS column
3. If it says "Ready", your data is available
4. If it says "Processing", wait a few more minutes and refresh

### Task 2: Download Results for Analysis

1. Find your ready order
2. Go to Visualizer
3. Select your order in the "SELECT CUSTOM ORDER DATA" section
4. Explore the data with charts and maps
5. Or use Data Hub for bulk download

### Task 3: Share Results with Team

1. Select the order you want to share
2. Click SHARE
3. Add team members' email addresses
4. They'll be able to access the data
5. Optionally, copy the bucket URL to share directly

### Task 4: Clean Up Old Orders

1. Use filters to find old orders (e.g., filter by year)
2. Select orders you no longer need
3. Click DELETE
4. Confirm deletion
5. This frees up space for new orders

## Troubleshooting

### Order Stuck in "Processing"

If an order has been processing for more than 15 minutes:
1. Check the order details for any error messages
2. Refresh the page
3. If still processing after 20+ minutes, contact support

### Can't See My Order

If you just created an order but don't see it:
1. Wait 1-2 minutes (there's a slight delay)
2. Refresh the page
3. Check that you're logged into the correct account
4. Verify the order was successfully submitted

### Can't Download Data

If you can't access order data:
1. Verify order status is "Ready" (not "Processing")
2. Try accessing through Visualizer instead of direct download
3. Check that you have the correct permissions
4. Contact support if issues persist

## Next Steps

After viewing your orders:

1. **[Visualize Your Data](visualizer-guide.md)** - Explore results with interactive charts
2. **[Generate a Report](reporter-guide.md)** - Create a Word document report
3. **[Publish Your Data](publishing-data.md)** - Share verified results publicly
4. **[Create More Orders](creating-orders.md)** - Submit additional modeling requests

## Related Topics

- **[Creating Orders](creating-orders.md)** - How to submit new orders
- **[Publishing Data](publishing-data.md)** - Publishing verified orders
- **[Sharing & Collaboration](sharing-collaboration.md)** - Sharing orders with colleagues
- **[Visualizer Guide](visualizer-guide.md)** - Viewing order data with visualizations

---

**Ready to visualize your data?** See [Visualizer Guide](visualizer-guide.md) to explore your order results with interactive charts and maps.




