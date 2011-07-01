Order Tickets, a Magento extension
==================================

This Magento extension add a system of tickets into orders.
It helps then to improve communication between customers and after-sale service.

## Features
 * Customers can add message to their orders
 * Administrators can reply to these message in BO
 * Administrators can change status of a chat
 * Different message can be seen in BO in a global grid, into orders and into
    customer account
 * Email notification send to administrator about new tickets posted by customers

## Installation
1. Install extension through Magento downloader or with pear. Extension can be 
found on [Magento Connect Order Tickets page][1].
2. For receiving automatically email about new tickets set correct email 
recipients in BO System > Configuration > Sales > Orders tickets
3. You can also change frequency for receiving this emails by changing cron
expression at the same place.
By default emails are send every day at 2:42 and 14:42  
[More about cron expression][2]

## More informations
Check [Magento Connect Order Tickets page][1] for more details.

## License
Order tickets extension is licensed under AFL 3.0 license.

[1]: http://www.magentocommerce.com/magento-connect/laurent35240/extension/7107/order_tickets
[2]: http://en.wikipedia.org/wiki/Cron#CRON_expression