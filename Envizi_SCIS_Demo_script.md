

**Steps:**

**Envizi: (Procurement Officer)**

1. On Envizi UI , navigate to organization hierarchy to show the OrgX Organiztaion structure. The Organization has various business operations like consultion services, IT operations and also Manufacturing plants.

< Explain various emissios w.r.t different business operations and untis> 

2. Navigate to Manufacturing plants and show OrgX manufacturing unit - "OrgX France - Puteaux Plant Ops" , The manufacturing untis deals with different suppliers to procure raw materials  like chemicals, etc or products from different suppliers.  The Organizations need to capture the emissions related to these procured items as part of their Scope 3 Category 1 Purchased Goods & Services emissions. 
   
3.  Now, lets see how SCIS would help organization to identify which are the products / suppliers impacting their scope 3 cat1 emissions and how the organization engages with Suppliers to capture the more accurate carbon emissions for each of these raw material / products and which in turn help them to reduce the emissions.  

**SCIS: (Procurement Officer)**

4. Click on Supply chain intelligent suite on Envizi home page -> Quick links

5. Navigate to Control Tower -> Data Explorer.  This page shows various tabs relates to Locations, Organizations, Orderlines , Orders and Products. 
   < Explain each of this tab in the context >
   
6. Navigate to Control Tower -> Supplier Engagement.  
7. On Materiality tab -> scroll down  to look at who are the Top 50 Suppliers in terms of Spend as well as Top 50 Product Categories in terms of Spend
8. Now the Organiztaion can identify which products / suppliers they would like to engage with to capture the emission details and prioritize accordingly. To do that, click on product category / supplier. 
9. On <Product category / Supplier > sustainability and compliance details page, navigate to section to view  "Top un-prioritized products"
10. Click on "Mark as material" button to prioritize the Product Category / Supplier 
11. Once marked as material, the corresponding products of product cateogry / supplier will move to "Prioritized products" section
12. From the list of "Prioritized products", chose a porduct and click on "Send Request" 
    
13.  "Product category sustainability and compliance details" page would be open for the chosen product.  < Explain the page>
14.  Scroll down to "Resolutions" section and Click on "Request PCF data from Supplier"
15.  On Request PCF data using the supplier portal , view product details as well as the contact details of the supplier to whom this request would be send. 
16.  Once verified, Click on "Send PCF Requests".  You can also click on "Preview email" before sending the PCF request. 
17. Naviage to  *Control Tower -> Supplier Engagement -> Engagement* tab and   look at the status against the supplier for the product which PCF request raised under the section "Supplier PCF requests"

**SCIS: Supplier Portal : (Supplier)**

18. The Supplier (X) receives an email about the PCF request  along with link to login into the Supplier Portal. The supplier clicks on the link.
19. Now, the supplier would login to the Portal and view the requests for PCF data from the Buyer Organization. 
20. Supplier chose the product for which they want to submit the PCF data and click on the "Complete Form" button
21. On "Product carbon footprint (PCF) request - Productxx " , Supplier enter the details related to Emissions like * Product carbon footprint (kgCO2e)* , specific *Calcuation method* used to derive the PCF as well as details like the validation period of the PCF data along with other details like Primary data share percent, Third party verified , etc. 

**SCIS: (Procurement Officer)**

23. Once the PCF data has submitted by the Supplier, the data will be reflected in SCIS dashboard. Naviate to Control Tower -> Supplier Engagement -> Engagement tab
24. View the Status of the PCF request against the suppliers. 
25. Chose the Supplier and click
26. On <Supplier> sustainability and compliance details page click on the "Date" under the "Received" to view the PCF data shared by the supplier for a given product under "Prioritized Products"
    
**SCIS: Emissions Management**

27.  Navigate to  *Control Tower -> Emission Management -> Emissions*
28.  This page provide different views  of Top emissions contributors with respect to Suppliers / Product Categories / Locations, etc for a given time period. The Procurement officer can also identify what % of  the emissions are calculated using PCF method vs Spend based (which is less accurate method)
Notice the emission by Factor type, The intent is to engage with suppliers more to reduce the spendFactor-based emissions and increase the supplier emissions

    
**SCIS: Export to Envizi for Emission Consolidation:** 

29.   On   *Control Tower -> Emission Management -> Summary* tab, the user can select a month to view the emissions corresponding to the particular location (location mapped ). The pages displays  emissions calculated using the PCF method and also the Spend based method for the product where PCF data is not available.  
30.   The user can click on *Export * button to send the data back to *Envizi*  This emissions data from SCIS will be placed in the AWS S3 folder provided by Envizi which is pre-configured for this demo. 


**Envizi: (Procurement Officer)**

31. On Envizi UI , navigate to organization hierarchy -> Manufacturing plant of OrgX and drill down to the location which is mapped with the SCIS location. 
32. The emissions related to this locations are aggregated in different accounts like Spend-based_xxx and Supplier-specific_xxx which are coming from the SCIS system. 


    

   
