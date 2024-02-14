# Order of Operations for DroneZone 2.0 Implementation

## 1. Creating Drones:
   - Create 5 drones (Drone A-E) in Odoo.
   - Set them up for sale under the inventory tab, selecting only the manufacture route, not the buy route. Since we will not be purchasing these from a vendor.
   
   **Bill of Materials (BoM) for Drones:**
   - Drone A: BoM Drone Battery, Drone Blade, Drone Plastic Structure, Drone Engine A
   - Drone B: BoM: Drone Battery, Drone Blade, Drone Plastic Structure, Drone Engine B
   - Drone C: BoM: Drone Battery, Drone Blade, Drone Plastic Structure, Drone Engine C
   - Drone D: BoM: Drone Battery, Drone Blade, Drone Plastic Structure, Drone Engine D
   - Drone E: BoM: Drone Battery, Drone Blade, Drone Plastic Structure, Drone Engine E

   One thing I did to showcase our unique product variant feature is create a single product Drone Engine and create 5 different variants: Drone Engine A, B, C, D, E. Each of these variants can have separate sales prices and separate costs for purchasing from our vendor.

   Which we should create now: We now have a new contact Drone Vendor which we will purchase all of our non- manufactured products such as our accessories and drone components.

## 2. Creating Drone Accessories:
   - Create Drone Case and Float Kit as accessories in Odoo.

## 3. Product Categorization:
   - This step isn’t completely necessary but I wanted to show you how we can categorize our products. I’ll keep it simple and create two product categories: Drones and Drone Accessories. Now each product can be put in one of these boxes.

   Let’s also set up our prices and costs for each product. For manufactured products we can add a cost to a component and the parent product `Cost` can be computed from our BoM.

   However for the components that we purchase we need to create a vendors price list and set the cost to the corresponding purchase price.

## 4. Price Lists:
   - 10% seasonal increase - We can select time frames for the month of July and December and a negative discount to increase our sales prices.
   - VIP - 15% discount for VIP customers.
   - Composite VIP Seasonal Discount - 5% discount for VIPs.

## 5. Create Two Sales Teams: 
   - B2B and B2C and assign our team leads.

## 6. User Creation:
   - We will also create a user with limited access that will be our intern. While creating the user we have an abundance of access rights for our business needs. In our case, we will have to remove administrative access rights from all apps. For this demo I will not create a User for every employee instead I will create two team leads and an intern for a total of 4 users (including my own which will serve as you David).
   - Sales we will set to: User: Own Documents Only.
   - We’ll trust our team leads with default admin access but in the real world we can tweak this very easily.

## 7. Intern Workflow:
   - Next, we’ll hop into a day in the life of your intern. Let's log onto his database so I can show you his limited access. I see you have him uploading contacts into the CRM to cold call.
   - Let’s head into our contacts page. We are fully compatible with your current Google Sheet spreadsheet. I created a Google sheet with 5 companies for him to cold call. We’ll need to refactor your column names but after that we will export as CSV and upload it into our contacts.
