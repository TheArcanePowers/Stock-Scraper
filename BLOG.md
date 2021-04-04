Initially, the program created seperate reports of most mentioned and highest scoring posts in the newest week on various subreddits.

Unfortunately this ended up outputting a multitude of files per subreddit:
And realistically, this barely addressed the actual aim of the program.

Thus entered **Verson 2**, which created a csv separated database per subreddit listing all the stocks mentioned and upvoted daily, and with their stock opening and closing prices. Additionally, running it appends the daily report to pre-existing csv files per subreddit.

This removes clutter completely, and allows one to run anaylsis on the data per subreddit - as each community and their impact will be entirely different. Also reads the text inside self posts and add those tickers to the count (both scores and mentions).