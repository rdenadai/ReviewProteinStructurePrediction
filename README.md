In this post i'll present the study i made for a state of art project for my class in this semester, where the subject of research was the field of protein structure prediction.

Protein Structure Prediction is another biggest challenge that mankind is looking to solve. If solved or at least partially solved it could revolutionize medicine and drug industry.

At the end of the day, the search is the simple process of given a amino-acid sequence, one must predict the 3D structure of the protein given physical restrictions (lower energy cost given by [Gibbs Free Energy][1]).

### Motivation

Proteins are a important part of every organism, they, for example, help in the transport of molecules between cells. Given their importance, as much proteins we know, the best we could find, for example,  better treatments to diseases.

### Research

I start the research choosing terms to search for and what bases i'll apply those terms.

Not an easy task to find terms to search if you are not familiar with the theme, but, at the end got to the following:

 - "protein structure prediction"
 - "protein structure similarity"
 - "protein structure modeling"
 - protein  "structure determination"
 - automated "protein structure determination"

And decided to search in [Google Scholar][2] and [PubMed][3].

Search throught does bases are easy and one could easily apply some filters, and that's was done. I limit my research filtering Full Papers from 2016 to 2020, getting the first 20 papers from best match results (the sites gives you the option to sort by date or best match).

After collect all papers, a new filter was made, preprocessing the papers by reading their abstract and seeing if there is some relationship with the theme, and the selected the most recently or the ones that have some interesting content. At the end i ended up with 22 papers to read.

![Searched papers distribution over years][4]

It's interesting to note that the number of papers in the research was getting high, but some strange down in 2019, so i thought why not to sum all papers from 2000 to 2020 given the terms.
Since PubMed gives a nice csv file to download, i joined the values for each of the terms over the years.
We could see a nice linear trend over the years.

![PubMed searched paper distribution over years][5]

### Prediction Models

After reading the papers (and search over the internet for terms and better explanation about topics related to proteins), there is a  separation between two methods to predict protein structures:

 - **ab initio**:
 - **template-based**:



  [1]: https://en.wikipedia.org/wiki/Gibbs_free_energy
  [2]: https://scholar.google.com.br/
  [3]: https://pubmed.ncbi.nlm.nih.gov/
  [4]: https://rdenadai-blog.s3-us-west-2.amazonaws.com/media/extra/papers.png
  [5]: https://rdenadai-blog.s3-us-west-2.amazonaws.com/media/extra/papers_pubmed.png