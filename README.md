## Frappe Healthcare

Open source & easy-to-use hospital information system(HIS) for all healthcare organisations.


### Introduction

Frappe Healthcare enables the Healthcare domain in ERPNext and has various features that will help healthcare practitioners, clinics and hospitals to leverage the power of Frappe and ERPNext. It is built on Frappe, a full-stack, meta-data driven, web framework, and integrates seamlessly with ERPNext, the most agile ERP software. Frappe Healthcare helps to manage healthcare workflows efficiently and most of the design is based on HL7 FHIR (Fast Health Interoperability Resources).


### Key Features

![Key Features](https://raw.githubusercontent.com/frappe/healthcare/develop/key-features.png)

Key feature sets include Patient management, Outpatient / Inpatient management, Clinical Procedures, Rehabilitation and Physiotherapy, Laboratory management etc. and supports configuring multiple Medical Code Standards. It allows mapping any Healthcare facility as Service Units and specialities as Medical Departments.

By integrating with ERPNext, features of ERPNext can also be utilized to manage Pharmacy and supplies, Purchases, Human Resources, Accounts and Finance, Asset Management, Quality etc. Along with authentication and role based access permissions, RESTfullness, extensibility, responsiveness and other goodies, the framework also allows setting up Website, payment integration and Patient portal.


### Installation

Using bench, [install ERPNext](https://github.com/frappe/bench#installation) as mentioned here.

Once ERPNext is installed, add healthcare app to your bench by running

```sh
$ bench get-app healthcare
```

After that, you can install healthcare app on required site by running

```sh
$ bench --site demo.com install-app healthcare
```


### Documentation

Complete documentation for Frappe Healthcare is available at https://docs.erpnext.com/docs/user/manual/en/healthcare


### License

GNU GPL V3. See [license.txt](https://github.com/frappe/healthcare/blob/develop/license.txt) for more information.


### Credits

Healthcare module is initially developed by Earthians. Currently, it is developed & maintained by Frappe Team and community contributors.
