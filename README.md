A repository for converting popular NER datasets to ConLL formats.

# Ontonotes 5.0 

* Ontonotes from LDC
** Obtain the Ontonotes 5.0 from Penn LDC Language Resources
Login to Penn LDC through your institutional login or register - https://catalog.ldc.upenn.edu/signup
Request the resource from the link - https://catalog.ldc.upenn.edu/LDC2013T19
The link to the resource would be mailed to you. Download and unpack the Ontonotes release.

** Verify the directory structure 
$ tree -L 3 -d ontonotes-release-5.0/data/files/data/
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

* CoNLL format files 

** Download from https://github.com/ontonotes/conll-formatted-ontonotes-5.0/releases/tag/v12 and unpack.
OR 
Run the commands -
$ wget https://github.com/ontonotes/conll-formatted-ontonotes-5.0/archive/v12.tar.gz
$ tar zxvf v12.tar.gz

** Verify the directory structure
$ tree -L 7 -d conll-formatted-ontonotes-5.0-12/data/files/data

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
conll-formatted-ontonotes-5.0-12
└── conll-formatted-ontonotes-5.0
    └── data
        ├── conll-2012-test
        │   └── data
        │       └── english
        │           └── annotations
        ├── development
        │   └── data
        │       └── english
        │           └── annotations
        ├── test
        │   └── data
        │       └── english
        │           └── annotations
        └── train
            └── data
                └── english
                    └── annotations

** More information about the format can be found here - http://cemantix.org/data/ontonotes.html 
