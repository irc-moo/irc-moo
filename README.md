# irc-moo

## motive

* Make IRC accessable to less technical people by reducing 'configuration', make setting up a bouncer trivial.

* Improve on UI and UX of current IRC clients

## art direction

* Minimal, intuitive, slack-like

* Abstract away hostnames (user enters freenode instead of irc.freenode.net)

* Abstract away Nickserv and figure out some sensible user registration flow.

* Abstract away the status box that shows MOTD. Instead we could have a preference to enable console toggling, or just make it a CMD+Letter hotkey.

* Also figure out some way to make it easy for some to figure out what network they want to get on and what channels they want to be on
 like suggestions or something.

## front-end architecture

The stack:

* electron
* redux
* react
* re-select
* flow-type