# dim

```
Dim is a date-based utility for writing quick notes
Usage: dim [option] <date>
        -n      	print the filepath
        -o		print the file
        -e editor	specify an editor
        -h		show this help

Example:
        # edit today's notes
        $ dim
	
        # write some notes for Monday before enjoying the weekend
        $ echo "reminder to do that one thing" | dim monday
        
        # understand Monday morning what you did on Friday
        $ dim -o last friday | less 
        
        # procrastinate a bit
        $ dim -o today | dim tomorrow
        
        # mark a great day
        $ cp \$(dim -n) ~/favorites/cool-stuff  
        
Environment:
        \$DIM_WS the directory to read/write notes
        \$DIM_EDITOR editor used to read/write files
```
