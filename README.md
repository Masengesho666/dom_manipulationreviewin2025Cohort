# dom_manipulationreviewin2025Cohort
//dom manipulation :JavaScript DOM manipulation is the process of using JavaScript to access, modify, or interact with the HTML elements of a web page

✅ 1. innerText
innerText returns only the visible text of an element.

-It ignores hidden text (like display: none).

-It respects CSS styles (e.g., it won’t show text that is hidden).

-It does NOT include HTML tags.
Examle: console.log(firstlistitem.innerText);
➡️ Output: "Home" (only visible text)

✅ 2. textContent
-textContent returns all text inside the element, even hidden text.

-It does not consider CSS visibility.

-It does NOT include HTML tags.

Example:
console.log(firstlistitem.textContent);


➡️ Output: "Home" (plus hidden text if any)

✅ 3. innerHTML

innerHTML returns HTML code inside the element.

It includes tags, text, children elements, etc.

Used when you want to add or change HTML structure.

//1. event:
 An event is something that happens on a web page — for example:
A user clicks a button


-A user moves the mouse


-A page loads


-A key is pressed


So, an event is simply the action or thing that happens.


//2. addEventListener():
This is a JavaScript method that tells the browser what to do when a specific event happens.
It “listens” for that event on an element and then runs some code when it occurs.
