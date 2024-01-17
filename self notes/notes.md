externally style sheets are those style sheets which apprear externally that ae accessed using links.for them we have to create a separate folder 

internal stylesheets are directly wrtten in html page  by the help of style tag  

the color of the sheet is designed by :- the last color assigned in the stylesheet  will be the color of the sheets
basically we have 3 css that are external,internal,inline.

inline css is generally not preferred.
inline css is given by writing style attribute in paragraph tags 
external style sheet is the best way to use .
for checking errors and if got confused do check ur code on inspect it will show line by line process.

element selectors are least specific and class seletor are more specific

!important flag is used to overwrite everthing basicaaly it ruins whole css but design is done 

we use specifity calculator to check which rule is better 
Specificity Calculator: https://specificity.keegan.st/


font size is for size of the letters
font family is for writing type
line height is for line spacing between 2 lines 
background color is for setting background color
for coloring the fonts we can use :- direct color name , rgb, rgba,#
 
2rem is equal to 32 px 

usually 1 rem is equal to 16 px.
there are so many text setting  lyk text allign , text center ,text left,text capatalise , text uppercase, text lowercase, text indent for starting spacing .
we can also use online fonts from google links ,just need to copy paste the the link in the inddex.html

if u want to generate a generic paragraph in an html page  then u can do it by  providing the instruction:-
p*5>lorem20
which means that lorem epsum which just generic verbiage we can put on a page for generic text content  and each paragragh has 20 words here it will create 5 paragraphs 

if u want to create a class in div in html then u can do it by just writing shorthand that is 
div.class
here in place of class u can write the name of the class that u want to create

to create a box aligned properly we use either of these two:-
overflow: auto; 
display: flow-root;
you dont need to write  
 column-count: 4;
 column-width: 250px;
again and again we can use short hand instead .that is :-
 columns: 4 250px ;



https://symbl.cc/en/unicode/table/
use this website for special html codes for some fancy design lyk hyphen ,double quotes etc.

if u want to take anything of tof the page then just give it a very bigger position value or  give it in minus range 
it will be removed from the page but will stay in the html code.
box items ar emainly known as flex items .

foreground images are the images on the page. 
background images are in the background


we can insert media type by a proper syntax:
@media media type and (condition: breakpoint)
{ }
in media type we can insert the type we want to insert example lyk screen 
@media screen and (condition: breakpoint){}
lykwise  we can insert the desired condition in the condition block 
also in the breakpoint area we will insert the value at which we want to stop the working of the condition 

some standard conditions and breakpoint that are followed 
### Common Media Query breakpoints:
| Breakpoint | Description |
| -------- | ---------- |
| < 481px | Mobile devices |
| 481px — 768px | iPads, Tablets |
| 769px — 1024px | Small screens, laptops |
| 1025px — 1200px | Desktops, large screens |
| 1201px and greater | Extra large screens, TV |

### Bootstrap breakpoints:
| Breakpoint | Description |
| -------- | ---------- |
| < 576px | xs |
| >=576px | small |
| >=768px | medium |
| >=992px | large |
| >=1200px | xl |
| >=1400px | 2xl |

### Tailwind breakpoints:
| Breakpoint | Description |
| -------- | ---------- |
| < 640px | xs |
| >=640px | small |
| >=768px | medium |
| >=1024px | large |
| >=1280px | xl |
| >=1536px | 2xl |

we can use markdown for writing notes in vs code 
to implement it in table form and preview the image the shorthand is 
ctrl+shift+v 




