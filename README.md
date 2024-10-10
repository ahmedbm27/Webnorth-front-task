# Dawn  Webnorth Front Task
# Shopify Custom Theme with Product Grid Section

This repository contains a Shopify theme that includes a customizable product List section. The section allows merchants to display products from specific collection, style the product cards, and manage the layout easily within the Shopify theme editor.

## Table of Contents
1. [Prerequisites](#prerequisites)
2. [Installation and Setup](#installation-and-setup)
3. [Local Development](#local-development)
4. [Importing Test Products with CSV](#importing-test-products-with-csv)


## Prerequisites

Before you begin, make sure you have the following software installed on your machine:

- [Node.js](https://nodejs.org/en/download/package-manager) (18.20+, 20.10 or higher)
- [Shopify CLI](https://shopify.dev/docs/api/shopify-cli) (Command Line Interface)
- A Shopify Partner account with a development store

## Installation and Setup
### install the Shopify CLI :

```bash
npm install -g @shopify/cli@latest
```
### Clone the Repository:

```bash
git clone https://github.com/ahmedbm27/Webnorth-front-task
cd Webnorth-front-task
```
### Start a local development server: [docs](https://shopify.dev/docs/storefronts/themes/getting-started/create)
```bash
shopify theme dev -s={store-name}
```
## Importing Test Products with CSV

To test the custom product grid section, you can import products into your Shopify store using a CSV file. We've provided a sample CSV file to help you get started.

### Download the CSV File

- [Click here to download the CSV file of test products](https://drive.google.com/file/d/1TZgd7y59RXpNTby1LYzUbe_KER1kcjo-/view?usp=drive_link)

Follow these steps to upload the CSV file to your Shopify store:
1. **Access the Shopify Admin Panel:**
   - Log in to your Shopify admin.
   - Navigate to **Products** from the left sidebar.

2. **Import Products:**
   - Click on the **Import** button located at the top of the Products page.
   - In the import dialog, click on **Add file** and select the CSV file containing your product data.

3. **File Format:**
   - Make sure that your CSV file is formatted according to Shopify's product CSV format. You can find the requirements for the CSV format in the [Shopify Product CSV guide](https://help.shopify.com/en/manual/products/import-export/using-csv).
   - Ensure that all necessary fields like `Title`, `Handle`, `Price`, `SKU`, and `Inventory` are correctly filled in.