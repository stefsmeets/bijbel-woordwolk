## Bijbel woordwolk

Jupyter notebook to generate word clouds from the Bible.

```console
virtualenv .venv -p 3.10
. .venv/bin/activate
pip install -r requirements.txt
```

Make sure to download the right model:

```bash
spacy download nl_core_news_sm
```

![Bible word cloud](bible.svg)
