# Notes

### Data Pipeline: Data Collection: 
- Data labeling. Better to throw the data out. 
- Feature engineering: 
  - Actually by hand writing equation to create new features. 
  - If its medical data then we might need to do feature engineering. Haveing the output of the Neural Net and the engineered features and then compare them as well. 
- Unsupervised/Semi-Supervised
  - Before you do the final hand labeling, we shoud do an unsuperbised training. 
  - Taking a pass with unsupervised, we avoid bias. We give a chance to the machine to learn without the bias. 
  - Its better to do first unsupervised rather than hand derived features. 
  - Key best practice. That is first use the autoencoder to learn the features and then use the hand derived features.
- Final Labeling: 
  - Question can be reformulated. 

### Learning Paradigms:
- Unsupervised, Supervised (Trying to predict the features from features), Contrastive learning, Self-Supervised. 


### Loss function Design: 
- Loss function is where the magic lies. 
- How to fit and not fit the datasets. 

### Kicking off Batches: 

### Hyperparapmeter Tunings: 


### Explainability: 
- OODA loop: 
  - Its part of the feedback loop. 
  - We should do this as we are iterating. 
  
### Conformance Testing: 
- Once you exported the model, produce the same outputs for the same outputs. 
- If the new system has a different float points, then it might produce differnet outputs. 