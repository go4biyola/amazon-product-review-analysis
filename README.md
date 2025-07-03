# amazon-product-review-analysis
“A data analysis project summarizing customer behavior and product insights based on e-commerce review data. Includes charts, metrics, insights, and recommendations.”
# 📘 Product Review Insights

A summary of key findings and strategic recommendations from the analysis of e-commerce product reviews. This document highlights patterns in customer behavior, product performance, and pricing dynamics to guide data-driven decisions.

---

## 📊 Key Takeaways

- **High discounts** don’t guarantee high satisfaction — some heavily discounted products still receive poor ratings.
- **Top revenue products** are those with a combination of **high price** and **high engagement** (measured by number of reviews).
- **Rating Impact Score** helps identify products that are not only well-rated but also widely reviewed — a proxy for trust and popularity.
- **Customer ratings alone** may not be a reliable indicator of product quality when not paired with review volume.

---

## 📈 Metrics Used

| Metric Name           | Formula                                  | Purpose |
|------------------------|-------------------------------------------|---------|
| Potential Revenue      | `Actual Price × Number of Reviews`        | Estimates revenue potential based on price and engagement |
| Rating Impact Score    | `Average Rating × Number of Reviews`      | Identifies products that are both well-liked and widely reviewed |
| Discount Effectiveness | `Discount % vs. Average Rating`           | Evaluates whether discounts correlate with customer satisfaction |

---

## 📌 Insights by Chart

### 📉 Chart (ii): Discount vs. Rating
- Products with high discounts often do **not** have the highest ratings.
- This suggests that **deep discounts may be compensating for lower product quality** or customer dissatisfaction.
- **Recommendation**: Encourage customers to read reviews, not just rely on star ratings or discounts.

---

### 💰 Charts (iv) & (v): Potential Revenue by Category/Product
- Top-performing categories and products were identified using the **Potential Revenue** metric.
- These products combine **high price points** with **strong customer engagement**.
- **Recommendation**: Focus marketing and inventory efforts on the **top 5 categories** or **top 10 products** with the highest potential revenue.

---

### 🌟 Rating Impact Score Chart
- This chart highlights products with the highest **Rating Impact Score**.
- These are products that are:
  - Highly rated (typically 4.5+ stars)
  - Reviewed by hundreds or thousands of customers
- **Recommendation**: Use these products for:
  - **Upselling and bundling**
  - **Case studies or testimonials**
  - **Identifying best practices** for product development

---

## 📁 Supporting Files

- 📄 [Cleaned Dataset](../data/product_reviews_clean.csv)
- 📊 [Charts Folder](../charts/)
- 📘 [Full Insights Table](../insights/product-review-insights.md)

---

## 🧠 Next Steps

- Add a priority score to each insight for roadmap planning.
- Monitor changes in product performance over time to validate insights.
- Expand analysis to include sentiment from review text (optional NLP extension).

---

## 📅 Last Updated

July 4, 2025

---

## 🧾 License

This content is part of the `product-review-insights-dashboard` project and is shared under the MIT License.
