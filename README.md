# spacysentiment
sentiment analysis using spacy

## Implementation

- __Clone the repository to your local__

```
cd spacysentiment/
unzip spacysentiment.zip
```

- __Implement the below code to get sentiment using spacy__

```python
import spacy
nlp = spacy.load("models/spacysentiment/")
input_text = input()
doc = nlp(input_text)
doc.cats
```

- __Result__
```
input_text =  Its completely useless mate, we can do it the way we want
docs.cats = {'positive': 0.29878824949264526, 'negative': 0.7012117505073547}
```