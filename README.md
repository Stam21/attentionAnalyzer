# attentionAnalyzer
Analyze and understand what attention heads a transformer-based language model is paying attention to. This implementation makes use of google's BERT model and provides some diagrams to get an insight on how this model understands language based on its attention mechanism.

## Example

You can experiment with the input and provide your own sentences to the program. First you need to install the necessary dependencies by running :

```
pip install -r requirements.txt
```

Then you can run the python file :

```
python mask.py

Text:  We turned down a narrow lane and passed through a small [MASK].


------
OUTPUT
------
We turned down a narrow lane and passed through a small field.
We turned down a narrow lane and passed through a small clearing.
We turned down a narrow lane and passed through a small park.
``` 


