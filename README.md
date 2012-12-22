# Senticnet API

Ultra simple API to use Senticnet without be bothered by RDF stuff.

## Dependencies

You need to install the rdflib:

```
$ pip install rdflib
```

## How to use

```python
from senticnet import Senticnet

sn = Senticnet()
polarity = sn.get_polarity("Friday night")
```
