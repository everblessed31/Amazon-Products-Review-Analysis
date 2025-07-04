
# 📊 E-Commerce Product Analysis Dashboard

## 📝 Description  
This project presents an in-depth analysis of an e-commerce product dataset. The aim is to derive actionable insights about product pricing, discount behavior, customer reviews, and overall product performance across various categories. The findings are visualized through an interactive Power BI dashboard.

## 💼 Business Problem  
E-commerce platforms host a wide range of products, but decision-makers often lack visibility into which products and categories perform best in terms of reviews, pricing, and customer satisfaction. The absence of clear insights makes it difficult to optimize product listings, promotional strategies, and pricing.

## 🎯 Aims of this Project  
- To analyze product pricing, discounts, and customer reviews across categories.  
- To identify high-performing and underperforming products.  
- To create a dashboard that allows stakeholders to make data-driven decisions.  
- To uncover relationships between discount levels, ratings, and review counts.

## 🔄 Processes  
1. **Data Cleaning**: Removed null values, duplicates, and formatted price and rating fields.  
2. **Data Transformation**:  
   - Calculated discount percentage.  
   - Created price range buckets (`<₹200`, `₹200–₹500`, `>₹500`).  
   - Aggregated review counts and ratings per category.  
   - Created calculated columns for potential revenue and combined performance scores.  
3. **Data Analysis**: Answered key business questions (see Insights).  
4. **Dashboard Development**: Visualized KPIs and insights in Power BI.

## 🛠️ Tools Used  
- **Microsoft Excel**  

## 📈 Insights  
1. **Average Discount % by Category**: Identified categories offering the highest savings.  
2. **Product Count per Category**: Helps assess product diversity.  
3. **Review Totals**: Shows customer engagement per category.  
4. **Top-Rated Products**: Identified top performers by average rating.  
5. **Price Comparison**: Compared average actual vs discounted prices by category.  
6. **Most Reviewed Products**: Highlights popular or viral items.  
7. **Deep Discounts**: Count of products with ≥50% off.  
8. **Rating Distribution**: Histogram of product ratings (e.g., 3.0, 4.0).  
9. **Potential Revenue**: Estimated using actual price × review count.  
10. **Product Count by Price Range**: Bucketed distribution into `<₹200`, `₹200–₹500`, `>₹500`.  
11. **Discount vs Rating Correlation**: Examined whether bigger discounts attract better ratings.  
12. **Low Engagement Products**: Counted products with fewer than 1,000 reviews.  
13. **High Discount Categories**: Identified categories offering the steepest average discounts.  
14. **Top 5 Overall Products**: Based on combined rating and review count.

## 💡 Recommendations  
- **Focus Marketing** on categories with high discounts and ratings.  
- **Promote Top 5 Products** in ads and newsletters.  
- **Re-evaluate Products with <1,000 Reviews**, possibly archive or improve listings.  
- **Optimize Pricing** by studying the balance between discount and rating satisfaction.  
- **Expand in Price Ranges with Low Product Count** to attract broader audiences.

## 📊 Dashboard View

### KPIs  
- **Total Products**  
- **Total Reviews**  
- **Average Rating**

### Slicers  
- **Category**  
- **Rating**  
- **Price Range**

### Visuals  
- **Donut Chart**: Unique Products by Price Bucket  
- **Line Chart**: Rating vs Discount  
- **Column Bar Chart**: Actual Price vs Average Discount  
- **Pie Chart**: Count of Products per Category
![cleaned_amazon_data-----j-1](https://github.com/user-attachments/assets/606057f3-1b50-4642-8510-c89e9b123cfc)

## 👤 Author  
**Blessing Ogar**  
Junior Data Analyst | Passionate about e-commerce insights and visualization

## 📝 License  
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
