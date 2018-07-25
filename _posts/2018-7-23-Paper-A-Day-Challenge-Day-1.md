---
layout: post
title: Meta-Learning Approach to One-Step Active Learning
---
### First Pass
*Questions*
  1. *What type of paper is this?* This paper presents a new hybrid method of meta training an active learning model. Instead of setting an initial heuristic which the model uses in order to consult some oracle, a learned model is used to consult an oracle.
  2. *What other research is this paper related to?* As the methods presented are a combination of emerging research topics in weak supervision, it would be useful to acknowledge **One Shot Learning**, **Meta Learning**, **Active Learning**, and **Monte Carlo Methods**. 
  3. *Do the assumptions seem to be valid?* As a novice, I will not make a claim about the validity of the claims made in the paper. I will, however, attest to the issue of gathering supervised data being a major concern in deep learning/machine learning.
  4. *What are the paper's main contributions?* Not sure.
  5. *Is this paper well written?* Again, as a novice it would be irresponsible to make some type of a claim. ~One major issue that troubles me, though, is that the introduction does not actually introduce the methods that they take to acheive the final result. Specifically, in the closing remarks, there is mention of employing a bi-LSTM, while it seems that the introduction seperates itself from that particular method.~
---

### Second Pass
*Questions*

  4. *What are the paper's main contributions?* In the second pass, I was able to gain more insight into the main contributions of this paper. They are as follows:
      - Develop an acquisition to determine the most relevant training subset to bring to an oracle.
      - Use a distribution to determine the usefulness of bringing a particular example to an oracle.
      - Determine a loss function that incorporates both the prediction error from an integrated predictor model, as well as the cost of bringing an example to an oracle.
 
  5. *Is this paper well written?* Yes. The paper is very well written, and explains the methods it employs very well. Originally, I believed that the bi-LSTM was an integral part of the model, and was skeptical that it wasn't mentioned in the introduction. Now, however, I realize that the bi-LSTM is simply a means to an end.
  
 #### Notes
 ---
 
 
 
