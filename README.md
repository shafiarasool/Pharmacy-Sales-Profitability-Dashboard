# Pharmacy Sales Profitability Dashboard
A 3-page Power BI dashboard analyzing sales, profit and product performance across a network of 120 pharmacies in 8 European countries, covering 2024–2025.

---

**Pages:**

**1.Overview:** Headline KPIs, profit by category, country and city, quarterly profit trend, and leading pharmacies

**2.Pharmacy Performance:** Sales by pharmacy type, store size and promotion status, plus a pharmacy ranking with current-year vs prior-year comparison

**3.Products & Brands:** Brand profitability, product-level volume vs margin, branded vs generic split, and lowest-margin products

---

**Highlights:**

**i.** The network generated €8.63M in sales and €2.42M in profit across 445,793 units sold, at a 28.04% profit margin, spanning 220 products and 120 pharmacies

**ii.** Prescription is the top profit category (€613K) but has the lowest margin of the main categories (21.9%). Wellness (€575K) and Personal Care (€487K) earn margins of 33.6% and 33.5%, followed by OTC (€528K) and Medical Devices (€218K)

**iii.** Germany leads profit by country (€439K), followed by France (€394K) and Italy (€374K), with margins holding at about 28% in every country. Munich HealthPoint #095 is the most profitable pharmacy (€45.2K profit on €162K sales)

**iv.** Quarterly profit rose from €285K in Q1 2024 to €318K in Q4 2025. It peaked in Q3 2024 (€314K), dipped to about €289K in early 2025, then reached its highest levels from Q2 2025 onward. Full-year profit grew 4.9% (€1.18M in 2024 to €1.24M in 2025)

**v.** Urban pharmacies lead on sales (€4.13M), followed by Suburban (€3.11M) and Rural (€1.40M). Medium-sized stores outsell Large and Small stores (€3.84M vs €3.17M and €1.63M)

**vi.** Promotional sales make up only 10.6% of total sales, and they carry a much lower margin (19.9% vs 29.0% for non-promo sales), so promotions are not the main sales driver and dilute profitability

**vii.** Munich HealthPoint #095 ranks first in sales (€162K), but its 2025 sales (€76.0K) fell 12% below 2024 (€86.3K). Lyon HealthPoint #073 grew 16% year over year (€77.2K vs €66.5K)

**viii.** AntiBioX is the top brand by profit (€170K), and AntiBioX ACE Inhibitor 400 mg is the most profitable single product (€45.3K)

**ix.** Branded medicines generate €2.10M in profit (87% of the total) compared with €0.32M from generics, and generics earn a lower margin (25.5% vs 28.5%)

**x.** The lowest-margin products (such as CardioPro Inhaler 10 mg at 17.48%) sit roughly 10 points below the 28% company average, highlighting pricing and cost opportunities

---

**Tools used:** Power BI Desktop, data modeling (star schema with date, pharmacy and product dimensions), DAX measures (current-year vs prior-year time intelligence, RANKX ranking, dynamic chart titles), field parameters for dynamic metric toggles (Sales, Profit, Margin % and Units sold) and interactive report design with bookmarks and drill-downs.

---

**Note:** This is a self-directed project built to practice dashboard design and business analytics using a sample pharmacy dataset. All pharmacy, brand and product names in the data are fictional.
