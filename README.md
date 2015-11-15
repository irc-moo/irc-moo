# irc-moo

## motive

* Make IRC accessible to less technical people by reducing 'configuration', make setting up a bouncer trivial.

* Improve on UI and UX of current IRC clients

## features

#### Always online
Maintain irc connection even when user is not using client.

#### Infinite logs
As a side effect of being always online, we can log all messages to enable features such as infinite past scrolling on the clients and searchable logs.

#### Notifications
As another side effect of being always online, we know when an AFK user receives a private message or a mention.

#### Persist User Preferences
Maintain user preferences such network and channel list on the cloud and bind it to his moo account.

#### Channel finding wizard
There is tons of communities on IRC, let's write an algorithm to index them and sort them in a meaningful way. Perhaps even give them popularity statistics.

#### Plugins
irc-moo clients will be able to detect other irc-moo clients on channels, enabling extra features between them such as:

* Encrypted p2p communication (completely outside of irc network, p2p!)

* Tic-Tac-Toe game between two irc-moo clients?

#### Simple
Abscract the ugly details of IRC such as hostname/channels and NickServ with comprehensive GUIs.
