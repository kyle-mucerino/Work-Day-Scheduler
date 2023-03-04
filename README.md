# Homework-5
ScreenShot: <img width="1423" alt="Screen Shot 2023-03-03 at 11 09 13 PM" src="https://user-images.githubusercontent.com/124935227/222881517-b8e96adf-7481-4d26-8774-cae552e20bbe.png">

Deplyed URL: https://kyle-mucerino.github.io/Homework-5/


We use 'this' to access the id when the user clicks to save to 'localStorage'. We then use DOM traversal to get the "hour-x" id of the time-block containing the clicked button. '$(this)' replaces selectElementbyID using jQuery and is used to access the save button when clicked, then used '.siblings('.description') to access the 'description' element of that's a sibling of the click to save button. We use '.parent()' to access the parent element of the click to save button and then retrieve the id using attr('id). We need to do this because inside each div the id changes with the hour change, so each element has a unique id based on the hour of the workday.

We use $('#currentDay').text(dayjs().format('dddd, MMMM D, YYYY'))to display the current day using dayjs in the format we want by accessing the currentDay id.  