## Initial Thoughts:
Based on my understanding of the modeling types, I initially think the Linear Regression will prove to be more accurate.  With so many variables (84 factors before adding dummies), there is likely a lot of noise in the data.  I'm expecting both to do pretty well since these are the kinds of tests in which both excel and I expect any lenders algorythyms to be pretty dialed in.

### Results:
Unscaled Logistic Regression Training Data Score: 0.7108374384236453
Unscaled Logistic Regression Testing Data Score: 0.5786899191833262
Unscaled Random Forest Training Score: 1.0
Unscaled Random Forest Testing Score: 1.0

### Unscaled Results Thoughts
Clearly the Random Forest out performs the LR, to a surprising degree to be honest. My hunch about noise was way off.

## Scaled vs Non Scaled:

My assumption will be that the scaled LR model will perform better after reducing the noise.  It's hard to be more right than the Random Forest already is, but I don't expect it to change.
 
### Results:
Scaled Logistic Regression Training Data Score: 1.0
Scaled Logistic Regression Testing Data Score: 0.9997873245427478
Scaled Random Forest Training Score: 1.0
Scaled Random Forest Testing Score: 1.0

### Results Thoughts

I was correct, the LR results did improve with scaling, fairly significantly. Overall it demonstrated the importance of scaling the sample set to reduce noise. Its surprising the level of accuracy in both, I was expecting in the 90's but not so close to "perfect."