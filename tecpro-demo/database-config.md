# Tecpro 2.0: Online Software Development Teaching Course

## Database Configuration

### Project Setup

1. Create a project named "Online Development Course".

2. Define stages: New, Assigned, Teaching, Done.

### Prerequisites

1. Create unit of measurement:

- Basic: `Ratio: 25/8`

- Standard: `Ratio: 50/8`

- Unlimited: `Ratio: 31.0`

2. Enable pricelists in Sales > Configuration.

- In the USD Pricelist entries `Configuration` tab, select your website.

## Products

### Email Support

- Type: Service

- Can be Sold and Recurring

- Sales Price: $50

- Recurring Price (Monthly): $50 (Default USD pricelist)

### Basic Pack

- Type: Service

- Can be Sold

- Set the sales price

- Link Email Support as an optional product

### Standard Pack

- Type: Service

- Can be Sold and Recurring

- Set the sales price

- Recurring Price (Monthly): $50 (Default USD pricelist)

- Link Email Support as an optional product

### Ultimate Pack

- Type: Service

- Can be Sold and Recurring

- Set the sales price

- Recurring Price (Monthly): $50 (Default USD pricelist)

- Link Email Support as an optional product

## Website Customization

- Install and customize the website with the provided theme.

- Use prompts for the initial setup.

- Edit the help page to add necessary fields for direct communication to the helpdesk team.

## Automation Rules

1. New Students:

- Send email + Update Stage to Assigning.

2. Assigned Teacher:

- Send email + Update Stage to Teaching.

3. Complete Trigger:

- Update stage to Done if remaining hours <= 0.

4. Out of Time:

- Send a warning email + Update stage to Done.

## Product Publishing

- Go to Website > Site > Products.

- Select all four products, click `Actions`, and then `Publish`.

## Payment Providers

- Configure Authorize.net in Sales > Configuration > Payment Providers with credentials.

## Software Updates

- Utilize the Contacts App for email announcements.

1. In the Contacts App, select the list view.

2. Utilize the filter to narrow down fields as needed, which can be extremely helpful for large contact lists.

3. Select the `Actions` button and choose "Send Email" to send announcements and updates to contacts.

- Alternatively, use Odoo's Email Marketing application.

## Project Statistics

- View project statistics in the Projects app under `Project Updates`.

In this Tecpro 2.0 demonstration, we've provided a detailed guide on establishing and operating an online software development teaching course. Covering database configuration, product management, automation, payment setup, and software updates, we've ensured a comprehensive overview. With Tecpro 2.0, educators gain a professional platform to streamline course administration and foster effective communication with students, facilitating a seamless online teaching experience.
