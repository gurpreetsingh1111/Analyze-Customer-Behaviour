# Analyze-Customer-Behaviour
## About Dataset:https://www.kaggle.com/datasets/iamprateek/store-transaction-data/data
## Kaggle NoteBook:https://www.kaggle.com/code/bunny11/analyze-customer-behavior
* **Context**
Nielsen receives transaction level scanning data (POS Data) from its partner stores on a regular basis. Stores sharing POS data include bigger format store types such as supermarkets, hypermarkets as well as smaller traditional trade grocery stores (Kirana stores), medical stores etc. using a POS machine.

While in a bigger format store, all items for all transactions are scanned using a POS machine, smaller and more localized shops do not have a 100% compliance rate in terms of scanning and inputting information into the POS machine for all transactions.

A transaction involving a single packet of chips or a single piece of candy may not be scanned and recorded to spare customer the inconvenience or during rush hours when the store is crowded with customers.

Thus, the data received from such stores is often incomplete and lacks complete information of all transactions completed within a day.

Additionally, apart from incomplete transaction data in a day, it is observed that certain stores do not share data for all active days. Stores share data ranging from 2 to 28 days in a month. While it is possible to impute/extrapolate data for 2 days of a month using 28 days of actual historical data, the vice versa is not recommended.

Nielsen encourages you to create a model which can help impute/extrapolate data to fill in the missing data gaps in the store level POS data currently received.

* **Content**
You are provided with the dataset that contains store level data by brands and categories for select stores-

* **Hackathon_ Ideal_Data** - The file contains brand level data for 10 stores for the last 3 months. This can be referred to as the ideal data.

* **Hackathon_Working_Data** - This contains data for selected stores which are missing and/or incomplete.

* **Hackathon_Mapping_File** - This file is provided to help understand the column names in the data set.

* **Hackathon_Validation_Data** - This file contains the data stores and product groups for which you have to predict the Total_VALUE.

* **Sample Submission** - This file represents what needs to be uploaded as output by candidate in the same format. The sample data is provided in the file to help understand the columns and values required.
