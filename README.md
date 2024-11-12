# Drug Toxicity Prediction using Graph Neural Networks


## Project Supervisor:-
Prof. Ashutosh Modi and Prof. Ritika Gautam

## Abstract:-
Drugs play an extremely crucial role in saving lives of people. However, some of them
are too toxic to be safe for human use. Determining a drug's toxicity usually takes a lot of
time, as it involves testing on large groups of people, waiting to see side effects, and
analyzing results. Apart from that, several chemical tests are conducted for testing a
variety of results before arriving at a conclusion. This process can be extremely time -
consuming delaying progress in the process of drug discovery.

In this study, we aim to address this problem by using computational methods instead
of traditional lab tests. Machine learning techniques are well-known for performing
several classification tasks. We employ Graph Neural Networks(GNNs) to solve our
problem. One thing must be noted is that for a classification to be performed by any ML
model, a set of features must be provided from which the model will extract information
and then perform the classification. However, in our case, we are provided with only the
SMILES representation of the drug and the toxicity label of it. So, we start with
extracting the feature vector from this SMILES representation (a type of chemical
notation) of the drug. And then perform the classification using GNNs and attention
mechanism to determine whether the drug is toxic or not. This study combines
chemistry and machine learning, marking it a significant step forward in the process of
drug discovery.
