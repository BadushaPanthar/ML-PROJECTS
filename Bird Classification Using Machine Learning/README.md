
## BIRD CLASSIFICATION USING MACHINE LEARNING

### MULTICLASS CLASSIFICATION

### About Dataset
#### Context:
There are many kinds of birds: pigeons, ducks, ostriches, penguins… Some are good at flying, others can't fly but run fast. Some swim under water, others wading in shallow pool.According to their living environments and living habits, birds are classified into different ecological groups. There are 8 ecological groups of birds:

Swimming Birds
Wading Birds
Terrestrial Birds
Raptors
Scansorial Birds
Singing Birds
Cursorial Birds (not included in dataset)
Marine Birds (not included in dataset)
First 6 groups are main and are covered by this dataset.

Apparently, birds belong to different ecological groups have different appearances: flying birds have strong wings and wading birds have long legs. Their living habits are somewhat reflected in their bones' shapes. As data scientists we may think of examining the underlying relationship between sizes of bones and ecological groups , and recognising birds' ecological groups by their bones' shapes.

#### Content:
There are 420 birds contained in this dataset. Each bird is represented by 10 measurements (features):

Length and Diameter of Humerus
Length and Diameter of Ulna
Length and Diameter of Femur
Length and Diameter of Tibiotarsus
Length and Diameter of Tarsometatarsus

#### Acknowledgements:
This dataset is provided by Dr. D. Liu of Beijing Museum of Natural History.

#### DESCRIPTION:
Classifying bird type using machine learning. I have balanced the data using Random Over Sampler because  the target data was not balanced. I have used RandomForest Classifier for the analysis and computed AUC and ROC for each class and plotted ROC curve for the same.


