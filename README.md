This application keeps track of USB keys that are distributed to a set of students. It connects to the Yale Oracle database to convert the magnetic stripe information on the Yale ID to identifiable information.

##Set Up
To set this up, you must install the ruby-oci8 gem by following the instructions here:
https://github.com/kubo/ruby-oci8/blob/master/docs/install-instant-client.md

##Troubleshooting install: 
Make sure to change all the commands for the OS you're using and your version numbers e.g. .so -> .dylib, the 11_number _ things
Also you may need to do ruby -e "require 'oci8'"

##Database Connection Information
A sample database.yml is available in Yale's private git repository (but it is private).
