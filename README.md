# external-shopify-link

Shopify --> External Link --> Change "Buy Now" Button

How to add an external link on a buy now button and remove add to cart button

STEP 1 Add and install the Simple Admin app to your Shopify store.

STEP 2 Once installed, go to your Apps section and click on Simple Admin to go to its dashboard.

STEP 3 Click on PRODUCTS over in the top right corner.

STEP 4 Choose the product you want add the Buy Now External Link button too, and click the ID number of that product.

STEP 5 Click on the META tab.

STEP 6 Click ADD METAFIELD.

STEP 7 Enter the following information: KEY: BuyNowText VALUE: BUY NOW on Amazon.com VALUE TYPE: String NAMESPACE: CustomExternalLink DESCRIPTION: The value is the text the customer will see on the button. Click SAVE.

STEP 8 Click ADD METAFIELD again.

STEP 9 Enter the following information: KEY: BuyNowLink VALUE: https://anydomain.com/some/link/to/product VALUE TYPE: String NAMESPACE: CustomExternalLink DESCRIPTION: Enter external link in the value field. To disable external link, enter the word “none” (without quotes) in the value field. Click SAVE.

STEP 10 Now go to ONLINE STORE then THEMES then click on ACTIONS for your current theme and choose EDIT CODE. NOTE: I am using the free SIMPLE theme.

STEP 11 Locate the SECTIONS / PRODUCT-TEMPLATE.LIQUID file and click on it so the file opens up in the editor. NOTE: The following code that I am going to modify is specific to the SIMPLE theme and is located in the SECTIONS / PRODUCT-TEMPLATE.LIQUID file. The code you are looking for may be slightly different if you are using a different theme, and may also be located in a different file. Another file to check for the code would be the TEMPLATES / PRODUCT.LIQUID file.

STEP 12

Look for the following code:
