<a href="https://ongoingwarehouse.com">![Logo](https://ongoingwarehouse.com/images/logo/ongoing_logo_rgb_150.webp)</a>

# Ongoing Warehouse Goods Owner SOAP API example requests
[Ongoing WMS](https://ongoingwarehouse.com/) is a Warehouse Management System (WMS).

We provide several [Application Programming Interfaces (APIs)](https://developer.ongoingwarehouse.com/). One of them is [based on SOAP](https://developer.ongoingwarehouse.com/goods-owner-soap-api). In this repository, we provide examples of what the requests look like.

In the directory called ``Postman`` you will find a [Postman](https://www.postman.com/) collection containing the requests. Postman is a program which can make API requests. You can use it to test out APIs. Note that the collection uses [Postman variables](https://learning.postman.com/docs/sending-requests/managing-environments/), which you will have to modify to suit your particular case. You will also have to fill in the username and password for your API user.

These examples will show you how to:
* Create and update articles (including attaching files to articles).
* Create and update orders (including attaching files to orders).
* Create and update purchase orders.
* Create and update return orders.
* Read inventory adjustments.
* Read transporter contracts (shipping methods).

We also provide a [WSDL file](https://developer.ongoingwarehouse.com/Basics) for our API. This is a machine-readable specification of the API, which allows you to automatically generate client code for your own programming language.

## How to import the Postman collection
1. Clone this repository.
2. Import the collection file into Postman
    - For this we refer to the Postman documentation: [Importing Postman data](https://learning.postman.com/docs/getting-started/importing-and-exporting-data/#importing-postman-data)