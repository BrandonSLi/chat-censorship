## Overview

A [collection](https://github.com/citizenlab/chat-censorship/tree/master/june-4/june-4-censored-keywords.csv) of censored keywords related to the June 4 1989 Tiananmen Square Massacare collected from chat apps (WeChat, LINE, TOM-Skype, Sina UC) and live streaming platforms (YY, Sina Show, 9158, GuaGua)
Each of these applications have client-side implementations of keyword censorship. 
Through reverse engineering we extract the keyword lists and track updates to the lists over time.  

## CSV Data Fields

The categorized data in each CSV is organized by the following fields:

word: keyword extracted from the app

machine_translation: translation from Google Translate

human_translation: translation from human. Only applied when necesssary 

client: application the keyword was collected from (WeChat, LINE, TOM-Skype, Sina UC, YY, Sina Show, 9158, GuaGua)
