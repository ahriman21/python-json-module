# python-json-module
working with json in python

#### to work with json in python import json module 
```
import json
```

#### convert a dictionary to json
```
my_dictionary_file = {name: 'Bob', last: 'Alex'}
my_json_file = json.dump(my_dictionary, indent=4)
```

#### convert a json to dictionary
```
json_file = {name:"Mohammed" ,last:"Salah"}
dictionary_file = json.loads(json_file)
```
