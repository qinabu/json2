# json2

json2 is xml2 for json

Example 1

    $ echo '{"name": "value", "name2": ["value2", "value3"]}' | ./json2
    /name=value
    /name2/0=value2
    /name2/1=value3

Example 2

    $ echo '"scalar"' | ./json2
    scalar
