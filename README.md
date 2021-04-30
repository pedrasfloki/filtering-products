
### filtering-products

- filtering-products is a django project that i built using Django, django-filter and bootstrap
- it allow users to filter products based on products.models.Product attributes (title, product_type, height, width and price)
- based on this [json file](https://github.com/wedeploy-examples/supermarket-web-example/blob/master/products.json), i created script.py to add some initial products to the database, i just have to open the shell and run the script:
    python manage.py shell
    from products import script
    script.create_products()


![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
