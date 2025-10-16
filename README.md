# build-a-cat-painting
fCC Positioning Workshop

Lecture Notes:

However, when using floats, it's important to handle the problem of collapsing parent elements when their child elements are floated. The clearfix technique solution is applied to the class container element to fix this issue.

/* Clearfix CSS */
.container::after {
  content: "";  
  display: block;
  clear: both;
}
