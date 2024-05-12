![birdclef2024](https://github.com/aniiketbarphe/Analyze_Audio_Data_to_Identify_Indian_Bird_Species-BirdCLEF-2024-Competition/assets/84449238/8889e805-f35d-49cf-8831-268dc01af024)

# Analyze_Audio_Data_to_Identify_Indian_Bird_Species-BirdCLEF-2024-Competition

Overview
Goal of the Competition
Birds are excellent indicators of biodiversity change since they are highly mobile and have diverse habitat requirements. Changes in species assemblage and the number of birds can thus indicate the success or failure of a restoration project. However, frequently conducting traditional observer-based bird biodiversity surveys over large areas is expensive and logistically challenging. In comparison, passive acoustic monitoring (PAM) combined with new analytical tools based on machine learning allows conservationists to sample much greater spatial scales with higher temporal resolution and explore the relationship between restoration interventions and biodiversity in depth.



For this competition, you'll use your machine-learning skills to identify under-studied Indian bird species by sound. Specifically, you'll develop computational solutions to process continuous audio data and recognize the species by their calls. The best entries will be able to train reliable classifiers with limited training data. If successful, you'll help advance ongoing efforts to protect avian biodiversity in the Western Ghats, India, including those led by V. V. Robin's Lab at IISER Tirupati.

Context
In the face of rapid anthropogenic pressures of habitat modification and climate change, we need to utilize the latest conservation tools and technologies to monitor biodiversity. Through the Kaggle competition, we aim to carry out automated detection and classification of bird species of the Western Ghats from soundscapes.

The Western Ghats are a Global Biodiversity Hotspot, with the mountain range running along the southwestern coast of India. It is home to diverse ecosystems that support extraordinary levels of biodiversity. These ecosystems range from high-elevation forest-grassland mosaics to tropical dry deciduous forests to wet-evergreen rainforests, to name a few. Additionally, this region is home to large human populations whose livelihoods depend on the forests and the natural resources the region provides. From an avifaunal perspective, this region is home to high levels of bird diversity, with several endemic and endangered species found nowhere else. However, this mountain range is undergoing drastic landscape and climatic changes that negatively affect biodiversity. Hence, we need conservation technologies and tools to help us assess and monitor bird diversity rapidly.

The broader goals for this Kaggle competition include:
(1) Identify endemic bird species of the sky-islands of the Western Ghats in soundscape data.
(2) Detect/classify endangered bird species (species of conservation concern) featuring limited training data.
(3) Detect/classify nocturnal bird species which are poorly understood.

Thanks to your innovations, it will be easier for researchers and conservation practitioners to survey avian population trends accurately. As a result, they'll be able to evaluate threats and adjust their conservation actions regularly and more effectively.

This competition is collaboratively organized by (alphabetic order) the Chemnitz University of Technology, Google Research, Indian Institute of Science Education and Research (IISER) Tirupati, K. Lisa Yang Center for Conservation Bioacoustics at the Cornell Lab of Ornithology, LifeCLEF, and Xeno-canto.

Timeline
April 3, 2024 - Start Date.

June 3, 2024 - Entry Deadline. You must accept the competition rules before this date to compete.

June 3, 2024 - Team Merger Deadline. This is the last day participants may join or merge teams.

June 10, 2024 - Final Submission Deadline.

All deadlines are at 11:59 PM UTC on the corresponding day unless otherwise noted. The competition organizers reserve the right to update the contest timeline if they deem it necessary.

Evaluation
The evaluation metric for this contest is a version of macro-averaged ROC-AUC that skips classes which have no true positive labels.

Submission Format
For each row_id, you should predict the probability that a given bird species was present. There is one column per bird species, so you will need to provide 182 predictions per row. Each row covers a five-second window of audio.

Working Note Award Criteria (optional)
Criteria for the BirdCLEF Best Working Note Award:

Originality. The value of a paper is a function of the degree to which it presents new or novel technical material. Does the paper present results previously unknown? Does it push forward the frontiers of knowledge? Does it present new methods for solving old problems or new viewpoints on old problems? Or, on the other hand, is it a rehash of information already known?

Quality. A paper's value is a function of the innate character or degree of excellence of the work described. Was the work performed or the study made with a high degree of thoroughness? Was high engineering skill demonstrated? Is an experiment described which has a high degree of elegance? Or, on the other hand, is the work described pretty much of a run-of-the-mill nature?

Contribution. The value of a paper is a function of the degree to which it represents an overall contribution to the advancement of the art. This is different from originality. A paper may be highly original but may be concerned with a very minor, or even insignificant, matter or problem. On the other hand, a paper may make a great contribution by collecting and analyzing known data and facts and pointing out their significance. Or, a fine exposition of a known but obscure or complex phenomenon or theory or system or operating technique may be a very real contribution to the art. Obviously, a paper may well score highly on both originality and contribution. Perhaps the important question is, will the engineer who reads the paper be able to practice his profession more effectively because of having read it?

Presentation. The value of the paper is a function of the ease with which the reader can determine what the author is trying to present. Regardless of the other criteria, a paper is not good unless the material is presented clearly and effectively. Is the paper well written? Is the meaning of the author clear? Are the tables, charts, and figures clear? Is their meaning readily apparent? Is the information presented in the paper complete? At the same time, is the paper concise?

Evaluation of the submitted BirdCLEF working notes:

Each working note will be reviewed by two reviewers and scores averaged. Maximum score: 15.

a) Evaluation of work and contribution

5 points: Excellent work and a major contribution

4 points: Good, solid work of some importance

3 points: Solid work but a marginal contribution

2 points: Marginal work and minor contribution

1 point: Work doesn't meet scientific standards

b) Originality and novelty

5 points Trailblazing

4 points: A pioneering piece of work

3 points: One step ahead of the pack

2 points: Yet another paper about…

1 point: It's been said many times before

c) Readability and organization

5 points: Excellent

4 points: Well written

3 points: Readable

2 points: Needs considerable work

1 point: Work doesn't meet scientific standards

Prizes
1st Place - $ 15,000
2nd Place - $ 10,000
3rd Place - $ 8,000
4th Place - $ 7,000
5th Place - $ 5,000
Best working note award (optional):

Participants of this competition are encouraged to submit working notes to the LifeCLEF 2024 conference. A best BirdCLEF working note competition will be held as part of the conference. The top two best working note award winners will receive $2,500 each. See the Evaluation page for judging criteria.

Code Requirements


This is a Code Competition
Submissions to this competition must be made through Notebooks. For the "Submit" button to be active after a commit, the following conditions must be met:

CPU Notebook <= 120 minutes run-time
GPU Notebook submissions are disabled. You can technically submit but will only have 1 minute of runtime.
Internet access disabled
Freely & publicly available external data is allowed, including pre-trained models
Submission file must be named submission.csv
Please see the Code Competition FAQ for more information on how to submit. And review the code debugging doc if you encounter submission errors.

Acknowledgements
Compiling these extensive datasets was a major undertaking, and we are very thankful to the many domain experts who helped to collect and manually annotate the data for this competition. Specifically, we would like to thank (institutions and individual contributors in alphabetic order):

Chemnitz University of Technology
Maximilian Eibl and Stefan Kahl

Columbia University
Vijay Ramesh

Google Research
Tom Denton

Indian Institute of Science Education and Research (IISER), Tirupati
Chiti Arvind, Harikrishnan C.P., Viral Joshi, V.V. Robin, and Suyash Sawant

K. Lisa Yang Center for Conservation Bioacoustics
Stefan Kahl, Holger Klinck, and Vijay Ramesh

LifeCLEF
Alexis Joly and Henning Müller

Nature Conservation Foundation
Divya Mudappa and T.R. Shankar Raman

Parry Agro Industries Ltd.
Project Dhvani
Meghana Srivathsa

Tamil Nadu Forest Department
Tata Coffee Ltd.
Tea Estates India Ltd.
The Rufford Foundation
The University of Florida
Akshay V. Anand

Xeno-canto
Willem-Pier Vellinga

Photo Credits
Banner picture of a Malabar Trogon by Saswat Mishra
Inset picture of a Sholicola by Ian Lockwood

Dataset Description
Your challenge in this competition is to identify which birds are calling in recordings made in a Global Biodiversity Hotspot in the Western Ghats. This is an important task for scientists who monitor bird populations for conservation purposes. More accurate solutions could enable more comprehensive monitoring.

This competition uses a hidden test set. When your submitted notebook is scored, the actual test data will be made available to your notebook.

Files
train_audio/ The training data consists of short recordings of individual bird calls generously uploaded by users of xenocanto.org. These files have been downsampled to 32 kHz where applicable to match the test set audio and converted to the ogg format. The training data should have nearly all relevant files; we expect there is no benefit to looking for more on xenocanto.org and appreciate your cooperation in limiting the burden on their servers.

test_soundscapes/ When you submit a notebook, the test_soundscapes directory will be populated with approximately 1,100 recordings to be used for scoring. They are 4 minutes long and in ogg audio format. The file names are randomized but have the general form of soundscape_xxxxxx.ogg. It should take your submission notebook approximately five minutes to load all of the test soundscapes.

unlabeled_soundscapes/ Unlabeled audio data from the same recording locations as the test soundscapes.

train_metadata.csv A wide range of metadata is provided for the training data. The most directly relevant fields are:

primary_label - a code for the bird species. You can review detailed information about the bird codes by appending the code to https://ebird.org/species/, such as https://ebird.org/species/amecro for the American Crow. Not all species have their own pages; some links will fail.
latitude & longitude: coordinates for where the recording was taken. Some bird species may have local call 'dialects,' so you may want to seek geographic diversity in your training data.
author - The user who provided the recording.
filename: the name of the associated audio file.
sample_submission.csv A valid sample submission.

row_id: A slug of soundscape_[soundscape_id]_[end_time] for the prediction.
[bird_id]: There are 182 bird ID columns. You will need to predict the probability of the presence of each bird for each row.
eBird_Taxonomy_v2021.csv - Data on the relationships between different species.

Competition Link:- https://www.kaggle.com/competitions/birdclef-2024?inquiry-id=inq_XUETmWriuTmmgb6npjKqbpfHtsQj&reference-id=10663864&subject=10663864&status=completed&fields%5Bcurrent-selfie%5D%5Btype%5D=selfie&fields%5Bcurrent-selfie%5D%5Bvalue%5D%5Bid%5D=self_AUqjBFhBWkNVQDN7BPnQXu85YAjR&fields%5Bcurrent-selfie%5D%5Bvalue%5D%5Btype%5D=Selfie%3A%3AProfileAndCenter
