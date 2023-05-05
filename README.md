Download Link: https://assignmentchef.com/product/solved-csis3280-lab-03-html-calendar
<br>
Visual Studio Code

<ol>

 <li>Download the lab template from Blackboard 2. Extract it to a directory.</li>

 <li>Rename the files/folders in accordance with the naming convention.</li>

</ol>

<h1>Solution</h1>

The flow of the program is as follows:

<ol>

 <li>A page is displayed prompting the user for the year and the month of which to display the calendar.</li>

 <li>The user must select the Month and the Year from the form.</li>

 <li>The user also has the option of selecting to mark a “special day” on the calendar.</li>

</ol>

If the user selects the special event they must input a special day, description and color for the event.

<ol start="4">

 <li>The user then presses the “Generate Calendar” button.</li>

 <li>The form data is validated and the calendar is displayed according to the various options the user selected.</li>

</ol>

Requirements:

The program must by default seleft the current month and year.

The user can select the month and the year from two drop down lists.

Days that are not part of the calendar are greyed out.

The numbering must accuratly reflect the Calendar

All data must be validated

If the user seelcts the Mark a special Event option, the data associated with that feature must be validated as well.

Validation errors must appear on the screen. Prompting the user to fix them.

You must implement the following files &amp; functions:

<strong>html.inc.php:</strong>

<ol>

 <li><strong>html_CalendarForm()</strong> – Generates the html form to prompt the user</li>

 <li><strong>html_Errors($errors)</strong> – Displays the User Errors.</li>

 <li><strong>html_Calendar($data)</strong> – Displays the html Calendar based on the data from getCalendarData() <strong>inc.php:</strong></li>

 <li><strong>validate_CalendarForm()</strong> – Validates the user input and returns an array of errors.</li>

</ol>

<strong>calendar.inc.php:</strong>

<ol>

 <li><strong>getCalendarData($month, $year)</strong> – Generates a <strong>single</strong> array of data containing all the information for the calendar.</li>

</ol>

Hints:

A calendar is always a grid of 7×6 rows.

It might be helpful to use two loops to generate the rows for the calendar.

If you pass the months and the year as integers you can use mktime to generate the appropriate timestamp.

It may be helpful to start as a single file and move your functions to the include files when they work It may also be helpful to try and just create the grid before you tackle the data structure.

<h1>Appendix</h1>

Screenshot of the Form for the user.

Screenshot of the Calendar generated based on the previous form data.