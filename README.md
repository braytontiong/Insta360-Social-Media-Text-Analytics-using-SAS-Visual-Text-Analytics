**Insta360 Social Media Text Analytics using SAS Visual Text Analytics**

***Project Overview***

This individual project was completed as part of INFS3830 Social Media Analytics at UNSW. The objective was to analyse customer discussions related to Insta360 products and transform unstructured social media data into actionable business insights. The analysis was conducted on a dataset containing 4,713 customer posts using SAS Visual Text Analytics.

***Project Scale***

This project involved a comprehensive 53-page analytical report examining 4,713 customer-generated Insta360 posts using SAS Visual Text Analytics. The project leveraged a wide range of SAS text analytics capabilities, including predefined concepts, topic discovery, custom concept development, custom category creation, term maps, linguistic rules, and sentiment-oriented topic analysis to transform large volumes of unstructured text into actionable business insights.

**Tools & Technologies**

* SAS Visual Text Analytics (Viya)
* Text Parsing
* Concepts Node
* Topics Node
* Categories Node
* Term Maps
* Custom Concept Rules (CLASSIFIER)
* Custom Concept Rules (REGEX)

***Key Findings***

**1. Product Discussions Dominated Customer Conversations**

Analysis using the predefined concept nlpNounGroup identified 3,717 posts (78.9% of the dataset) containing product-related discussions. The most frequently discussed topics included the Insta360 application, camera hardware, and SD card functionality, indicating that customers were primarily focused on product usability and performance.

**2. Battery and Recording Performance Were Major Pain Points**

Topic analysis identified a discussion cluster related to camera performance, battery life, and recording functionality.

* 685 posts were associated with this topic.
* 272 posts expressed negative sentiment, representing approximately 40% of discussions within the topic.

Customer complaints frequently referenced:

* Rapid battery drain
* Unexpected shutdowns
* Recording interruptions
* Reduced recording duration during use

These findings suggest that battery performance and recording reliability were key contributors to customer dissatisfaction.

**3. Video Experience Was the Most Discussed Product Feature**

A custom concept covering core product features identified 1,605 relevant posts, with the term “video” appearing 892 times across 638 posts, making it the most frequently discussed product feature.

Term map analysis further revealed strong co-occurrence relationships between:

* Video ↔ Edit
* Video ↔ Export

This indicated that users frequently encountered challenges during video editing and exporting workflows rather than only during recording itself.

**4. X-Series Cameras Generated Significant Customer Attention**

Using custom REGEX rules, the analysis identified 1,109 posts discussing Insta360 X-Series products.

Among all X-Series models:

* X3 was the most discussed product
* Mentioned 372 times across 297 posts

This finding highlights the importance of monitoring model-specific feedback to support future product development and marketing decisions.

**5. Customer Service Discussions Were Predominantly Positive**

A separate topic related to customer support and service interactions contained:

* 375 matched posts
* 291 positive posts

This represents approximately 78% positive sentiment, indicating that customer support was generally viewed favourably despite concerns surrounding product performance.

***Recommendations***

Based on the analysis, the following recommendations were proposed:

1. Improve **battery optimisation** and **recording stability** for **high-resolution** video modes.
2. Enhance application performance, particularly for v**ideo editing and export functionality**.
3. Provide **clearer battery-life expectations and performance benchmarks** under different recording conditions.
4. Monitor **X-Series product** discussions to identify model-specific issues and improve product development decisions.
5. Strengthen **warranty and after-sales support processes** to maintain customer satisfaction and brand reputation.

***Business Value***

This project demonstrates how text analytics can be used to analyse large volumes of customer-generated content, identify emerging product issues, uncover customer sentiment, and support data-driven decision making for product improvement and brand management.
