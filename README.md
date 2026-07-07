# My Affiliate Product Website

A premium, lightweight, and SEO-optimized static website for displaying affiliate products.

## 🚀 How to Add New Products
To add a product, open `index.html` and look for the block starting with `<!-- START PRODUCT BLOCK -->`.

1. **Copy** the entire block from `<!-- START PRODUCT BLOCK -->` to `<!-- END PRODUCT BLOCK -->`.
2. **Paste** it directly below the previous product.
3. **Change the details**:
    - `data-title`: Set this for search functionality.
    - `<img> src`: Replace with your product image URL.
    - `<h2 class="product-title">`: Change the name.
    - `<p class="product-desc">`: Change the description.
    - `<div class="product-price">`: Update or remove the price.
    - `<a> href`: Paste your affiliate link.

## 🔗 Adding Unlimited Buttons
Inside any product block, look for the `<div class="button-group">`. You can add as many links as you want:
```html
<a href="YOUR_LINK" target="_blank" rel="noopener noreferrer nofollow" class="btn btn-official">MY BUTTON TEXT</a>
