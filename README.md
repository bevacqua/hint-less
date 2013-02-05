Hint.LESS
=========

Extracted from the source code in [**NBrut**](https://github.com/bevacqua/NBrut), and originally forked from [hint.css](https://github.com/chinchang/hint.css).

**Hint.LESS** is a LESS-CSS tool tip stylesheet.

Purpose
=======

Aims to simplify the already very succint **hint.css**, ported it from SASS to LESS, removed chaff and left just the wheat.

Possibly _the only reason_ why **Hint.LESS** exists is the ability to use just `:before` or just `:after` rather than both, in case you already use one of these pseudo selectors.

To use:

    <a href='/foo' data-hint='Hint: this is clickable!' class='hint' />
	
`hint` defaults to the `:after`, and less commonly used pseudo-selector, if you want to use `:before` instead, just use `hint-before`, like so:

    <a href='/foo' data-hint='Look, ma! No hacks!' class='hint-before' />
	
That's it.