## Writing down my intuition and thinking on ResNet and 'Residuals'

- Where it comes from
  - Consider really deep NN, the deeper layer could at least not harm the performance by doing 'identity map'
  - So the reason deeper NN does not function well is that we are using the wrong way of training it
    - But there is another situation: consider when humans 'think too much' <-- does this mean the poor performance of deep NN is reasonable?

- From a math perspective
  - Universal Approximation Theorem
    - Look up 'Borel Measurable Function'
  - Some math of residuals, specifically(See handwritten notes)




- Some intuition
  - Why training algo fails to find the specific function?
    - Wrong with the Algo
    - Overfitting
      - Which, should be considered when we talk about training loops, so we don't discuss that here
    - Shortlinks, shortlinks, shortlinks
      - It suddenly occurred to me that this could mean, when we think deeper, we take the shallow thinking into consideration to avoid 'think too much'
    - Less wide NN, but deeper, with shortlinks perform significantly better than wider and less deep NN <-- even for an extremely simple task
      - That leads me back to thinking what the width and depth of NN really stand for 
      - human attention and human reference depth?


- **DenseNet!**
  - Densely connected nets
  - Dense Block & Transition Layer
  - Mathematical Intuition:
    - Consider Taylor's expansion