# User Guide - MO Receipt

<img src="../../../images/banner-mobilefirst-cloudsuite.jpg" alt="banner" style="zoom:100%;" />



# Table of contents

- **[About this guide](#about-this-guide)**
  - [Intended Audience](#intended-audience)
    - [MO Receipt standard functionality](#std-func)
- **[Workflow, Screen Layouts & API Logic](#wrk)**
  
  - [Settings](#settings)
  - [Item Entry](#itno)
  - [Reporting Receipt](#submit-scr)
  
- **[M3 sample workflow](#m3sample)**

  - [Create customer order PMS001](#crt-pms)

  

# <a name="about-this-guide"></a>About this guide

### <a name="intended-audience"></a>Intended Audience

MobileFirst Configuration User Guide provides guidance for LeanSwift customers and consultants regarding understanding the basic concept, functionality and configuration of the MO Receipt Standard App. Further information about MobileFirst standard applications can be found at [www.inform3marketplace.com](http://www.inform3marketplace.com).

#### **<a name="std-func"></a>MO Receipt standard functionality**

The intended use of this app is for a user to be reporting receipts against Manufacturing orders (MOs) with a trimmed down way to quickly and easily report quantity produced.

Using PO Receipt module in MobileFirst Orders can be searched by providing order number and product number. They can also input only product number and list all orders containing the product and choose from the list.The receipt report can be done by tapping the orders in the list and on selecting valid location and manufactured quantity that order can be reported using slide to confirm at the end.



# **<a name="wrk"></a>Workflow, Screen Layouts & API Logic**

### <a name="settings"></a>Settings

​		Initially, the MO Receipt module settings can be opened to choose the warehouse and facility.

<img src="../images/MORE/1.gif" style="zoom:100%;" />



### <a name="itno"></a>Item Entry #

Item Number and Order Number can be entered or scanned from the inbuilt camera.

<img src="../images/MORE/2.gif" style="zoom:100%;" />

Entered details will be validated against M3 services.

### <a name="submit-scr"></a>Reporting Receipt

On successful retrieval of head info data for the item number. Users can select an order and can be reported.

After selecting a line item in the order. Enter the location and manufactured quantity.

All the entered details will be validated and if the data were valid the slider will be shown. On slide to confirm the order receipt will be reported.

<img src="../images/MORE/3.gif" style="zoom:100%;" />

# <a name="m3sample"></a>M3 Sample Flow

This section describes the MO Receipt workflow in M3 to create the purchase order. The current warehouse and facility selection can be made using the search icon on the top right corner of the screen.

### <a name="crt-pms"></a>Create customer order PMS001

- Manufacture order can be created in PMS001.
- Enter Product, Product structure type.
- Product and its details will be defined in MMS001.
- On clicking [+] the order will be created this order can be viewed in PMS100 sort the list based on 70-Res/Prod/MO to see the orders.

The Product number with the manufacturing order can be searched in MO Receipt module and the receipt can be reported.