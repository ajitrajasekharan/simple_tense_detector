# simple_tense_detector
This is a simple present/past tense detector of a sentence using DEP-POS tagger

# Installation.

1) Install the POS server as per instructions in the URL below and test the server first
https://github.com/ajitrajasekharan/JPTDP_wrapper.git

After this step a server should be running on port 8028. The step below expects that. If running the server on  a different port, change the port in the  File: tense_detector.py

Step 1 requires python 2.7

2) python tense_detector.py test.txt

Step 2 requires python 3+
