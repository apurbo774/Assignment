(1)-What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
Ans-
getElementById: Finds only ONE element with that ID.
getElementsByClassName: Finds MANY elements with the same class (like an array).
querySelector: Finds the FIRST element that matches CSS selector.
querySelectorAll: Finds ALL elements that match CSS selector (gives NodeList).



(2)- How do you create and insert a new element into the DOM?
 Ans-
  Steps:
 1. Make a new element: let para = document.createElement("p");
 2. Add text inside: para.textContent = "Hello World!";
 3. Put it into the page: document.body.appendChild(para);



(3)- What is Event Bubbling and how does it work?
 Ans-
Event bubbling means when you click a small element, the event goes up to its parent and then grandparent.
Example: Click a button inside a div -> button gets click, then div also gets click



(4)- What is Event Delegation in JavaScript? Why is it useful?
 Ans-
  Instead of adding event to every child, we put ONE event on parent and check who was clicked.
  Why useful?- Less code- Faster- Works for new elements added later.



(5)-What is the difference between preventDefault() and stopPropagation() methods?
Ans-
-preventDefault(): Stops the browser default action (like stopping a form submit or link navigation).
-stopPropagation(): Stops the event from going up to parent.
 

