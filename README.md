# Regex-Filter

<b>STATUS : DEVELOPING</b>

Use Case 1: `online`

```python

X = RegexFilter(['https://github.com/hackerarbaz/Tryme/blob/master/creds.py','http://anysite.com/'],'online',{'CSE':'.+\.xml','PASS':'PASSWORD'})
XX = X.output()
XX.items()
```

Use Case 2: `offline`

```python

X = RegexFilter({r'/kiraakboi/cralwed/woot/1.raw':'1'},'offline',{'CSE':'.+\.txt','PASS':'checking '})
XX = X.output()
XX.items()

```

```python
from collections import Counter
for each_url,each_res in XX.items():
    pattern_match_count = dict(Counter(each_res))
    print(each_url,a)
```

````
> https://github.com/realchief/Node.js_Ecommerce/blob/c917f1aaeeb42a83677ef18fa036843ea603b85e/environment.json {'PASS': 213}
````

<i>`Random helper`</i>
