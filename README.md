Swiss army knife for dealing with JSON on the CLI.

Why another JSON filtering tool ?
Becase there are things to improve.

Goals:
* usable in unix pipe
* colored output on terminal
* uses json path
* able to format json
* relaxed and intuitive query syntax
* able to process stream of json objects (a la jsonlines)
* able to filter json objects by contents/structure
* able to edit json object

Switches:
* -c, --compact : output compact representation (--inline)
* --color
* ? --ptr : use json pointer instead of json path
* -r, --replace : replace matched expression with given value (expression ?)
* -d, --delete : delete matching paths inside objects
* -v, --invert : delete everything _but_ the matching paths inside objects

Maybe goals:
* support yaml
* support toml
* xml version using xpath ?
* csv version ?

Prior art:
* [jq](https://stedolan.github.io/jq/)
* [jql](https://github.com/yamafaktory/jql)
