Dear Candidate, 

As part of our recruitment process please complete the below assessment.
You may complete the tasks in any language as long as the result is a responsive HTML page with associated assets such as CSS and JavaScript.
Provide any build instructions or other information in a markdown readme file.
Zip or tar your complete work including source files. 

Please send your feedback before the end of (Date) February 2021.

Assessment: 
The goal is to produce a responsive HTML5 page displaying various music playlists.
As this is a front-end assessment, no databases or back-end  processes should be used to store or retrieve data.
Where possible consider performance enhancements.

Please note: No music is required to play as part of this assessment and as such should not be catered for.

Task 1
Create a menu using json to display a minimum selection of 4 different playlists.

Task 2
Fix the JavaScript:

Window.loadPlaylist = function('list.html') {
  var xhttp = new XMLHttpRequest();
  xhttp.onreadystatechange = function() {
    if (this.readyState === '4' && this.status === '200') {
      document.body.innerHTML = this.responseText;
    }
  }
  xhttp.open("GET", url, true);
  xhttp.send();
}

Task 3
Display each of the playlists from the menu using AJAX.
The playlist should have a minimum of 5 items.
The user should be able to re-order, remove, like/unlike etc. items in the playlist.
