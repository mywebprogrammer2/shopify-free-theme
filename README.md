# Clothing Store Theme
# Link to live theme is given below:
[https://varyingstore.myshopify.com/](https://varyingstore.myshopify.com/) Password to view live theme: password
# What I did in this:
Introducing a comprehensive clothing store template designed specifically to showcase collections and categories. With this template, you can effortlessly present your clothing products in an organized and visually appealing manner.
The template offers built-in features for creating and highlighting different collections of clothing items. Whether you have seasonal collections, specific themes, or curated selections, this template allows you to showcase them effectively. Each collection can have its own dedicated section, allowing users to browse through the items seamlessly.
Whether you're launching a new clothing brand, an online boutique, or simply want to showcase your fashion creations, this template serves as an ideal starting point. It offers a solid foundation for presenting your clothing store in a user-friendly and visually appealing manner, ensuring a seamless experience for your customers.
# How to use
To use this repository for making Shopify themes, use the following command of Shopify CLI.

`shopify theme init [ NAME OF YOUR THEME ] --clone-url https://github.com/url/to/store/repository`

`shopify login --store [ link to your store ]`

`shopify theme serve`

If you don't have Shopify CLI installed to your computer, navigate to the [installation page of Shopify CLI](https://shopify.dev/themes/tools/cli/installation).

## How to setup

After 'shopify theme serve' open customizer link provided by shopify CLI also the preview link for preview

OR

After installing theme and publishing it to the store , Goto -> Online Store -> Themes and select Customize. There you would have sections:

1.  Head Section (for adding logo)
2.  Head Section (for favicon logo)

To chane the theme colors and schemes, Goto -> Online Store -> Themes and click three dots next to customize, select Edit Code

On the left panel, scroll down to assets folder, and there you would find timber.scss.liquid.
You can find all the classes to modify there

Add liquid pages under templates for categories, you would find more categories pages eg:  page.shirts.liquid, 
Just replicate these pages and replace your category
Add page in the pages from store, and link the page you created.
Create Collection and add products from store
In Navigation under online store, under Shop category, add your clothing category, and link it to the collection.

# Screenshots
![Home Page](https://i.ibb.co/Gdj9pWv/Teststore-home.png)

![Product Detail Page](https://i.ibb.co/19582vH/product-detail.png)

![Cart Page](https://i.ibb.co/jhRdqT1/cart-page.png)

![Checkout Page](https://i.ibb.co/vZKWvH2/Information-Teststore-Checkout.png)

# That would be it :)
