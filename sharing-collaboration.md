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

# Sharing & Collaboration

Learn how to share your order data with colleagues and manage access to your emissions modeling results.

## What is Sharing?

**Sharing** allows you to grant other users access to view and download your order data. When you share an order:

- The person you share with can access the order's data
- They can view the data in Visualizer and other tools
- They can download the data for their own analysis
- You maintain control and can revoke access at any time

This is useful for:
- Team collaboration: Sharing results with colleagues
- Stakeholder review: Allowing others to review your analysis
- External partners: Granting access to consultants or partners
- Public transparency: Making data available to specific individuals

## Sharing an Order

### Step 1: Select an Order

1. Go to **"View Orders"** in the sidebar
2. Find the order you want to share
3. **Select exactly one order** by clicking its checkbox
   - ⚠️ **Important**: You can only share one order at a time
   - If you select multiple orders, you'll see an error message

### Step 2: Click Share

1. Click the **"SHARE"** button
2. A modal window will open showing sharing options

### Step 3: View Current Access

The share modal shows:
- **"People with access"**: A list of email addresses that can currently view the order
- **Table**: Shows all users who have viewer access
- Your own email should appear in the list (you're the owner)

### Step 4: Add Someone

To grant access to a colleague:

1. Enter their **email address** in the "Email" field
2. Click the **"Add"** button
3. The system will grant them viewer access
4. Their email will appear in the "People with access" table
5. You'll see a confirmation message: "Viewer permission added."

### Step 5: Remove Someone

To revoke access:

1. Enter the person's **email address** in the "Email" field
2. Click the **"Remove"** button
3. Their access will be revoked
4. Their email will be removed from the table
5. You'll see a confirmation message: "Viewer permission removed."

### Step 6: Copy Bucket URL (Optional)

The share modal also shows:
- **Bucket URL**: A direct link to the data storage location
- **Copy Link button**: Click to copy the URL to your clipboard
- You can share this URL directly if needed (advanced use)

## Understanding Access Levels

### Viewer Access

When you share an order, the person receives **viewer access**, which allows them to:
- ✅ View the order data in Visualizer
- ✅ Download the data
- ✅ Use the data in their own analysis
- ❌ Cannot modify the order
- ❌ Cannot delete the order
- ❌ Cannot share it with others

### Owner Access

As the order owner, you can:
- ✅ View and download the data
- ✅ Share with others
- ✅ Revoke access
- ✅ Delete the order
- ✅ Publish the order (if verified)

## Managing Shared Access

### Viewing Shared Orders

If someone shares an order with you:
- The order may appear in your Visualizer's custom order selection
- You can access the data through the shared bucket
- You'll see the data as if it were your own (for viewing purposes)

### Revoking Access

To remove someone's access:
1. Open the share modal for the order
2. Enter their email
3. Click "Remove"
4. They will no longer be able to access the data

### Updating Access

You can add and remove people at any time:
- Access changes take effect immediately
- No notification is sent (the person may notice when they try to access)
- You can re-add someone if needed

## Best Practices

### Before Sharing

1. **Verify Order Status**: Make sure the order is "Ready" (not "Processing")
2. **Review Data**: Check the data in Visualizer to ensure it's what you want to share
3. **Confirm Email Addresses**: Double-check email addresses before adding
4. **Document Purpose**: Note why you're sharing (for your records)

### When Sharing

1. **Share Selectively**: Only share with people who need access
2. **Communicate**: Let people know you've shared data with them
3. **Set Expectations**: Explain what they can do with the data
4. **Monitor Access**: Periodically review who has access

### After Sharing

1. **Follow Up**: Confirm recipients can access the data
2. **Answer Questions**: Be available to help with data interpretation
3. **Update as Needed**: Add or remove people as projects evolve
4. **Clean Up**: Remove access when it's no longer needed

## Common Scenarios

### Scenario 1: Share with Team Member

1. Select your order
2. Click SHARE
3. Add team member's email
4. They can now access the data
5. Communicate that you've shared it

### Scenario 2: Share with External Consultant

1. Select the relevant order
2. Click SHARE
3. Add consultant's email
4. They can access data for their analysis
5. Remove access when project is complete

### Scenario 3: Revoke Access

1. Open share modal
2. Enter person's email
3. Click Remove
4. Access is immediately revoked
5. They can no longer access the data

### Scenario 4: Share Multiple Orders

Since you can only share one order at a time:
1. Share first order with person
2. Close modal
3. Select second order
4. Click SHARE again
5. Add same person's email
6. Repeat for additional orders

## Troubleshooting

### "Please Select Just 1 Bucket" Error

**Problem**: You selected multiple orders and tried to share.

**Solution**: 
1. Deselect all orders
2. Select only one order
3. Click SHARE again

### "No Rows Selected" Error

**Problem**: You clicked SHARE without selecting an order.

**Solution**:
1. Select an order first
2. Then click SHARE

### Person Can't Access Data

If someone says they can't access:
1. Verify you added the correct email address
2. Check that the order status is "Ready"
3. Confirm they're using the same email you shared with
4. Try removing and re-adding them

### Can't Remove Someone

If removal fails:
1. Verify the email address is correct
2. Check that the person is actually in the access list
3. Try refreshing the page
4. Contact support if problem persists

## Security Considerations

### Email Verification

- The system uses email addresses to grant access
- Make sure you enter correct email addresses
- The person must use the exact email you shared with

### Access Control

- Only you (the owner) can manage sharing
- Shared users cannot share further
- You can revoke access at any time

### Data Privacy

- Shared data is accessible to those you share with
- Be mindful of what data you share
- Consider data sensitivity before sharing

## Related Topics

- **[Viewing Orders](viewing-orders.md)** - Managing your orders before sharing
- **[Creating Orders](creating-orders.md)** - Create orders to share
- **[Publishing Data](publishing-data.md)** - Make data publicly available (different from sharing)

## Next Steps

After sharing:

1. **Communicate**: Let recipients know you've shared data
2. **Monitor**: Check who has access periodically
3. **Update**: Add or remove people as needed
4. **Clean Up**: Remove access when no longer needed

---

**Ready to make data publicly available?** See [Publishing Data](publishing-data.md) for publishing to the public database.




