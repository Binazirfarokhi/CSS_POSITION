# CSS_POSITION

position and non-positioned elements :
By default all elements are non-positioned. 
Non-positioned elements can not be affected by positioning styles like top, button, left and right. 
these positioning styles only apply to positioned elements. 
by default all elemets are positioned static. for example the order is the same as html flow - static makes elemets non-postioned. so , positioning properties t l r b will not work on such elements. try and see.
you would say hmm I can do it with margin, but margin will push the other elements you have to find space for its element.     /* margin-left:280px; */

position relative will makes element positioned , but keeps it in the markup flow until it is re-positioned. it can go outof his parent box, it can go based on its first position, whereever it wants to go, it will go. the problem is, you will have a space there, and it is hard to get rid of this space . 

position absolute : 

