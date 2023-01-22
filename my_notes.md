


## 4. Extending a Service

### 4.1

Install the package for doing http requests

```
pip install requests
```

```python
response = requests.get(
    "http://api.worldbank.org/v2/countries/USA/indicators/SP.POP.TOTL?per_page=5000&format=json")

last_twenty_years = response.json()[1][:20]
```
