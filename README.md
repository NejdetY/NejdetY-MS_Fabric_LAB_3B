# NejdetY-MS_Fabric_LAB_3B
# Medallion Architecture in Microsoft Fabric Lakehouse

This repository contains the lab files and instructions for implementing a Medallion Architecture in a Microsoft Fabric Lakehouse. The exercise guides you through creating a workspace, setting up a lakehouse, and building bronze, silver, and gold layers for data transformation.

## **Exercise Overview**
- **Workspace Setup**: Create a Fabric workspace with trial capacity.
- **Lakehouse Creation**: Build a lakehouse and upload raw data to the bronze layer.
- **Data Transformation**: Use PySpark notebooks to clean and transform data into silver Delta tables.
- **Star Schema Modeling**: Create dimension and fact tables in the gold layer.
- **Semantic Model**: Generate a Power BI semantic model for analytics.

## **Files Included**
- `orders.zip` - Sample sales data (2019-2021) for the bronze layer.
- Notebook scripts for transforming data from bronze → silver → gold.

## **Step-by-Step Instructions**
Follow the detailed guide in the [Lab Instructions](#) or check out the [LinkedIn Post](https://www.linkedin.com/posts/...) for a summary.

## **Prerequisites**
- Microsoft Fabric trial license.
- Basic knowledge of PySpark/SQL.

## **How to Use**
1. Download the dataset (`orders.zip`) and extract the CSV files.
2. Upload files to the bronze layer in Fabric.
3. Run the provided notebooks to process data into silver and gold layers.

## **Results**
- **Bronze**: Raw CSV files.
- **Silver**: Cleaned Delta tables with validation columns.
- **Gold**: Star schema (dimensions + facts) optimized for reporting.
