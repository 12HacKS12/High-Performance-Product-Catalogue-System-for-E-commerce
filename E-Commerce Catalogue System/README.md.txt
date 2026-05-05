Project Description:

Title: High-Performance Product Catalogue System for E-commerce

Overview:
This project focuses on resolving the technical challenges faced by large-scale e-commerce systems—specifically, the need to balance rapid product sorting (e.g., by price or rating) with real-time searchability across extensive catalogues containing 100,000 or more items.

Core Technologies and Algorithms:
The project is implemented in Python and leverages a "hybrid system" approach by utilizing two main data structures/algorithms:

Merge Sort:
Purpose: Used to effectively sort large product inventories based on user-defined attributes like alphabetical order, price, or rating.
Why it was chosen: It offers a stable and consistent time complexity of 
 across best, average, and worst-case scenarios. Its divide-and-conquer methodology ensures dependable performance without lagging during high-demand operations.

Hash Tables (Python Dictionaries):
Purpose: Used for near-instant retrieval of product information using unique identifiers like Product IDs or Stock Keeping Units (SKUs).
Why it was chosen: It provides an average-case lookup time complexity of 
, which is optimal for user-initiated direct searches.

System Performance & Testing:
The system was comprehensively tested using Python scripts mimicking real operational processes. It was proven capable of handling small datasets (5–50 items) as well as large-scale datasets (100,000 items). Batch searches of 10,000 products and combined sorting/searching tasks were executed efficiently in fractions of a second.