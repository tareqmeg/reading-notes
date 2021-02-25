> # Forms

HTML Form

An HTML form is used to collect user input. The user input is most often sent to a server for processing.

The `<form>` Element

The `<form>` element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc.

There are several types of form controls that
you can use to collect information from visitors
to your site.

- ADDING TEXT (insrt text, passwod, ...etc).

- Making Choices (Radio buttons, Checkboxes, Drop-down boxes, .. etc).

- Submitting Forms (Submit buttons, Image buttons, ...etc).

- Uploading Files.

> How Forms Work

1. A user fills in a form and then presses a button
to submit the information to the server.

2. The name of each form
control is sent to the
server along with the
value the user enters or
selects

3. The server processes
the information using a
programming language
such as PHP, C#, `VB.net`,
or Java. It may also store
the information in a
database.

4. The server creates a new
page to send back to the
browser based on the
information received.

> # Event

Event handlers let you indicate which event you
are waiting for on any particular element.
There are three types of event handlers. 

1. HTML EVENT
HANDLERS

   This is bad practice, but you
need to be aware of it because
you may see it in older code. 

2. TRADITIONAL DOM
EVENT HANDLERS

     DOM event handlers were
introduced in the original
specification for the DOM.
They are considered better than
HTML event handlers because
they let you separate the
JavaScript from the HTML. 

    Support in all major browsers is
very strong for this approach.
The main drawback is that you
can only attach a single function
to any event. For example, the
submit event of a form cannot
trigger one function that checks
the contents of a form, and a
second to submit the form data if
it passes the checks. 

3. DOM LEVEL 2 EVENT
LISTENERS


    Event listeners were introduced
in an update to the DOM
specification (DOM level 2,
released in the year 2000).
They are now the favored way of
handling events 

> ## EVENT LISTENERS 

    Event listeners are a more recent approach to handling events. They can deal with more than one function at a time but they are not supported in older browsers. 


> FORM EVENTS

There are two events that are commonly used with forms.
In particular you are likely to see submit used in form validation.

 Submit

 When a form is submitted, the submit
event fires on the node representing the
`<form>` element. It is most commonly
used when checking the values a user has
entered into a form before sending it to the
server. 

change

e Fires when the status of several form
elements change. For example, when:
- a selection is made from a drop-down
select box.
- a radio button is selected.
- a checkbox is selected or deselected.

input

The i nput event. which you saw on the
previous page is commonly used with
`<input>` and `<textarea>` elements.


