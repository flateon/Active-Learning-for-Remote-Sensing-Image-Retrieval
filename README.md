# Active Learning for Remote Sensing Image Retrieval
Unofficial implementation of paper [A Novel Active Learning Method in Relevance
Feedback for Content-Based Remote
Sensing Image Retrieval](https://ieeexplore.ieee.org/document/6920022/)
<img src="./block_diagram_of_AL_method.png"/>

## Usage
[![Open TCAL in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1O1rVIDR6gsheBJq3s4M-D_stOiWYGSvb?usp=sharing)
### Running locally 
1. Clone this Repository  
2. Download and Unzip the [UCMerced_LandUse](http://weegee.vision.ucmerced.edu/datasets/landuse.html) dataset  
3. Open rf_al.ipynb in Jupyter Notebook  
## Result
| Metric            | Reported | Our Implementation |
|-------------------|----------|--------------------|
| Average Precision | 69%      | 68.69%             |
## Acknowledgements
[Kernel K-means](https://gist.github.com/mblondel/6230787)