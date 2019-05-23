EO Spot Task
============

.. contents:: Table of Contents


This is the main form used to collect data regarding the Risk Education Activity in Syria.

form_version
------------

General Information
-------------------

id_eo_sy
^^^^^^^^
.. bibliographic fields (which also require a transform):

This is the main report ID, each field report must be assigned a special report identification that is unique and can help distinguish reports by organizations. This will be assigned by UNMAS to each report received.

+------------------------+-------------------------------------------------------------------------------------+
| Type                   | Text                                                                                |
+------------------------+-------------------------------------------------------------------------------------+
| Calculation            | ``${organsiation ID} + '-RO-' + format-date(${start_date},'%Y%m%d-%H%M')``          |
+------------------------+-------------------------------------------------------------------------------------+
| Mandatory              | **Yes**                                                                             |
+------------------------+-------------------------------------------------------------------------------------+
| Unique                 | **Yes**                                                                             |
+------------------------+-------------------------------------------------------------------------------------+
| Hidden                 |                                                                                     |
+------------------------+-------------------------------------------------------------------------------------+
| Suggested Text         | ``Report ID``                                                                       |
+------------------------+-------------------------------------------------------------------------------------+
| Arabic Label           | ``رقم التقرير``                                                                     |
+------------------------+-------------------------------------------------------------------------------------+
