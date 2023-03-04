# Homework-5
To add a listner for click events on the save button we use $('.saveBtn') using jQuery to replace getElementbyID. We then use $(this).siblings and $(this).parent.()attr('id') to access the parent 'div' element's id when clicked. Then sending it local storage using setIten(inputID, inputValue). 
