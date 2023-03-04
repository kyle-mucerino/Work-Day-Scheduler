# Homework-5
ScreenShot: <img width="718" alt="HW-5" src="https://user-images.githubusercontent.com/124935227/222881077-47cca75b-f2a1-4af9-82f4-16b8c05134ec.png">





We use 'this' to access the id when the user clicks to save to 'localStorage'. We then use DOM traversal to get the "hour-x" id of the time-block containing the clicked button. '$(this)' replaces selectElementbyID using jQuery and is used to access the save button when clicked, then used '.siblings('.description') to access the 'description' element of that's a sibling of the click to save button. We use '.parent()' to access the parent element of the click to save button and then retrieve the id using attr('id). We need to do this because inside each div the id changes with the hour change, so each element has a unique id based on the hour of the workday.

We use $('#currentDay').text(dayjs().format('dddd, MMMM D, YYYY'))to display the current day using dayjs in the format we want by accessing the currentDay id.  