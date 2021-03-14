# simple_tense_detector
This is a simple present/past tense detector of a sentence using DEP-POS tagger

# Installation.

1) Install the POS server as per instructions in the URL below and test the server first
https://github.com/ajitrajasekharan/JPTDP_wrapper.git

After this step a server should be running on port 8028. The step below expects that. If running the server on  a different port, change the port in the  File: tense_detector.py

Step 1 requires python 2.7

2) python tense_detector.py test.txt

Step 2 requires python 3+

# Test install


*python tense_detector.py*

```
VERB DEPTH SCORE[0-1]|tense type - undecided,present,past|confidence [0-1]|sentence
1|past|1.0|He fell down and broke his leg
1|past|1.0|Her hypophysitis secondary to ipilimumab was well managed with supplemental hormones
1|past|0.57|She imagined herself going into the future and baking a cake
1|past|0.9|He fell down and bled to death near the park where children were playing and having fun with their parents
1|past|0.47|Before going to the school he decided to examine the landscape
1|undecided|1.0|He will try to fly his kite again tomorrow
1|present|0.67|He plans to finish his school sometime in the distant future
1|present|1.0|Patient history includes asthma and peanut allergy
```

# License
MIT License
