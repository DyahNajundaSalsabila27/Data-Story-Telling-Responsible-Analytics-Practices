# Data-Story-Telling-Responsible-Analytics-Practices
This week I learned how to process datasets (Data Understanding) into data visualizations then create Data Story Telling and learn Responsible Analytics Practices.

## Data Understanding (Dataset)
Data Understanding (Dataset) is a dataset that refers to the process of understanding and exploring the dataset used. This stage is the first step in analyzing data to understand the characteristics, properties, and content of the dataset before conducting further analysis. The goal is to gain initial insight into the dataset that will be used in the analysis.

In learning to analyze and process datasets, I use the Social Assistance Distribution Monitoring Dataset in the DKI Jakarta Region.The dataset contains data on the distribution of social assistance in DKI Jakarta during April 2020 to the poor and vulnerable people affected by Covid-19, both DKI KTP and Non DKI KTP.

The contents of the dataset column contain:
- Wilayah Kota : Name of the city where social assistance is distributed
- Kecamatan : Name of the sub-district where social assistance is distributed
- Kelurahan : Name of the urban village where the social assistance is distributed
- RW : Area based on RW that received social assistance
- Penerima (KK) : Number of recipients of social assistance count per (KK) 
- Jadwal Distribusi : Scheduling the distribution of social assistance in each region
- Tanggal Distribusi : Implementation of social assistance distribution in each region
- Sembako: Contains any basic necessities that will be distributed


## Data Story Telling
Data storytelling is the process of communicating insights, information, or findings found in data in a narrative way that is compelling and understandable to a wider audience. In data storytelling, data is transformed into a story that has a clear narrative flow, a clear communication objective, and can move the audience to understand, respond, or take action based on the information presented.

The following is story telling data using the Social Assistance Distribution Monitoring Dataset : 

- Total beneficiaries by 5 highest sub-districts (Pie Circle Chart)

   ![image](https://github.com/DyahNajundaSalsabila27/Data-Story-Telling-Responsible-Analytics-Practices/assets/73014611/3b5b5edc-317e-4941-8f3e-b9966322cdb4)
  Story Telling :

   Based on the data, the district with the highest number of aid recipients is Kramat Jati District, about 22.7% of the total KK revenue in Kramat Jati, which shows that this area has significant aid needs during the period of PSBB related to COVID-19.

- Total social assistance recipients per City Region (Bar Chart)

   ![image](https://github.com/DyahNajundaSalsabila27/Data-Story-Telling-Responsible-Analytics-Practices/assets/73014611/88f65c61-63c4-4453-85d5-a27a318f6646)

Story Telling : Based on the data generated, you can see a comparison of the number of aid recipients (KK) in various areas of DKI Jakarta. So it can be seen that the city area of East Jakarta had the most aid recipients that year and the lowest aid recipient area was the Thousand Islands with a percentage of 1.51%. This percentage result is calculated based on the total data of aid recipients (KK) in the DKI Jakarta city area. In other words, the Thousand Islands region only has about 1.51% of the number of recipients (KK) in East Jakarta.

- Percentage of social assistance recipients categorized Kecamatan 

![image](https://github.com/DyahNajundaSalsabila27/Data-Story-Telling-Responsible-Analytics-Practices/assets/73014611/af5366d8-3ac6-4a1c-804e-28c750741faa)

Story Telling : Based on the data, it is known that there are 5 lowest sub-districts with the least number of recipients (KK), namely Gambir Subdistrict as much as 2.5% calculated from the total number of recipients (KK) based on the sub-district. This shows that Kecamatan Gambir has a relatively lower level of assistance (KK) than other kecamatan in the region

- Lowest total social assistance recipients by RW category (Plot Diagram)

![image](https://github.com/DyahNajundaSalsabila27/Data-Story-Telling-Responsible-Analytics-Practices/assets/73014611/8d035490-b22e-4ede-9b1b-2f36ca28f26d)

Story Telling : Based on the data, it can be seen that the lowest number of recipients based on RW is RW 23 with 0.43% of households and RW 24 and RW 25 have the same number of recipients, which is 0.68% of total recipients (KK).

- Total distribution of basic food items(Barplot Chart)

   ![image](https://github.com/DyahNajundaSalsabila27/Data-Story-Telling-Responsible-Analytics-Practices/assets/73014611/56b82ae6-9169-4a8b-8826-75f4251a0c2a)

Story Telling : Based on the data above, it can be seen that the types of food are distributed equally. such as rice, biscuits, masks, soap, oil and canned sardines


## Responsible Analytics Practices
Responsible analytics practices refer to a set of guidelines, ethics, and practices applied by data analytics professionals, data scientists, and related practitioners in order to use data and data analysis with ethical consideration, fairness, and transparency. The goal of responsible analytics practices is to ensure that data and analysis results are used in a way that supports moral and social values and minimizes the risk of negative impacts.

### Data Privacy and Best Practices
1. Data Privacy Laws 
Data privacy laws, also known as data protection laws, are legal regulations governing the collection, use, processing, storage and sharing of personal data. These laws are designed to protect the privacy and rights of individuals by imposing certain obligations on organizations, businesses, and other entities that handle personal data.

- General Data Protection Regulation (GDPR) : 
  Applicable in the European Union, GDPR is one of the most comprehensive data privacy regulations, setting high standards for data protection.
- Family Educational Rights and Privacy Act (FERPA) : 
  federal laws in the United States governing privacy and access to educational data. FERPA gives parents and students the right to access and control their education data.
- Health Insurance Portability and Accountability Act (HIPAA) : 
  Federal laws governing the privacy and security of health information. HIPAA applies to healthcare entities and sets privacy and security standards for medical data.
- Institutional Review Board (IRB) : 
  an ethics committee tasked with assessing, monitoring, and protecting the rights and welfare of human research subjects in scientific research. The IRB ensures that research involving human subjects is conducted ethically and adheres to privacy and security standards.
- Payment Card Industry (PCI) : 
  data security standards that apply to organizations that manage credit card payment data. It regulates payment data security and requires organizations to protect customer credit card information.

### Best Practices for Responsible Data Handling
Responsible data handling means applying ethical principles of transparency, fairness and respect to how we treat data that affects people's lives. This protects our privacy and autonomy and builds the trust necessary for digital innovation to flourish in ways that benefit everyone.

- Methods of Handling PII :
  PII stands for Personally Identifiable Information. PII is a type of information that can be used to uniquely identify an individual.
- Security Data :
  Importance of Data Security has to make sure our small data is safe from unauthorized access or hacking. 
- Balance Between Interpretation and Accuracy : Sometimes, small data needs to be simplified or interpreted for better understanding without losing accuracy.
- Limitations in Generalization on Limited Sample Data :
  Small data may not represent the entire population, so avoid making strong generalizations.
- Transparency and Documentation : Always document the steps and methods used in handling data.
- Regulatory Compliance and Ethics :
  Make sure we comply with privacy regulations and consider the ethical impact of data handling.

### Types of bias that affect collection and interpretation of data
Bias that affect collection and interpretation of data refers to deviations or distortions in the process of data collection, analysis, and interpretation that can lead to errors or unobjectivity in research results. Bias in this context can arise from a variety of sources, such as cognitive bias, motivation, sampling error, or other factors that affect the way data is collected, analyzed, and presented.

- Confirmation Bias : Confirmation bias is a human tendency to seek out, remember, or give more attention to information that validates or confirms existing beliefs or views, while ignoring or downplaying conflicting information.
- Human Cognitive Bias :  Human Cognitive Bias is a group of biases that arise due to the way humans process information and make decisions. These biases can include cognitive biases such as the negative scanning effect, the superficial understanding effect, and the emotion-based decision-making effect.
- Motivational Bias : Motivational bias is a bias that arises when individuals have certain motivations or interests that influence how they collect or interpret data. This bias can occur when an individual has a specific goal or incentive in the research results.
- Sampling Bias : Sampling bias occurs when the sample used for data collection does not properly represent the overall population. This can lead to biased and unreliable results.
