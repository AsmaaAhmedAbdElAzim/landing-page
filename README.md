# Landing Page Project

## Table of Contents

* [Instructions](#instructions)

## Instructions


# Required of me:

# I used that :
1- html (when i creat forth section manual and creat button to add section ).
2-css (when change background of sections when have "active-class")
3-java script
4- ECMA script6

# I do that :
1-  creat variabile (counting) is equal 0 ,and increment this variable in function(creatSection) .
2-  create a variable(container) that holds the text of section.in which id of section = section + counting , 
    data-nav = section + counting  (Hint:'+' is cocatenation oprator).
3-use method insertAdjacentHTML has two parameter(position , text (container)).Through this step, I can add the section in  main .
4- creat avariable (nav) that holds 'ul' by method(getElementById) .
5- creat function (creatNav) at frist make nav empty then use forEach on sections. this loop creat links in navbar 'li' Taking into account href of a = section.id , data-nav= section.id . to connect section and link which has the same name.
6- use method insertAdjacentHTML has two parameter(position , text (listNav)).Through this step, I can add the link item in navbar.
7- use for loop less than or equal 4 to creat 4 sections dynamically in loop call function(creatSection) then call function(creatNav) to creat number of links equal number of sections.
8-in html creat button (add section) and hold it by method(getElementById) and use method(addEventListener)is work when clicked on button to call two function (creatSection) and (creatNav).    
9-  when scrolling in window assign to anonymous function  in this function use forEach on section .
10-used method(getBoundingClientRect) in if condition when near top of viewport add active class on this section . if not remove active class .
11-use method (preventDefault) to stop default behavior of (addEventListener) , and use if condition when
(e.target.dataset.nav == true) move to section has id (e.target.dataset.nav) but smooth by used method (scrollIntoView) .

# landing-page
