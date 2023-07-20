Css positions include :static which is the default ,absolute which is used when say you have a div then now
you want to like position elements inside that div it uses top,left,right and bottom .
To use absolute we first need to declare the parent to relative then now position the childrenn 
elements.
Position sticky and fixed  use now te screen itself like say if i set a div to fixed top 0 
even if the div is inside a parent div that has a margin top to  30px you will notice that 
 the child div will be fixed at the top of the screen and not at the top of the parent div because this fixed and sticky position 
 uses the screen itself and not the parent divs 
 To like create this scroll effect first  create a  main container to hold your elements set and overflow hidden set the 
 height to 100vh to cover all screen remove padding and margin of the body then now declare 
 your two divs inside a container declare the container to flex jusd do flex row  and add there 
 heights to 100%   now for each div and overflow scroll and thats it 
