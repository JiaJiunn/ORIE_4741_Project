## Project Proposal

Zoe Pan (zp45)
Christopher Archer (caa234)
Jia Jiunn Ang (ja497)

[Dataset](https://github.com/cptq/genius-expertise/tree/master/data)

Dear Genius.com representative,

Genius is well known for being a public source of music knowledge, including song lyrics and analysis. As a user, you’re able to follow music artists, write bios, and annotate song lyrics, to potentially earn votes and increase user IQ. 

With this in mind, we aim to answer the following question: given user and song information, can we predict how many votes an annotation will receive?

For this purpose, we reference a dataset crawled by Derek Lim and Professor Austin Benson between September 2019 and January 2020. The dataset is broken down into 3 categories: “Users”, “Annotations”, and “Artists & Songs”. “User” contains information on the user, including User IQ, their roles (Contributor, Editor), and the number of annotations they’ve given. “Annotations” contains details on each annotations’ verification status, number of votes, number of pyongs (how many times this annotation has been shared by other users), associated songs and lyrics, as well as its edit history. “Artists & Songs” includes the number of followers an artist has and the number of contributors a song has. It’s important to note that all activity on Genius is voluntary, which results in a big, _messy_ dataset.

Votes are the Genius community’s way of determining whether an annotation is helpful, insightful, interesting, etc. Identifying what makes a “good”  annotation can be useful in helping Genius staff editors more efficiently prune submissions to be included in the official Genius lyrical breakdown. Additionally, this can be integrated into Genius’ system of “penalty-boxing” which suspends a contributor’s activity if they consistently have inaccurate annotations. 	

Thank you,
Geniuses 4 Genius
