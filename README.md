# The-Punch-Data-Analysis

Natural Language Processing (NLP) is used everywhere, from chatbots to even your favourite search engines(Bing, Google, etc). This is what computers use to understand human language (or natural language) and I wanted to explore how it could be used to help businesses in the media industry.

The Punch newspaper is the most widely read newspaper in Nigeria and I wondered how I could use NLP to answer some of their business questions.

I collected 585 links from their online platform: https://punchng.com/ and scraped at least 70 articles for each of the following categories:

- Politics
- News
- Metro Plus
- Sports
- Business
- Editorial and
- HealthWise


I wanted to find out the following:
1. Who is the average person that can read articles on the PUNCH website? (Readability Index)
2. How subjective are the articles? (Integrity of the News Source)
3. Which category has the most positive emotion? (Positive Polarity) and finally
4. Which category of articles has the lowest number of words? (User Attention)

### Who is the average person that can read articles from the PUNCH website? (Readability Index)
Sadly, not everybody has the ability to read and write. According to data from the World Bank, the literacy rate of adults in Nigeria (2018) is 62%. This means that only 62% of Nigerian adults can read and write. It is important for everyone to have access to news to stay up to date on events happening around them both at home and abroad.

<div class="img-container" align='center'>
  <img src="https://github.com/posi-olomo/The-Punch-Data-Analysis/assets/75603128/0c6fb5ba-fd7c-41f1-a73b-eaf1f63a5b48" style="width:50%">
  <img src="https://github.com/posi-olomo/The-Punch-Data-Analysis/assets/75603128/4fb55a42-df33-4520-abd1-93c39f1b6301" style="width:40%">
</div>

My analysis showed that the fog index (reading level) is 6.3. This corresponds to the 6th grade reading level. The average age of a child in the 6th grade is 12. **This means that people aged 12 and above can read an average article on the PUNCH website.**


### How subjective are the articles? (Integrity of the News Source)
It is important that an international newspaper put out unbiased information. Unlike personal blogs or websites where people give their own perspectives and opinions on things, newspapers are to tell you how things are as objectively as possible, not adding salt or sugar.

<p align='center'>
<img [Screenshot (610)] src = 'https://github.com/posi-olomo/The-Punch-Data-Analysis/assets/75603128/e07bd383-7482-4c45-b8e6-eb1fa4f07064'>
</p>

Subjectivity is measured on a scale of 0 – 1. Where 0 stands for objectivity (i.e. zero to little bias/personal opinion) and 1 stands for subjectivity (i.e. high bias/personal opinion). As you can see **the average subjectivity is less than zero which means that the articles are on average very objective.**

### Which category has the most positive emotion? (Positive Polarity)
An article talking about a huge natural disaster where people died will have a negative polarity because the topic brings about negative or sad emotions. On the other hand, if an article was talking about how a couple that has been married for 10 years without children finally gave birth to twins, the article will have a positive polarity.

This is the formula for polarity score:

```math
polarity \space score = \frac{positive \space score \space — \space negative \space score}{(positive \space score + negative \space score) + 0.000001}
```

where:

positive score = number of positive words in the article

negative score = number of negative words in the article

<p align='center'>
<img [Screenshot (611)] src = 'https://github.com/posi-olomo/The-Punch-Data-Analysis/assets/75603128/68eb04b0-455f-4446-ad68-b9b906ddab20' width = 70%>
</p>

Although both Sport and Business articles are close, **Sport articles have the highest positive emotion** unlike that of Metro Plus which has the lowest polarity score of -0.485. This is not surprising since Metro Plus articles are articles surrounding natural disasters and criminal activities.

### Which category of articles has the lowest number of words? (User Attention)
Nobody likes reading a lengthy article. User retention is a key success metric in the media industry, from YouTube videos to blog posts, it is one of the reasons TikTok is so popular, they put out short videos which easily retain the attention of users. I wanted to see which category of articles has the lowest number of words.

<p align='center'>
<img [Screenshot (612)] src ='https://github.com/posi-olomo/The-Punch-Data-Analysis/assets/75603128/62aa137c-2560-4a30-893b-ca64802444da'>
</p>

**Metro Plus articles have the lowest number of words**. This may be due to the articles being a summary of incidents and not really a detailed write-up like Editorial articles which have the highest number of words.

### What more can I do?
If I had access to the website’s User Engagement, I would be able to see which patterns encourage high user engagement and those that do not thereby making changes to improve the engagement of users on the platform.

Although it is important to note that User engagement is not only linked to the articles but also to the User Interface of the website. Is the website easy to navigate or do people get lost trying to read the next article?

### References
Literacy rate, adult total (% of people ages 15 and above) — Nigeria | Data (worldbank.org)
