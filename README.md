
<p align="left" ><b><i>Authors:</i></b></p> 
<p align="left"> Anastasiia Khaburska</p>
<p align="left"> Dmitri Glusco</p>
<p align="left"> Maksym Opirskyi</p>
<p align="left"> Oleh Misko</p>
<p align="left"> Valerii Veseliak</p>

# MMDS-wikipedia

### News sources diversity
- **Problem Statement:** Calculate and show the diversity of sources of some news articles
- **Define ML tasks:** We want to draw metrics about the diversity of sources (e.g. how many different news sources, and/or political bias of sources, if we can find this data) across article topics and quality levels in English. This is basically about using ores to categorize quality and topics of articles and parse dumps to calculate some sort of diversity metric at the source level, then look at the distribution across topic dimensions. Could be extended by characterizing articles according to the average expertise of editors, etc. 
- **Data:** We will use provided data and if needed scrap the web for some data.
- **Evaluation:** We will calculate diversity for some topics by hand and compare them with the ones that our algorithm will show.
- **Justification:** There exist methods for text summarization. We can use them for extracting the main content of the news article. Based on these features we will be able to predict the truth of the news.
- **Impact:**  We consider that it would be useful to have an ability to quickly get a sense of the diversity of sources for news since a lot of people nowadays tend not to believe in news articles since biases and unfairness are easily added to them.
We believe that provided data contain enough information 
                   

### Wikipedia
www.wikidata.org

https://dumps.wikimedia.org/enwiki/latest/

- **Problem Statement:** extract and construct an interactive map for the provenance of historical artefacts such as artworks, archaeological and paleontological remaining. To show the inflow and outflow of historical artifacts for each country.        
- **Define ML tasks:** construct two bipartite graphs that show the provenance and the displaying place of historical artifacts respectively.
- **Data:** We are aiming to use semantic web structure of [WikiData](www.wikidata.org)
- **Evaluation:** Check the consistency of the graph structure and check topics by hand and compare them with the results that our algorithm will show. 
- **Justification:** We suppose, that in the artwork article description should be the origin place. Moreover, we assume that we will also be able to extract information about the current residence of the artwork directly from the text. So the idea to create a historical path of the artwork through the time.
