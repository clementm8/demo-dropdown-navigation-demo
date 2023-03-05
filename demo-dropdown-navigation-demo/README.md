# dmit1530-lab-02

## Lab 02: Single-Level Drop-Down Menu

**Weight**: 5% of your final grade

---

## Instructions

For this Lab, you will create a website for a fictitious All Things Design Site. It will be an in-class Code-A-Long where you are expected to put in the final touches.

---

## The Build Methodology 

### HTML

1. Write all of the necessary HTML. This will include a ``<header>`` with a ``<nav>``. Inside of your ``<nav>``, you will have an unordered list with a class of ``.menu`` and two nested unordered lists with a class of ``.submenu``. Altogether, you menu will have the following links and nested links: 

	> UX Tutorials

	> UX/UI Design Tools

		>> Figma<
		>> Adobe Xd
		>> Sketch
		>> Maze
		>> Marvel
		>> Adobe Xd
		>> Sketch
		>> Maze
		>> Marvel
	
	> Typography Resources

		>> Google Fonts
		>> Font Squirrel
		>> Fonts in Usee
		>> I Love Typography

	> Blog

2. In your ``<nav>``, include the provided ``<svg>`` beside the links with nested menus. 

> **Note**: Because of the way SVG files are encoded by Adobe Illustrator and other vector editing programs, you will need to 'clean it up'. This means removing and DOCTYPE declarations, IDs, or inline styles. If you do not do this correctly, your HTML will not pass validation and you will not be able to style your SVG with an external stylesheet. 


### Validation

3. Validate and outline your HTML. You should not have any validation errors or _Untitled Sections_. You **must** have a flawless foundation before you can begin writing your CSS.

### Mobile-First CSS

6. Begin by writing universal styles (i.e. things that will remain the same regardless of the size of the viewport).

7. Next, style everything for the mobile view. Your ``<nav>`` should be vertical and fill the full width of the screen. For this view, your ``<svg>`` element should be hidden, as you will not need anything to indicate that there are sub-menus. Underneath, your hero banner should have the darker, smaller background, with all of its contents centred. 

### Media Queries

8. Begin styling the medium view. Using a media query, define your flex containers. 

9. Make your ``<svg>`` element visible again.


10. Position and hide your nested links (i.e. the drop-down menu). 

### On Your Own
11. Make them appear again whenever the user hovers over the parent ``<li>``. Add a transition to make everything a little smoother.

12. Add accessibility with the :focus and :focus-within state on each ``<li>``. This will allow users to tab through all of your links with their keyboard or a swipe rather than having to click it with a mouse or a tap. 

13. Finally, write a media query for the largest view (this should be smaller or as large as max-width you set earlier). At the largest view your logo should on the left and your menu to right.  

**Hint**: How can we horizontally align things to the right-hand side of a flex container? How can we vertically centre things within a flex container? 

14. When finished upload your work to Moodle before the due date.
