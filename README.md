# Myntra-Fashion-Clothing-Analysis-Sales-Discounts-and-Customer-Behavior
# Introduction:
This project focuses on analyzing product data through pivot tables to uncover meaningful insights across categories, brands, sizes, ratings, and pricing.
The study highlights dominant segments, customer satisfaction trends, and discount strategies that shape overall product distribution.
By synthesizing these findings, the project aims to guide better inventory planning, marketing focus, and pricing decisions for stronger business outcomes.
# Objective:
The objective of this project is to analyze product distribution, brand performance, customer ratings, size availability, and pricing-discount patterns in order to:
•	Identify dominant categories and gender representation in the catalog.
•	Highlight leading brands and their contribution to overall product counts.
•	Assess customer satisfaction levels through average ratings.
•	Understand size availability trends to evaluate inclusivity and accessibility.
•	Examine pricing and discount structures to uncover affordability patterns and premium item strategies.
# Data description:
•	This dataset contains product-level details from a fashion retail store.
•	Each row represents one product, showing its ID, brand, category, gender target, price, discount, final price, size options, and customer feedback (ratings and reviews).
•	It helps analyze sales performance, discount impact, and customer preferences across different brands, categories, and sizes
# Data Cleaning in Power Query
•	Removed duplicates to ensure each product ID is unique.
•	Handled missing values by replacing nulls with defaults or removing incomplete rows.
•	Standardized text fields (brand names, categories, discount labels) using Transform → Format tools.
•	Split & merged columns where needed (e.g., separating discount % from text, merging category fields).
•	Ensured numeric consistency by converting prices, ratings, and reviews into proper number formats.
•	Verified calculations so that Final Price = Original Price – Discount Price.
# Data Cleaning in Excel
•	Used filters & conditional formatting to spot duplicates and errors.
•	Applied formulas (e.g., TRIM, PROPER, VALUE) to clean text and numeric fields.
•	Checked relationships between discount %, discount price, and final price for accuracy.
•	Standardized size options by aligning formats (e.g., “S, M, L” vs “Small, Medium, Large”).
•	Validated data ranges to ensure ratings (1–5) and reviews are logical.
•	Created a clean master table ready for PivotTable analysis.
# Data Exploration:
# Final Price statistics:
•	Average final price: ₹1,598, with median ₹1,487 and mode ₹1,424.
•	Variation: Standard deviation is high (₹868), showing wide differences in product prices.
•	Range: Prices span from ₹185 (minimum) to ₹9,499 (maximum), a huge range of ₹9,314.
•	 Distribution shape: Skewness of 2.04 and kurtosis of 8.25 indicate a right skewed, heavy tailed distribution (few very high prices pulling the average up).
•	Sample size: 4,898 products, with a total final price sum of ₹7,824,624
# Discount Price statistics:
•	 Average discount: ₹90.44, with median and mode both at ₹80.
•	 Variation: Standard deviation is ₹64.47, showing moderate spread in discount values.
•	 Range: Discounts go from ₹3 (minimum) to ₹1,035 (maximum), a wide range of ₹1,032.
•	 Distribution shape: Skewness of 3.67 and kurtosis of 28.96 indicate a highly right skewed, peaked distribution (few very large discounts pulling the average up).
•	 Sample size: 4,898 products, with a total discount sum of ₹442,985.
# Pivot table:
1.	Women’s average product share (105.5%) is higher than men’s (91.45%), showing stronger representation overall.
2.	The top 10 brands — led by Florence, Urban Dog, and Vastranand — consistently offer the highest average discounts (≈100%+), showing an aggressive pricing strategy to attract customers and position themselves as strong value-driven players.
3.	Roadster dominates the top 10 brands with 982 products, making it the largest contributor, while other brands like Mast & Harbour and HERE&NOW follow at much smaller counts.
4.	Most brands hold consistently Top 10 high ratings around 4.5–4.6, with Espresso and River of Design Jeans slightly leading at 4.6, reflecting strong overall customer satisfaction.	
5.	Western wear is the largest category with 1,648 products, followed by Topwear (878) and Indian wear (738), showing these three segments dominate the overall product distribution.
6.	Standard clothing sizes dominate, with S–XL, XXL, and XS–XXL ranges together accounting for the majority (≈2,700 products), while numeric sizes (26–44) and onesize contribute smaller shares.
7.	Average original prices rise with higher discount percentages — peaking above ₹4,000–₹7,000 at 76–85% discounts — while the overall mean price across all discounts is about ₹1,688, showing that premium items tend to carry deeper discounts.
# Key Insights:
•	Gender dominance – Women’s categories have stronger representation (105.5% vs. 91.45% for men), with Western wear leading overall.
•	Category leaders – Western wear (1,648), Topwear (878), and Indian wear (738) together dominate the product distribution.
•	Brand concentration – Roadster is the largest contributor (982 products), far ahead of other top brands like Mast & Harbour and HERE&NOW.
•	Customer satisfaction – Ratings are consistently high (~4.5–4.6), with Espresso and River of Design Jeans slightly ahead at 4.6.
•	Size availability – Standard sizes (S–XL/XXL, XS–XXL) account for the majority (~2,700 products), while numeric sizes and onesize are less common.
•	Pricing & discounts – Average original prices increase with higher discount percentages, peaking above ₹4,000–₹7,000 at 76–85% discounts. The overall mean price is ₹1,688, showing premium items attract deeper discounts.
# Conclusion:
This analysis provides a clear picture of the product catalog	 across categories, brands, sizes, pricing, and discounts. The findings highlight that women’s fashion dominates the assortment, with Western wear leading in volume. Roadster emerges as the strongest brand, while overall ratings remain consistently high, reflecting strong customer satisfaction. Standard sizes (S–XL/XXL) are most prevalent, ensuring accessibility for the majority of customers. Pricing and discount trends reveal a skewed distribution, where most products are affordable mid range, but premium items with deeper discounts raise averages.
