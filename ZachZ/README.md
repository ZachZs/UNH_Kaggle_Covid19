# File Information

 <ul>
  <li><em>Loading In Files.ipynb</em>: This notebook contains code for loading and formatting the papers from the Kaggle site. Since there was already a few people posting the results of searching through the data, I decided to see if there was an alternate way to laod in the JSON files into pandas. Using the dictor package, it is simple to navigate the nested lists/dicts in order to extract features to use</li>
  <li><em>Covid Papers Search Tool</em>: This notebook adds to the <em>Loading In Files.ipynb</em> notebook. A basic search tool (since it only uses direct matches) was generated using spaCy to tokenize the papers and the search terms, and to return papers that had matches. A more comlex search tool using Doc2Vec was used to select a paper and find the most similar papers based on the created vectors. Finally, three different models (LDiA, NMF, and LSA) were used to generate topics for the papers.</li>
</ul> 
