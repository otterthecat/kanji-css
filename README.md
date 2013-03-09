Kanji CSS
=========

Early stages of a (partially) gridless responsive CSS framework.

There's a couple approaches available to you:

Groupings
---------

You can set a grouping my applying a "plural" class to a wrapping element.
For instance:

	<div class="quarters">
		<article>
			Each Article
		</article>

		<article>
			Will Be
		</article>

		<article>
			25% Wide
		</article>

		<article>
			As defined by parent element's class
		</article>
	<div>

Along with quarters, you may define a wrapper with the *.thirds* class...

	<div class="thirds">
		<article>
			Each Article
		</article>

		<article>
			Will Be
		</article>

		<article>
			divided into thirds
		</article>
	<div>	

Or with *.halves*

	<div class="halves">
		<article>
			Each Article Will Be
		</article>

		<article>
			Half the Width of it's parent
		</article>
	</div>

Any immediate child elements of the defined grouping that are in excess of the defined size (4, 3, or 2),
will take up a new row under the first set, and continue on for all other siblings.


Grid
-----

Kanji CSS also can be used as a (overly simplified) grid. Similar to 12/16 grids - the idea is to have
all the parts add up to a whole.

A few samples:

	<div class="quarter">
		Left Rail
	</div>

	<div class="half">
		Middle Content
	</div>

	<div class="quarter">
		Right Rail
	</div>

Or 

	<div class="third">
		Narrow
	</div>

	<div class="two-thirds">
		Super Wide
	</div>