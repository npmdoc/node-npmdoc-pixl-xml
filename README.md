# api documentation for  [pixl-xml (v1.0.10)](https://github.com/jhuckaby/pixl-xml)  [![npm package](https://img.shields.io/npm/v/npmdoc-pixl-xml.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-pixl-xml) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-pixl-xml.svg)](https://travis-ci.org/npmdoc/node-npmdoc-pixl-xml)
#### A simple module for parsing and composing XML.

[![NPM](https://nodei.co/npm/pixl-xml.png?downloads=true)](https://www.npmjs.com/package/pixl-xml)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pixl-xml/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-pixl-xml_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pixl-xml/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-pixl-xml/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-pixl-xml/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Joseph Huckaby",
        "email": "jhuckaby@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/jhuckaby/pixl-xml/issues"
    },
    "dependencies": {},
    "description": "A simple module for parsing and composing XML.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "aedc1a47d8b16b9a71d9dad9f51332163f7a70ee",
        "tarball": "https://registry.npmjs.org/pixl-xml/-/pixl-xml-1.0.10.tgz"
    },
    "gitHead": "2f6b7612813836bcdde22eac255e4c914bd1dd8e",
    "homepage": "https://github.com/jhuckaby/pixl-xml",
    "keywords": [
        "xml"
    ],
    "license": "MIT",
    "main": "xml.js",
    "maintainers": [
        {
            "name": "jhuckaby",
            "email": "jhuckaby@gmail.com"
        }
    ],
    "name": "pixl-xml",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jhuckaby/pixl-xml.git"
    },
    "scripts": {},
    "version": "1.0.10"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module pixl-xml](#apidoc.module.pixl-xml)
1.  [function <span class="apidocSignatureSpan">pixl-xml.</span>Parser (args, opts)](#apidoc.element.pixl-xml.Parser)
1.  [function <span class="apidocSignatureSpan">pixl-xml.</span>XML (args, opts)](#apidoc.element.pixl-xml.XML)
1.  [function <span class="apidocSignatureSpan">pixl-xml.</span>alwaysArray (obj, key)](#apidoc.element.pixl-xml.alwaysArray)
1.  [function <span class="apidocSignatureSpan">pixl-xml.</span>decodeEntities (text)](#apidoc.element.pixl-xml.decodeEntities)
1.  [function <span class="apidocSignatureSpan">pixl-xml.</span>encodeAttribEntities (text)](#apidoc.element.pixl-xml.encodeAttribEntities)
1.  [function <span class="apidocSignatureSpan">pixl-xml.</span>encodeEntities (text)](#apidoc.element.pixl-xml.encodeEntities)
1.  [function <span class="apidocSignatureSpan">pixl-xml.</span>firstKey (hash)](#apidoc.element.pixl-xml.firstKey)
1.  [function <span class="apidocSignatureSpan">pixl-xml.</span>hashKeysToArray (hash)](#apidoc.element.pixl-xml.hashKeysToArray)
1.  [function <span class="apidocSignatureSpan">pixl-xml.</span>isaArray (arg)](#apidoc.element.pixl-xml.isaArray)
1.  [function <span class="apidocSignatureSpan">pixl-xml.</span>isaHash (arg)](#apidoc.element.pixl-xml.isaHash)
1.  [function <span class="apidocSignatureSpan">pixl-xml.</span>numKeys (hash)](#apidoc.element.pixl-xml.numKeys)
1.  [function <span class="apidocSignatureSpan">pixl-xml.</span>parse (text, opts)](#apidoc.element.pixl-xml.parse)
1.  [function <span class="apidocSignatureSpan">pixl-xml.</span>stringify (node, name, indent, indent_string, eol)](#apidoc.element.pixl-xml.stringify)
1.  [function <span class="apidocSignatureSpan">pixl-xml.</span>trim (text)](#apidoc.element.pixl-xml.trim)
1.  object <span class="apidocSignatureSpan">pixl-xml.</span>Parser.prototype

#### [module pixl-xml.Parser](#apidoc.module.pixl-xml.Parser)
1.  [function <span class="apidocSignatureSpan">pixl-xml.</span>Parser (args, opts)](#apidoc.element.pixl-xml.Parser.Parser)

#### [module pixl-xml.Parser.prototype](#apidoc.module.pixl-xml.Parser.prototype)
1.  boolean <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>lowerCase
1.  boolean <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>preserveAttributes
1.  boolean <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>preserveDocumentNode
1.  [function <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>compose (indent_string, eol)](#apidoc.element.pixl-xml.Parser.prototype.compose)
1.  [function <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>error ()](#apidoc.element.pixl-xml.Parser.prototype.error)
1.  [function <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>getError (error)](#apidoc.element.pixl-xml.Parser.prototype.getError)
1.  [function <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>getLastError ()](#apidoc.element.pixl-xml.Parser.prototype.getLastError)
1.  [function <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>getTree ()](#apidoc.element.pixl-xml.Parser.prototype.getTree)
1.  [function <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>parse (branch, name)](#apidoc.element.pixl-xml.Parser.prototype.parse)
1.  [function <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>parseCDATANode (tag)](#apidoc.element.pixl-xml.Parser.prototype.parseCDATANode)
1.  [function <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>parseCommentNode (tag)](#apidoc.element.pixl-xml.Parser.prototype.parseCommentNode)
1.  [function <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>parseDTDNode (tag)](#apidoc.element.pixl-xml.Parser.prototype.parseDTDNode)
1.  [function <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>parsePINode (tag)](#apidoc.element.pixl-xml.Parser.prototype.parsePINode)
1.  [function <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>throwParseError (key, tag)](#apidoc.element.pixl-xml.Parser.prototype.throwParseError)
1.  object <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>patAttrib
1.  object <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>patCDATANode
1.  object <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>patCDATATag
1.  object <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>patCommentTag
1.  object <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>patDTDNode
1.  object <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>patDTDTag
1.  object <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>patEndCDATA
1.  object <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>patEndComment
1.  object <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>patEndDTD
1.  object <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>patExternalDTDNode
1.  object <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>patInlineDTDNode
1.  object <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>patNextClose
1.  object <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>patPINode
1.  object <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>patPITag
1.  object <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>patSelfClosing
1.  object <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>patSpecialTag
1.  object <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>patStandardTag
1.  object <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>patTag
1.  string <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>attribsKey
1.  string <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>dataKey



# <a name="apidoc.module.pixl-xml"></a>[module pixl-xml](#apidoc.module.pixl-xml)

#### <a name="apidoc.element.pixl-xml.Parser"></a>[function <span class="apidocSignatureSpan">pixl-xml.</span>Parser (args, opts)](#apidoc.element.pixl-xml.Parser)
- description and source-code
```javascript
function XML(args, opts) {
	// class constructor for XML parser class
	// pass in args hash or text to parse
	if (!args) args = '';
	if (isa_hash(args)) {
		for (var key in args) this[key] = args[key];
	}
	else this.text = args || '';
	
	// options may be 2nd argument as well
	if (opts) {
		for (var key in opts) this[key] = opts[key];
	}
	
	// stringify buffers
	if (this.text instanceof Buffer) {
		this.text = this.text.toString();
	}
	
	if (!this.text.match(/^\s*</)) {
		// try as file path
		var file = this.text;
		this.text = fs.readFileSync(file, { encoding: 'utf8' });
		if (!this.text) throw new Error("File not found: " + file);
	}
	
	this.tree = {};
	this.errors = [];
	this.piNodeList = [];
	this.dtdNodeList = [];
	this.documentNodeName = '';
	
	if (this.lowerCase) {
		this.attribsKey = this.attribsKey.toLowerCase();
		this.dataKey = this.dataKey.toLowerCase();
	}
	
	this.patTag.lastIndex = 0;
	if (this.text) this.parse();
}
```
- example usage
```shell
...
var xml_string = '<?xml version="1.0" encoding="UTF-8"?><Document>' +
	'<Simple>Hello</Simple>' +
	'<Node Key="Value">Complex</Node>' +
	'</Document>';

var parser = null;
try {
	parser = new XML.Parser( xml_string, { preserveAttributes: true } );
}
catch (err) {
	throw err;
}

var doc = parser.getTree();
doc.Simple = "Hello, I changed this.";
...
```

#### <a name="apidoc.element.pixl-xml.XML"></a>[function <span class="apidocSignatureSpan">pixl-xml.</span>XML (args, opts)](#apidoc.element.pixl-xml.XML)
- description and source-code
```javascript
function XML(args, opts) {
	// class constructor for XML parser class
	// pass in args hash or text to parse
	if (!args) args = '';
	if (isa_hash(args)) {
		for (var key in args) this[key] = args[key];
	}
	else this.text = args || '';
	
	// options may be 2nd argument as well
	if (opts) {
		for (var key in opts) this[key] = opts[key];
	}
	
	// stringify buffers
	if (this.text instanceof Buffer) {
		this.text = this.text.toString();
	}
	
	if (!this.text.match(/^\s*</)) {
		// try as file path
		var file = this.text;
		this.text = fs.readFileSync(file, { encoding: 'utf8' });
		if (!this.text) throw new Error("File not found: " + file);
	}
	
	this.tree = {};
	this.errors = [];
	this.piNodeList = [];
	this.dtdNodeList = [];
	this.documentNodeName = '';
	
	if (this.lowerCase) {
		this.attribsKey = this.attribsKey.toLowerCase();
		this.dataKey = this.dataKey.toLowerCase();
	}
	
	this.patTag.lastIndex = 0;
	if (this.text) this.parse();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pixl-xml.alwaysArray"></a>[function <span class="apidocSignatureSpan">pixl-xml.</span>alwaysArray (obj, key)](#apidoc.element.pixl-xml.alwaysArray)
- description and source-code
```javascript
function always_array(obj, key) {
	// if object is not array, return array containing object
	// if key is passed, work like XMLalwaysarray() instead
	if (key) {
		if ((typeof(obj[key]) != 'object') || (typeof(obj[key].length) == 'undefined')) {
			var temp = obj[key];
			delete obj[key];
			obj[key] = new Array();
			obj[key][0] = temp;
		}
		return null;
	}
	else {
		if ((typeof(obj) != 'object') || (typeof(obj.length) == 'undefined')) { return [ obj ]; }
		else return obj;
	}
}
```
- example usage
```shell
...
'''
ARRAY alwaysArray( MIXED )
'''

This function will wrap anything passed to it into an array and return the array, unless the item passed is already an array, in
 which case it is simply returned verbatim.

'''javascript
var arr = XML.alwaysArray( maybe_array );
'''

## hashKeysToArray

'''
ARRAY hashKeysToArray( OBJECT )
'''
...
```

#### <a name="apidoc.element.pixl-xml.decodeEntities"></a>[function <span class="apidocSignatureSpan">pixl-xml.</span>decodeEntities (text)](#apidoc.element.pixl-xml.decodeEntities)
- description and source-code
```javascript
function decode_entities(text) {
	// Decode XML entities into raw ASCII
	if (text == null) return '';
	
	if (text && text.replace && text.match(/\&/)) {
		text = text.replace(/\&lt\;/g, "<");
		text = text.replace(/\&gt\;/g, ">");
		text = text.replace(/\&quot\;/g, '"');
		text = text.replace(/\&apos\;/g, "'");
		text = text.replace(/\&amp\;/g, "&"); // MUST BE LAST
	}
	
	return text;
}
```
- example usage
```shell
...
STRING decodeEntities( STRING )
'''

This function decodes all the standard XML entities back into their original characters.  This includes ampersand ('&'), left-angle
-bracket ('<'), right-angle-bracket ('>'), single-quote (''') and double-quote ('"').  It is used when parsing XML element and attribute
 values.  Example:

'''javascript
var text = '&lt;Hello&gt;&quot;&amp;&quot;&lt;There&gt;';
console.log( XML.decodeEntities(text) );
// Would output: <Hello>"&"<There>
'''

## alwaysArray

'''
ARRAY alwaysArray( MIXED )
...
```

#### <a name="apidoc.element.pixl-xml.encodeAttribEntities"></a>[function <span class="apidocSignatureSpan">pixl-xml.</span>encodeAttribEntities (text)](#apidoc.element.pixl-xml.encodeAttribEntities)
- description and source-code
```javascript
function encode_attrib_entities(text) {
	// Simple entitize exports.for = function for composing XML attributes
	if (text == null) return '';
	
	if (text && text.replace) {
		text = text.replace(/\&/g, "&amp;"); // MUST BE FIRST
		text = text.replace(/</g, "&lt;");
		text = text.replace(/>/g, "&gt;");
		text = text.replace(/\"/g, "&quot;");
		text = text.replace(/\'/g, "&apos;");
	}
	
	return text;
}
```
- example usage
```shell
...
STRING encodeAttribEntities( STRING )
'''

This function does basically the same thing as [encodeEntities](#encodeentities), but it also includes encoding for single-quotes
 (''') and double-quotes ('"').  It is used for encoding an XML string for composing into an attribute value.  It returns the result
.  Example:

'''javascript
var text = '<Hello>"&"<There>';
console.log( XML.encodeAttribEntities(text) );
// Would output: &lt;Hello&gt;&quot;&amp;&quot;&lt;There&gt;
'''

## decodeEntities

'''
STRING decodeEntities( STRING )
...
```

#### <a name="apidoc.element.pixl-xml.encodeEntities"></a>[function <span class="apidocSignatureSpan">pixl-xml.</span>encodeEntities (text)](#apidoc.element.pixl-xml.encodeEntities)
- description and source-code
```javascript
function encode_entities(text) {
	// Simple entitize exports.for = function for composing XML
	if (text == null) return '';
	
	if (text && text.replace) {
		text = text.replace(/\&/g, "&amp;"); // MUST BE FIRST
		text = text.replace(/</g, "&lt;");
		text = text.replace(/>/g, "&gt;");
	}
	
	return text;
}
```
- example usage
```shell
...
STRING encodeEntities( STRING )
'''

This function will take a string, and encode the three standard XML entities, ampersand ('&'), left-angle-bracket ('<') and right
-angle-bracket ('>'), into their XML-safe counterparts.  It returns the result.  Example:

'''javascript
var text = '<Hello>&<There>';
console.log( XML.encodeEntities(text) );
// Would output: &lt;Hello&gt;&amp;&lt;There&gt;
'''

## encodeAttribEntities

'''
STRING encodeAttribEntities( STRING )
...
```

#### <a name="apidoc.element.pixl-xml.firstKey"></a>[function <span class="apidocSignatureSpan">pixl-xml.</span>firstKey (hash)](#apidoc.element.pixl-xml.firstKey)
- description and source-code
```javascript
function first_key(hash) {
	// return first key from hash (unordered)
	for (var key in hash) return key;
	return null; // no keys in hash
}
```
- example usage
```shell
...
STRING firstKey( OBJECT )
'''

This function returns the first key of the hash when iterating over it.  Note that hash keys are stored in an undefined order.

'''javascript
var my_hash = { foo: "bar", baz: 12345 };
var key = XML.firstKey( my_hash ); // foo or baz
'''

# Known Issues

* Serialized XML doesn't exactly match parsed XML.
* Unicode XML entities are not decoded when parsed.
...
```

#### <a name="apidoc.element.pixl-xml.hashKeysToArray"></a>[function <span class="apidocSignatureSpan">pixl-xml.</span>hashKeysToArray (hash)](#apidoc.element.pixl-xml.hashKeysToArray)
- description and source-code
```javascript
function hash_keys_to_array(hash) {
	// convert hash keys to array (discard values)
	var array = [];
	for (var key in hash) array.push(key);
	return array;
}
```
- example usage
```shell
...
ARRAY hashKeysToArray( OBJECT )
'''

This function returns all the hash keys as an array.  Useful for sorting and then iterating over the sorted list.

'''javascript
var my_hash = { foo: "bar", baz: 12345 };
var keys = XML.hashKeysToArray( my_hash ).sort();

for (var idx = 0, len = keys.length; idx < len; idx++) {
	var key = keys[idx];
	// do something with key and my_hash[key]
}
'''
...
```

#### <a name="apidoc.element.pixl-xml.isaArray"></a>[function <span class="apidocSignatureSpan">pixl-xml.</span>isaArray (arg)](#apidoc.element.pixl-xml.isaArray)
- description and source-code
```javascript
function isa_array(arg) {
	// determine if arg is an array or is array-like
	return isArray(arg);
}
```
- example usage
```shell
...
BOOLEAN isaArray( MIXED )
'''

This function returns 'true' if the provided argument is an array (or is array-like), 'false' otherwise.

'''javascript
var my_arr = [ "foo", "bar", 12345 ];
var is_arr = XML.isaArray( my_arr );
'''

## numKeys

'''
INTEGER numKeys( OBJECT )
'''
...
```

#### <a name="apidoc.element.pixl-xml.isaHash"></a>[function <span class="apidocSignatureSpan">pixl-xml.</span>isaHash (arg)](#apidoc.element.pixl-xml.isaHash)
- description and source-code
```javascript
function isa_hash(arg) {
	// determine if arg is a hash
	return( !!arg && (typeof(arg) == 'object') && !isa_array(arg) );
}
```
- example usage
```shell
...
BOOLEAN isaHash( MIXED )
'''

This function returns 'true' if the provided argument is a hash (object), 'false' otherwise.

'''javascript
var my_hash = { foo: "bar", baz: 12345 };
var is_hash = XML.isaHash( my_hash );
'''

## isaArray

'''
BOOLEAN isaArray( MIXED )
'''
...
```

#### <a name="apidoc.element.pixl-xml.numKeys"></a>[function <span class="apidocSignatureSpan">pixl-xml.</span>numKeys (hash)](#apidoc.element.pixl-xml.numKeys)
- description and source-code
```javascript
function num_keys(hash) {
	// count the number of keys in a hash
	var count = 0;
	for (var a in hash) count++;
	return count;
}
```
- example usage
```shell
...
INTEGER numKeys( OBJECT )
'''

This function returns the number of keys in the specified hash.

'''javascript
var my_hash = { foo: "bar", baz: 12345 };
var num = XML.numKeys( my_hash ); // 2
'''

## firstKey

'''
STRING firstKey( OBJECT )
'''
...
```

#### <a name="apidoc.element.pixl-xml.parse"></a>[function <span class="apidocSignatureSpan">pixl-xml.</span>parse (text, opts)](#apidoc.element.pixl-xml.parse)
- description and source-code
```javascript
function parse_xml(text, opts) {
	// turn text into XML tree quickly
	if (!opts) opts = {};
	opts.text = text;
	var parser = new XML(opts);
	return parser.error() ? parser.getLastError() : parser.getTree();
}
```
- example usage
```shell
...

'''javascript
var XML = require('pixl-xml');
'''

# Simplified API

The simplified API provides basic 'XML.parse()' and 'XML.stringify()' standalone functions for parsing and serializing XML.  Also
 see the [Object-Oriented API](#object-oriented-api) below, for more control over your XML.

Parse some XML by passing a string to 'XML.parse()':

'''javascript
var xml_string = '<?xml version="1.0"?><Document>' +
	'<Simple>Hello</Simple>' +
	'<Node Key="Value">Complex</Node>' +
...
```

#### <a name="apidoc.element.pixl-xml.stringify"></a>[function <span class="apidocSignatureSpan">pixl-xml.</span>stringify (node, name, indent, indent_string, eol)](#apidoc.element.pixl-xml.stringify)
- description and source-code
```javascript
function compose_xml(node, name, indent, indent_string, eol) {
	// Compose node into XML including attributes
	// Recurse for child nodes
	if (typeof(indent_string) == 'undefined') indent_string = "\t";
	if (typeof(eol) == 'undefined') eol = "\n";
	var xml = "";
	
	// If this is the root node, set the indent to 0
	// and setup the XML header (PI node)
	if (!indent) {
		indent = 0;
		xml = xml_header + eol;
		
		if (!name) {
			// no name provided, assume content is wrapped in it
			name = first_key(node);
			node = node[name];
		}
	}
	
	// Setup the indent text
	var indent_text = "";
	for (var k = 0; k < indent; k++) indent_text += indent_string;
	
	if ((typeof(node) == 'object') && (node != null)) {
		// node is object -- now see if it is an array or hash
		if (!node.length) { // what about zero-length array?
			// node is hash
			xml += indent_text + "<" + name;
			
			var num_keys = 0;
			var has_attribs = 0;
			for (var key in node) num_keys++; // there must be a better way...
			
			if (node["_Attribs"]) {
				has_attribs = 1;
				var sorted_keys = hash_keys_to_array(node["_Attribs"]).sort();
				for (var idx = 0, len = sorted_keys.length; idx < len; idx++) {
					var key = sorted_keys[idx];
					xml += " " + key + "=\"" + encode_attrib_entities(node["_Attribs"][key]) + "\"";
				}
			} // has attribs
			
			if (num_keys > has_attribs) {
				// has child elements
				xml += ">";
				
				if (node["_Data"]) {
					// simple text child node
					xml += encode_entities(node["_Data"]) + "</" + name + ">" + eol;
				} // just text
				else {
					xml += eol;
					
					var sorted_keys = hash_keys_to_array(node).sort();
					for (var idx = 0, len = sorted_keys.length; idx < len; idx++) {
						var key = sorted_keys[idx];					
						if ((key != "_Attribs") && key.match(re_valid_tag_name)) {
							// recurse for node, with incremented indent value
							xml += compose_xml( node[key], key, indent + 1, indent_string, eol );
						} // not _Attribs key
					} // foreach key
					
					xml += indent_text + "</" + name + ">" + eol;
				} // real children
			}
			else {
				// no child elements, so self-close
				xml += "/>" + eol;
			}
		} // standard node
		else {
			// node is array
			for (var idx = 0; idx < node.length; idx++) {
				// recurse for node in array with same indent
				xml += compose_xml( node[idx], name, indent, indent_string, eol );
			}
		} // array of nodes
	} // complex node
	else {
		// node is simple string
		xml += indent_text + "<" + name + ">" + encode_entities(node) + "</" + name + ">" + eol;
	} // simple text node
	
	return xml;
}
```
- example usage
```shell
...

'''javascript
var XML = require('pixl-xml');
'''

# Simplified API

The simplified API provides basic 'XML.parse()' and 'XML.stringify()' standalone functions for parsing and serializing XML.  Also
 see the [Object-Oriented API](#object-oriented-api) below, for more control over your XML.

Parse some XML by passing a string to 'XML.parse()':

'''javascript
var xml_string = '<?xml version="1.0"?><Document>' +
	'<Simple>Hello</Simple>' +
	'<Node Key="Value">Complex</Node>' +
...
```

#### <a name="apidoc.element.pixl-xml.trim"></a>[function <span class="apidocSignatureSpan">pixl-xml.</span>trim (text)](#apidoc.element.pixl-xml.trim)
- description and source-code
```javascript
function trim(text) {
	// strip whitespace from beginning and end of string
	if (text == null) return '';
	
	if (text && text.replace) {
		text = text.replace(/^\s+/, "");
		text = text.replace(/\s+$/, "");
	}
	
	return text;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pixl-xml.Parser"></a>[module pixl-xml.Parser](#apidoc.module.pixl-xml.Parser)

#### <a name="apidoc.element.pixl-xml.Parser.Parser"></a>[function <span class="apidocSignatureSpan">pixl-xml.</span>Parser (args, opts)](#apidoc.element.pixl-xml.Parser.Parser)
- description and source-code
```javascript
function XML(args, opts) {
	// class constructor for XML parser class
	// pass in args hash or text to parse
	if (!args) args = '';
	if (isa_hash(args)) {
		for (var key in args) this[key] = args[key];
	}
	else this.text = args || '';
	
	// options may be 2nd argument as well
	if (opts) {
		for (var key in opts) this[key] = opts[key];
	}
	
	// stringify buffers
	if (this.text instanceof Buffer) {
		this.text = this.text.toString();
	}
	
	if (!this.text.match(/^\s*</)) {
		// try as file path
		var file = this.text;
		this.text = fs.readFileSync(file, { encoding: 'utf8' });
		if (!this.text) throw new Error("File not found: " + file);
	}
	
	this.tree = {};
	this.errors = [];
	this.piNodeList = [];
	this.dtdNodeList = [];
	this.documentNodeName = '';
	
	if (this.lowerCase) {
		this.attribsKey = this.attribsKey.toLowerCase();
		this.dataKey = this.dataKey.toLowerCase();
	}
	
	this.patTag.lastIndex = 0;
	if (this.text) this.parse();
}
```
- example usage
```shell
...
var xml_string = '<?xml version="1.0" encoding="UTF-8"?><Document>' +
	'<Simple>Hello</Simple>' +
	'<Node Key="Value">Complex</Node>' +
	'</Document>';

var parser = null;
try {
	parser = new XML.Parser( xml_string, { preserveAttributes: true } );
}
catch (err) {
	throw err;
}

var doc = parser.getTree();
doc.Simple = "Hello, I changed this.";
...
```



# <a name="apidoc.module.pixl-xml.Parser.prototype"></a>[module pixl-xml.Parser.prototype](#apidoc.module.pixl-xml.Parser.prototype)

#### <a name="apidoc.element.pixl-xml.Parser.prototype.compose"></a>[function <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>compose (indent_string, eol)](#apidoc.element.pixl-xml.Parser.prototype.compose)
- description and source-code
```javascript
compose = function (indent_string, eol) {
	// compose tree back into XML
	if (typeof(eol) == 'undefined') eol = "\n";
	var tree = this.tree;
	if (this.preserveDocumentNode) tree = tree[this.documentNodeName];
	
	var raw = compose_xml( tree, this.documentNodeName, 0, indent_string, eol );
	var body = raw.replace(/^\s*\<\?.+?\?\>\s*/, '');
	var xml = '';
	
	if (this.piNodeList.length) {
		for (var idx = 0, len = this.piNodeList.length; idx < len; idx++) {
			xml += '<' + this.piNodeList[idx] + '>' + eol;
		}
	}
	else {
		xml += xml_header + eol;
	}
	
	if (this.dtdNodeList.length) {
		for (var idx = 0, len = this.dtdNodeList.length; idx < len; idx++) {
			xml += '<' + this.dtdNodeList[idx] + '>' + eol;
		}
	}
	
	xml += body;
	return xml;
}
```
- example usage
```shell
...
catch (err) {
	throw err;
}

var doc = parser.getTree();
doc.Simple = "Hello, I changed this.";

console.log( parser.compose() );
'''

This would produce the following output:

'''xml
<?xml version="1.0" encoding="UTF-8"?>
<Document>
...
```

#### <a name="apidoc.element.pixl-xml.Parser.prototype.error"></a>[function <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>error ()](#apidoc.element.pixl-xml.Parser.prototype.error)
- description and source-code
```javascript
error = function () {
	// return number of errors
	return this.errors.length;
}
```
- example usage
```shell
...
				if (this.preserveAttributes && !num_keys(attribs)) {
					delete leaf[this.attribsKey];
				}
				
				// Recurse for nested nodes
				if (!selfClosing) {
					this.parse( leaf, nodeName );
					if (this.error()) break;
				}
				
				// Compress into simple node if text only
				var num_leaf_keys = num_keys(leaf);
				if ((typeof(leaf[this.dataKey]) != 'undefined') && (num_leaf_keys == 1)) {
					leaf = leaf[this.dataKey];
				}
...
```

#### <a name="apidoc.element.pixl-xml.Parser.prototype.getError"></a>[function <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>getError (error)](#apidoc.element.pixl-xml.Parser.prototype.getError)
- description and source-code
```javascript
getError = function (error) {
	// get formatted error
	var text = '';
	if (!error) return '';

	text = (error.type || 'General') + ' Error';
	if (error.code) text += ' ' + error.code;
	text += ': ' + error.key;
	
	if (error.line) text += ' on line ' + error.line;
	if (error.text) text += ': ' + error.text;

	return text;
}
```
- example usage
```shell
...

	return text;
};

XML.prototype.getLastError = function() {
	// Get most recently thrown error in plain text format
	if (!this.error()) return '';
	return this.getError( this.errors[this.errors.length - 1] );
};

XML.prototype.parsePINode = function(tag) {
	// Parse Processor Instruction Node, e.g. <?xml version="1.0"?>
	if (!tag.match(this.patPINode)) {
		this.throwParseError( "Malformed processor instruction", tag );
		return null;
...
```

#### <a name="apidoc.element.pixl-xml.Parser.prototype.getLastError"></a>[function <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>getLastError ()](#apidoc.element.pixl-xml.Parser.prototype.getLastError)
- description and source-code
```javascript
getLastError = function () {
	// Get most recently thrown error in plain text format
	if (!this.error()) return '';
	return this.getError( this.errors[this.errors.length - 1] );
}
```
- example usage
```shell
...
		type: 'Parse',
		key: key,
		text: '<' + tag + '>',
		line: lineNum
	});
	
	// Throw actual error (must wrap parse in try/catch)
	throw new Error( this.getLastError() );
};

XML.prototype.error = function() {
	// return number of errors
	return this.errors.length;
};
...
```

#### <a name="apidoc.element.pixl-xml.Parser.prototype.getTree"></a>[function <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>getTree ()](#apidoc.element.pixl-xml.Parser.prototype.getTree)
- description and source-code
```javascript
getTree = function () {
	// get reference to parsed XML tree
	return this.tree;
}
```
- example usage
```shell
...
try {
	parser = new XML.Parser( xml_string, { preserveAttributes: true } );
}
catch (err) {
	throw err;
}

var doc = parser.getTree();
doc.Simple = "Hello, I changed this.";

console.log( parser.compose() );
'''

This would produce the following output:
...
```

#### <a name="apidoc.element.pixl-xml.Parser.prototype.parse"></a>[function <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>parse (branch, name)](#apidoc.element.pixl-xml.Parser.prototype.parse)
- description and source-code
```javascript
parse = function (branch, name) {
	// parse text into XML tree, recurse for nested nodes
	if (!branch) branch = this.tree;
	if (!name) name = null;
	var foundClosing = false;
	var matches = null;
	
	// match each tag, plus preceding text
	while ( matches = this.patTag.exec(this.text) ) {
		var before = matches[1];
		var tag = matches[2];
		
		// text leading up to tag = content of parent node
		if (before.match(/\S/)) {
			if (typeof(branch[this.dataKey]) != 'undefined') branch[this.dataKey] += ' '; else branch[this.dataKey] = '';
			branch[this.dataKey] += trim(decode_entities(before));
		}
		
		// parse based on tag type
		if (tag.match(this.patSpecialTag)) {
			// special tag
			if (tag.match(this.patPITag)) tag = this.parsePINode(tag);
			else if (tag.match(this.patCommentTag)) tag = this.parseCommentNode(tag);
			else if (tag.match(this.patDTDTag)) tag = this.parseDTDNode(tag);
			else if (tag.match(this.patCDATATag)) {
				tag = this.parseCDATANode(tag);
				if (typeof(branch[this.dataKey]) != 'undefined') branch[this.dataKey] += ' '; else branch[this.dataKey] = '';
				branch[this.dataKey] += trim(decode_entities(tag));
			} // cdata
			else {
				this.throwParseError( "Malformed special tag", tag );
				break;
			} // error
			
			if (tag == null) break;
			continue;
		} // special tag
		else {
			// Tag is standard, so parse name and attributes (if any)
			var matches = tag.match(this.patStandardTag);
			if (!matches) {
				this.throwParseError( "Malformed tag", tag );
				break;
			}
			
			var closing = matches[1];
			var nodeName = this.lowerCase ? matches[2].toLowerCase() : matches[2];
			var attribsRaw = matches[3];
			
			// If this is a closing tag, make sure it matches its opening tag
			if (closing) {
				if (nodeName == (name || '')) {
					foundClosing = 1;
					break;
				}
				else {
					this.throwParseError( "Mismatched closing tag (expected </" + name + ">)", tag );
					break;
				}
			} // closing tag
			else {
				// Not a closing tag, so parse attributes into hash.  If tag
				// is self-closing, no recursive parsing is needed.
				var selfClosing = !!attribsRaw.match(this.patSelfClosing);
				var leaf = {};
				var attribs = leaf;
				
				// preserve attributes means they go into a sub-hash named "_Attribs"
				// the XML composer honors this for restoring the tree back into XML
				if (this.preserveAttributes) {
					leaf[this.attribsKey] = {};
					attribs = leaf[this.attribsKey];
				}
				
				// parse attributes
				this.patAttrib.lastIndex = 0;
				while ( matches = this.patAttrib.exec(attribsRaw) ) {
					var key = this.lowerCase ? matches[1].toLowerCase() : matches[1];
					attribs[ key ] = decode_entities( matches[3] );
				} // foreach attrib
				
				// if no attribs found, but we created the _Attribs subhash, clean it up now
				if (this.preserveAttributes && !num_keys(attribs)) {
					delete leaf[this.attribsKey];
				}
				
				// Recurse for nested nodes
				if (!selfClosing) {
					this.parse( leaf, nodeName );
					if (this.error()) break;
				}
				
				// Compress into simple node if text only
				var num_leaf_keys = num_keys(leaf);
				if ((typeof(leaf[this.dataKey]) != 'undefined') && (num_leaf_keys == 1)) {
					leaf = leaf[this.dataKey];
				}
				else if (!num_leaf_keys) {
					leaf = '';
				}
				
				// Add leaf to parent branch
				if (typeof(branch[nodeName]) != 'undefined') {
					if (isa_array(branch[nodeName])) {
						branch[nodeName].push( leaf );
					}
					else {
						var temp = branch[nodeName];
						branch[nodeName] = [ temp, leaf ];
					}
				}
				else {
					branch[nodeName] = leaf;
				}
				
				if (this.error() || (branch == this.tree)) break;
			} // not closing
		} // standard tag
	} // main reg exp
	
	// Make sure we found the closing tag
	if (name && !foundClosing) {
		this.throwParseError( "Missing closing tag (expected </" + name + ">)", name );
	}
	
	// If we are the master node, finish parsing and setup our doc node
	if (branch == this.tree) {
		if (typeof(this.tree[this.dataKey]) != 'undefined') delete this.tree[this.dataKey];
		
		if (num_ke ...
```
- example usage
```shell
...

'''javascript
var XML = require('pixl-xml');
'''

# Simplified API

The simplified API provides basic 'XML.parse()' and 'XML.stringify()' standalone functions for parsing and serializing XML.  Also
 see the [Object-Oriented API](#object-oriented-api) below, for more control over your XML.

Parse some XML by passing a string to 'XML.parse()':

'''javascript
var xml_string = '<?xml version="1.0"?><Document>' +
	'<Simple>Hello</Simple>' +
	'<Node Key="Value">Complex</Node>' +
...
```

#### <a name="apidoc.element.pixl-xml.Parser.prototype.parseCDATANode"></a>[function <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>parseCDATANode (tag)](#apidoc.element.pixl-xml.Parser.prototype.parseCDATANode)
- description and source-code
```javascript
parseCDATANode = function (tag) {
	// Parse CDATA Node, e.g. <![CDATA[Brooks & Shields]]>
	var matches = null;
	this.patNextClose.lastIndex = this.patTag.lastIndex;
	
	while (!tag.match(this.patEndCDATA)) {
		if (matches = this.patNextClose.exec(this.text)) {
			tag += '>' + matches[1];
		}
		else {
			this.throwParseError( "Unclosed CDATA tag", tag );
			return null;
		}
	}
	
	this.patTag.lastIndex = this.patNextClose.lastIndex;
	
	if (matches = tag.match(this.patCDATANode)) {
		return matches[1];
	}
	else {
		this.throwParseError( "Malformed CDATA tag", tag );
		return null;
	}
}
```
- example usage
```shell
...
		// parse based on tag type
		if (tag.match(this.patSpecialTag)) {
			// special tag
			if (tag.match(this.patPITag)) tag = this.parsePINode(tag);
			else if (tag.match(this.patCommentTag)) tag = this.parseCommentNode(tag);
			else if (tag.match(this.patDTDTag)) tag = this.parseDTDNode(tag);
			else if (tag.match(this.patCDATATag)) {
				tag = this.parseCDATANode(tag);
				if (typeof(branch[this.dataKey]) != 'undefined') branch[this.dataKey] += ' '; else branch[this.dataKey] = '';
				branch[this.dataKey] += trim(decode_entities(tag));
			} // cdata
			else {
				this.throwParseError( "Malformed special tag", tag );
				break;
			} // error
...
```

#### <a name="apidoc.element.pixl-xml.Parser.prototype.parseCommentNode"></a>[function <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>parseCommentNode (tag)](#apidoc.element.pixl-xml.Parser.prototype.parseCommentNode)
- description and source-code
```javascript
parseCommentNode = function (tag) {
	// Parse Comment Node, e.g. <!-- hello -->
	var matches = null;
	this.patNextClose.lastIndex = this.patTag.lastIndex;
	
	while (!tag.match(this.patEndComment)) {
		if (matches = this.patNextClose.exec(this.text)) {
			tag += '>' + matches[1];
		}
		else {
			this.throwParseError( "Unclosed comment tag", tag );
			return null;
		}
	}
	
	this.patTag.lastIndex = this.patNextClose.lastIndex;
	return tag;
}
```
- example usage
```shell
...
			branch[this.dataKey] += trim(decode_entities(before));
		}
		
		// parse based on tag type
		if (tag.match(this.patSpecialTag)) {
			// special tag
			if (tag.match(this.patPITag)) tag = this.parsePINode(tag);
			else if (tag.match(this.patCommentTag)) tag = this.parseCommentNode(tag);
			else if (tag.match(this.patDTDTag)) tag = this.parseDTDNode(tag);
			else if (tag.match(this.patCDATATag)) {
				tag = this.parseCDATANode(tag);
				if (typeof(branch[this.dataKey]) != 'undefined') branch[this.dataKey] += ' '; else branch[this.dataKey] = '';
				branch[this.dataKey] += trim(decode_entities(tag));
			} // cdata
			else {
...
```

#### <a name="apidoc.element.pixl-xml.Parser.prototype.parseDTDNode"></a>[function <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>parseDTDNode (tag)](#apidoc.element.pixl-xml.Parser.prototype.parseDTDNode)
- description and source-code
```javascript
parseDTDNode = function (tag) {
	// Parse Document Type Descriptor Node, e.g. <!DOCTYPE ... >
	var matches = null;
	
	if (tag.match(this.patExternalDTDNode)) {
		// tag is external, and thus self-closing
		this.dtdNodeList.push( tag );
	}
	else if (tag.match(this.patInlineDTDNode)) {
		// Tag is inline, so check for nested nodes.
		this.patNextClose.lastIndex = this.patTag.lastIndex;
		
		while (!tag.match(this.patEndDTD)) {
			if (matches = this.patNextClose.exec(this.text)) {
				tag += '>' + matches[1];
			}
			else {
				this.throwParseError( "Unclosed DTD tag", tag );
				return null;
			}
		}
		
		this.patTag.lastIndex = this.patNextClose.lastIndex;
		
		// Make sure complete tag is well-formed, and push onto DTD stack.
		if (tag.match(this.patDTDNode)) {
			this.dtdNodeList.push( tag );
		}
		else {
			this.throwParseError( "Malformed DTD tag", tag );
			return null;
		}
	}
	else {
		this.throwParseError( "Malformed DTD tag", tag );
		return null;
	}
	
	return tag;
}
```
- example usage
```shell
...
		}
		
		// parse based on tag type
		if (tag.match(this.patSpecialTag)) {
			// special tag
			if (tag.match(this.patPITag)) tag = this.parsePINode(tag);
			else if (tag.match(this.patCommentTag)) tag = this.parseCommentNode(tag);
			else if (tag.match(this.patDTDTag)) tag = this.parseDTDNode(tag);
			else if (tag.match(this.patCDATATag)) {
				tag = this.parseCDATANode(tag);
				if (typeof(branch[this.dataKey]) != 'undefined') branch[this.dataKey] += ' '; else branch[this.dataKey] = '';
				branch[this.dataKey] += trim(decode_entities(tag));
			} // cdata
			else {
				this.throwParseError( "Malformed special tag", tag );
...
```

#### <a name="apidoc.element.pixl-xml.Parser.prototype.parsePINode"></a>[function <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>parsePINode (tag)](#apidoc.element.pixl-xml.Parser.prototype.parsePINode)
- description and source-code
```javascript
parsePINode = function (tag) {
	// Parse Processor Instruction Node, e.g. <?xml version="1.0"?>
	if (!tag.match(this.patPINode)) {
		this.throwParseError( "Malformed processor instruction", tag );
		return null;
	}
	
	this.piNodeList.push( tag );
	return tag;
}
```
- example usage
```shell
...
			if (typeof(branch[this.dataKey]) != 'undefined') branch[this.dataKey] += ' '; else branch[this.dataKey] = '';
			branch[this.dataKey] += trim(decode_entities(before));
		}
		
		// parse based on tag type
		if (tag.match(this.patSpecialTag)) {
			// special tag
			if (tag.match(this.patPITag)) tag = this.parsePINode(tag);
			else if (tag.match(this.patCommentTag)) tag = this.parseCommentNode(tag);
			else if (tag.match(this.patDTDTag)) tag = this.parseDTDNode(tag);
			else if (tag.match(this.patCDATATag)) {
				tag = this.parseCDATANode(tag);
				if (typeof(branch[this.dataKey]) != 'undefined') branch[this.dataKey] += ' '; else branch[this.dataKey] = '';
				branch[this.dataKey] += trim(decode_entities(tag));
			} // cdata
...
```

#### <a name="apidoc.element.pixl-xml.Parser.prototype.throwParseError"></a>[function <span class="apidocSignatureSpan">pixl-xml.Parser.prototype.</span>throwParseError (key, tag)](#apidoc.element.pixl-xml.Parser.prototype.throwParseError)
- description and source-code
```javascript
throwParseError = function (key, tag) {
	// log error and locate current line number in source XML document
	var parsedSource = this.text.substring(0, this.patTag.lastIndex);
	var eolMatch = parsedSource.match(/\n/g);
	var lineNum = (eolMatch ? eolMatch.length : 0) + 1;
	lineNum -= tag.match(/\n/) ? tag.match(/\n/g).length : 0;
	
	this.errors.push({
		type: 'Parse',
		key: key,
		text: '<' + tag + '>',
		line: lineNum
	});
	
	// Throw actual error (must wrap parse in try/catch)
	throw new Error( this.getLastError() );
}
```
- example usage
```shell
...
			else if (tag.match(this.patDTDTag)) tag = this.parseDTDNode(tag);
			else if (tag.match(this.patCDATATag)) {
				tag = this.parseCDATANode(tag);
				if (typeof(branch[this.dataKey]) != 'undefined') branch[this.dataKey] += ' '; else branch[this.dataKey] = '';
				branch[this.dataKey] += trim(decode_entities(tag));
			} // cdata
			else {
				this.throwParseError( "Malformed special tag", tag );
				break;
			} // error
			
			if (tag == null) break;
			continue;
		} // special tag
		else {
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
