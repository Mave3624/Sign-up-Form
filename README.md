# Sign-up-Form

**Note**

*Section*

The type attribute sets the control type, and there’s a large choice of options:

type	description
button	a button with no default behavior
checkbox	a check/tick box
color	a color picker
date	a date picker for the year, month, and day
datetime-local	a date and time picker
email	an email entry field
file	a file picker
hidden	a hidden field
image	a button which displays the image defined by the src attribute
month	a month and year picker
number	a number entry field
password	a password entry field with obscured text
radio	a radio button
range	a slider control
reset	a button that resets all form inputs to their default values (but avoid using this, as it’s rarely useful)
search	a search entry field
submit	a form submission button
tel	a telephone number entry field
text	a text entry field
time	a time picker with no time zone
url	a URL entry field
week	a week number and year picker

*Section 2*

Other useful <input> attributes include:

attribute	description
accept	file upload type
alt	alternative text for the image types
autocomplete	hint for field auto-completion
autofocus	focus field on page load
capture	media capture input method
checked	checkbox/radio is checked
disabled	disable the control (it won’t be validated or have its value submitted)
form	associate with a form using this ID
formaction	URL for submission on submit and image buttons
inputmode	data type hint
list	ID of <datalist> autocomplete options
max	maximum value
maxlength	maximum string length
min	minimum value
minlength	minimum string length
name	name of control, as submitted to server
pattern	a regular expression pattern, such as [A-Z]+ for one or more uppercase characters
placeholder	placeholder text when the field value is empty
readonly	the field is not editable, but it will still be validated and submitted
required	the field is required
size	the size of the control (often overridden in CSS)
spellcheck	set true or false spell-checking
src	image URL
step	incremental values in numbers and ranges
type	field type (see above)
value	the initial value

*Example*

    <form>
      <label for="choose">Would you prefer a banana or a cherry?</label>
      <input id="choose" name="i_like" required pattern="[Bb]anana|[Cc]herry">
      <button>Submit</button>
    </form>