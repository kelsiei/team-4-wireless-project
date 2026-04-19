# Paper Summary - Poison Frogs!

Citation: Shafahi, A., et al. "Poison Frogs! Targeted Clean-Label Poisoning Attacks on Neural Networks." Proceedings of the 32nd International Conference on Neural Information Processing Systems (NIPS), 2018.

https://papers.nips.cc/paper_files/paper/2018/hash/22722a343513ed45f14905eb07621686-Abstract.html

## Summary

This paper covers clean-label poisoning attacks where an attacker injects malicious samples into a training set without altering their actual labels. By subtly modifying the features of training data to mimic a target instance while retaining a base class label, the attacker forces the model to misclassify specific targets during the testing phase. This method is exceptionally difficult to detect because the labels remain visually and logically consistent with the data.

## Relevance to our Research

For 6G security, this type of attack shows that an attacker doesnt actually need to hack into a system to change the labels, they only have to feed altered data into a set of trainig data. This direclty explains the security threats part of the topic we chose and justifies why systems like de-pois are non-negotiables.

## An Issue I Identified

The attack requires the attacker to have some knowledge of the model's architecture.
in a highly dynamic 6G environment, an attacker might struggle to maintain this level of precision as network states change rapidly.

## AI usage disclosure

Google Gemini was used to help understand and quality check the technical aspects of the summary, along with refine the technical terminology
and ensure the summary adhered to the project's formatting requirements.
