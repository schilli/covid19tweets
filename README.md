# covid19tweets
Analysis of twitter tweets related to Covid-19
[Homepage on github](https://github.com/schilli/covid19tweets)

## Installations
* Download or clone the repository.
* As the dataset is rather huge, a workstation with plenty of RAM is required (at least 32 GB).

### Required Python packages
* Python 3.8
* Pandas
* Matplotlib
* Seaborn
* Scipy
* tqdm

### Data Source
* [TweetsCOV19 dataset](https://data.gesis.org/tweetscov19/)
* Download the dataset and unpack it to `../data/tweetsCov19/` (relative to project directory).

## Project Motivation
The Covid-19 outbreak was a globally very special event.
It sparked fear in many.
Other people tried to exploit this fear.
This project analyses what topics moved the the twitter community.

## File Descriptions

### covid19tweets_exploration.ipynb
Contains all the code.

### Readme.md
This file

### LICENSE
Contains the GPCv3 License agreement.

## How to use
* Run the included jupyter notebook covid19tweets_exploration.ipynb
* Total processing time is on the order of 1 hour on a recent workstation ([Single threaded on Intel Xeon Prozessor E5-2698](https://ark.intel.com/content/www/de/de/ark/products/91753/intel-xeon-processor-e5-2698-v4-50m-cache-2-20-ghz.html), at least 32 GB RAM)
* The results are discussed in this [medium article](https://medium.com/@spambeantworter/tweetscov19-what-moved-the-world-when-the-pandemic-started-cac4518d13f7)
* The notebook is commited with output as this is required for the udacity project review process, even though this is generally bad git practice.

## Licensing
This code is released under GPC v3 license. The terms and conditions are contained in the file LICENSE.

## Acknowledgements
Special thanks goes to Dimitrov, D. et al. for preparing and sharing the dataset!