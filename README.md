# Chemicals-in-Cosmetics
A comprehensive analysis of reports on Chemicals in Cosmetics data, providing insight on hazardous and potentially hazardous ingredients in cosmetic products sold in California and to make this information available to the public.
## Project Overview
* In today's data-driven landscape, extracting valuable insights from extensive datasets has become paramount for informed decision-making across diverse industries. This report offers a thorough data analysis focusing on harmful ingredients, specifically chemicals utilized in cosmetics production, as reported to the California Safe Cosmetics Program (CSCP) within the California Department of Public Health (CDPH). The objective is to uncover significant patterns, trends, and insights to support strategic decision-making regarding the discontinuation of these harmful ingredients.
## Data Source
The dataset utilized for this analysis is sourced from a CSV file documenting hazardous and potentially hazardous ingredients found in cosmetic products retailed in California between 2009 and 2020.
## Tools
Power Querry - Data Cleaning

Power BI - Creating Reports
## Data Cleaning And Preparation
The following steps were taken in the data cleaning steps;
* I loaded and inspected the data.
* I handled the empty columns and missing values.
## Exploratery Data Analysis
* I utilized DAX functions to establish metrics for analyzing active chemicals, the quantity of chemical reports, time disparities, discontinued chemical tallies, unique chemical, unique brands, unique CAS IDs, unique companies, and unique products.
* With respect to this dataset, the reports spanned from 2009 to 2020, including days and months, to facilitate year-based analysis, a new column called 'year' was generated using a DAX function.
* Created a comprehensive report dashboard displaying key metrics such as, chemical reported, initial date reported, most recent date reported, discontinued date reported, active chemicals, discontinued chemicals, distinct products, distinct companies, distinct CAS IDs, distinct brands, distinct CSF and count of primary category with card visuals.
* I employed area charts to showcase the initial reported dates of chemicals, the most recent reported dates for chemicals, and the dates when chemicals were discontinued, all by months. Filters were utilized via slicers to enable customization of the display based on both year and chemical name.
* I developed a tree visualization to present all chemical reports categorized by company name, product name, chemical name, primary category, and sub-category. Additionally, filters were implemented through slicers to enable customization of the display based on both year and chemical name.
* I designed a tabular visualization to comprehensively display data on each product name, including their chemical reports, counts of discontinued chemicals, and active chemicals. Similarly, each chemical name was presented alongside its respective chemical reports, discontinued chemical count, and active chemicals. Furthermore, each company name was included with their chemical reports, discontinued chemical count, and distinct products. Filters were also integrated through slicers to facilitate tailored viewing options, allowing users to customize displays based on both year and chemical name.
## Results
* Upon visualizing and analyzing the data, the cumulative count of chemical reports reached 114.64 thousand. Among these reports, Titanium Dioxide garnered the highest number, totaling 93.4 thousand reports, trailed by Silica - Crystalline with 2.8 thousand reports, and Retinol/Retinyl Esters with 2.1 thousand reports following suit.
* Within the dataset comprising 114.64 thousand chemical reports, a total of 635 companies are utilizing these chemicals. Leading the count is L’Oreal USA, with 5.7 thousand reports, followed closely by S+ and Coty, both tallying 5.1 thousand reports each.
* A total of 33.45 thousand products were manufactured using these chemicals. The product named Eyecolor received the most reports, with 766, followed by Nail Lacquer with 668 reports, and Black Label Lipstick with 487 reports.
* Between 2009 and 2020, Titanium Dioxide consistently maintained its status as the most frequently reported chemical, albeit with varying figures. In 2009, Titanium Dioxide received 25.30k reports, with 1.74k discontinued chemical counts and 22.45k active chemicals. Following Titanium Dioxide were Butylated Hydroxyanisole with 1.56k reports, 54 discontinued chemical counts, and 1.42k active chemicals; Retinol/Retinyl Esters with 939 reports, 54 discontinued chemical counts, and 834 active chemicals; and Trade Secret with 526 reports, 1 discontinued chemical count, and 474 active chemicals.
* In 2010, Titanium Dioxide continued to lead with 12.12k reports, followed by Retinol/Retinyl Esters with 782 reports and Cocamide Diethanolamine with 539 reports. Similarly, in 2011, Titanium Dioxide remained in the lead with 3.67k reports, accompanied by Retinol/Retinyl Esters with 400 reports and Retinyl Palmitate with 110 reports.
* In subsequent years, Titanium Dioxide maintained its prominence, receiving 3.11k reports in 2012, 4.74k reports in 2013, 7.69k reports in 2014, 6.10k reports in 2015, 4.06k reports in 2016, 5.65k reports in 2017, 7.59k reports in 2018, 11.09k reports in 2019, and 1.80k reports in 2020. Notably, the chemicals Silica, Mica, Carbon Black, and others emerged as secondary or tertiary reported chemicals in various years throughout the period analyzed.
## Recommendations
Based on analysis, here are some potential recommendations I would give as a data analyst:
* Since Titanium Dioxide has consistently been the most reported chemical across 2009 and 2020, it's crucial to prioritize monitoring and potentially regulating its use in cosmetic products. Conduct further research on the potential health and environmental impacts of Titanium Dioxide exposure.
* Reach out to companies like L'Oreal USA, S+, and Coty, which have the highest number of chemical reports, to understand their product formulations and explore safer alternatives to the reported chemicals.
* Focus on products like Eyecolor, Nail Lacquer, and Black Label Lipstick, which have the highest number of chemical reports. Collaborate with manufacturers to reformulate these products or provide clear labeling and warnings for consumers.
* Promote transparency and full disclosure of product ingredients, especially for chemicals like Retinol/Retinyl Esters, Silica - Crystalline, and Butylated Hydroxyanisole, which have a high number of reports.
* Implement a system for continuous monitoring of chemical reports, enabling trend analysis and early detection of potential issues. This will help identify emerging chemicals of concern and adapt regulations accordingly.
* Develop educational campaigns and resources to raise consumer awareness about potentially hazardous chemicals in cosmetic products. Empower consumers to make informed choices and advocate for safer alternatives.
* Work closely with cosmetic industry associations and regulatory bodies to establish stricter guidelines, testing protocols, and potentially banning or restricting the use of certain chemicals based on scientific evidence.
* Explore incentives or recognition programs for companies that actively seek and develop safer alternatives to hazardous chemicals in their products.
* Encourage further data collection and research to understand the long-term health and environmental impacts of commonly reported chemicals, particularly those with limited existing research.
* Periodically review and update regulations based on the latest scientific findings, consumer trends, and industry practices to ensure the safe use of chemicals in cosmetic products.
* Furthermore, it's important to note that these recommendations should be tailored and prioritized based on the specific goals, resources, and regulatory frameworks of the organization or jurisdiction overseeing the California Safe Cosmetics Program.





