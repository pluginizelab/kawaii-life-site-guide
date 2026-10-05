[Kawaii Life Site Owner's Guide](../README.md) › 7. Products

# 7. Products

**Where:** **Products → All Products**

![The product list](../images/products-list.png)

## 7.1 Adding or editing a product

1. Click **Add new product**, or hover over a product and click **Edit**.
2. Type the **product name** at the top and the **description** in the big box under it.
3. Fill in the **Product data** box (below the description):
   - **General**: the **Regular price** and, for a sale, the **Sale price**.
   - **Inventory**: the **SKU** (needed for barcode labels) and stock.
   - **Shipping**: weight and size, if you use them.
   - **Linked Products**: see [7.5](#75-you-may-also-like-and-complete-your-set).
   - **Attributes** and **Variations**: for sizes or colours (see [7.4](#74-products-with-colours-sizes-or-styles)).
   - **Product page**: Kawaii Life's own tab (see [7.3](#73-the-product-page-tab-taglines-video-shipping-and-returns-text)).
   - **Product Badges**: the NEW and BESTSELLER badges for this product (see [7.7](#77-new-and-bestseller-badges)).
4. On the right:
   - **Product categories**: tick its category.
   - **Friends**: tick the character(s), if it's a character product.
   - **Product image**: the main photo. **Product gallery**: extra photos.
5. Click **Publish** (or **Update**).

![The product edit screen](../images/product-edit.png)

![The right-hand column: categories, Friends, image and gallery](../images/product-sidebar.png)

💡 **Product images.** Every product image on the site is a square picture with a cute 3D emoji on a soft gradient. Use square images, at least 800 × 800 pixels, to keep the shop consistent.

## 7.2 What shoppers see

![A product page](../images/fe-product.png)

The product page brings together the gallery, price, the taglines, the colour or style choices, **Add to Cart** and **Buy It Now**, the expected delivery date, any **Offers for you**, the Description, Specification, Shipping, Returns and Reviews tabs, a video and **You May Also Like**.

<img src="../images/fe-product-full.png" alt="The full product page" width="420">

## 7.3 The Product page tab (taglines, video, shipping and returns text)

![The Product page tab in the Product data box](../images/product-page-tab.png)

- **Tagline**: short phrases shown under the product name, joined with a dot: "Ultra-Soft • Huggable Fit • Hypoallergenic". Click **Add phrase** for another one. Empty boxes are ignored.
- **Shipping tab** / **Returns tab**: text for this product only. Leave them empty to use the shop's text from **Theme Options → Product page**.
- **Video**: shown as "Watch it in action". Click **Choose from library** to use an uploaded video, or paste a YouTube, Vimeo or .mp4 link.
- **Video poster**: the picture shown before the video plays.

## 7.4 Products with colours, sizes or styles

A product that comes in several options is a **Variable product**:

1. In **Product data**, change the drop-down at the top from *Simple product* to **Variable product**.
2. In **Attributes**, add an attribute (for example *Color*), pick its values and tick **Used for variations**. Click **Save attributes**.
3. In **Variations**, click **Generate variations**, then open each variation to set its price, stock and picture.

![The Variations tab](../images/product-variations.png)

💡 Shoppers pick options from round colour dots or small image tabs instead of plain drop-downs. To set this up, see [8.3 Attributes](08-categories-friends-attributes.md#83-attributes-colour-dots-and-image-swatches).

## 7.5 "You may also like" and "Complete your set"

![The Linked Products tab](../images/product-linked.png)

- **Cross-sells**: products shown in the cart drawer's **You may also like** row and under **You will love these** on the cart page when this product is in the cart. Use this for "complete your set".
- **Upsells**: WooCommerce's own "you may also like" suggestions.

The cart drawer fills any free spots with matching products by itself. It never suggests something already in the cart or out of stock.

![The cart drawer with the "You may also like" row](../images/fe-minicart.png)

## 7.6 Reviews

**Where:** **Products → Reviews**

![The product reviews list](../images/reviews.png)

Customers can give a review a title and attach one photo or video. Reviews with a photo or video wait for you here:

- Hover over a review and click **Approve** to publish it, **Spam** or **Trash** to remove it.
- The **Photo / video** column shows what they attached. Check it before approving.

## 7.7 NEW and BESTSELLER badges

New products get a **NEW** badge and well-selling products a **BESTSELLER** badge by themselves. You set how long and how many in **Theme Options → Shop page** ([2.2](02-theme-options.md#22-shop-page)).

**To change one product's badges:**

1. Edit the product.
2. In **Product data**, click the **Product Badges** tab.
3. **NEW badge**: choose **Always show** or **Never show (disable)**. Keep **Automatic** to let the shop decide.
4. Tick **Disable Bestseller** to never show the BESTSELLER badge on this product.
5. Click **Update**.

![The Product Badges tab](../images/product-badges-tab.png)

## 7.8 Gift boxes (bundles)

A gift box, such as the **Kawaii Girl Box**, is one product made of several others. Its page lists everything inside it.

**To make a new gift box:**

1. Click **Add new product** and add its name, description and pictures as usual.
2. In **Product data**, change the drop-down at the top to **Smart bundle**.
3. In the **Bundled Products** tab, search for each product to put in the box and set how many.
4. To set your own price, tick **Disable auto calculate price.** and type the price in the **General** tab. Otherwise the box costs its items added up.
5. Click **Publish**.

![The Bundled Products tab of a gift box](../images/product-bundle-tab.png)

![A gift box on the site](../images/fe-bundle.png)

---

← [6. The home page](06-home-page.md) · [Contents](../README.md) · [8. Categories, Friends and attributes](08-categories-friends-attributes.md) →
