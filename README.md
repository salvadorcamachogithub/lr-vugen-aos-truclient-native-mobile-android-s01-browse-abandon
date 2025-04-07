Updated: 04.2025  
Script created by Salvador Camacho

This script Access Key needs to be updated before using it, use your own key, you might need to update the deviceID with a more current Android device ID

This script was created with best practices, so it is more resilient, such as:
* Transaction naming
* No add cookies
* No third party
* One validation per transaction
* Think times at the end of each transaction to better simulate user behavior
* deviceID parametrized

This script goes to the Laptops category, goes to a product, adds it to the cart and then goes back to Home, there is an iOS script that does the same exact steps

Runtime Settings were set to log only on errors and generate snapshot on errors, think times set to random from 15 seconds to 25 seconds

This script has 4 transactions:  
AOS-TruClient Native Mobile Android-S01-01 Laptops  
AOS-TruClient Native Mobile Android-S01-02 Product  
AOS-TruClient Native Mobile Android-S01-03 Add To Cart  
AOS-TruClient Native Mobile Android-S01-04 Home