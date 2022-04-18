# Ellipsis

Goals

* [ ]  Catch issues before they are caputred by CI
* [ ]  Automatically run tasks for the developer as the develop in a remote development environment( ex: execute tests, linters etc)
* [ ]  Capture task output
* [ ]  Notify of events (ex: test failure)
* [ ]  Browser based GUI that streams log files
* [ ]  Configure which commands to run, at what intervals or on file changes

# Happy Path

1. Type a new command in the browser
2. Set to watch file or interval
3. See streamed output

# Stack Notes

* Display of code in the browser
  * Prismjs, Sytax Highlighting, in browser: https://prismjs.com
  * Prismjs, Line Numbers, in browwser: https://prismjs.com/plugins/line-numbers/
* Nodejs File streams instead of entire contents
  * https://stackabuse.com/read-files-with-node-js/

# Todos

* [ ]  Get a Static Hello World Web page

# Decion Records

1. This could be replaced by a series of terminal tabs performing each action on watch/time interval and sending some notification upon failure
