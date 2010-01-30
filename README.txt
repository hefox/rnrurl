Reverse node reference url

updates a node's reference of a node from the url. 

 Name refers to being a reverse of nodereference_url; and some code based off of it

ie node/add/something?rnrurl=6&field_name=field_blah updates the node reference field_blah in node 6 with the newly created node.

Link appears in node link section. 

To enable adding this way, use 


Note about access

By default it just checks if user has "Bypass rnrurl acces" to let em add it, but can extend that via hook_nrnurlaccess.. maybe.
