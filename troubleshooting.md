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

# Troubleshooting

Solutions to common issues when using CAT.

## Account & Login Issues

### Can't Log In

**Symptoms**: Login fails, error message appears

**Solutions**:
1. Verify your email and password are correct
2. Check for typos (email is case-sensitive)
3. Try resetting your password (if available)
4. Clear your browser cache and cookies
5. Try a different browser
6. Contact support if problem persists

### Account Creation Failed

**Symptoms**: Signup doesn't complete, error message

**Solutions**:
1. Check that all required fields are filled
2. Verify email format is correct
3. Ensure passwords match
4. Check that password meets requirements (minimum 6 characters)
5. Try again with a different email if needed
6. Contact support if issue continues

### Forgot Password

**Solutions**:
1. Check if password reset is available on login page
2. Contact support for password reset assistance
3. Provide your registered email address

## Order Issues

### Order Not Appearing

**Symptoms**: Created an order but don't see it in View Orders

**Solutions**:
1. Wait 1-2 minutes (there's a slight delay)
2. Refresh the page
3. Check that you're logged into the correct account
4. Verify the order was successfully submitted (you should have seen a success message)
5. Check for any error messages on the New Order page

### Order Stuck in "Processing"

**Symptoms**: Order has been processing for more than 15 minutes

**Solutions**:
1. Check the order details for any error messages
2. Refresh the page to see if status updated
3. Wait up to 20 minutes (very large orders can take longer)
4. If still processing after 20+ minutes, contact support
5. Provide order ID when contacting support

### "Out of Space" Error

**Symptoms**: Can't create new orders, see "Out of Space" message

**Solutions**:
1. Check your order limits on the New Order page
2. Delete old orders you no longer need
3. Wait until next month (if you hit monthly limit)
4. Upgrade your subscription for more capacity
5. See [Account Management](account-management.md) for subscription options

### File Upload Failed

**Symptoms**: Can't upload file, error message appears

**Solutions**:
1. Check file format (must be .xlsx, .zip, or .csv)
2. Verify file isn't corrupted
3. Check file size (very large files may fail)
4. Try converting Excel to CSV if having issues
5. Ensure file contains valid MOVES input data
6. Contact support if problem persists

### Order Status Shows "Error"

**Symptoms**: Order completed but shows error status

**Solutions**:
1. Click "Details" to see error message
2. Check if the error is recoverable (e.g., invalid geoid)
3. Create a new order with corrected information
4. Contact support with order ID if error is unclear

## Data Access Issues

### Can't Download Order Results

**Symptoms**: Order is "Ready" but can't access data

**Solutions**:
1. Verify order status is "Ready" (not "Processing")
2. Try accessing through Visualizer instead of direct download
3. Check that you have the correct permissions
4. Try a different browser
5. Check browser download settings
6. Contact support if issues persist

### Data Not Showing in Visualizer

**Symptoms**: Selected order but no data appears

**Solutions**:
1. Verify order status is "Ready" in View Orders
2. Make sure you selected the order in "SELECT CUSTOM ORDER DATA"
3. Check that the order's county/year matches your scenario selection
4. Wait a moment for data to load
5. Try selecting different options (year, pollutant)
6. Refresh the page

### Custom Order Data Not Loading

**Symptoms**: Your order data doesn't appear in visualizations

**Solutions**:
1. Confirm order is "Ready" (not "Processing")
2. Verify you selected the order in the custom order selection
3. Check that county/year in order matches your scenario
4. Wait for data to load (may take a few seconds)
5. Try refreshing the page

## Tool-Specific Issues

### Visualizer Not Loading

**Symptoms**: Visualizer page doesn't load or shows errors

**Solutions**:
1. Wait a few seconds for page to fully load
2. Refresh the page
3. Check your internet connection
4. Try a different browser
5. Clear browser cache
6. Contact support if problem continues

### Calculator Table Not Editable

**Symptoms**: Can't edit values in Calculator table

**Solutions**:
1. Make sure you've selected a table (geographic area)
2. Wait for data to load completely
3. Try clicking directly on a cell
4. Refresh the page if needed
5. Check that you're not in a read-only view

### Reporter Download Not Starting

**Symptoms**: Click download but file doesn't download

**Solutions**:
1. Check browser's download settings
2. Ensure pop-up blockers aren't preventing download
3. Wait longer (generation can take 10-30 seconds)
4. Try again if it times out
5. Check browser console for errors (advanced)

### Aggregator No Data Showing

**Symptoms**: Aggregator table/chart is empty

**Solutions**:
1. Make sure you've selected at least one county
2. Verify you've selected pollutant, aggregation level, and metric
3. Check that selected group type (if applicable) exists in data
4. Try selecting "Overall" aggregation to see if data appears
5. Ensure counties have available data

### Data Hub Processing Takes Too Long

**Symptoms**: Data Hub download seems stuck

**Solutions**:
1. Very large requests (many years × many counties) can take 1-2 minutes
2. Wait at least 2 minutes before assuming it failed
3. Try a smaller request first to test
4. Check your internet connection
5. Contact support if it consistently fails

## Verification & Publishing Issues

### "Not Verified" Error When Publishing

**Symptoms**: Can't publish order, see "Not verified for geoid" error

**Solutions**:
1. Go to Account page
2. Check "Verified Areas" section
3. If county is missing, request verification
4. Wait for approval (1-2 business days)
5. Then try publishing again

### Verification Request Not Approved

**Symptoms**: Submitted verification but not approved

**Solutions**:
1. Check that you used a .gov or .edu email address
2. Verify the geoid (FIPS code) is correct
3. Wait 1-2 business days for review
4. Contact support if it's been longer than 2 business days
5. Check your email for any messages from administrators

### Can't Find Verification Status

**Solutions**:
1. Go to Account page
2. Scroll to "Verified Areas" section
3. Check the table for your requested counties
4. Status will show if verified or pending

## Sharing Issues

### "Please Select Just 1 Bucket" Error

**Symptoms**: Tried to share but got error about selecting multiple orders

**Solutions**:
1. Deselect all orders
2. Select only one order
3. Click SHARE again

### Person Can't Access Shared Data

**Symptoms**: Shared order but person says they can't access

**Solutions**:
1. Verify you added the correct email address
2. Check that the order status is "Ready"
3. Confirm they're using the exact email you shared with
4. Try removing and re-adding them
5. Have them check their access through Visualizer

## Browser & Technical Issues

### Page Won't Load

**Symptoms**: Page is blank or won't load

**Solutions**:
1. Check your internet connection
2. Refresh the page (Ctrl+F5 or Cmd+Shift+R for hard refresh)
3. Try a different browser
4. Clear browser cache and cookies
5. Disable browser extensions temporarily
6. Check if other websites load (to rule out connection issues)

### Buttons Not Working

**Symptoms**: Click buttons but nothing happens

**Solutions**:
1. Wait a moment (page may still be loading)
2. Try clicking again
3. Check browser console for errors (F12, then Console tab)
4. Refresh the page
5. Try a different browser
6. Disable browser extensions

### Slow Performance

**Symptoms**: Platform is slow or laggy

**Solutions**:
1. Check your internet connection speed
2. Close other browser tabs/applications
3. Clear browser cache
4. Try a different browser
5. Wait for large operations to complete (some take time)
6. Contact support if consistently slow

### JavaScript Errors

**Symptoms**: See error messages in browser console

**Solutions**:
1. Refresh the page
2. Clear browser cache
3. Try a different browser
4. Disable browser extensions
5. Contact support with error message details

## Getting More Help

### When to Contact Support

Contact support if:
- Issue persists after trying solutions above
- You see error messages you don't understand
- Data appears incorrect
- You need help with a specific workflow
- You have suggestions for improvements

### Information to Provide

When contacting support, include:
- Description of the problem
- Steps you took that led to the issue
- Any error messages you saw
- Your browser and operating system
- Order IDs (if relevant)
- Screenshots (if helpful)

### Contact Information

See [Contact Support](contact-support.md) for how to reach support.

## Related Topics

- **[Frequently Asked Questions](frequently-asked-questions.md)** - Common questions
- **[Getting Started](getting-started.md)** - Basic platform usage
- **[Contact Support](contact-support.md)** - Get additional help

---

**Still having issues?** See [Contact Support](contact-support.md) for assistance.




