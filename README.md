# Receivables Radar

> A dashboard and collection tool for businesses that sell on credit. It shows which overdue invoices to chase first.

**[Live demo](https://sri-setiowati.github.io/receivables-radar/)**

In the simulated demo data, 79 invoices fell due in the last 30 days and only 28 were paid on time. The useful question is which customers to call first.

I ran a building-materials store for 17 years, so I have chased my share of late invoices. The hard part was rarely the call itself. It was deciding who to call when ten customers owed money and I had one afternoon.

![Findings](screenshots/04-findings.png)

## What it does

- Reads an invoice export from a spreadsheet, including messy dates and amounts
- Groups receivables by age: not yet due, 1-30, 31-60, 61-90 and 90+ days overdue
- Ranks customers by how much they owe and how late they are
- Calculates days sales outstanding (DSO) and the share of invoices paid on time
- Writes three findings from the data, for example how much of the overdue balance sits with the top five customers
- Drafts a WhatsApp reminder for each customer

## About the demo

The data is simulated: a fictional building-materials distributor with 12 months of invoices. Nothing in it comes from a real company. The page is available in English and Indonesian.

The month buttons at the top are 12 snapshots, one per month. Each shows the books as of the 25th. Click a month and every number on the page changes to match.

![Overview](screenshots/01-overview.png)
![Trend and aging](screenshots/02-trend-aging.png)
![Late payers](screenshots/03-late-payers.png)

## Status

Tested on simulated data only. I am looking for a few businesses that sell on credit and are willing to try it on a real invoice file. If that is you, message me on LinkedIn.

## Built with

| Part | Tool |
| :--- | :--- |
| Data processing and tests | Python, 80 automated tests |
| Dashboard | Plain HTML and JavaScript, one file, works offline |
| Browser checks | Headless Chromium via Playwright |

## More of my work

- [Olist e-commerce analysis](https://github.com/sri-setiowati/olist-ecommerce-analysis)
- [Marketing campaign ROI analysis](https://github.com/sri-setiowati/marketing-campaign-roi-analysis)

## Contact

Sri Setiowati, Sidoarjo, Indonesia
[LinkedIn](https://linkedin.com/in/sri-setiowati) · [GitHub](https://github.com/sri-setiowati)
