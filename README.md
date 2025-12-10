# BasicOdooServerSideProject
Odoo server-side module that prevents orders of items outside the shopping cart.”

# Odoo Cart Restriction Module

This Odoo module enforces cart integrity by preventing customers from ordering products outside the shopping cart.  
When a user attempts to bypass the cart and directly order a product, the system raises a controlled error message to ensure proper workflow and order validation.

## Features

- Server-side enforcement to block direct product ordering.
- Raises a clear error message when users try to bypass the cart.
- Fully compatible with standard Odoo sales workflow.
- Easy to install and integrate into any Odoo instance.

## Installation

1. Copy the module folder into your Odoo `addons` directory.
2. Update the Apps list in Odoo.
3. Install the module from the Apps menu.

## Usage

- Customers add products to the cart as usual.
- Attempting to order products outside the cart will trigger an error message.
- No extra configuration is required—works immediately after installation.

## Benefits

- Ensures proper order processing flow.
- Prevents accidental or unauthorized direct product orders.
- Maintains consistent cart behavior across your Odoo instance.
