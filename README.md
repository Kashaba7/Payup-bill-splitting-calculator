# PayUP

PayUP is a small command-line bill-splitting app. It calculates a bill total after a tip or service charge, then divides that amount evenly among the people in the group.

## Requirements

- Python 3
- A terminal or command prompt

## Run the app

Open a terminal in the folder containing `PayUP.py`, then run:

```bash
python PayUP.py
```

On some systems, use `python3 PayUP.py` instead.

## How to use it

When prompted, enter:

1. The event or occasion name
2. The bill cost
3. The tip or service-charge percentage as a number, such as `20` for 20% (you can also enter `20%`)
4. The number of people sharing the bill

PayUP prints the bill cost, service charge amount, group size, grand total, and the amount each person pays. The service charge is calculated as a percentage of the bill cost and included in the grand total.

## Example

For a `$100` bill, a `20%` service charge, and `4` people:

- Service charge: `$20.00`
- Grand total: `$120.00`
- Each person pays: `$30.00`

## Notes

- Enter numeric values for the cost and service-charge percentage, and a whole number for the group size.
- The group size must be greater than zero; the app currently does not validate inputs.
- The app displays amounts with a dollar sign and two decimal places.
.
