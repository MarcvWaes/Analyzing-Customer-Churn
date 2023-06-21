# Datacamp-Analyzing-Customer-Churn

Performed the following challenges:
- data check
![fg3loe2o avj](https://github.com/MarcvWaes/Datacamp-Analyzing-Customer-Churn/assets/120553175/8c341c80-b5ee-42b2-8d0b-3e8e3abc02ce)
  - performed calculation
  - Number of Customers = COUNT('Databel - Data'[Customer ID])
  - Number of Unique Customers = DISTINCTCOUNT('Databel - Data'[Customer ID])
- calculate churn
![22advpdy wmr](https://github.com/MarcvWaes/Datacamp-Analyzing-Customer-Churn/assets/120553175/6a623957-f112-45ce-867e-f266564453fe)
  - performed calculation
  - Churn Rate = [Number of Churned Customers]/[Number of Customers]
- churn reasons
![b2s1yrk4 lmb](https://github.com/MarcvWaes/Datacamp-Analyzing-Customer-Churn/assets/120553175/335b055b-ccbb-4449-bd25-ed847f212782)
- digging deeper
![tdvnehy5 3pt](https://github.com/MarcvWaes/Datacamp-Analyzing-Customer-Churn/assets/120553175/6facf2a4-a923-4a2b-a44d-08cd42f55ec2)
- creating maps
![ekz4wcav lq4](https://github.com/MarcvWaes/Datacamp-Analyzing-Customer-Churn/assets/120553175/911a3911-8a3c-4c69-bfee-792773439763)
- demographics investigation
![d2vnwseq xam](https://github.com/MarcvWaes/Datacamp-Analyzing-Customer-Churn/assets/120553175/e2c8ba4f-ec52-406c-a5e1-95a471554c8c)
- age bins
![mcpmtllx le5](https://github.com/MarcvWaes/Datacamp-Analyzing-Customer-Churn/assets/120553175/0400e3db-46c0-4a33-b339-7ef79c5c941a)
- inspecting groups
![clr2ckfp x53](https://github.com/MarcvWaes/Datacamp-Analyzing-Customer-Churn/assets/120553175/e7bc2fdf-e3c5-4940-a974-53187c4afec3)
- multiple fields
![rrewstof 3fq](https://github.com/MarcvWaes/Datacamp-Analyzing-Customer-Churn/assets/120553175/7bdc76e5-9359-4f84-bc69-3284141d5e8c)
- data
![p5im5n4p au4](https://github.com/MarcvWaes/Datacamp-Analyzing-Customer-Churn/assets/120553175/c249ebc7-062b-4856-b982-6efa3e0895f6)
- international calls
![0squtmgn o3r](https://github.com/MarcvWaes/Datacamp-Analyzing-Customer-Churn/assets/120553175/c0b2e372-3e5d-4529-bda5-04403d42d9b4)
- contract type
![qm3ydyd1 rzb](https://github.com/MarcvWaes/Datacamp-Analyzing-Customer-Churn/assets/120553175/c38e3d50-7381-4454-be05-04f68e2c173e)

- overview page
![wqum32gm kmc](https://github.com/MarcvWaes/Datacamp-Analyzing-Customer-Churn/assets/120553175/87a78d1c-b8b1-4b8d-b138-65b0c96ee891)
  - performed calculation
  - Churned = IF('Databel - Data'[Churn Label] = "Yes", 1, 0)
- age groups
![kyb5pw4g ubz](https://github.com/MarcvWaes/Datacamp-Analyzing-Customer-Churn/assets/120553175/c9bcf22c-5de7-4227-ab4c-bc9e3289cffb)
- payment contract
![yxjwoln2 ncf](https://github.com/MarcvWaes/Datacamp-Analyzing-Customer-Churn/assets/120553175/a2fea737-0fc5-47fe-ab68-ed813832435d)
  - performed calculation
  - Avg Customer Service Calls = SUM('Databel - Data'[Customer Service Calls]) / [Number of Customers]
- plans
![iwlpp2uv cnk](https://github.com/MarcvWaes/Datacamp-Analyzing-Customer-Churn/assets/120553175/cbfc01e8-23f3-46ea-bab7-f2c0e3fb100d)
- more insights
![vyspr5jf mp2](https://github.com/MarcvWaes/Datacamp-Analyzing-Customer-Churn/assets/120553175/72c34f33-1289-412a-9a36-c642f870cb21)
  - performed calculation
  - Avg Extra Data Charges = SUM('Databel - Data'[Extra Data Charges])/[Number of Customers]
  - Avg Extra International Charges = Sum('Databel - Data'[Extra International Charges])/[Number of Customers]
