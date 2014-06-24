# scribus-plugin-message

A scribus plugin that shows messages.

# Todo

- create the plugin
- find out how to store the messages in a .SLA and how to retrieve them
- create a QML file for the list
- let the user add messages
- create an API that lets the code add simple messages
- show the list of active messages in the list
- let the user mark the messages as done and hide the done messages
- optionally attach the message to the current / specific (API only) page or item
- get the preflight verifier to show that there are open messages

# Planned features

- A palette shows a list of messages that have to be accepted by the user
- Accepted messages are hidden
- There is a way to see old messages
- Messages can automatically be created by Scribus
- Messages can manually be added by the user
- Pages and frames can have messages
- The preflight verifier shows if there are pending messages

# Use cases

- When deleting a page, a right page could get on the left side (in the future, it should automatically switch MP, and a warning also be issued).
- When, in the future,  automatically syncing a text frame with its content.
- When the source of an image frame has changed.
- As a todo list for the user
