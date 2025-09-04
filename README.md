# Perfume Data Scraping & Analysis

This project was completed as part of the "Web Scraping and Social Media Scraping" course at the University of Warsaw. This project focuses on web scraping and data analysis in the domain of perfumes. The goal was to collect detailed product information from a UK-based cosmetics website (parfumdreams.co.uk) and prepare the dataset for further exploration of patterns in pricing, fragrance composition, and product characteristics.

# Data Source

Data was collected from the Women’s Fragrances section of the site. Individual product pages provided rich details, including: <br>

- Perfume name <br>
- Price by volume and discounts <br>
- Product images<br>
- Fragrance descriptions and notes (head, heart, base)<br>

# Legal Considerations

Before scraping, the site’s robots.txt and legal information were reviewed. Scraping factual, public product data (e.g., names, prices, fragrance notes) for non-commercial, academic purposes was found to be permissible. Use of copyrighted content such as images or detailed descriptions is excluded from this scope.

# Tools & Frameworks

Selenium – dynamic scraping, extended to ~90 products across four listing pages.

# Challenges

- Cookie Consent Shadow DOM – required accessing the shadow root to interact with hidden buttons.<br>
- Dynamic Elements – banners and optional fields appeared inconsistently across pages, requiring adaptive logic for XPath selection.

# Outcome

The project successfully produced a dataset of perfume products with detailed attributes, providing a strong basis for subsequent data analysis and visualization tasks.
