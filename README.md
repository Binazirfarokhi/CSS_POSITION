# CSS_POSITION

position and non-positioned elements :
By default all elements are non-positioned. 
Non-positioned elements can not be affected by positioning properties like top, button, left and right. 
these positioning properties only apply to positioned elements. 
by default all elemets are positioned static. for example the order is the same as html flow - static makes elemets non-postioned. so , positioning properties t l r b will not work on such elements. try and see.
you would say hmm I can do it with margin, but margin will push the other elements you have to find space for its element.     /* margin-left:280px; */

position relative will makes element positioned , but keeps it in the markup flow until it is re-positioned. it can go outof his parent box, it can go based on its first position, whereever it wants to go, it will go. the problem is, you will have a space there, and it is hard to get rid of this space . 

position absolute : makes an element positioned , and removes it from the html flow, it is also bounded by the closest relative parent if you do not specifiy whic parent are you talking about by default will choose body or html. it can take any space.the postion absolute work with position realtive, 
"position: absolute; works with position: relative;" → Not always! It only considers an ancestor with position: relative;, absolute;, or fixed;.


fixed doesnot care to any parent, just use the view port. and will stay all the time. 

Sticky: untill you have content will be stick to them and once its finished there is no where to go.

overall: static : default, for non-positioned elements. 
relative: behaves like static by maintaining markup flow but makes elements positioned 
absolute: takes an element form the flow in the markup, and the elements respect positioning distance of the closest relative parent.if there is no parent relative to absolute it will choose body or html( view port) .if  there are   other element can take thatelement space.
absolute use the closes raltive postion to make it as a base. 

fixed: silimar to absolute, but respects only the viewport and not looking for any parent or relative postion. but absolute is looking for some parent. 

Sticky: switches between relative and fixed. its relative by default but becomes fixed whe na position in a scrolling container is marched.( it should work with scrolling content if you do not have it will not work for you)