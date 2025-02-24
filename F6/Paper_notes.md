- Title: AlphaEdit: Null-Space Constrained Knowledge Editing for Language Models
    - The core idea on updating the model on new knowledge (while preserving the old knowledge) is to leverage the null space of the 'weights'. It is not super clear how to ensure there is a nullspace.  
    - Paper link: https://arxiv.org/abs/2410.02355
 
- Title: What Neural Networks Memorize and Why: Discovering the Long Tail via Influence Estimation
    - Memorization actually helps with long-tail data (of course based on their experiments on image data + a bunch of caveats). They also have some 'efficient' compute methods for memorization scores, which could be useful. Kind of counterintuitive but quite interesting.
    - Paper link: https://arxiv.org/abs/2008.03703


- Title: 
    - The idea is very similar to FAR's data augumentation idea (without the forecasting part). We argument the training data with similar to serving data to come. The process include (forcasting),  data featurization, similarity measurement, retrival, etc. 
    - Paper link: https://arxiv.org/abs/2305.12837
    - Design:
        - <img src="Screenshot%202024-12-11%20at%201.59.46%E2%80%AFPM.png" alt="Before" width="300">
        - <img src="Screenshot%202024-12-11%20at%201.59.55%E2%80%AFPM.png" alt="After" width="300">
