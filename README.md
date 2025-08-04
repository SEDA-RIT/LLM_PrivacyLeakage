# LLM_PrivacyLeakage

This repository contains materials for our project on detecting privacy leakage in Android application logs using Large Language Models (LLMs).

## Project Description

Android app logs are essential resources for recording runtime information, but they may also include users' privacy information. Existing privacy leakage detection approaches in logs are primarily based on regular expressions or keyword-based searches, which heavily rely on the comprehensiveness of the keyword list and can result in high detection inaccuracy.
Therefore, we propose two research questions studying the ability of LLMs to detect privacy leakage in Android app logs. In our preliminary experiment, we used ChatGPT and found that while ChatGPT can detect privacy leakage in Android app logs, its ability can result in high inaccuracy. After improving the detection strategy by modifying the prompts to allow ChatGPT to learn the contextual knowledge of privacy leakage, it significantly improved in detecting more privacy leakage and reducing false positives. The detection results also indicate that privacy leakage in Android app logs is a non-trivial issue.