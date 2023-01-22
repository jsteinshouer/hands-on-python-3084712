


## 4. Extending a Service

### 4.1 http requests

Install the package for doing http requests

```
pip install requests
```

```python
response = requests.get(
    "http://api.worldbank.org/v2/countries/USA/indicators/SP.POP.TOTL?per_page=5000&format=json")

last_twenty_years = response.json()[1][:20]
```


### 4.2 Flask

```
pip install flask
```

dunderscore - i.e. __name__

decorators

```
@app.route("/")
```

Run the app

```python
app.run(debug=True)
```

Render an html template

```python
# template found in templates/index.html
return render_template("index.html")
```

redner json data

```python
return jsonify(results)
```

### 4.3 Searching through data

Ex_Files/04_03_begin/app.py

### Next Steps

- Advanced Python with Joe Marini
- Faster Python Code
- Secure python code

