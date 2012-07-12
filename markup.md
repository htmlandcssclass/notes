Elements
=======

HTML stand for Hypertext Markup Language.
Hypertext

HTML pages are composed of elements.
Elements consist of an opening tag, a closing tag, and content.
An element may contain text, other elements, or both.
Opening and closing tags have matching tag names.
Elements may also have attributes.

Here's what an element looks like:

	<p id="intro" class="pullquote">It was the best of times, it was the worst of times.</p>

#####opening tag
	<p>
	
#####closing tag
	</p>

#####tag name
	p
	
#####attributes
	id="intro" class="pullquote"
	
#####id
	intro
	
#####class
	pullquote
	
#####content
	It was the best of times, it was the worst of times.

Id and class
------------

Id and class are two common and useful attributes.
Classes may describe the 'kind of thing' an element is— 
what conceptual set it belongs to.
Classes may also be used to describe the state an element is in—
a selected item in a list may be assigned a class of "selected".
Elements may have any number of classes, separated by spaces.

The id attribute uniquely identifies an element.
No two elements on a page may have the same id.
Each element may have only one id.

If you were to mark up everyone in the class as elements,
you might assign everyone a class of "person",
and each would be assigned an id that identified them uniquely.
ID's may be people's names or social security numbers.

	<div id="sean-durham" class="person" />
	
Parents, children, and siblings
-------------------------------



	<ul class="fish">
		<li>One fish</li>
		<li>Two fish</li>
		<li>Red fish</li>
		<li>Blue fish</li>
	</ul>