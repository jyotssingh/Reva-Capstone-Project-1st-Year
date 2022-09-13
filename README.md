# Reva-Capstone-Project-1st-Year
Capstone Project first year - Recommender system for suggesting “Frequently used together” SAP Fiori Apps for SAP S/4 HANA system

SAP S/4 HANA is SAP's ERP for large enterprises meant to cover all day-to-day processes of an enterprise (for example, order-to-cash, procure-to-pay, plan-to-product, and request-to-service) and core capabilities. It is a next-generation, intelligent ERP business suite and is the successor of SAP ERP designed specifically for SAP’s in-memory computing SAP HANA database.

SAP Fiori is a set of apps, that address the most broadly and frequently used SAP functions, such as workflow approvals, information lookups, and self-service tasks etc. They provide simple and easy-to-use user interface across desktops, tablets, and smartphones. SAP Fiori delivers an intuitive, role based UX that improves both employee productivity and satisfaction.

There are hundreds of SAP Fiori Apps in SAP S/4 HANA system, with simplified user interface supporting multiple device types. However, only few of them are getting actively used by Customers, as many of them are ignorant and unfamiliar with the full library of SAP Fiori Apps. Customers are unable to use these simplified and the award-winning user interface in the form of Fiori Apps, for most of their day to day activities, resulting in the difficult and slow adoption of S/4 HANA system.

Buyers at Amazon know this very prominent offer, after they have picked a product; a bundle of 2-3 products under the title “Frequently bought together” is showcased to buyers. Using this idea, I would like to drive the adoption of SAP Fiori apps among customers, because it is essential for the success of SAP S/4HANA, which is the most widely used product of SAP.
This project will take the usage statistics of SAP Fiori Apps from S/4 HANA on-premise and S/4 HANA Cloud customers. In addition, a mapping will be built for the relationship between Apps based on the Line of Business, Business Role, Industry, Application Area (all these attributes are available in the Fiori Apps library database). 
From the combination of the usage data and the relationship data, system will recommend the Best Bets for Apps that a customer is not yet using, but which are trending at other customers who use related apps. 
In this way we can provide a personalized recommendation of trending apps to the customer and the end-users.

In this project a User-Based collaborative filtering Recommender system will be built, using the data from both SAP Fiori Apps library and SAP EarlyWatch alert usage data. A relationship mapping i.e. an interaction matrix will be generated between the App usage by the customers and the Apps attributes like Line of Business, Business Role, Industry, Application Area. K-Nearest Neighbour and Neural Network Algorithms will be used to predict the utilities of Fiori Apps to Customers based on the interaction Matrix.

Customer’s landscape data also provide information about the SAP Fiori Apps list per system which are installed at Customer’s landscape but are not getting used. Using the information from the mapping tables, Customer’s usage data and the landscape data, a personalized recommendation of Trending Apps will be generated and proposed to customers based on their Business and Industry types.
