* [table.xml](table.xml) source file for `curl_xml`
* [table_OK.conf](table_OK.conf) working collectd config with both *simple* and *table* xpaths: **should succeed** with [these values](table_OK.out)
* [table_NOK.conf](table_NOK.conf) collectd config with a table xpath **without** `InstanceFrom`: **should fail** with [this error message](table_NOK.out)
