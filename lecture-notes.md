#Lecture 10 pt. 3
create a mobile version only

make 2nd text input method validate correct text

<form novalidate>
</form>
The above code will make text input unvalidated

Redo all inputs with a form

#TIME STAMP 14 MINUTES

#input-pri:not(:checked) ~ label {
    background-color: red;
}
Define: the id of "input-pri" when not checked, make element <label> red.

#input-pri:checked + label {
    background-color: green;
}
Define: the id of "input-pri" when checked, make element <label> green.

input[type="checkbox"]:not(:checked) ~ label {
    background-color: red;
}
Define: the element of "input" with the attribute "type" and value of "checkbox" when not checked, make element <input> red.

border-radius: x%
^^this softens the corners of a boxed element. so 100% will be circle

lookinto :placeholder-shown