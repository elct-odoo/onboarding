# Inventory / Purchase Business Case

This guide provides step-by-step instructions for setting up inventory management within your system.

## Setup Steps

1. **Create Two Vendors**
   
2. **Set Cost and Lead Time for Products**
   - Navigate to the "Products and Purchase" Tab

3. **Configure Reordering Rules in Inventory App**
   - Access the Inventory App > Configuration
   - Enable Development Mode
   - Run Scheduler

4. **Configure Dropship**
   - Enable Dropship in Inventory Configuration
   - Remove Make to Order (MTO) and Buy options from Product Inventory Tab, toggle Dropship

5. **Configure Multi-Step Routes**
   - Enable Multistep Routes in Inventory Configuration
   - Unarchive Make to Order (MTO) in Routes
   - Turn on MTO Multi-Step Routes in Product Inventory Tab

6. **Set Items to Consumables**

7. **Create Product "Drone 3.0"**
   - Set Cost to 1000

8. **Turn on Variants**
   - Create Variants and Set Pricing

9. **Configure Traceability**
   - Create Two Items: "Drone Lights" and "Waterproof Cameras"
   - Navigate to Configuration
   - Under Traceability, enable Tracking by Lot and Serial Number
   - Ensure Items are Storable Products
   - Select Associated Way of Tracking

## Additional Notes

- **Development Mode**: Make sure to switch to Development Mode before making configuration changes.
- **Scheduler**: Run Scheduler after configuring reordering rules to ensure proper scheduling of tasks.
- **Multi-Step Routes**: If necessary, configure multi-step routes for specific products.
- **Variants**: Utilize variants for products with different attributes or pricing options.

Please follow these instructions carefully to ensure smooth setup and management of your inventory system.

