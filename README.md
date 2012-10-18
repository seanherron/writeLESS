#writeLESS
##Introduction
writeLESS is a simple LESS component library that offers a few standard features to make writing LESS a bit easier. Even better, it includes all browser specific extensions so that you don't have to!

##Usage
Simply include write.less in your main LESS stylesheet.

	@import "write.less";

To use writeLESS mixins, simply put the following in your LESS:
	
	#w.border-radius();

For example, to apply a border-radius of 10px to a `DIV` with the class of `.awesome`, your LESS stylesheet should read as follows:

	div.awesome {
		#w.border-radius(10px);
	}

Simple, right?

##Included Mixins
writeLESS includes the following mixins to help writing LESS easier

* `#w.clearfix();` - Applies a clearfix to child elements
* `#w.border-radius();` - Applies a border radius to the element
* `#w.drop-shadow();` - Applies a drop shadow to a block element
* `#w.inset-shadow();` - Applies a inset shadow to a block element
* `#w.text-shadow();` - Applies a text shadow to a text element
* `#w.background-gradient();` - Applies a background gradient to a block element
* `#w.background-size();` - Applies a simple background size
* `#w.rotate();` - Applies a 2D rotation

More are to come!

##License
writeLESS is released under the [MIT License](http://opensource.org/licenses/MIT).