# E-commerce-Customer-Segmentation-
<b>Overview</b>

<p>This project focuses on segmenting e-commerce customers based on their transactional behavior and demographic features. . The goal is to identify distinct customer groups and provide actionable insights to improve customer loyalty and satisfaction through targeted coupon campaigns.</p>
<p>The project uses Hierarchical Clustering with k = 4 to segment customers. The clustering results are evaluated using the Silhouette Score, and each segment is analyzed to provide recommendations for targeted marketing strategies. </p>
<br>
<b>Project Structure</b>
<br>
<br>
 - Data Preparation <br>
 - Data engneering <br>
 - Modeling <br>
 - Analysis <br>
 - Visualization <br>
<br>
<b>Model Approach</b><br><br> 

<b>Hierarchical Clustering</b></br>

<strong>Algorithm:</strong> Agglomerative Hierarchical Clustering.</br>
<strong>Linkage Method:</strong> Ward’s method</br>
<strong>Number of Clusters (k): :</strong> 4 (chosen based on a balance between granularity and interpretability).</br>
</br><b>Evaluation Metrics</b></br>
- Silhouette Score : A higher score indicates better clustering.

</br>
<strong>  Key Findings </strong></br>
Four customer clusters were identified with distinct patterns:</br>

 - Cluster 0: High usage frequency (8.15), moderate burned and subscribed counts, mixed gender (57% male).</br>

 - Cluster 1: Moderate usage (3.90), lower burned and subscribed counts, exclusively male.</br>

 - Cluster 2: Balanced usage (5.11), higher subscriptions, primarily located in Cairo, mixed gender (44% male).</br>

 - Cluster 3: Lower usage (4.15),  moderate burned and subscribed counts, exclusively female.</br>
</br>

 <strong> Segment Analysis </strong><br>
 
 <strong>Cluster 0: High-Engagement Customers </strong><br>
 
<b>Behavior:</b> High usage_frequency (8.15) and burned_count (4.00). High subscribed_count (4.15).

<b>Demographics:</b> 57% male and not from Cairo.

<b>Recommendations:</b> These customers are highly engaged and loyal. To maintain thier engagement offer loyalty rewards or exclusive discounts.

<br>


 <strong>Cluster 1: Low-Engagement Male Customers  </strong>
 
<b>Behavior:</b> Low usage_frequency (3.90) and burned_count (2.03). Low subscribed_count (1.87).

<b>Demographics:</b> 100% male. Not from Cairo.

<b>Recommendations:</b> These customers are less engaged but have potential for growth. Can offer bundled deals and personalized discounts to encourage more frequent purchases.
ALso, send reminders about unused coupons to increase redemption rates.
<br>

<br>

 <strong>Cluster 2: Cairo-Based Moderate Customers </strong><br>
 
<b>Behavior:</b> Moderate usage_frequency (5.11) and burned_count (2.35). Moderate subscribed_count (2.76).

<b>Demographics:</b>44% male and 100% from Cairo.

<b>Recommendations:</b> Offer location-based promotions, since these customers are location-specific. For example free shipping for Cairo residents.

<br>

 <strong>Cluster 3: Low-Engagement Female Customers </strong><br>
<b>Behavior:</b> Low usage_frequency (4.15) and burned_count (2.13). Low subscribed_count (2.01).

<b>Demographics:</b> 100% female. Not from Cairo.

<b>Recommendations:</b> have potential for growth but are less engaged. To increase engagement ffer gender-specific promotions. Could utilize email marketing to re-engage them with personalized offers.





<br>
<br>
 <strong>Recommendations for Coupon Campaigns </strong> <br>
 
 <br>
 
<strong>High-Engagement Customers (Cluster 0):</strong>

 - Focus on retention by offering loyalty rewards and exclusive discounts. To encourage repeat purchases with subscription-based offers.

<strong>Low-Engagement Male Customers (Cluster 1):</strong><br>

 - Use personalized discounts to increase engagement. For instance, send reminders about unused coupons to improve redemption rates.

<strong>Cairo-Based Moderate Customers (Cluster 2):</strong><br>

 - Utilize localized marketing campaigns to increase engagement. And offer location-based promotions (e.g., free shipping for Cairo).
   
<strong>Low-Engagement Female Customers (Cluster 3):</strong><br>

 - Offer gender-specific marketing campaigns and promotions to re-engage this specific segment.


<br>

<strong>Conclusion</strong>

<br>

<p>By segmenting customers into 4 clusters, we identified distinct groups with unique behaviors and demographics. These insights can be used to design targeted coupon campaigns that maximize customer loyalty and satisfaction. The Hierarchical Clustering model performed well in clustering the data into segments that then helped into analyzing the segments and delivering actionable insights.</p> 
