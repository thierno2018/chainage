# Reponse

## Commande utilisée

```
 grep \"raw\" **/package.json | awk -F ':'  '{print $3}'| sed -e 's|["'\'']||g' | awk -F '@' '{print ($1 " " $2)}' | sort | uniq | awk -F ',' '{print $1}'

```
 


## Le résultat

Listing de la commande passée : 

```

acorn 3.3.0
 acorn 5.3.0
 acorn-jsx 3.0.1
 ajv 5.5.2
 ajv-keywords 2.1.1
 align-text 0.1.4
 amdefine 1.0.1
 ansi-escapes 3.0.0
 ansi-regex 2.1.1
 ansi-regex 3.0.0
 ansi-styles 2.2.1
 ansi-styles 3.2.0
 append-transform 0.4.0
 archy 1.0.0
 argparse 1.0.9
 array-union 1.0.2
 array-uniq 1.0.3
 array-unique 0.2.1
 arr-diff 2.0.0
 arr-flatten 1.1.0
 arrify 1.0.1
 asn1 0.2.3
 assert-plus 0.2.0
 assert-plus 1.0.0
 async 1.5.2
 asynckit 0.4.0
 aws4 1.6.0
 aws-sign2 0.6.0
 aws-sign2 0.7.0
 babel-code-frame 6.26.0
 babel-generator 6.26.0
 babel-messages 6.23.0
 babel-runtime 6.26.0
 babel-template 6.26.0
 babel-traverse 6.26.0
 babel-types 6.26.0
 babylon 6.18.0
 balanced-match 1.0.0
 bcrypt-pbkdf 1.0.1
 bind-obj-methods 1.0.0
 bluebird 3.5.1
 boom 2.10.1
 boom 4.3.1
 boom 5.2.0
 brace-expansion 1.1.8
 braces 1.8.5
 builtin-modules 1.1.1
 caching-transform 1.0.1
 caller-path 0.1.0
 callsites 0.2.0
 camelcase 1.2.1
 camelcase 4.1.0
 caseless 0.11.0
 caseless 0.12.0
 center-align 0.1.3
 chalk 1.1.3
 chalk 2.3.0
 chardet 0.4.2
 circular-json 0.3.3
 clean-yaml-object 0.1.0
 cli-cursor 2.1.0
 cliui 2.1.0
 cliui 3.2.0
 cli-width 2.2.0
 co 4.6.0
 code-point-at 1.1.0
 color-convert 1.9.1
 color-name 1.1.3
 color-support 1.1.3
 combined-stream 1.0.5
 commander 2.13.0
 commondir 1.0.1
 concat-map 0.0.1
 concat-stream 1.6.0
 convert-source-map 1.5.1
 core-js 2.5.3
 core-util-is 1.0.2
 coveralls 2.13.3
 coveralls 3.0.0
 cross-spawn 4.0.2
 cross-spawn 5.1.0
 cryptiles 2.0.5
 cryptiles 3.1.2
 dashdash 1.14.1
 debug 2.6.9
 debug 3.1.0
 debug-log 1.0.1
 decamelize 1.2.0
 deep-is 0.1.3
 default-require-extensions 1.0.0
 del 2.2.2
 delayed-stream 1.0.0
 detect-indent 4.0.0
 diff 1.4.0
 doctrine 2.0.2
 ecc-jsbn 0.1.1
 error-ex 1.3.1
 escape-string-regexp 1.0.5
 eslint 4.14.0
 eslint-config-usecases 1.2.2
 eslint-scope 3.7.1
 eslint-visitor-keys 1.0.0
 espree 3.5.2
 esprima 2.7.3
 esprima 4.0.0
 esquery 1.0.0
 esrecurse 4.2.0
 estraverse 4.2.0
 esutils 2.0.2
 events-to-array 1.1.2
 execa 0.7.0
 expand-brackets 0.1.5
 expand-range 1.8.2
 extend 3.0.1
 external-editor 2.1.0
 extglob 0.3.2
 extsprintf 1.3.0
 fast-deep-equal 1.0.0
 fast-json-stable-stringify 2.0.0
 fast-levenshtein 2.0.6
 figures 2.0.0
 file-entry-cache 2.0.0
 filename-regex 2.0.1
 fill-range 2.2.3
 find-cache-dir 0.1.1
 find-up 1.1.2
 find-up 2.1.0
 flat-cache 1.3.0
 foreground-child 1.5.6
 forever-agent 0.6.1
 for-in 1.0.2
 form-data 2.1.4
 form-data 2.3.1
 for-own 0.1.5
 fs-exists-cached 1.0.0
 fs.realpath 1.0.0
 functional-red-black-tree 1.0.1
 function-loop 1.0.1
 generate-function 2.0.0
 generate-object-property 1.2.0
 get-caller-file 1.0.2
 getpass 0.1.7
 get-stream 3.0.0
 glob 7.1.2

```
