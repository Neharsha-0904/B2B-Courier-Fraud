# B2B Courier Fraud Detection Project 📦🔍

Welcome to the B2B Courier Fraud Detection Project! We are excited to introduce you to our initiative aimed at identifying and mitigating fraudulent activities in courier operations. This project focuses on analyzing various datasets to detect discrepancies and ensure accurate billing and operations.
## Project Objective 🎯

The goal of our project is to enhance the accuracy and transparency of courier operations by using advanced data analysis techniques. By scrutinizing various aspects of the courier system, we aim to identify fraudulent activities, such as overcharging and discrepancies in delivery zones.

## How We Approach the Project 🛠️

### 1. Data Collection 📊

We work with a comprehensive set of data related to courier operations. This data includes:

- **Order Report**: Details of all orders, including order numbers, SKUs, and quantities.
- **SKU Master**: Information about the weight of different SKUs.
- **Pincode Mapping**: Mapping of warehouse and customer pincodes to their respective zones
- **Courier Invoice**: Billing information from the courier company, including charged weights and billing amounts.
- **Courier Company Rates**: The rate cards for different zones and weight slabs.

### 2. Data Cleaning and Preparation 🧹

We start by cleaning and preparing the datasets to ensure consistency and accuracy. This involves removing unnecessary columns, handling missing values, and merging relevant data.

### 3. Merging Datasets 🔗

To create a comprehensive view, we merge the following datasets:
- **Order Report** with **SKU Master** based on SKU to get the weight of each order.
- **Order Report** with **Pincode Mapping** to get the delivery zone for each order.
- **Merged Data** with **Courier Invoice** to compare expected and actual charges.

### 4. Weight Calculation and Slab Determination ⚖️

We calculate the total weight of each order and determine the appropriate weight slab based on predefined rules.

### 5. Expected Charge Calculation 💸

Using the courier company rates, we calculate the expected charges for each order based on its weight slab and delivery zone.

### 6. Discrepancy Analysis 🔍

We compare the expected charges with the actual charges billed by the courier company to identify discrepancies. This helps in detecting potential overcharges or undercharges.

### 7. Summary and Insights 📈

We summarize our findings to provide insights into:
- Orders correctly charged.
- Orders overcharged.
- Orders undercharged.
- The total amount of discrepancies.

## What We Discover 🔍

Our analysis provides valuable insights into:
- **Billing Accuracy**: Identifying discrepancies between expected and actual charges.
- **Zone-Based Analysis**: Understanding if certain zones are more prone to discrepancies.
- **Weight Slab Analysis**: Evaluating if weight slabs are applied correctly.

## Next Steps 🚀

Based on our findings, we propose actions to mitigate fraudulent activities and improve billing accuracy. This may involve:
- Adjusting internal checks for weight and zone calculations.
- Negotiating with courier companies based on identified discrepancies
- Implementing automated fraud detection systems.

## Conclusion 🎉

The B2B Courier Fraud Detection Project is dedicated to enhancing the transparency and accuracy of courier operations. By leveraging data and analytics, we strive to ensure fair billing practices and improve operational efficiency.

Thank you for exploring our project. If you have any questions or would like more information, please feel free to ask!

---

Neharsha Vishnu Kanneganti
