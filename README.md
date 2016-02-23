# Collection of tools related to libraries written in PHP [to be continued ...]

Pull requests are welcome!

## SRU/SRW

|name|description|license|requires|
|---|---|---|---|
|scriptotek/sru-client|Package for making Search/Retrieve via URL requests and parse the responses|MIT|danmichaelo/quitesimplexmlelement: >=0.2.1<br>guzzle/guzzle: ~3.8|
|ck/sru|A very simple PHP SRU search client|-|-|

## MARC

|name|description|license|requires|
|---|---|---|---|
|medlib/marcxml|-|MIT|php: >=5.5.9<br>nesbot/Carbon: 1.*<br>danmichaelo/quitesimplexmlelement: ~0.2.4<br>illuminate/support: ~4.1\|~5.0|
|scriptotek/marc|Simple interface to parsing MARC records using File_MARC|GNU-LGPL|php: >=5.3<br>ck/file_marc_reference: dev-master<br>pear/file_marc: *|
|scriptotek/simplemarcparser|A simple MARC21/XML parser|MIT|php: >=5.3<br>danmichaelo/quitesimplexmlelement: ~0.2.4<br>nesbot/carbon: 1.*<br>illuminate/support: ~4.1\|~5.0|
|pear/file_marc|Supports the MAchine Readable Cataloging (MARC) file format documented at http://loc.gov/marc/|LGPL-2.1|pear/pear_exception: 1.*|
|ck/file_marc_reference|MARCspec adapter for File_MARC|MIT|ck/php-marcspec: ^1.0<br>php: >=5.4.0<br>pear/file_marc: ^1.1|
|ck/php-marcspec|PHP based MARCspec parser and validator|MIT|php: >=5.4.0|
|tonyhhyip/marc4php|Marc Handle with PHP|LGPL-3.0+|php: >=5.3.1|
|swiss-social-archives/alephmarc2xml|This php class converts an MARC output from Aleph to a XML file|MIT|php: >=5.2|

## Pica

|name|description|license|requires|
|---|---|---|---|
|hab/picareader|Classes for reading Pica+ records encoded in Pica, PicaXML and PicaPlain|GPL-3.0+|hab/picarecord: ~1.0|
|hab/picarecord |Object oriented interface to Pica+ records, fields, and subfields|GPL-3.0+|-|
|hab/picawriter |Classes for writing Pica+ records to PicaXML and PicaPlain|GPL-3.0+|hab/picarecord: ~1.0|
|ck/picaxmlconv|Converts PicaXML (namespace info:srw/schema/5/picaXML-v1.0) and ppxml (namespace http://www.oclcpica.org/xmlns/ppxml-1.0) vice versa.|MIT|lib-libxml|

## ILS

|name|description|license|requires|
|---|---|---|---|
|scriptotek/alma-client|Package for interacting with some of the Alma APIs|MIT|php : ^5.5 \|\| ^7.0<br>guzzlehttp/guzzle: ~6.0<br>scriptotek/marc: dev-master<br>danmichaelo/quitesimplexmlelement: ^0.3.0<br>scriptotek/sru-client: ~0.3.0|
|hab/picaauth|A collection of authentication modules for Pica based library systems|GPL-3.0+|-|
|hab/simplesamlphp-module-pica |Provides authentication module for Pica-based library systems|GPL-3.0+|simplesamlphp/composer-module-installer: ~1.0<br>hab/picaauth: ~0.1|
|worldcat/discovery|Library to interact with OCLC's WorldCat Discovery Web Services|Apache-2.0|php : >=5.4.0<br>lib-curl : *<br>lib-openssl : *<br>ext-curl : *<br>ext-json : *<br>ext-openssl : *<br>guzzle/guzzle : >=3.7.0,<3.9.0<br>easyrdf/easyrdf : *<br>OCLC/Auth : *|

# OAI-PMH

|name|description|license|requires|
|---|---|---|---|
|scriptotek/oai-pmh-client|Package for harvesting data from OAI-PMH repositories|MIT|php: >=5.3<br>danmichaelo/quitesimplexmlelement: ~0.2<br>guzzle/guzzle: ~3.8<br>evenement/evenement: 1.0.*|

# Data quality

|name|description|license|requires|
|---|---|---|---|
|pear/validate_ispn|Validation class for ISPN (International Standard Product Numbers)|BSD-2-Clause|pear/validate: *|

# Discovery

|name|description|license|requires|
|---|---|---|---|
|vufind/vufind|A flexible discovery layer.|GPL-2.0|aferrandini/phpqrcode: 1.0.1<br>jasig/phpcas: 1.3.3<br>cap60552/php-sip2: 1.0.0<br>los/losrecaptcha: 1.0.0<br>ahand/mobileesp: dev-master<br>ocramius/proxy-manager: 1.0.2<br>oyejorge/less.php: 1.7.0.9<br>pear/file_marc: 1.1.2<br>pear/validate_ispn: dev-master<br>serialssolutions/summon: 1.0.0<br>symfony/yaml: 2.7.6<br>vufind-org/vufindcode: 1.0.2<br>vufind-org/vufindhttp: 2.0.0<br>zendframework/zendframework: 2.4.6<br>zendframework/zendrest: 2.0.2<br>zendframework/zendservice-amazon: 2.0.4<br>zf-commons/zfc-rbac: 2.5.2|

# JSKOS

|name|description|license|requires|
|---|---|---|---|
|gbv/jskos|PHP library to access and serve JSKOS data and services|LGPL|"phpunit/phpunit": "~4.8"<br>"jakub-onderka/php-parallel-lint": "~0.9"<br>"jakub-onderka/php-console-highlighter": "~0.3"|

# Template

|name|description|license|requires|
|---|---|---|---|
|||||
