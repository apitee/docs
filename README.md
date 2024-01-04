 [docs](http://docs.apitee.com)

IaC solution multiplatform, can provide services based on kubernetes/gitlab/docker in automated way, 
You write the scenario and the operation script can be easly runneda and updated
It's an opened standard for DSL and DEpendency Definition creating for automation and AI/ML integration on any environment with any techstack.

## Secure

+ private variables
+ passwords
+ credentials
+ api keys
+ rights
+ roles

are not depends the script, sensitive data remains in the script-independent secure handling layer
as an browser pocket store for passwords and is sharing just data selected to the script in the environment like:
+ gitlab pipeline
+ docker environment
+ private user environment
+ kubernetes cluster
+ ....

## Usage

+ integration for browser, shell, email client
+ integration many platform based on shell/browser client
+ automation for cloud, embedded, edge infrastructure

## Why yaml

The yaml give a benefit to create multilanguage layer with the way to use line by line commands in shell
The structure is offering grammatics for building the correct sentences with validation


## Start

Without params:
```bash
lua apitee.lua
```

Result:
```shell
git.yaml
test.yaml
```


with file and extension
```bash
lua apitee.lua git.yaml
```


without extension
```bash
lua apitee.lua git
```


with sentence to run selected line:
```bash
lua apitee.lua RUN HOST client 1
```



## Schema

### types

+ as yaml doc structure
+ as sentence, in shell, text file, csv


### structure

+ global apitee command from command
+ local defined in yaml functions by SET
+ imported by GET


### yaml schema

+ VERSION
+ GET - require
+ DOC - documentation, description by url
+ VAR - set local variable
+ FUN - set local function
+ RUN - run script by defined functions


