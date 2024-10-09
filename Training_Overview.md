# **Training Overview: Dope Thrifts Model**

## **Purpose**
This repository is designed to train and refine a model for generating product titles, descriptions, hashtags, and pricing for **Dopamine Thrifts**, an online thrift store specializing in secondhand clothing and accessories. The goal is to generate creative, trendy, and SEO-optimized outputs that align with the brand’s identity while meeting the needs of a fashion-forward, sustainability-conscious audience.

### **Scope**
This model will use predefined templates, logic tables, and picklists to ensure consistency and accuracy across product types, focusing on key areas:
- **SEO-optimized titles**: Titles will follow a structured format including key elements like [Notable Terms], [Brand], [Product Type], and [Size], optimized for search engines to increase visibility and discoverability.
  
- **Short descriptions**: Short descriptions will be engaging and concise, summarizing the product's key features and unique selling points within 2-3 sentences.

- **Fixed templates**: The combined total character count for the **short description** and **template** should not exceed **500 characters** to ensure brevity and clarity across all listings.

- **Hashtags**: Each product listing will include **5-8 hashtags**, focusing on niche trends and aesthetic-driven keywords like **#Balletcore**, **#Gorpcore**, and **#SustainableFashion** to increase discoverability.

- **Competitive potential pricing**: Pricing recommendations will be provided for each product based on factors like item condition, brand, and market trends. Predefined pricing templates will ensure fair and competitive pricing across all categories, aligning with current secondhand market standards.

---

## **Core Objectives**

1. **Consistency with Brand Voice**:
    - Dope Thrifts is a **Neurodivergent and Minority Woman Owned** brand that curates secondhand clothing and accessories with an emphasis on creativity and affordability. The model must generate content that accurately reflects the **unique features of each product**, while staying true to the brand’s overall identity.
    - The model will consistently reflect Dope Thrifts' tagline: *Experience the Dopamine Rush ⚡️ Discover Unique Threads*.
    - The tone should be modern, trendy, and conversational, avoiding excessive formal language and unnecessary gendered or binary language.

2. **SEO Optimization**:
    - Titles and descriptions must be optimized for search engines by incorporating core SEO keywords related to product categories, materials, and trending styles.
    - Hashtags should focus on driving discoverability and be relevant to both broad and niche audiences, particularly in secondhand and sustainable fashion spaces.

3. **Creativity and Flexibility (for Descriptions, Hashtags, and Pricing)**:
    - **Short Descriptions**: This section allows for creativity and flexibility. Descriptions should avoid repetitive, formulaic language, including **predictable selling structures** like the "feature-benefit formula" or overused phrases such as "perfect for any occasion" or "stand out from the crowd." 
    - The model will prioritize storytelling and use descriptive, engaging language to appeal to buyers, highlighting key features in a **creative yet informative** way. Each product description should feel unique and tailored, avoiding cliché structures that can feel impersonal or generic.
    - **Hashtags**: While there is a defined range of 5-8 hashtags per listing, the choice of hashtags allows flexibility based on trending styles and product features. The model should select creative, relevant hashtags to maximize discoverability.
    - **Pricing**: Price suggestions should reflect flexibility, accounting for factors like condition, brand, and market trends. The model should balance **competitive pricing** with the flexibility to adjust based on product-specific details and market shifts.

4. **Consistency and Streamlined Output (for Titles and Fixed Templates)**:
    - **Titles and Fixed Templates**: These sections require rigid adherence to predefined structures. The model must consistently follow the **title structures** and **fixed templates** to ensure uniformity across listings.
        - **Title Structure**: Follows a rigid format for SEO optimization and clarity, ensuring that each listing includes [Notable Terms], [Gender], [Brand], [Color], [Product Name], [Attributes], [Product Type], and [Size].
        - **Fixed Templates**: Ensure key product information is consistently included (e.g., material, brand, size) and that the total character count for short descriptions and templates does not exceed 500 characters.

---

### **Diverse Product Categories**

The model will handle a wide range of product categories, starting with clothing and accessories such as dresses, outerwear, and shoes. Templates are designed to adapt based on the type of product, ensuring that each listing includes the necessary and relevant details.

Key product attributes like **style**, **type**, and **sleeve length** will be pulled from **picklists** to maintain consistency across listings. Other details, such as **material**, **brand**, and **size**, will be entered based on the product’s specific information, without relying on picklists.

As the model is trained on the basics, we will gradually expand to include non-clothing categories, such as **housewares**, **toys**, and more. Templates will continue to ensure consistency, and that all pertinent information is included in each listing, no matter the product type.


5. **Scalability and Refinement**:
    - The model will be scalable, allowing for iterative refinements based on feedback and evolving trends in the market.
    - Regular feedback loops will be implemented, documenting changes to templates, picklists, and logic to improve accuracy and relevance over time.

---

## **Key Guidelines**

### **Title Generation:**
Titles will follow a predefined structure that ensures consistency and SEO compliance. The full structure includes elements such as:
- **[Notable Terms]**
- **[Gender]**
- **[Brand]**
- **[Color]**
- **[Product Name]**
- **[Attributes]**
- **[Product Type]**
- **[Size]**
- **[Style #]**

**Example**:  
*“Vintage Women’s Levi’s Blue High-Rise Straight Jeans Size 28 - A6895”*

This ensures that key elements for SEO are included in a clear and optimized format.

### **Short Descriptions:**
Short descriptions must be engaging, concise, and written in a trendy, conversational tone. Descriptions should highlight the product's unique features while maintaining an informal yet informative style.  
- The total character count for the **short description and fixed template combined** must not exceed **500 characters**.
  
**Avoid overused phrases and predictable structures**, such as the "feature-benefit formula" or vague phrases like "perfect mix of comfort and style." Descriptions should remain creative and avoid clichés to keep the listing fresh and appealing.

### **Fixed Templates:**
The **fixed template** will ensure that pertinent product information is consistently included across all listings, with essential product details like brand, type, and material being highlighted in a structured, clear manner. Combined with the short description, the total character count should not exceed **500 characters**.

### **Hashtags:**
Listings will include **5-8 hashtags** that align with current trends and product features. Hashtags must reflect niche styles such as **#Balletcore**, **#Cottagecore**, **#Y2K**, and other trending aesthetics, ensuring the product reaches both broad and niche audiences.

### **Competitive Pricing:**
Pricing suggestions will be provided based on the product's condition, brand, and current market trends. Templates for pricing will ensure that each item is fairly priced based on its value and demand.

**Example**:  
- **New With Tags (NWT)** items will be priced at **70-80%** of the original retail price.
- **Pre-owned items in excellent condition** will range from **50-60%** of the original retail price.

---

## **Feedback and Refinement Process**
- **Consistency Checks**: Each product description must pass a checklist for required fields, formatting, and SEO compliance. Common issues like overuse of generic phrases or redundancy will be corrected based on feedback.
- **Refinement Sessions**: All feedback will be documented, noting the changes made to templates and picklists after each session to ensure the model remains adaptable and improves over time.
