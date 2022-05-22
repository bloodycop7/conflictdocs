# Conflict Studios Developer Documentation

## Player Meta Tables
![](https://files.facepunch.com/wiki/files/19952/8d7b58d999caa0e.png)
```lua
IsCitizen() -- SHARED
```
Checks if the player is Citizen

Returns bool

```lua
IsLoyalist() -- SHARED
```
Checks if the player is UUA

returns bool

```lua
IsCombine() -- SHARED
```
Checks if the player is Combine

returns bool

```lua
IsCA() -- SHARED
```
Checks if the player is City Administrator

returns bool

```lua
IsDispatch() -- SHARED
```
Checks if the player is Dispatch

returns bool

```lua
IsCombineCommand() -- SHARED
```
Checks if the player is a Combine Command

returns bool

```lua
IsRunning() -- SHARED
```

Checks if the player is running

returns bool

```lua
IsDeveloper() -- SHARED
```

Checks if the player is a developer

returns bool

```lua
IsDonator() -- SHARED
```

Checks if the player is donator

returns bool

```lua
GetSanity()
```

Returns the amount of sanity for the player

```lua
GetMood()
```

Returns the mood of the player.

```lua
SetMood(int)
```

Sets the mood of the player followed by the id of the mood.

## Functions

![](https://files.facepunch.com/wiki/files/19952/8d7b58d7428c9c6.png)

```lua
ix.event.PlaySound(ply, sndtable)
```

sndtable contents:

```lua
sound -- string
db -- number
pitch -- number
volume -- number
delay -- bool
```

Plays a sound to a specific Player

```lua
ix.event.PlaySoundGlobal(sndtable)
```

sndtable contents:

```lua
sound -- string
db -- number
pitch -- number
volume -- number
delay -- bool
```

Plays a sound globally ( every client )

```lua
ix.event.StopSoundGlobal(sound)
```

Stops a sound globally ( every client )

```lua
ix.intro:Start(ply)
```

Plays the map intro for the player

```lua
ix.quiz.GetQuestions()
```

Returns all questions on the quiz menu.

```lua
ix.quiz.GetQuestion(id)
```

returns the table of information for the specific question

```lua
ix.quiz.GetMessage(id)
```

Returns the message of the specified question.

```lua
ix.quiz.GetOptions()
```

Returns all options on the specific Question.

```lua
ix.quiz.GetCorrectAnswer(id)
```

Returns the correct answer on the specified question.











