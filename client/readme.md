# Browser-based XML-RPC client

A JavaScript client for the browser.

The core code for the browser version is <a href="https://github.com/scripting/xml-rpc/blob/master/client/xmlrpc.js">xmlrpc.js</a>. 

It uses routines in several of my libraries: 

* utils.js -- stringMid, stringNthField, filledString, encodeXml.

* xml.js -- xmlGetAddress.

It also uses jQuery.

The demo app, in <a href="https://github.com/scripting/xml-rpc/blob/master/client/index.html">index.html</a> and its two included files, <a href="https://github.com/scripting/xml-rpc/blob/master/client/code.js">code.js</a> and <a href="https://github.com/scripting/xml-rpc/blob/master/client/styles.css">styles.css</a>, make six calls to the <i>betty</i> server, two to test error reporting, and four to test various combinations of scalars, parameter lists, structs and array. 

The server it calls is a clone of the one we used in the earlier work on XML-RPC.

You can run the test app <a href="http://scripting.com/code/xmlrpcbrowserclient/">from</a> scripting.com.   

