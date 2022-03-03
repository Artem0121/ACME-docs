Welcome to ACME's documentation!
================================

ACME Corp provides its customers with a solution to build up and manage master data.
The essence of the solution is in using machine learning techniques for building a
Customer’s data taxonomy / data map from the inter-service calls, providing a Customer
with relevant hints as to which services act as actual master data sources, what information
should be included in the combined ‘golden’ record if there are several services involved,
and so on.

The ACME solution can act both as an inter-service traffic monitor and a data map
constructor and as a master data controller, providing golden records with verified and
cleaned data to all services of the Customer. ACME Corp hopes that the intelligence which is
built into the solution will eliminate the need for any manual configuration, and the
Customers will be able to solve the master / reference data management issues once and
for all.

There are two parts to the solution: one is a special component which is deployed by the
customer themselves (:doc:`ACME-oPS`), another is a cloud control center (:doc:`ACME-CS`), i.e. a service which is managed by
the ACME Corp.

Contents
--------

.. toctree::

   getting-started
   ACME-oPS
   ACME-CS