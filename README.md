#sublime_ruby_snippets

Addendums and fixes for default ruby snippets; tested on Sublime 3

## cla:

	class {cursor1}

		def initialize({cursor2})
			{cursor3}
		end

		def to_s
			{cursor4}
		end

	end

added to_s function to default class snippet


### do:

    do
    	{cursor}
    end

do end snippet slightly modified (to run on 'do' instead of 'doe') from:
http://blog.ianvaughan.co.uk/2013/06/sublime-text-ruby-doend-snippet.html

### doo:

    do |{cursor1}|
	    {cursor2}
    end

### rand:

    rand({cursor1}..{cursor2})

default is from 1..6

### rr:

    require_relative '{cursor}'