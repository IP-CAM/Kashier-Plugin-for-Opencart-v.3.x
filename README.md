# kashier-openCart-plugin

![](https://raw.githubusercontent.com/Kashier-payments/kashier-openCart-plugin/main/kashier-logo.png)
![](https://raw.githubusercontent.com/Kashier-payments/kashier-openCart-plugin/main/opencart-logo.png)



### Features

- Fully PCI DSS compliant as a Level 1 Service.

- IFrame Integration.

- 3D secure cards authentication support.

- Support acquiring multiple currencies "EGP, USD, GBP, EUR".

- Plug and play.

- Customize order state after success payment.

### Installation

- Download kashier-payments-1.0-unity.ocmod.zip https://github.com//Kashier-payments/kashier-openCart-plugin/raw/main/kashier-payments-1.0-unity.ocmod.zip
- Log into **OpenCart Webstore Admin**.
- Navigate to the **Admin Panel > Extensions > Extension installer**.

![](https://raw.githubusercontent.com/Kashier-payments/kashier-openCart-plugin/main/steps/Opencart_ex_installer_v3.png)

- Click the **Upload** button, then select the downloaded **zip** file (Step 1), then click the **Continue** button and wait for the process to complete.
- Navigate to **Extensions > Extensions**.
- On the Extensions page, select **Payments** from the dropdown and install the **Kashier Payments Getaway** extension.

![](https://raw.githubusercontent.com/Kashier-payments/kashier-openCart-plugin/main/steps/opencart_extn.png)

- After installation, proceed for configuration.


### Configuration

- Log into **OpenCart Webstore Admin**.
- Navigate to **Extensions** and then select **Extensions**.
- On the **Extensions** page, select **Payments** from the dropdown and then install the **Kashier Payments Getaway** extension.
- Save the configuration below.

![](https://raw.githubusercontent.com/Kashier-payments/kashier-openCart-plugin/main/steps/open_Cart_configuration.png)

- Save the configuration below.
   1. **Merchant ID** - Enter your Merchant ID provided by kashier
   2. **Test Mode**  test mode for testing and development
   3. **Test Api Key** - Enter your Merchant test Api Key provided by kashier
   4. **Live Api Key** - Enter your Merchant test Api Key provided by kashier
   5. **Order Success Status** - Order status that will set for Successful Payment
   6. **Order Failed Status** - Order status that will set for Failed Payment
   7. **Order Pending Status** - Order status that will set for Panding Payment
   8. **Status** - Keep this Enabled to accept payment through kashier
   9. **Sort Order** - Set ordering in the payment methods list

### Your kashier Payment Gateway is enabled. Now you can accept payment through kashier.
