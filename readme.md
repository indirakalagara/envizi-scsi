# Integration of Envizi and Supplychain Intelligent suite

## Usecase:

Envizi captures scope 1,scope 2 and scope 3 emissions and can calculate the spend-based emissions for scope 3. However, a more accurate methodology for Scope 3 Cat 1 emission is using the Product/SKU-based emissions from the supplier. The SCIS-Envizi addon helps achieve this, by engaging with the suppliers in IBM Supply Chain Intelligence Suite and procuring the  SKU-based emissions from the supplier.

## Pre-requisites 

### Envizi:
1. Define Organization hierarchy and locations in Envizi
2. Extract location and location reference

### SCIS :
1. Associate the Factor codes for the products purchased.


## Steps to Follow 

1. Prepare **Master data**
   1. Download the sample files
   2. Prepare master data files
   3. Upload the master data into SCIS

2. Prepare **Oder data**
   1. Prepare Orders and Orderlines
   2. Upload Order and Orderlines

3. Verify data uploaded from **Data Explorer**


4. Mark as Material - Identiy and **Prioritize the Suppliers / Products**

5. Engage with Supplier - **Request PCF for product**
   
6. Capture the PCF data from Suppliers
   1. Manual upload of PCF data
   2. Using Supplier Portal

7.  Explore the PCF requests received 
8.  Explore Data quality of PCF requests
9.  Verify the Emissions using Emission management
10. Export the Emission data to Envizi

## Step 1 : Prepare Master data

### Step 1.1 : Download the sample files

Download the sample files from the  [IBM Envizi Supply Chain Intelligence](https://www.ibm.com/docs/en/envizi-supply-chain?topic=configuring-sample-files) 

<img src="images/envizi-scis-samples.png">

### Step 1.2 : Prepare master data files

Fill in the data in the sample files uploaded in previous step. 
Refer to the [data dictionary](https://www.ibm.com/docs/en/SSULNGL/attachments/envizi_data_dictionary.xlsx.zip) for details on the data object and the field names.

### Step 1.3 : Upload the master data into SCIS

Login into the [IBM Supply Chain Intelligence suite](https://www.supply-chain.ibm.com/) using your IBM Id credentials.
Traverse to Control Tower -> Management -> Job Managament from the hamburger menu on the left side of the screen

<img src="images/ImportJob1.png">


<img src="images/ImportJob2.png">


<img src="images/ImportJob3.png">


<img src="images/ImportJob4.png">

### Step 1.4 : Prepare Orders and Orderlines

### Step 1.5 : Upload Order and Orderlines

## Step 2 : Prepare Oder data

### Step 2.1 : Prepare Orders and Orderlines
### Step 2.2 : Upload Order and Orderlines


## Step 3 : Verify data uploaded from **Data Explorer**

<img src="images/DataExplorer-Orgs.png">

<img src="images/DataExplorer-Locs.png">

<img src="images/DataExplorer-Products.png">

<img src="images/DataExplorer-Orders.png">

<img src="images/DataExplorer-OrderlInes.png">

## Step 4 : Identiy and Prioritize the Suppliers / Products
<img src="images/Supplier-engagement-materiality-1.png">


## Step 5 : Engage with Supplier - Request PCF for product

## Step 6 : Supplier provides the PCF form
### Step 6.1 : Manual upload of PCF data
### Step 6.2 : Using Supplier Portal

## Step 7 : Explore the PCF requests received 

## Step 8 : Explore Data quality of PCF requests
## Step 9 : Verify the Emissions using Emission management
## Step 10 : Export the Emission data to Envizi
