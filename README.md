# E-commerce Back End

## Description
This is a back-end application for an e-commerce site.  It uses express and sequelize with a MySQL back-end.

### Usage
Run "node seeds/index.js" to seed the database.

Run "node server.js" to run the application.

There are 3 API endpoints.

- /api/categories
    - GET / to get all categories.
    - GET /:id to get category by ID.
    - POST / to add a new category.
    - PUT /:id to update a category.
    - DELETE /:id to delete a category.

- /api/products
    - GET / to get all products.
    - GET/:id to get a product by ID.
    - POST / to a add a product.
    - PUT /:id to update a product.
    - DELETE /:id to delete a product.

- /api/tags
    - GET / to get all tags.
    - GET/:id to get a tag by ID.
    - POST / to a add a tag.
    - PUT /:id to update a tag.
    - DELETE /:id to delete a tag.

Please visit this URL for a video walkthrough: https://watch.screencastify.com/v/O0D551RaHaJnVKRFkTzf