# dispiano
A discord bot for playing music notes.

dispiano utilizes the pysynth library to create audio from musical notes.

### Example command:

```
Bach: Bourrée (from BWV 996)
!piano e,8 f#,8 g,4 F#,8 e,8 d#,4 e,8 f#,8 b3,4 c#,8 d#,8 e,4 d,8 c,8 b3,4 c#,8 d#,8 e,4 d,8 c,8 b3,4 a3,8 g3,8 f#3,4 g3,8 a3,8 b3,8 a3,8 g3,8 f#3,8 e3,4 e,8 f#,8 g,4 f#,8 e,8 d#,4 e,8 f#,8 b3,4 c#,8 d#,8 e,4 d,8 c,8 b3,4 a3,8 g3,8 f#3,32 g3,32 f#3,32 g3,32 f#3,32 g3,32 f#3,6 g3,8 g3*
```

### Usage:

To use dispiano you need to create a bot for discord and then generate a token:

https://github.com/reactiflux/discord-irc/wiki/Creating-a-discord-bot-&-getting-a-token

Then add the bot to your server:

https://github.com/jagrosh/MusicBot/wiki/Adding-Your-Bot-To-Your-Server

Next you need to install the dependencies:

* __discord.py__

  ```python3 -m pip install -U discord.py```

* __PySynth__

  Download the stable release from:
  https://mdoege.github.io/PySynth/#d

  then run setup.py:

  ```python3 setup.py install```
  
Now you can run dispiano:

```
python3 dispiano.py <YOUR_TOKEN_HERE>
```
