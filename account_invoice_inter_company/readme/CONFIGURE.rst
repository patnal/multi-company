To configure this module, you need to go to the menu *Settings > General Settings*, go to the tab *Multi-Companies* then check *Multi-companies*

You now have access to other checks:

- *Common Product Catalog*
- *Generate Intercompany Invoices* (if two companies don't have both flags "Generate Intercompany Invoices" enabled, there's no invoice or bill creation between them)
- *Invoice Auto Validation*

To customize products sharing don't hesitate to override `_compute_share_product()` in `res.company` model.
