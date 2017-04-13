# WP Simple Pay Lite for Stripe (add post-purchase download link)

Original Plugin: https://en-au.wordpress.org/plugins/stripe/  
Author Website: https://wpsimplepay.com/  


## Background
This is an excellent plugin, very simple and fulfils all my needs, except  
I need to be able to provide some post purchase instructions which should  
only be available to those who have completed a purchase.  

Made some simple modifcations to allow user to enter some associated information  
e.g. download link which refereces the 'description' used in the shortcode.

## File Changes  

Added an extra text area to save details in views/admin-shared-tab-default.php  
Added extra line on post-puchase screen classes/class-stripe-checkout-shared-functions.php  