# research_methods
Sem Huisman
S4779428

In English the present perfect is used to indicate a link between the present and the past. The present perfect always consists of a form of the verb 'having' and a past participle. For example:  *have seen*.

## Research Question
Do British Twitter users use the present perfect more when describing something that has recently occurred?

Hundt, 2009 states that in both American English and British English the use of the present perfect is decreasing. It also says that in the 1990s the present perfect was significantly more often used in British English than in American English.[^1] This leads to the following **hypothesis**:
Twitter users from the UK will more often use the present perfect than Twitter users from the US.

![contingency table](https://github.com/SemHuis/research_methods/blob/main/contingency_table.png "Figure 1")

## Method
In 2017 Twitter changed the character limit from 140 to 280. To get a fair comparison between British and American English we want all tweets to have the same character limit. I will therefore only use data from 2018 to 2022.The data is saved on the RUG karora server. With a python program I get random files until I have 150 cases for both groups. So we have a sample of 300 Twitter users. I use NLTK to give tags to all the words in each tweet. The past participles are tagged as "VBN" and we can find the forms of the verb having with a wordlist. 

[^1]: Hundt, M., & Smith, N. (2009). The present perfect in British and American English: Has
there been any change, recently. ICAME journal, 33(1), 45-64.
