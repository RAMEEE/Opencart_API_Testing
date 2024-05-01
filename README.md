OpenCart is free open source e-commerce platform for online merchants.
API
For using OpenCart API you should enable it previously, via admin part of you're site.
Go to System->Users->API and you'll see a predefined user named "Default".
Edit it - and the are no API-key so generate it, by pressing the button and set "Status" to enable.
Next, add you'r IP to list of permitted for API access on another tab.

API is available via URL like

https://myopencart.example.com/index.php?route=api/cart/add
where route is using choose appropriate controller.
