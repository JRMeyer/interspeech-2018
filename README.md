# Multilingual Multi-Task Learning for Low-Resource Languages

## Abstract

  The following study investigates low-resource multilingual acoustic model training with Multi-Task Learning (MTL) for Automatic Speech Recognition. The main question of this research is: *What is the best way to represent a source language with MTL to improve performance on the target language?* The two parameters of interest are (1) the level of detail at which the source language is modeled, and (2) the relative weighting of source vs. target languages during backprop.

Results show that when the source task is weighted \textit{higher} than the target task, a *more* detailed task representation (ie. the triphone) leads to better performance on the target language. On the other hand, when the source task is weighted *lower*, then a *less* detailed level of source task representation (ie. the monophone) is better for performance in the target language. Given all levels of detail in the source task, a 1-to-1 weighting ratio of source-to-target leads to best results on average.

This study uses Kyrgyz (audiobook recordings) as a target language and English (LibriSpeech subset) as a source language.

## Reviewer Comments

You can find the Interspeech Committee's comments in the `REVIEWER_COMMENTS.txt` file.