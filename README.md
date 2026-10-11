# NIC Basket Simulation — Italian Consumer Price Index

This repository contains an Excel workbook that explores the **NIC** (*Indice Nazionale dei prezzi al Consumo per l'Intera Collettività*), the main consumer price index used by ISTAT to measure inflation in Italy.

## What is the NIC?

The NIC tracks how much it costs to buy a fixed "basket" of goods and services representative of what the average Italian household consumes. Each category in the basket is assigned a percentage weight; when prices rise, the weighted average of those increases becomes the official inflation figure.

Because it is built around a statistical average, the NIC may diverge significantly from the actual spending patterns of any specific household.

## Contents

The workbook contains two sheets:

| Sheet | Description |
|---|---|
| `Composizione del NIC` | Full breakdown of the 12 NIC categories, their weights, and a plain-language description of what each covers |
| `Simulazione famiglia` | Interactive simulation: enter a monthly budget and the workbook projects how a family of three would spend it according to NIC weights, with commentary comparing those figures to real-world costs |

## How to use it

1. Open `NIC_basket_simulation.xlsx` in Excel or LibreOffice Calc.
2. In the `Simulazione famiglia` sheet, change the value in the **monthly budget cell** (marked with ◄) to match your household's actual spending.
3. The table recalculates automatically, showing what the NIC "expects" each category to cost for your budget.
4. Compare the NIC-implied figures with your real expenses to see where the index is more or less representative.

## Key finding

The NIC is a population-level average. A family that rents its home, owns a car, or lives in a high-cost area will typically find that the index understates their real cost of living — and therefore understates the inflation they actually experience.

## Data source

Basket weights are taken from the official ISTAT NIC methodology. All calculations in the workbook are transparent and editable.
