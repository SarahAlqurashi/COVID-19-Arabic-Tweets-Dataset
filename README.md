# COVID-19-Arabic-Tweets-Dataset
The repository contains a collection of Arabic tweets IDs associated with the novel coronavirus COVID-19. The dataset contains Tweets' ids dating back to March,30,2020. The Twitter search API was used to gather real-time tweets that contained specific keywords in the Arabic language. In compliance with Twitter’s Terms of Service,only the IDs of the tweets collected are released. The gathered tweets are released for non-commercial research use only.
# Data Organization
*	Tweet-ID files are stored in folders that indicate the year and month of the collection
*	The Tweet-ID files contain the tweets ids, all files name have the same structure, with a prefix “COVID19-tweetID-year-month-DATE"
# Dataset collection
*	Only tweets in Arabic language were collected from   1 ,March,2020  to  30,March,2020.
* The keywords.txt file contains the updated keywords along with the date we began tracing them. The Hashtags.txt files contain the Hashtags that we are followed in our Twitter data-set and the number of tweets collected for each hashtag.
* Since Twitter’s search API have a restriction on the amount of the retrieved data there  are missing hours of data.
* We provided preliminary statistics of the data-set in the associated paper to this repository. the preliminary statistics will be automatically updated with every update of the dataset.
* For retrieving, the full object of the tweet considers the following tools [Hydrator](https://github.com/DocNow/hydrator)  and [twarc](https://github.com/DocNow/twarc) .

# Dataset Statistics
The following statistics is from Tweets colected until 12:59  PM  UTC 30,March,2020.<br/>
The Number of Tweets: 2,433,660<br/>
The Number of Orignal Tweets:2,433,389<br/>
The Number of  Retweets:271<br/>
The Average  of Tweets Collected Daily : 77279<br/>
![](images/daily_distributions.png)
# Licensing
This dataset is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License ([CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)). you agree to abide by the stipulations in the license, remain in compliance with Twitter’s Terms of Service, and cite the following manuscript:
# Inquiries  
for Inquiries about the dataset contact Dr Eisa Alanazi at eaanazi@uqu.edu.sa
or DR Ahmad Alhindi at ahhindi@uqu.edu.sa or Sarah Alqurashi at saraa.alqurashi@gmail.com 


Shield: [![CC BY-NC-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0
International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
