equalizeHeight
==============
by: Daniel Tapias Morales - <a href="https://twitter.com/tapmorales">@tapmorales</a> <br/>


equalizeHeight is a plugin Jquery for recalculate de height of elements with float, keeping the layout consize.

This plugin was created in order to make layout concise when you is working with elements float into a container. It's very simple. Just write a single line in your code: $('container').children().equalizeHeight(). 

It is supposed that you have a container with several children float with specifc width. It is no needed to define a height for these children, because the plugin will fix them and your layout will be fine.

If you have a fluid container, it is interesting that you fix the height again whenever the user resize the window: 
$(window).resize(function(){
    $('container').children().equalizeHeight();
})

<br/>
<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/br/deed.pt"><img alt="Licença Creative Commons" style="border-width:0" src="http://i.creativecommons.org/l/by-sa/3.0/br/88x31.png" /></a><br />O trabalho <span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Plugin Jquery equalizeHeight</span> de <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Daniel Tapias Morales</span> foi licenciado com uma Licença <a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/br/deed.pt">Creative Commons - Atribuição - CompartilhaIgual 3.0 Brasil</a>.