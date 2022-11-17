# Risk_Manage
This a project to create a Risk Management Plan, Risk Assessment Plan, Risk Mitigation Plan, Business Impact Analysis, and Business Continuity Plan.

Scenario

You are an IT security intern working for Health Network, Inc. (Health Network), a fictitious health services 
organization headquartered in Minneapolis, Minnesota. Health Network has over 600 employees throughout the 
organization and generates $500 million USD in annual revenue. The company has two additional locations in 
Portland, Oregon and Arlington, Virginia, which support a mix of corporate operations. Each corporate facility is 
located near a co-location data center, where production systems are located and managed by third-party data 
center hosting vendors. 

Company Products

Health Network has three main products: HNetExchange, HNetPay, and HNetConnect.
HNetExchange is the primary source of revenue for the company. This service handles secure electronic medical 
messages that originate from its customers, such as large hospitals, which are then routed to receiving customers 
such as clinics.
HNetPay is a web portal used by many of the company’s HNetExchange customers to support the management of 
secure payments and billing. The HNetPay web portal, hosted at Health Network production sites, accepts various 
forms of payments and interacts with credit-card processing organizations.
HNetConnect is an online directory that lists doctors, clinics, and other medical facilities to allow Health Network 
customers to find the right type of care at the right locations. It contains doctors’ personal information, work 
addresses, medical certifications, and types of services that the doctors and clinics offer. Doctors are given 
credentials and can update the information in their profile.
Health Network customers, which are the hospitals and clinics, connect to all three of the company’s products 
using HTTPS connections. Doctors and potential patients can make payments and update their profiles using 
Internet-accessible HTTPS websites.

Information Technology Infrastructure Overview

Health Network operates in three production data centers that provide high availability across the company’s 
products. The data centers host about 1,000 production servers, and Health Network maintains 650 corporate 
laptops and company-issued mobile devices for its employees.

Threats Identified

Upon review of the current risk management plan, the following threats were identified:
Loss of company data due to hardware being removed from production systems,
Loss of company information on lost or stolen company-owned assets, such as mobile devices and laptops,
Loss of customers due to production outages caused by various events, such as natural disasters, change 
management, unstable software, and so on,
Internet threats due to company products being accessible on the Internet,
Insider threats,
Changes in regulatory landscape that may impact operations
