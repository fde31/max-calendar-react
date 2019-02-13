# max-calendar-react

Implements a NodeJS-based event calendar for use in Max 8 (node.script). This version uses React/Bootstrap for the front end, allowing for a dynamic listing of existing scheduled events.

* Needs an added "delete" button for listed events
* Edit existing events?

To use, you must first build a deployment version of the React site by navigating your terminal to "/max-calendar-react/client/" and then running "npm run build". Open the Max patcher and hit "script start" to start the server, and then navigate your browser to localhost:5000

To use in development mode, you must first start the node script in the patcher and then navigate to "max-calendar-react/client/" and typing in "npm start". This will work through a proxy with the Max server, so it's good for developing new features.

