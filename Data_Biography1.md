# Data Biography

## Student Number: 20101663

---

### 1. Who collected the data?

_The data was collected by Inside Airbnb project, they sourced publicly available information from the Airbnb website[1]._

---

### 2. Why did they collect it?

_The data was collected to facilitate and analyse general and specific questions. For example, it could be used to studying the relationship between price and demand, finding customers' preference based on their review and understanding the real estate market in London[2]._

---

### 3. How was it collected?

_The data was collected by utilising public information from the Airbnb website with respect to the 365 days per year and reviews for each listing[3]. The raw data on the website was stored in a database base on city, in this case, London. The database has a structured format so each id will match its corresponding detailed data in the same row. The columns are the factors associate with the listing and they provide key information for various study purposes. _

---

### 4. What useful information does it contain?


_It contains useful information like host name, about and location; latitude and longitude; price; review scores from six areas, namely accuracy, cleanliness, check-in, communication, location, and value; and total rating for review score. These information are crucial for analysing problems like which area is the best for customer and which area is more expensive. Based on the location data, price and review score data, users of this dataset can create multiple maps with regards to their interests. Moreover, the host about data (textual) can also be used to filter the data and adjust it into a better manner for specific interests of study._

---

### 5. What useful information is it missing?

_The information about host gender, occupancy rate, host income and guest information are not given[4], these are the structural missing data. Fields like Calendar update, neighborhood group and bathroom are partially or completely blank can be deemed as randomly missing data._

---

### 6. To what extent is the data 'complete'?

_To a large extent, the data is complete. Like the key information summarised in Q4, the listing data is sufficient to conduct location-based research, price driven studies as well as ranking customer’s preference. It follows a process of getting hosts id and provided further detail linked to that id. The whole data gather process is logical and quite complete except some missing fields mentioned in Q5. It would be useful for state legislation, companies interested in London real Estate, hosts, and potential customers. Although there are structural missing and randomly missing data, the dataset is generally not so biased. The missing piece of occupancy rate and host income will only hinder the investigation about quantifying hosts’ performance economically and the random missing value will have no impact on drawing the conclusion for research if handled properly. Thus, to a large extent, the data is complete and good to use for data scientist._

---

### 7. What kinds of analysis would this support?

_This dataset can support analyses how appealing each neighborhood is based on the location average score of reviews. It can further determine the best and the most expensive/budget area by combining the geo-spatial data, price data, and review scores. The dataset can also support investigation about the types of listing in London, to determine which is the most popular style. Besides, by studying number of reviews and prices, the relationship between demand and price can be induced. This helps host in certain area to set a more competitive price. Furthermore, data mining about customers’ reviews can help companies or host figure out customer’ preference. This will help them to determine what matters most for guests and they should enhance it as their core competitive force._

---

### 8. What kinds of analysis would it _not_ support?

_This dataset cannot support the analyses of “does customer prefer male host or female host?” as the gender information of the host is not given. It also could not quantify and estimate the annual or monthly income of the host due to the lack of occupancy rate. Besides, no information about customer are given means it is difficult to take “guest” as a study object. Data scientists can only infer customers’ preference based on their review scores, but they cannot induce which age group customers like which area specifically or will customers’ income level/gender/occupation affect their choice of accommodation._

---

### 9. Which of the uses presented in Q.7 and Q.8 are _ethical_?

_According to Data Ethics Framework[5], there are three principles, namely Transparency, Accountability, and Fairness to assess whether the data is ethical. Besides that, data used must fulfil public benefits and user needs, comply with the law, and involve diverse expertise. Quality and limitations of data or model are also key factors to be considered (). The study about relationship between price and demand and customers’ preference in Q7 can be ethical. Firstly, the results of these study will fulfil the desire of users like renting companies or hosts, as they would like to know the appropriate price for guests across different neighborhoods. By understanding customers’ preference, they can better adjust their room settings to attract more customers. It also promotes social benefits like reducing price discrimination in harmful competition among the house hosts. Secondly, the data collection process is completely complied with the law and ensures the Transparency and Fairness of using the data since the data is compiled from public website. Thirdly, the data contains location information, reviews, price, and host information across multiple data types, this provides diversified fields to conduct research and data scientists can investigate problem from different perspectives. Lastly, the quality of the data is high and complete, despite certain random missing value in the fields. This would not limit the models (mentioned in Q7) applied on the data. However, the studies mentioned in Q8 may violate the ethics of data as it requires private information about the guest and the leak of these private information may cause serious consequences. Moreover, the structural missing of fields will limit the study about hosts’ income. The lack of occupancy rate can only be inferred by 50% * reviews, which is not very accurate and thus decrease the data quality for further investigation to carry on._

---

### References

_[1]  “Get the Data,” Insideairbnb.com. [Online]. Available: http://insideairbnb.com/get-the-data.html. [Accessed: 26-Nov-2020]._
---
_[2]  S. Gupta, “Airbnb rental listings dataset mining - towards Data science,” Towards Data Science, 04-Jan-2019. [Online]. Available: https://towardsdatascience.com/airbnb-rental-listings-dataset-mining-f972ed08ddec. [Accessed: 26-Nov-2020]._
---
_[3]  “Inside Airbnb. Adding data to the debate,” Insideairbnb.com. [Online]. Available: http://insideairbnb.com/about.html. [Accessed: 26-Nov-2020]._
---
_[4]  “Airbnb Data Collection: Methodology and Accuracy,” Tomslee.net. [Online]. Available: https://tomslee.net/airbnb-data-collection-methodology-and-accuracy. [Accessed: 26-Nov-2020]._
---
_[5]  Gov.uk. [Online]. Available: https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/923108/Data_Ethics_Framework_2020.pdf. [Accessed: 26-Nov-2020]._
---
