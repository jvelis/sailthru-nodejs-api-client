## Basic Node.js CLI for the Sailthru REST API

* Upload templates and includes

## Setup

* Add `config/credentials.json` and `config/config.json`
* Run `npm install`

## Examples

* Help
	`node . --help`

* Print the list of existing templates:
	`node . -t template -a "ACC1"`

* Print the list of includes:
	`node . -t include -a "ACC1"`


* To update an include:
	`node . -t include -a "ACC1" -f "core-module.html" -n "CoreModule"`

* To update a template:
	`node . -t template -a "ACC1" -f "template.html"`
	`node . -t template -a "ACC1" -f "template.html" -n "Template Name"`

* To update an include in all accounts:
	`node . -t include -a "ALL" -f "core-module.html" -n "CoreModule"`