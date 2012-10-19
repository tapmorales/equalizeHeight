equalizeHeight
==============

equalizeHeight is a plugin Jquery for recalculate de height of elements with float, keeping the layout consize.

This plugin was created in order to make layout concise when you is working with elements float into a container. It's very simple. Just write a single line in your code: $('container').children().equalizeHeight(). 

It is supposed that you have a container with several children float with specifc width. It is no needed to define a height for these children, because the plugin will fix them and your layout will be fine.

If you have a fluid container, it is interesting that you fix the height again whenever the user resize the window: 
$(window).resize(function(){
    $('container').children().equalizeHeight();
})