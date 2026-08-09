# Retail Inventory

Edit `inventory.json` to control the orange **In Stock** highlights in the Retail catalog.

Each entry tracks individual vials for one exact product and strength:

```json
{
  "product": "Tirzepatide",
  "strength": "60mg",
  "quantity": 12
}
```

## Updating inventory

1. Open `inventory.json` in this repository.
2. Click the pencil icon to edit it.
3. Add or update the product, strength, and quantity.
4. Click **Commit changes**.

Use the product name and strength exactly as they appear in Retail. Quantities represent individual vials.

- Any quantity above `0` displays an orange In Stock highlight in Retail.
- A quantity of `0` removes the highlight.
- Retail checks this file when the page opens and every five minutes.

Keep a comma between entries, but do not add a comma after the final entry.
