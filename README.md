# structuring_data_science_2
A secondary method for structuring online data science resources.
A video presenting the project and initial results is below:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=tpAQ-9vlJtw" target="_blank"><img src="http://img.youtube.com/vi/tpAQ-9vlJtw/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

CODE TO BE UPLOADED SOON

### Overview of Methods Used
Used topic modeling to relate technical resources to one another.  Extracting the fundamental concepts in a text and creating links to other resources by their concept similarities. Allowing a user to read a journal and directly see videos or blogs covering those same concepts.
- TFIDF+SVD pipeline created to generate topic similarities based on concept vocabulary created. 
- Network graph created for topic ontologies and PageRank used in recommendation engine.
- MongoDB database created for hosting the different data collections.
- Multiple web spiders developed to mine blog pages and video transcripts with a corpus of 80k blog pages, 30k papers and 8k video transcripts curated.
- Deployed through a flask generated website.
