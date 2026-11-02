# European Retail Sales Dashboard (Tableau)

**Live dashboard:** [Tableau Public — European Sales Overview](https://public.tableau.com/app/profile/sumanth.gm/viz/eroupenSales_Project/Overview)

An interactive Tableau dashboard analysing four years (2011–2014) of European retail sales — orders, sales, profit and
quantity across product categories (Furniture, Office Supplies, Technology), regions and customer segments.

![Dashboard](https://github.com/user-attachments/assets/e9672985-c48c-4e00-becb-1f1f0de093c8)

## Questions answered

1. Which sub-category sells the highest quantity, and in which region?
2. Waterfall chart of one measure across one dimension.
3. Which state has the highest and lowest profit ratio (calculated field: profit ÷ sales)?
4. Tree map: which order IDs received the largest and smallest discounts?
5. An interactive dashboard combining the worksheets above.

## Headline KPIs (from the dashboard)

| KPI | Value |
| --- | --- |
| Total sales | $2,348,482 |
| Total profit | $283,240 |
| Orders | 8,047 |

## Approach

1. **Data understanding** — reviewed order, product, customer and geography fields.
2. **Preparation** — typed and structured fields (order date, category, sub-category, sales, profit, discount).
3. **Analysis** — targets vs actuals by month and year, top customers and products, sub-category profitability,
   discount and profit-ratio patterns by region and state.
4. **Dashboard and story** — linked views with filters for region, category and year.

## Findings

- Technology has the strongest profit margins; Furniture is the weakest on profitability.
- A small set of products and customers contributes most of the profit.
- Recommendations: prioritise high-margin technology lines, prune low-performing SKUs, review discount policy, and
  shift sales effort toward the most profitable regions.

## Files

| File | Contents |
| --- | --- |
| `European_Sales_Dashboard.twbx` | Tableau packaged workbook (open with Tableau Desktop or Tableau Reader) |
| `European_Sales_Dashboard.pptx` | Presentation of the dashboard and findings |

**Tools:** Tableau Desktop, Tableau Public.
