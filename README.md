A repository for converting popular NER datasets to CoNLL formats.

# Ontonotes 5.0

## Ontonotes from LDC

* Obtain the Ontonotes 5.0 from Penn LDC Language Resources
* Login to Penn LDC through your institutional login or register - https://catalog.ldc.upenn.edu/signup<br />
* Request the resource from the link - https://catalog.ldc.upenn.edu/LDC2013T19
* The link to the resource would be mailed to you. Download and unpack the Ontonotes release. 
* Verify the directory structure by running the command - 

``
$ tree -L 3 -d ontonotes-release-5.0/data/files/data/
``
```
ontonotes\_5/data/files/data/
├── arabic
│   ├── annotations
│   │   └── nw
│   └── metadata
│       ├── frames
│       └── sense-inventories
├── chinese
│   ├── annotations
│   │   ├── bc
│   │   ├── bn
│   │   ├── mz
│   │   ├── nw
│   │   ├── tc
│   │   └── wb
│   └── metadata
│       ├── frames
│       └── sense-inventories
├── english
│   ├── annotations
│   │   ├── bc
│   │   ├── bn
│   │   ├── mz
│   │   ├── nw
│   │   ├── pt
│   │   ├── tc
│   │   └── wb
│   └── metadata
│       ├── context
│       ├── frames
│       └── sense-inventories
└── ontology
    └── sense-pools
    └── ...
```
<tree>
    
## ConLL03 formatted Ontonotes 

* Download from https://github.com/ontonotes/conll-formatted-ontonotes-5.0/releases/tag/v12 and unpack.<br/>
OR<br/> 
Run the commands -<br/>
``
$ wget https://github.com/ontonotes/conll-formatted-ontonotes-5.0/archive/v12.tar.gz<br/>
$ tar zxvf v12.tar.gz<br/>
``

* Verify the directory structure by running the command - 
```
$ tree -L 7 -d conll-formatted-ontonotes-5.0-12/data/files/data
```
```
conll-formatted-ontonotes-5.0-12
└── conll-formatted-ontonotes-5.0
    └── data
        ├── conll-2012-test
        │   └── data
        │       └── english
        │           └── annotations
        │               ├── bc
        │               ├── bn
        │               ├── mz
        │               ├── nw
        │               ├── pt
        │               ├── tc
        │               └── wb
        ├── development
        │   └── data
        │       └── english
        │           └── annotations
        │               ├── bc
        │               ├── bn
        │               ├── mz
        │               ├── nw
        │               ├── pt
        │               ├── tc
        │               └── wb
        ├── test
        │   └── data
        │       └── english
        │           └── annotations
        │               ├── bc
        │               ├── bn
        │               ├── mz
        │               ├── nw
        │               ├── pt
        │               ├── tc
        │               └── wb
        └── train
            └── data
                └── english
                    └── annotations
                        ├── bc
                        ├── bn
                        ├── mz
                        ├── nw
                        ├── pt
                        ├── tc
                        └── wb
```

* More information about the format can be found here - http://cemantix.org/data/ontonotes.html 

# TempEval
