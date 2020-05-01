# Simple_text_classification
This was from a competition held by ZINDI on  To Vaccinate or Not to Vaccinate:

The data comes from tweets collected and classified through Crowdbreaks.org [Muller, Martin M., and Marcel Salathe. "Crowdbreaks: Tracking Health Trends Using Public Social Media Data and Crowdsourcing." Frontiers in public health 7 (2019).]. Tweets have been classified as pro-vaccine (1), neutral (0) or anti-vaccine (-1). The tweets have had usernames and web addresses removed.

The objective of this challenge is to develop a machine learning model to assess if a twitter post that is related to vaccinations is positive, neutral, or negative.

Variable definition:

tweet_id: Unique identifier of the tweet
safe_tweet: Text contained in the tweet. Some sensitive information has been removed like usernames and urls
label: Sentiment of the tweet (-1 for negative, 0 for neutral, 1 for positive)
agreement: The tweets were labeled by three people. Agreement indicates the percentage of the three reviewers that agreed on the given label. You may use this column in your training, but agreement data will not be shared for the test set.
Files available for download are:

Train.csv - Labelled tweets on which to train your model
Test.csv - Tweets that you must classify using your trained model
SampleSubmission.csv - is an example of what your submission file should look like. The order of the rows does not matter, but the names of the ID must be correct. Values in the 'label' column should range between -1 and 1.




Work has already begun towards developing a COVID-19 vaccine. From measles to the common flu, vaccines have lowered the risk of illness and death, and have saved countless lives around the world. Unfortunately in some countries, the 'anti-vaxxer' movement has led to lower rates of vaccination and new outbreaks of old diseases.

Although it may be many months before we see COVID-19 vaccines available on a global scale, it is important to monitor public sentiment towards vaccinations now and especially in the future when COVID-19 vaccines are offered to the public. The anti-vaccination sentiment could pose a serious threat to the global efforts to get COVID-19 under control in the long term.

The objective of this challenge is to develop a machine learning model to assess if a Twitter post related to vaccinations is positive, neutral, or negative. This solution could help governments and other public health actors monitor public sentiment towards COVID-19 vaccinations and help improve public health policy, vaccine communication strategies, and vaccination programs across the world.

About #ZindiWeekendz

The Zindi community is joining the fight against COVID-19! #ZindiWeekendz are virtual weekend hackathons hosted by Zindi. This series of #ZindiWeekendz throughout April and May 2020 focuses specifically on COVID-19.

In a time of lockdowns, remote work, and general uncertainty, #ZindiWeekendz offer data scientists the opportunity to continue to develop their skills while contributing to practical, open-source AI solutions to help in the battle against COVID-19.

All winning solutions will be shared as a public good on GitHub. We are committed to supporting partners implement these solutions and encourage anyone who is interested to reach out to us at zindi@zindi.africa.

About Microsoft (microsoft.com)

📷
This hackathon is sponsored by Microsoft (Nasdaq “MSFT” @microsoft). Microsoft enables digital transformation for the era of an intelligent cloud and an intelligent edge. Microsoft has operated in Africa for more than 25 years. In that time they have built strong partnerships across the continent, helped bridge gaps in infrastructure, connectivity and capability, and are working to empower countries in Africa to digitally transform while creating sustained societal impact. Earlier this year, Microsoft opened Africa’s first hyper-scale data centers in Johannesburg and Cape Town, South Africa. Most recently, the company also announced the opening of two Africa Development Centers in Nairobi and Lagos, where world-class African talent can create innovative solutions for local and global impact.
