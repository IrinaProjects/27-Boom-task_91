# ⚙ HTML, CSS and SASS Boilerplate 
This project is used as a boilerplate for tasks in the "HTML, CSS and SASS" course in boom.dev

🤯💥💣

Objective
Import the project https://gitlab.com/boomdotdev/tasks/task-91
Checkout the dev branch
Create a ".message" for each lyric every time the beat ticks
When implemented merge the dev branch into master before validating
Requirements
The project must run when started via npm run start
There must be a "_beat" instance in the Application class attached to the class instance (this._beat = new Beat())
The Beat class must emit the Beat.events.BIT on every interval
The Application class must have a "_create" method
A .message should be created for each lyric every time the event is emitted
There must be an event listener in the Application class for Beat.events.BIT
There must be an import statement for eventemitter3 in Beat
The Beat class must extend EventEmitter
