# elastic-appsearch

Elastic App Search API Client

### Installation
`pip install elastic-appsearch`

### Usage

```python
from elastic_appsearch import Client

endpoint = 'app-search-api-endpoint'
key = 'private-key'

c = Client(endpoint, key)
```

##### Search
```python
c.search('engine-name', 'sunny')
```

##### Create a synonym
```python
c.create_synonym('engine-name', ['hi', 'hello', 'hiya'])
```

##### List all synonyms
```python
c.get_synonyms('engine-name')
```
