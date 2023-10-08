# Data Visualization Projects
This repository contains examples of dashboards I developed during my work at Tinkoff.

[**Tinkoff**](https://tinkoff-group.com/company-info/summary/) is an online ecosystem of financial and non-financial services with over 35 million users (both retail customers and legal entities, including sole proprietors). In particular, Tinkoff is a group of companies which includes a bank, an insurance company,
a mobile operator, microfinance organizations, IT centers, etc.

## Tech Stack
1. **DWH:** Greenplum
2. **Visualization:** Tableau

## 1. Active Clients

<img src="dashboards/active clients blurred.png" width="800"/>

### 1.1 Description

This dashboard was developed using internal data about Tinkoff's active base of clients, including retail clients and legal entities.
Because of the NDA, I had to blur the numbers on the dashboard. 

**The dashboard includes:**
- Total number of active clients and the number of active products per client as of the report date
- Total number of active clients with every product, including a "Subscription" filter (every user of Tinkoff's products can subscribe to different services to access more functionality or increase interest rates)
- Distribution of clients by the number of products they have
- Top product combinations (Tinkoff operates as a product ecosystem, and it's important to track which combinations of products are most popular among customers)
- Distribution of active clients by the year they joined the ecosystem (the year when a client started using their first product)

### 1.2 Users

- Top management of the Group
- Marketing teams
- Financial department
- Business lines

## 2. Customer's Profile

<img src="dashboards/customer's profile blurred.png" width="800"/>

### 2.1 Description

This dashboard was developed using internal Tinkoff retail customers' demographics data.
Because of the NDA, I had to blur the numbers on the dashboard.

**The dashboard includes:**
- Total number of active customers with every product, including a "Subscription" filter (every user of Tinkoff's products can subscribe to different services to access more functionality or increase interest rates)
- Distributions of customers by:
  - Gender
  - Education
  - Marital status
  - Number of products
  - Age (pie chart and a histogram)
  - City
  - Product age (how long customers have been using a selected product)
  - Income (histogram)
  - Region (colored map)

### 2.2 Users

- Top management of the Group
- Marketing teams
- Business lines

## 3. Financial Services Market

<img src="dashboards/financial services market.png" width="800"/>

### 3.1 Description

This dashboard was developed using open data from the Central Bank's website and shows the assets and liabilities of Russian banks.
Central Bank's data contains data about every credit organization in Russia,
which makes market analytics much more convenient.

**The dashboard includes:**
- Structure of assets and liabilities of the whole market in absolute values and in shares
- Market size of the selected segment (segments are retail loans, loans to legal entities, retail deposits, legal entities' current accounts, etc.)
- Market growth rate of the selected segment (segments are retail loans, loans to legal entities, retail deposits, legal entities current accounts, etc.) and rolling growth rate with an ability to choose the window size
- Top banks in the selected segment
- Share of banks in the selected segment
- Portfolio size of the selected bank in the selected segment with a growth rate line chart

### 3.2 Users

- Top management of the Group
- Financial department
- Business lines

## 4. SME Market

<img src="dashboards/sme market.png" width="800"/>

### 4.1 Description

This dashboard was developed using open data from the Central Bank's website and shows 
the debit portfolio and interest expenses of Russian banks.
Debit portfolio of a bank is a balance of clients' current accounts and deposits as of the selected date.
Interest expenses are bank's expenses from operations related to raising funds at interest rate (for example, 
accrued and paid interest on loans, deposits, securities, and other borrowed funds).
In other words, this dashboard is made to analyze how much money clients have in their accounts/deposits and how expensive it is for the bank to raise these funds.

**The dashboard includes:**
- Market size and market share of Tinkoff with an ability to select the type of SME (legal entities, sole proprietors, or both)
- Top banks by balance of debit portfolio
- The same banks' balances by term (deposits/accounts)
- The same banks' balances by currency (RUB/foreign currencies)
- The same banks' interest expenses by term (deposits/accounts)
- The same banks' interest expenses by currency (RUB/foreign currencies)
- Cost of funding (metric which shows how expensive it is for a bank to raise funds) with an ability
to select accounts/deposits/both types and a bank
- Average turnover/balance ratio

### 4.2 Users

- Top management of the Group
- Financial department
- Business lines

## 5. CBRF Normatives

<img src="dashboards/cbrf normatives.png" width="800"/>

### 5.1 Description

This dashboard was developed using open data from the Central Bank's website and shows 
the mandatory ratios of the Central Bank.

**Mandatory ratios of the Central Bank** are quantitative performance indicators that all Russian banks are required to comply with.

**Mandatory ratios include:**
- capital adequacy ratio (N1)
- liquidity ratios (N2, N3, N4)
- maximum exposure per borrower and group of related borrowers (N6)
- maximum size of large credit risks (N7)
- maximum amount of loans, bank guarantees, and sureties granted by the bank to its participants (shareholders) (N9.1)
- other

**The dashboard includes:**
- Ratios of Tinkoff Bank
- Change of the selected ratio in Tinkoff Bank
- Ratios of other banks
- Change of the selected ration in the selected bank
- Top 15 banks by the selected metric (total assets, retail loans, loans to legal entities, retail and legal entities' accounts,
retail deposits, legal entities' deposits, total capital)
- Top and bottom 15 banks by the selected ratio

### 5.2 Users

- Top management of the Group
- Financial department

## 6. Loans and Overdue

<img src="dashboards/loans and overdue.png" width="800"/>

### 6.1 Description

This dashboard was developed using open data from the Central Bank's website and shows 
the credit portfolio of Russian banks and share of overdue.

**The dashboard includes:**
- Loans and overdue in selected banks
- Overdue rate by banks in percents
- Overdue rate by banks in a colored table
- Detailed credit portfolio and overdue of the selected bank as of the selected report date

### 6.2 Users

- Top management of the Group
- Financial department
- Business lines
