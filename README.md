# A Deep Learning Approach to Embryo Quality Assessment
## Authors: Minh H Le, Viet V Truong, Pham Le Phu, Huy Phan, Toan Le, Hieu Nguyen, Van Dai Pham, and Hieu Le.
#### Abstract: In this study, we proposed a Deep Learning-based approach to embryo quality assessment at early stage (cleavage) and blastocyst stage. We acknowledged that this is the first work conducted utilizing data from a Vietnam hospital with the stated aim in both day 3 and day 5 image data. Our experimental results conclusively show that the proposed approaches significantly outperformed traditional classification methods, surpassing them by a margin of at least 9.3% and thereby won the annual international competition in ISODS’s Kaggle challenge 2023 
#### What is in this repository?
You can find the code of models without tuning in the folder 'Baseline' and also the code of our approach in folder 'EfficientNet_Tuning'
#### Dataset
Here is the link of dataset which provided by a Vietnam hospital on Kaggle: https://www.kaggle.com/competitions/world-championship-2023-embryo-classification/data
#### Getting started
1. Folder 'Baseline':
- File 'swintransformer-no-tuning.ipynb' contains the code of Swintransformer model without tuning techniques for the embryo quality classification.
- File 'resnet-no-tuning.ipynb' contains the code of Resnet50 model without tuning techniques for the embryo quality classification.
- File 'vit-b16-no-tuning.ipynb' contains the code of Vision transformer b16 model without tuning techniques for the embryo quality classification.
- File 'efficientnet-no-tuning.ipynb' contains the code of EfficientNet B5 model without tuning techniques for the embryo quality classification.
2. Folder 'EfficientNet_Tuning'
- File 'eff-b5-clw.ipynb' contains the code of EfficientNet B5 model with class weight technique for the embryo quality classification.
- File 'eff-b5-tta.ipynb' contains the code of EfficientNet B5 model with TTA technique for the embryo quality classification.
- File'efficientnet-tta-and-classweight.ipynb' contains the code of our approach: EfficientNet B5 with combine TTA and class weight techniques.
