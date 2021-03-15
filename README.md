# simple_tense_detector
This is a simple present/past/future tense detector of a sentence using DEP-POS tagger. 
**This detector assumes POS tagger output is [Penn tree bank POS tags](https://www.ling.upenn.edu/courses/Fall_2003/ling001/penn_treebank_pos.html)**   *( [Penn tree bank Tags with examples](https://www.sketchengine.eu/penn-treebank-tagset/) )*

# Installation.

**Step 1)** Install the POS server as per instructions in the URL below and test the server first
https://github.com/ajitrajasekharan/JPTDP_wrapper.git

After this step a server should be running on port 8028. The step below expects that. If running the server on  a different port, specify a different port to the command open in step 2 below. *python tense_detector.py --help for the options*

*Step 1 requires python 2.7*

**Step 2)** python tense_detector.py

```
VERB DEPTH SCORE[0-1]|tense type - undecided,present,past,future|confidence [0-1]|sentence
1|future|0.18|We will repeat a stress test on him next spring to make sure he has not had progression of disease in his other arteries.
1|past|1.0|He fell down and broke his leg
1|past|1.0|Her hypophysitis secondary to ipilimumab was well managed with supplemental hormones
1|past|0.57|She imagined herself going into the future and baking a cake
1|past|0.9|He fell down and bled to death near the park where children were playing and having fun with their parents
1|past|0.47|Before going to the school he decided to examine the landscape
1|future|0.2|He will try to fly his kite again tomorrow
1|present|0.67|He plans to finish his school sometime in the distant future
1|present|1.0|Patient history includes asthma and peanut allergy
1|future|0.2|He could finish his homework if he only tried
```

*Step 2 requires python 3+*



# License
MIT License
