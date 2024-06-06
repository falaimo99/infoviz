# Iconographic research:
**Big question**
There are symbols in artistic represantation, are we able to track the evolution in symbols choice following a time series, determining how they changed through artistic periods? (Artist who went through strong changes are i.e. Picasso, Kandinskiy)
	
### Research questions:

- Which are the main symbols (having more than one occurrence) in this artist production or in this movement?
- Do they change in a given relevant time series?

Social relevant question
- Are they exotic? (maybe difficult to keep track)
- Are they more or less abstract? (difficult to know)
- How "coral" these representations are? (how crowded they are according to a bare count of distinct subjects)

### Storytelling and general structure ideas
- Maybe a comparison between two close art movements such as impressionism and expressionism using different datasets
	
### Options about the database:

- Most painful one: BUILDING IT FROM WIKIPEDIA
- Less painful one: We find something that contains a similar property to property:P180 from wikidata (depicts)
- ???: We mix up stuff and hope for the best?

### Social relevance

Keeping track of artists or movement subjects according to a workflow of data querying and 
 
### Problems
Do we have enough data about this? Wikidata may record too few works per artist (don't know if it's a copyright problem)

---

# Datasets considerations and analysis
### [huggan/wikiart](https://huggingface.co/datasets/huggan/wikiart/viewer/default/train)

Pros:
- big dataset extracted from wikiart (contains )
- the columns genre and style contains a strong and significant correlation for  the project

Cons:
- few columns
- no ids or identification because it's a training ml set, so it contains just basic metadata about the raster image that is the main focus
- 30gbs

Potential questions it can answer:
- Frequency per artist or movement of a certain genre, we can dispose it in a time series to visualize it, or just leave it to a Movement / Artist vs Frequency of genre

- We can use it to "confirm" the fewer data we extract from other sets

---

### [kaggle](https://www.kaggle.com/datasets/steubk/wikiart)

# Changing focus (storytelling idea)


# Designing the dataset from wikidata

__why wikidata?__ the property depicts is stricter than the one used by the one used by _dbpedia_

starting point => movement ==artists_adering_to_the_movement=> artists ==notable_works=> works ==depicts / icon_class_notation=> symbols 

__GOTTA CHECK ARTCHIVES PROPERTIES__