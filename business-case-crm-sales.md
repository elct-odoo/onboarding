# Airproof Business Case Readme

This document outlines the setup and configuration steps for Airproof's business case using the Odoo platform.

## Products

Airproof offers the following products:

1. Drone 1.0
2. Drone Blades
3. Drone Case

## Contacts

Airproof maintains two main contacts:

1. **Tech Company**
   - This contact represents a technology company.
   - [x] Company checkbox toggled.
   - Default email: info@demo-database-name.odoo.com

2. **Big Client**
   - This contact represents a significant client.
   - [x] Company checkbox toggled.
   - Default email: info@demo-database-name.odoo.com

## Configuration Steps

1. Enable Leads:
   - Navigate to CRM > Configuration > Toggle Leads.

2. Create Sales Team:
   - Navigate to Sales > Configuration > Sales Team.

3. Configure Email Aliases for Sales Team:
   - Set up email aliases for each sales team.

4. Send Practice Email:
   - Send a practice email to the configured email alias.

5. Manage Leads:
   - Monitor and manage leads in CRM > Leads.

6. Convert Leads to Opportunities:
   - Convert leads to opportunities within the CRM module.
   - Opportunities start at the leftmost stage of the pipeline.

7. Sales Order Automation:
   - Enable quotation templates:
     - Sales > Configuration > Toggle Quotation Template.
   - Configure Quotation Template:
     - Include Drone 1.0 and 4 Drone Blades.
   - Select Quotation Template:
     - Automatically populate products in sales orders.
   - Confirm Sales Order:
     - Sales orders automatically populated with associated products.

8. Payment Terms Customization:
   - Set default payment terms based on client relationship.
   - Grant different lead times for different clients.

9. Down Payment Option:
   - Upon confirming the sales order and creating an invoice, select down payment percentage option.

## Additional Information

- **Business Requirement:**
  Airproof seeks to streamline the sales process by automating the creation of sales orders, particularly for bundles like Drone 1.0 with 4 Drone Blades.

- **Solution:**
  Quotation templates are utilized to automatically populate products in sales orders, reducing manual entry.

By following these steps, Airproof can efficiently manage sales processes and enhance customer relationships.
