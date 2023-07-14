# FLO CLTV-Prediction
Customer Lifetime Prediction with BG/NBD and Gamma Gamma Models

# Business Problem
[ENG] FLO wants to determine a roadmap for its sales and marketing activities. The company needs to predict its customers value in order to make a plan in the mid-long term.

[TR] FLO satış ve pazarlama faaliyetleri için roadmap belirlemek istemektedir. Şirketin orta uzun vadeli plan yapabilmesi için var olan müşterilerin gelecekte şirkete sağlayacakları potansiyel değerin tahmin edilmesi gerekmektedir.

# Data Set
[ENG] The dataset consists of information derived from the past shopping behaviors of customers who made purchases from FLO in the years 2020-2021 as OmniChannel customers, meaning they shopped both online and offline.

[TR] Veri seti Flo’dan son alışverişlerini 2020 - 2021 yıllarında OmniChannel (hem online hem offline alışveriş yapan) olarak yapan müşterilerin geçmiş alışveriş davranışlarından elde edilen bilgilerden oluşmaktadır.

# Variables
- master_id: Unique customer number id
- order_channel : Which channel is used (Android, ios, Desktop, Mobile, Offline)
- last_order_channel : Last order channel
- first_order_date : the first order date of customer
- last_order_date : the last order date of customer
- last_order_date_online : the last order date of customer in online platform
- last_order_date_offline : the last order date of customer in offline platform
- order_num_total_ever_online : the total number of online order of customer
- order_num_total_ever_offline : the total number of offline order of customer
- customer_value_total_ever_offline : Total fee paid by the customer for offline purchases
- customer_value_total_ever_online : Total fee paid by the customer for online purchases
- interested_in_categories_12 : List of categories the customer has shopped in the last 12 months
- store_type : It refers to 3 different companies. If the person who shopped from company A made it from company B as well, it is written as A, B.
