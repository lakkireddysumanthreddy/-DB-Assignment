1. Explain the relationship between the "Product" and "Product_Category" entities from the above diagram.

ANS:
the relationship between the "Product" and "Product_Category" entities is One to One Relationship, category_id and product_category both are same Id.

2.How could you ensure that each product in the "Product" table has a valid category assigned to it?

ANS:
enforce a foreign key constraint between the "Product" table and the "Category" table. This constraint will ensure that only category IDs that exist in the "Category" table can be assigned to products in the "Product" table.
