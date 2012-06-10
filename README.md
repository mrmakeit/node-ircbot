node-ircbot
===========

Our turntable and IRC bot in one.

Enviroment Variables
===========

AUTH: turntable auth variable
USERID: turntable user id
ROOMID: turntable room id
PASS: database password

Plugins
===========

Hello: Replys to !hello command with greeting and the time.
Botsnack: Responds to !botsnack with a thank you.
karma: Allows users to give and take awsome points with !<nick>++ and !<nick>--
  will list all karma with !karma? and individual karma with !karma?<nick>
Logging: Logs all irc and turntable activity on mongoDB. Viewable with tulsalogs at tulsalogs.jit.su/logs/service/year/month/day
turntable: impliments turntable commands in both irc and turntable chats.  !dj puts tulsabot on deck if there is an open space. !listen pull him off. !skip causes him to skip a song. bop anywhere in a chat causes him to awsome song. 
  following commands only work in pm on turntable.  !add?<query> adds first song in query to his list. !<comp>top changes laptop to either chrome, linux, or pc. !android changes to android phone. !iphone changes to iphone.

Change log
============

1.0.0:
Plugins added:
Hello
Botsnack
Karma
Logging
Turntable

First published version.


Licence
=============

This work is licensed under the Creative Commons Attribution-NonCommercial 3.0 Unported License. To view a copy of this license, visit http://creativecommons.org/licenses/by-nc/3.0/ or send a letter to Creative Commons, 444 Castro Street, Suite 900, Mountain View, California, 94041, USA.

