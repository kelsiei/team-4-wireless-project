# Paper Summary - De-pois
  
  Citation: C. Wang, et al., "De-Pois: An attack-agnostic defense against data poisoning attacks," IEEE Transactions on Information Forensics and Security, 2021.

  ## Summary

  This paper covers the vulnerabilities of LLMs and Machine Learning models to be poisoned by their own training data, this can cause degradation
  a in performance or the creation of backdoors. The authors of this paper propose a system called "De-Pois", a defense system that uses 
  GAN (Generative Adversarial Networks) to create a clean form of data distribution. By comparing its training samples against the pre-established
  GAN-generated "baseline", the system can identifiy and filter out any malicious data without knowing the specific type of attack before hand.

  ## Relevance to our Research

  In 6G, AI models manage most major policies, this includes routing, security, etc. De-Pois provides a technical method for ensuring that 
  these models are not compromised by poisoned data fed into their training sets by attackers. 

  ## An Issue I Identified

  While the concept is ideal for the scenario, the actual cost of training and utilizing GAN to mimic the complex traffic of these systems and their 
  patterns might introduce too much lag and latency for 6G's standards. 

  ## AI usage disclosure

  Google Gemini was used to help understand and proof read/quality check the technicals aspects of the paper.
    
