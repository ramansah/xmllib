## Synopsis

The utility library for Python to convert between xml and dict objects

## Usage

test_string = '<parent><child2>CHILD2</child2><child1><child11>CHILD11</child11></child1></parent>'

print(xml2dict(test_string))

test_obj = {
    'parent': {
        'child1': {
            'child11': 'CHILD11'
        },
        'child2': 'CHILD2'
    }
}

print(dict2xml(test_obj))

## License

MIT License. Further details in LICENSE.txt