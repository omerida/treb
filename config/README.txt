The /config/ directory should specifically hold one file, config.xml, 
which is parsed by the framework in order to store various configuration 
options for you.  The reason for a whole directory for this, is under the 
assumption that you will end up with multiple configuration files (live, 
test, preview, etc), that you will want to keep track of separately, and 
that get copied to 'config.xml' as appropriate.
