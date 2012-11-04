#bindbook

## Installation & Usage

**Requires:**

* Nodejs 0.8.x

Install: `npm install -g bindbook`

**Usage:**

Write output to terminal `bindbook`

Write output to file output.md `bindbook >> output.md`




##Chapter/Article Loop

	/_header.md # Book Header

	/1.{ChapterName/Identifier}/_header.md # Chapter Header
	 
	# Articles within First Chapter

	/1.{ChapterName/Identifier}/1.{ArticleName/Identifier}.md
	/1.{ChapterName/Identifier}/2.{ArticleName/Identifier}.md
	/1.{ChapterName/Identifier}/3.{ArticleName/Identifier}.md
	/1.{ChapterName/Identifier}/...

	/1.{ChapterName/Identifier}/_footer.md # Chapter Footer
	
	# Repeats `Articles within First Chapter` with 2.{ChapterName/Identifier} and so on
	/2.{ChapterName/Identifier}/_header.md
	# ...

	/_header.md # Book Footer
	
	

##Licence

(MIT Licence)

Copyright (c) 2012 Ben Evans

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
