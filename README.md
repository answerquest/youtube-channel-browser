# youtube-channel-browser
Everything in one single HTML file. Enter a youtube channel or playlist id, and browse through all its videos with their details and descriptions. 500 or even more at a time. 

A javascript function batch-loads RSS feeds from youtube and parses the data, rendering information like title, duration, date of publishing, description and thumbnail into a table. This makes it a lot more convenient, and fast on slower computers, to browse through long list of videos, and read all their descriptions in one place.

Though the youtube feed server only returns 50 entries at a time, the script batch-loads consecutive feeds and displays them all in a row.

This is useful to create a catalogue of all videos published by a channel. Saving the file using Ctrl+S *works*.. there is no change in functionality, AND whatever content was being displayed gets saved as basic HTML into the saved file inside the <div> tag whose innerHTML is being used to show the output.

Compatibility : Works in Firefox browser, tested in v32.
