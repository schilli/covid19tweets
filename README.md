# covid19tweets
Analysis of twitter tweets related to Covid-19

## How to
* Run the included jupyter notebook covid19tweets_exploration.ipynb
* Total processing time is on the order of 1 hour on a recent workstation ([Single threaded on Intel Xeon Prozessor E5-2698](https://ark.intel.com/content/www/de/de/ark/products/91753/intel-xeon-processor-e5-2698-v4-50m-cache-2-20-ghz.html), at least 32 GB RAM)
* The results are discussed in this [medium article](https://medium.com/@spambeantworter/tweetscov19-what-moved-the-world-when-the-pandemic-started-cac4518d13f7)
* The notebook is commited with output as this is required for the udacity project review process, even though this is generally bad git practice.

## Prerequisites
As the dataset is rather huge, a workstation with plenty of RAM is required (at least 32 GB).

### Python packages
* Python 3.8
* Pandas
* Matplotlib
* Seaborn
* Scipy
* tqdm

## Data Source
* [TweetsCOV19 dataset](https://data.gesis.org/tweetscov19/)