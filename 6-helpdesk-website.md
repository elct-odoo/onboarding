# Helpdesk and eCommerce App Installation Guide

## Step 1: Install the Helpdesk and eCommerce app

## Step 2: Create Two Helpdesk Teams

### Customer Care Template:
- Check the Automatic Assignment checkbox and select "Each user is assigned an equal number of tickets".
- Uncheck the Email Alias checkbox.

### Drone Maintenance Template:
- Check the Email Alias checkbox and set up a domain, e.g., support@demo-db.odoo.com.
- Check return, refunds, and coupons.

## Setting up Drone Maintenance Pipeline Automations

1. Navigate to the Drone Maintenance pipeline.
2. Select the gear icon on the `Solved` stage and choose `Automations`.
3. Create a New automation:
   - Model: Helpdesk Ticket
   - Trigger: Stage is set to `Solved`
4. Add an action:
   - Type: `Send Email`
   - Email Template: `Helpdesk Ticket Rating Request`

## Setting Up eCommerce

1. Navigate to Website > Configuration > Settings > Configure Payment Providers.
2. Input the given credentials.

## Configuring Products

1. Ensure that the Product Type is set to `Storable Product`.
2. In the sales tab, toggle the Out-of-stock Continue selling checkbox.

## Publishing Products

1. Navigate to Website > Site > Products.
2. In the list view, publish products in bulk:
   - Select the products.
   - Use the `Actions` gear icon and select publish.
  
## eCommerce Categories

1. Navigate to Website > eCommerce Categories.
2. Add two new categories: Drones & Accessories.
3. In each product template, navigate to the `Sales` tab.
4. Add your associated category to eCommerce Shop | Categories.

## Conclusion
Your Helpdesk and eCommerce setup is now configured as per the provided instructions. For any further assistance, refer to the documentation or contact support.
