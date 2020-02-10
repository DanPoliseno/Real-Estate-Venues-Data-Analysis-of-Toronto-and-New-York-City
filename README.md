# Real-Estate-Venues-Data-Analysis-of-Toronto-and-New-York-City

Introduction/Business Problem


Toronto is known as an international center of finance, arts, culture, and business as well as being known as one of the most multicultural cities in the world. Toronto is the provincial capital of Ontario and the most populous city in Canada, with a population of 2,731,571 as of 2016.2 In comparison, New York City is the most populous city in the United States with an estimated 2018 population of 8,398,748. In addition, New York City is known as a global power city and renowned as the financial, cultural, and media capital of the world.3


For Alphabet Inc., parent company of Google Inc., both New York City and Toronto are important cities. Google’s Toronto Offices serve as a hub-office for many members of the company’s creative team and salespeople. Engineers and computer scientists at the Google office in Toronto work on many of Google’s well known products and services. In addition, in August 2019 Google announced it would be expanding office space in the financial district of Toronto.4 New York is home to Google’s second largest office in the Chelsea neighborhood of Manhattan. “Engineers work on Google Drive, Search, AdWords, and Maps, and the large sales team works with clients that include media companies and ad agencies.”1


For Real Estate Agents, determining the best area or neighborhood and finding a client’s perfect home at the right place can be the most difficult and time consuming aspect. To complete this task, an agent may spend countless hours on researching and showing clients homes or may pay significant amounts of money to hire employees to conduct research and/or pay for expensive subscriptions to companies that aggregate statistical data. 


As a Real Estate Agent in New York City, a client has contacted me who has accepted a job offer at Google’s NYC office and is relocating from Toronto. The client is ready to make an offer on their new condo/co-op as quickly as possible. This project will help to understand the diversity of each neighborhood analyzed by leveraging venue data from Foursquare’s Places API and k-means clustering unsupervised machine learning algorithm. The objective of this project will be to propose the 3 best listings I can find for my client who will be arriving next week and is ready to buy their new home. The client would like to buy a condo/co-op in a neighborhood most similar to the one they live in now, as similar as possible in price/size to the one they have now, and closest to Google’s NYC office building. 


The apartment in Toronto they are moving from is a 2 bedroom & 2 bathroom condo listed for C$899,000 in the Downtown Toronto (Old Toronto) neighborhood of Toronto, ON, Canada. The current home address is: 1 A The Esplanade Ave # 2008, Toronto, ON, M5E 0A8. 
Google’s NYC office building address is: 75 9th Ave, New York, NY 10011.


Farfan, Barbara. “Google’s Global Headquarters and Offices Around the World.” The Balance Small Business, The Balance Small Business, 5 Aug. 2019, www.thebalancesmb.com/google-headquarters-offices-2892790.


Wikipedia contributors. "Toronto." Wikipedia, The Free Encyclopedia. Wikipedia, The Free Encyclopedia, 26 Jan. 2020. Web. 26 Jan. 2020.


Wikipedia contributors. "New York City." Wikipedia, The Free Encyclopedia. Wikipedia, The Free Encyclopedia, 19 Jan. 2020. Web. 26 Jan. 2020.


Robertson, Becky. “Google Is Opening Another Office in Toronto.” BlogTO, 5 Oct. 2019, www.blogto.com/tech/2019/10/google-opening-another-office-toronto/.



**Data Section**


I will be analyzing neighborhood data from Toronto, Ontario and New York, NY. The first step will be to analyze the neighborhood of the client’s current home in the Downtown Toronto (Old Toronto) neighborhood of Toronto. After obtaining the latitude and longitude of Downtown Toronto, I will obtain the latitude and longitude of Google’s NYC Office as a starting point. Subsequently I will obtain the latitudes and longitudes of NYC neighborhoods surrounding Google’s NYC Office. Once all necessary latitudes and longitudes are obtained, I will analyze each neighborhood utilizing the FourSquare’s Places API to create a profile for each neighborhood based on nearby venues. 


Utilizing the FourSquare’s Places API, I will create neighborhood profiles based on nearby venues and the frequency their visited and k-means clustering machine learning algorithm to compare and contrast the profiles created of each neighborhood. Exploratory Data Analysis will assist to determine each neighborhood’s profile. The project objective will be to determine which NYC neighborhoods closest to Google’s NYC Office are the most similar to the Downtown Toronto neighborhood of Toronto. After determining which neighborhood in NYC is closest and most similar, I will utilize Zillow’s API to propose three current listings that are most similar to the client’s current home in the most similar neighborhood. 


Stakeholders would be Real Estate Agents, Real Estate Buyers, and other individuals or groups interested in a new way to use quantifiable analysis to understand and profile a neighborhood based on venue information obtained via FourSquare Places API. Previously neighborhood profiles have always been aggregated and compared based on statistical or demographic information. However, I believe a new approach based on venues and often they’re visited for creating neighborhood profiles in order to compare other neighborhood profiles can be much more accurate than the previous method.


New York City Dataset. Link: https://cocl.us/new_york_dataset
Toronto Dataset. Link: https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M
FourSquare API. Link: https://developer.foursquare.com/docs
Zillow API. Link: https://www.zillow.com/howto/api/APIOverview.htm
