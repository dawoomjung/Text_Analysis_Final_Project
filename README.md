#### Text_Analysis_Final_Project
# Predicting North Korea's Nuclear Tests Through Text Analysis
### Introduction
The Democratic People's Republic of Korea (DPRK) has been a persistent concern in international relations due to its nuclear ambitions and the implications they pose for global security. Predicting the DPRK's next nuclear test is a vital issue for internationall security and diplomacy. In this context, my research project seeks to explore the possibility of forecasting DPRK's nuclear tests by examining patterns of words and news content in English-language government-controlled news sites operated by the DPRK. This study addresses a critical public policy question by investigating whether linguistic analysis of DPRK's official English-language communications can offer early warning signals of impending nuclear tests.

#### Research Question
Can we predict the DPRK's next nuclear test by studying the pattern of words used in their English medium government-controlled news sites? Are there any words that were used frequently in the days leading up to their previous nuclear tests? Are there patterns in the type of news that are published in the days leading up to the tests?

#### Hypothesis
This project hypothesizes that there may be discernible patterns in the word usage and content published on DPRK's English-language government-controlled news sites in the days leading up to their previous nuclear tests. These patterns, if identified and analyzed effectively, could serve as early indicators of impending nuclear tests.
including your research question, hypothesis, and why it’s important

### Methods of Data Collection and Analysis
###### Data Collection:
Web Scraping: I collected data from DPRK's official English-language news websites: KCNA (Korean Central News Agency). However, since KCNA website has been banned for any users in the U.S. and South Korea, I used a website called https://kcnawatch.org/ which is an aggregator of official DPRK media output, which updates in real time.

In the middle of the research, I had to relocate to South Korea where the KCNA Watch website is also banned. I used a VPN to change my location to the US and was able to access the KCNA Watch website that way.

###### Event Data: 
I will also acquire a dataset of all the past DPRK nuclear tests, including dates and details of each test, to serve as a reference for our analysis.
North Korea has so far conducted 6 nuclear tests.
1. 9 October 2006
2. 25 May 2009
3. 12 February 2013
4. 6 January 2016
5. 9 September 2016
6. 3 September 2017

The official website of the Korea Central News Agency (KCNA) was launched in late 2010, but because of a deletion of older content in late 2013 its archive currently goes back only to that time. This is significant because it brought down the number of the nuclear tests I could analyze to 3. 
1. 6 January 2016
2. 9 September 2016
3. 3 September 2017

Out of the three, I decided to analyze the text from 6 January 2016 as it was the closest in the time frame compared to the control data. The control data was collected from Dec 14, 2023 to Dec 21, 2023.

##### Text Analysis:
Web-scraping: The time frame I used was a week before the test. This was mostly for my own sake because of the sheer number of the articles. Over 40 articles per test so total that’s about 120 articles. This part was the most time consuming because I had to manually find all the relevant articles within the time frame and copy paste them.

Cleaning: I used the nltk to remove stop words, but this was not enough as a website had a lot of irrelevant information such as "Sign Up here, Other articles, Terms & Conditions, Warnings, etc." As a result, I had to create a custom list of stop words to finetune my results.

Word clouds: I chose to analyze my text using word clouds because they provide visual representation of word frequency in the text. Not only do they offer a quick and intuitive way to identify the most prevalent terms, but they are also are user-friendly and accessible, making them a popular tool for individuals without specialized knowledge in data analysis or natural language processing. 

Initially, I had considered using Term Frequency-Inverse Document Frequency (TF-IDF) to analyze which words appear the most in the news articles. However, I realized that an average person would not know the meaning and significance of a TF-IDF score. Thus, I chose to go with the word clouds as they are also visually engaging and effective for presentations or reports, helping to communicate the most salient words. 

###### Limitations: 
Because of the limitations of time, I could only analyze one the three nuclear tests. If I had more time, an analysis of all three nuclear tests would have provided better results.

Additionally, while word clouds provide a broad overview of word frequency, they lack context, treating all words equally based on frequency and disregarding their importance or sequential information. Despite these limitations, word clouds can serve as a preliminary exploration tool and offer insights into trends or commonalities within a dataset.

### Results


### Discussion & conclusion
