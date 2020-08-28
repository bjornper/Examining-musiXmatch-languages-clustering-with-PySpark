
I found the musiXmatch data (the lyrics part of "millionsongdataset" at http://millionsongdataset.com/) intriguing and wanted to learn a bit of PySpark so I did some language clustering

I noticed just by looking at the first few hundred words in its dictionary that there are non-English words - SOMETIMES it helps to be a native speaker of something else than English. Then I also wanted to see if the underlying structure of this dataset made up of songs and the collection of words in each song would be especially conductive to clustering. I thought to myself that the words that make up the lyrics of a song will come predominantly from one language giving me an opportunity to determine if the clustering falls mostly along the lines of language boundaries and also to try out an idea I had for semi-supervised K-means.
