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

# Frequently Asked Questions

Common questions and answers about using the CAT Platform.

## Account & Access

### How do I create an account?

See [Getting Started](getting-started.md#creating-your-account) for step-by-step instructions. You'll need:
- A valid email address
- A password (minimum 6 characters)
- Your name, affiliation, and user type

### Can I change my email address?

Email addresses cannot be changed through the Account page. Contact support if you need to change your email.

### What subscription do I have?

Check your Account page to see your current subscription tier. New accounts start with a Free subscription.

### How do I upgrade my subscription?

Visit the "Plans & Pricing" page (INFO section in sidebar) to see subscription options and upgrade.

### I forgot my password. How do I reset it?

Password reset functionality may be available through the login page. If not, contact support for assistance.

## Orders

### What is an "order"?

An order is a request to run emissions modeling for a specific county and year. See [Creating Orders](creating-orders.md#what-is-an-order) for details.

### How long does an order take to process?

Orders typically take 5-10 minutes to process. You'll see the order appear in "View Orders" within 1-2 minutes, and status will change to "Ready" when complete.

### Can I cancel an order?

Once submitted, orders cannot be cancelled. However, you can delete completed orders if you no longer need them.

### Why is my order stuck in "Processing"?

If an order has been processing for more than 15 minutes:
1. Check the order details for error messages
2. Refresh the page
3. If still processing after 20+ minutes, contact support

### How many orders can I create?

This depends on your subscription tier:
- **Free**: Typically 5 orders per month
- **Basic**: More orders per month
- **Premium/Institutional**: Even more capacity

Check your Account page or the New Order page to see your limits.

### What file formats can I upload?

You can upload:
- Excel files (.xlsx)
- ZIP files (.zip) containing CSV files
- CSV files (.csv) - will be converted to ZIP automatically

### What happens if I exceed my order limit?

You'll see an "Out of Space" error message. Options:
- Wait until next month (for monthly limits)
- Upgrade your subscription
- Delete old orders you no longer need

## Data & Results

### How do I download my order results?

Once an order status shows "Ready":
1. Go to Visualizer and select your order
2. Or use Data Hub for bulk downloads
3. Or access through the bucket link (advanced)

See [Viewing Orders](viewing-orders.md#downloading-order-results) for details.

### What data is included in an order?

Each order includes:
- Emissions by pollutant (CO2e, CO, NOx, etc.)
- Vehicle miles traveled (VMT)
- Vehicle counts
- Breakdowns by vehicle type, fuel type, road type, regulatory class

### Can I modify my order data after it's created?

No, order data cannot be modified after creation. If you need different data, create a new order.

### What is the difference between my order data and public granddata?

- **Your order data**: Results from orders you created (custom modeling)
- **Public granddata**: Data published by verified users to the public database
- You can use both in Visualizer and other tools

## Verification & Publishing

### What is verification?

Verification allows you to publish order results to the public CAT Grand Database. See [Account Management](account-management.md#verification-for-publishing) for details.

### How do I get verified?

1. Go to your Account page
2. Enter a geoid (FIPS code) and your .gov or .edu email
3. Submit verification request
4. Wait for approval (typically 1-2 business days)

### Why do I need a .gov or .edu email?

Only government and educational institutions can publish public data. The .gov/.edu email requirement ensures data quality and accountability.

### How long does verification take?

Verification requests are typically reviewed within 1-2 business days.

### Can I publish without verification?

No, you must be verified for a county (geoid) before you can publish orders for that county.

### What happens when I publish an order?

Your data becomes publicly available in the CAT Grand Database within 5-10 minutes. Other users can then access it.

### Can I unpublish data?

No, publishing is permanent. Published data cannot be removed from the public database.

## Tools & Features

### What's the difference between Visualizer and Calculator?

- **Visualizer**: View and explore existing data with charts and maps
- **Calculator**: Adjust activity measures to estimate how emissions would change

### Can I export visualizations?

Visualizations in the Visualizer are interactive but not directly exportable. Use the Reporter to generate downloadable reports with charts.

### How do I compare multiple counties?

Use the Aggregator tool to select multiple counties and compare them side-by-side. See [Aggregator Guide](aggregator-guide.md).

### Can I use my own MOVES input files?

Yes! When creating an order, you can upload custom MOVES input files (Excel, ZIP, or CSV). See [Creating Orders](creating-orders.md#step-3-upload-custom-files-optional).

### What is the Translators tool?

The Translators tool lets you edit MOVES input tables. This is an advanced feature. See [Translators Guide](translators-guide.md).

## Sharing & Collaboration

### How do I share my order data with colleagues?

1. Go to View Orders
2. Select one order
3. Click SHARE
4. Add colleague's email address
5. They'll receive access

See [Sharing & Collaboration](sharing-collaboration.md) for details.

### Can I share multiple orders at once?

No, you can only share one order at a time. Share each order individually.

### How do I revoke access?

Open the share modal, enter the person's email, and click "Remove."

### Can shared users modify my data?

No, shared users have viewer access only. They can view and download but cannot modify or delete.

## Technical Issues

### The page won't load. What should I do?

1. Check your internet connection
2. Refresh the page
3. Try a different browser
4. Clear your browser cache
5. Contact support if problem persists

### I'm getting an error message. What does it mean?

Error messages usually explain the issue. Common ones:
- "Out of Space": You've reached your order limit
- "Not Verified": You need verification to publish
- "Invalid File Format": Check your uploaded file format

### My order data isn't showing in Visualizer.

1. Verify order status is "Ready" (not "Processing")
2. Make sure you selected the order in "SELECT CUSTOM ORDER DATA"
3. Check that the order's county/year matches your scenario
4. Wait a moment for data to load

### The download isn't working.

1. Check your browser's download settings
2. Ensure pop-up blockers aren't preventing downloads
3. Wait longer (some downloads take 30-60 seconds)
4. Try a different browser

## Data Concepts

### What is a FIPS code?

FIPS (Federal Information Processing Standards) codes are 5-digit numbers that identify counties. Example: 36109 = Tompkins County, NY.

### What is a geoid?

Geoid is another term for FIPS code - the geographic identifier for a county.

### What pollutants are available?

Common pollutants include:
- CO2e (Carbon dioxide equivalent)
- CO (Carbon monoxide)
- NOx (Nitrogen oxides)
- PM (Particulate matter)
- And others

### What is VMT?

VMT = Vehicle Miles Traveled. The total miles driven by all vehicles.

### What are aggregation levels?

Aggregation levels group data by:
- Vehicle Type (cars, trucks, buses, etc.)
- Fuel Type (gasoline, diesel, electric, etc.)
- Road Type (rural/urban, restricted/unrestricted)
- Regulatory Class (light duty, medium/heavy duty)

## Getting Help

### Where can I find more information?

- **[Table of Contents](table-of-contents.md)**: Complete guide to all documentation
- **[Getting Started](getting-started.md)**: Step-by-step guide for new users
- **[Glossary](glossary.md)**: Definitions of key terms

### How do I contact support?

See [Contact Support](contact-support.md) for how to get help.

### Can I request new features?

Yes! Contact support with feature requests or suggestions.

---

**Still have questions?** See [Contact Support](contact-support.md) or [Troubleshooting](troubleshooting.md) for more help.




