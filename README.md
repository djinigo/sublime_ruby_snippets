#sublime_ruby_snippets

Addendums and fixes for default ruby snippets; tested on Sublime 3

### do:

    do
    	{cursor}
    end

do end snippet slightly modified (to run on 'do' instead of 'doe') from:
http://blog.ianvaughan.co.uk/2013/06/sublime-text-ruby-doend-snippet.html

### doo:

    do |{cursor}|
	    {secondary tab position}
    end

### ran:

    rand({cursor}..{secondary tab position})

default is from 1..6

### rr:

    require_relative "{cursor}"