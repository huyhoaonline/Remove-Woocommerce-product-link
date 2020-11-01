# remove-product-in-link
<h2>Remove Woocommerce product link</h2>
Removing /product/, /product-category/, or /shop/ from the URLs is not advisable due to the way WordPress resolves its URLs. It uses the product-category (or any other text for that matter) base of an URL to detect that it is an URL leading to a product category.
 <br>
There are SEO plugins that allow you to remove this base, but that can lead to a number of problems with performance and duplicate URLs. <br>

For example: <br>

https://huyhoa.net/product/apple-iphone-12-pro/ (this is the URL of a standard page) <br>
https://huyhoa.net/product/iphone/apple-iphone-12-pro/ (this is the URL leading to a product category) <br>

What would happen if we remove that "product-category" part? <br>

https://huyhoa.net/apple-iphone-12-pro/ <br>
https://huyhoa.net/iphone/apple-iphone-12-pro/  <br>
<h2> How to Use </h2>
Just copy all of the code in file to buttom of your functions.php (inside theme directory)
Save and check it. <br> <br> <br>
Follow us to update at:  <br>
Oficial website: https://huyhoa.net  <br>
Find us on Facebook: https://www.facebook.com/huyhoaonline  <br>
Find us on Twitter: https://twitter.com/huyhoaonline  <br>
Find us on Pinterest: https://www.pinterest.com/huyhoaonline  <br>
Find us on Youtube: https://www.youtube.com/huyhoaonline  <br>