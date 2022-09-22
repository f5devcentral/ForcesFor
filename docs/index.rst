Warsaw, Welcome to the ForceFor Lab Guide
=============================

Welcome
-------

.. warning:: Workshop under construction

Welcome to the |classbold| - |year|

|repoinfo|

The intention of the Lab Guide is to provide you with helpful content to run trough the Lab on your own pace.
The Lab Guide is not providing a step-by-step exercise as well cover the overall concept of the Lab as well as the path trough the Lab during our session.

A high level diagram for "OWASP Top 10 2021 Declarative AWAF policy lifecycle in CI/CD Pipeline" environment can be found below along with the technologies that are being used on this lab.

.. image:: ./sources/pictures/udf-lab.png
   :align: center

It covers:

* The 3 main WAAP use cases ``(Class 1)``
  
  * Application exposed on internet and protected by F5XC Global Network (RE only)
  * Application not exposed on internet and only available in a private zone (VPC, VNET, internal VLAN ...) and protected by F5XC Global Network (RE + CE)
  * Application not exposed on internet and protected by F5XS instance in a private zone (CE only)

* How to apply and create a Positive Security policy with F5XC WAAP ``(Class 2)``
* F5XC Shape Bot Protection ``(Class 2)``

* A dedidacted workshop for Modern App Specialists ``(Class 3)``

.. toctree::
   :maxdepth: 3
   :caption: Contents:
   :glob:

   class*/class*
