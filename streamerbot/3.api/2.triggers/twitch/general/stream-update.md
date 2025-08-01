---
title: Stream Update
description: Trigger for a Twitch Stream Update
version: 0.0.30
twitchService: EventSub
variables:
  - name: status
    type: string
    description: The current stream title
    value: My stream title
  - name: gameUpdate
    type: boolean
    description: has the game been updated?
    value: True
  - name: statusUpdate
    type: boolean
    description: has the status been updated?
    value: True
  - name: gameId
    type: number
    description: The game id of the stream
    value: 509658
  - name: gameName
    type: string
    description: The game name of the stream
    value: Just Chatting
  - name: oldStatus
    type: string
    description: The old title of the stream
    value: My old stream title
  - name: oldGameId
    type: number
    description: The old game id of the stream
    value: 518203
  - name: oldGameName
    type: string
    description: The old game name of the stream
    value: Sports
  - name: gameBoxArt
    type: string
    description: The box art for the game
  - name: oldGameBoxArt
    type: string
    description: The old box art for the game
commonVariables:
  - TwitchBroadcaster
  - TwitchUser
---

## Details
This triggers when the title or the description changes on your stream.

## Parameters
::field-group
  ::field{name="Game Only" type=Checkbox}
    Check this field if you only want this to trigger when the game changes
  ::
  ::field{name=Game type=Select}
    Select a game if you only want this to trigger when the stream changes to this game
  ::
::
