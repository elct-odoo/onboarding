### Project Setup Instructions

#### Step 1: Create Projects

1. **Consultancy**
2. **Maintenance**
3. **Design** (with stages: Start, Prototype, Delivery)

#### Step 2: Configure Project Settings

1. Go to the project view Kanban and select the three dots on the project.
2. Head into the project settings.
3. Add an email alias (e.g., consultancy@edu-onboarding-elct-2.odoo.com) and toggle the billable checkbox.

#### Step 3: Create Products

1. **Airproof Consultancy**
2. **Airproof Design**
3. **Airproof Maintenance**
   
   *Product Type*: Service
   
   Install the Time sheets app for Maintenance and Design projects to enable hourly billing.

#### Step 4: Task Creation from Sales Order (SO) (During Step 3)

- Set Invoice Policy to `Based on Timesheets`.
- Create on Order: Task.
- Set Project to the associated project.

**For Consultancy:**

- Set Invoicing Policy to Prepaid/Fixed Price.

#### Additional Setup:

1. **Unit of Measurement (UoM) Configuration:**

   Navigate to Inventory > Configuration > UoM Categories:
   Select `Working Time`
   Add a line:
   Unit of Measure: `25 Hour Pack`
   Type: `Bigger than the reference Unit of Measure`
   Ratio: `=25/8`

   Now when we add a product with this UoM it will autopopulate the Sales Order.
---

This setup guide outlines the steps to configure projects, products, and tasks within the Odoo environment for efficient project management and billing. The creation of tasks from Sales Orders is integrated into Step 3 for streamlined setup.
