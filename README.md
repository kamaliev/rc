# rc
Recursice replacment file content by regular pattern
	This script copies the contents of the [source file] in the file 
	that matches the [regexp pattern] in the directory [path] and its subdirectories
	-r: Restore content from a backup file , use the directive

	Using:	 	 ./rc [source file] [path] [regexp pattern]
	Exmaple:	 ./rc source.js /var/www/sites 'jquery.[0-9].*.js'

	Using:		 ./rc -r [backup list]
	Exmaple:	 ./rc -r rc.replacement.20160607.txt
