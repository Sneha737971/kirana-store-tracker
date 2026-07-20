# Kirana Store Reorder & Wastage Tracker

## Problem
A small kirana (grocery) store owner has no easy way to see which products
are about to run out of stock, or which product categories are losing the
most money to wastage (spoilage, damage, expiry).

## Solution
An Excel workbook that turns raw daily stock data into a live dashboard with:
- Automatic reorder alerts (IF logic comparing closing stock to reorder level)
- Wastage % by product and by category
- Top 10 products by sales value
- KPI summary: total revenue, total wastage cost, overall wastage %, products needing reorder

## Tools & Skills Used
- Excel formulas: SUMIFS, COUNTIFS, IF, IFERROR, INDEX, MATCH, RANK
- Conditional formatting for reorder alerts
- Category-wise rollups (pivot-style summary using SUMIFS)
- Bar charts for wastage % and top-selling products

## Key Insight
Dairy products had the highest wastage rate (~15%) compared to packaged
goods (3-7%), pointing to a need for tighter ordering or shelf-life
management specifically for perishables.

## Files
- `kirana_store_tracker.xlsx` — full workbook (README, Dashboard, Raw_Data, Category_Summary sheets)