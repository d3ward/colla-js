colla
======================================

What is colla?
---------------------

Fork of Svelte JS is a lightweight modern JavaScript library intended for use on projects where legacy browser support is not necessary.

It uses modern JavaScript (querySelectorAll, classList, matchesSelector) to help make it as lightweight as possible and therefore only works on the latest version of modern browsers E.g. Chrome, Firefox, Opera, IE10+.


Getting Started
---------------------

Simply download the minified version of colla and reference it in your page.

	<script src="colla.min.js"></script>

How To
---------------------

If you have used other JavaScript libraries like Zepto or jQuery most functions will be familiar to you. For example, to set the text of an element, you would write:

	$('.hello').text('Hello colla');

API
---------------------

* $(selector, context)
* each(callback)
* css(property, value)
* hide()
* show()
* fade()
* toggle(className)
* addClass(className)
* removeClass(className)
* hasClass(className)
* on(name, callback)
* one(name, callback)
* off(name, callback)
* focus()
* blur()
* trigger(eventName, detail)
* next()
* first()
* last()
* parent()
* children()
* append(position, html)
* text(textToAdd)
* html(html)
* outerHTML(html)
* empty()
* clone()
* remove()
* attr(name, (value))
* removeAttr(name)
* val((value))
* length()
* height()
* width()
* position()
* matches(selector)
* closest(selector)

Custom functions
---------------------

You can easily add a custom function to colla by adding to $.fn.

	$.fn.cool = function() {
		return this.each(function(el) {
	    	el.textContent = 'Cool';
	    });
	}
	
	$('.says-cool').cool();	



Get Involved
---------------------

Feel free to help make Colla better :-).

