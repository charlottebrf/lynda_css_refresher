/*class & ID attributes
<tag attrubute="value"></tag>
<p class="example"></p>
<div id="example"></div>*/

/*class
<p class="highlighted">I want to highlight this.</p>
<p class="highlight">This is highlighted too.</p>

.highlight {
  background: yellow;
}

<p id="highlighted">This paragraph is highlighted.</p>

Multiple IDs can't be used in same element
#highlighted {
  background: yellow;
}

ID selecor
Define the value & can only be used once per page */

/*<!-- // selectors determine HTML element to apply rules to Intro --> */

/*descendent selectors
Use multiple selectors separated by a space to match the descendent elements
<p> Paragraph with a <a href="#placeholder">link</a>,</p>

p a {
  will only select links inside of a paragraph
}

<section>
  <p>Paragraph with a <a href="#">link</a>,</p>
  <a href="#placeholder">Just a link.</a>
  </section>
  <p>Paragraph and <a href="#">link</a>.</p>

  section p a {
    color: red;
  }*/

  /*grouping multiple selectors
   h1, h2, h3 {
     color: red;
   }


Pseudo-Class selectors

a:hover {
  color: black;
}

a:active {
  color: black;
}
#moment you press on the link

<a href="http://website.com">link</a>

normally only need a*/

Type Selector:
use when all or most instances of an element need to be styled in same way

Classes:
elements more specific, reusable than other elements

ID values can only be used once per page:
use them for unique or global styles that are not repeated
ID can be used for inpage linking

Descendent selectors:
try not to go 3 deep

Combining selectors:
apply the same style to different elements in one declaration block

h1, h2, .class-name {
  font-size: 12px
}

Comments

/* */

/* --------------------------*/

hex codes:
