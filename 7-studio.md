# Odoo Contact Customization and Product Relationship Setup

This repository provides instructions on how to customize contact templates and establish relationships between contacts and products in Odoo using Studio.

## Installation

1. Install the Studio module if it's not already installed.

## Usage

1. Navigate to the Contacts module and select an existing contact.

2. Toggle Studio by clicking on the wrench icon in the top right corner.

3. Edit Contact Template:
   - Add a new tab to the right of Internal Notes.
   - Within this tab, add the requested fields:
     - Text field for Nickname.
     - Date field for Birthdate.
     - Checkbox field indicating if the client signed the contract or not.
     - File field to upload the signed Customer Contract.
   - Create a conditional invisible rule for the Date field indicating since which year they've been clients, based on the Client Signed checkbox.
   - Create a conditional invisible rule for the Selection field showing where the contact was referred from (Social Media, Referral, TV), also based on the Client Signed checkbox.

4. Connect Products to Contacts:
   - Add a many2one field to products on the Contacts form.
   - Add a one2many field to contacts on the Products form to establish the relationship between contacts and products.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](LICENSE)
