# Records

## Inventory

| File | Entries |
| --- | ---: |
| [Console Repair Inventory](console-inventory.csv) | 136 |
| [Controller and Accessory Inventory](controller-accessory-inventory.csv) | 105 |

These are the two original inventory lists. [Console faults](console-faults.csv)
groups the console list by model and reported problem.

## Why the repair register has seven more entries

The original controller/accessory CSV comes from the 105-entry stock list.
The repair register combines three overlapping source lists, using the highest
quantity listed for each controller or accessory type. That gives 112 entries:
100 controllers and 12 accessories.

Three item counts explain the difference:

| Item | Original inventory | Repair register | Difference |
| --- | ---: | ---: | ---: |
| PlayStation DualShock 2 | 10 | 15 | 5 |
| Wii Remote | 5 | 6 | 1 |
| Xbox 360 breakaway cable | 1 | 2 | 1 |
| Total difference | | | 7 |

The console count is 136 in both. This brings the register to 248 entries,
compared with 241 across the two original CSVs. The source lists overlap, so
their quantities are not added together.

## Repair log

The [repair register](repair-register.csv) is the later, fuller log of 248 entries.
It includes repair notes, outcomes, and costs. It covers the same business
stock as the inventory lists, so their totals should not be added together.

`EX-` IDs belong to the repair log; `REC-` IDs belong to the original inventory.
They are separate sets of IDs.

Purchase and tool costs were split across the stock because the consoles and
controllers were bought in lots. See [sales and costs](../docs/business-record.md)
for the calculation.

Sale dates appear on the individual repair pages.

Pending items have asking prices and are excluded from sales totals.
