---
title: Poll Terminated
description: Trigger for when a Twitch Poll has been terminated
version: 0.0.50
twitchService: EventSub
variables:
  - name: poll.Id
    type: string
    description: Twitch's internal id for the poll
    value: f76ddfef-8654-4fd1-9dda-b377a73ed9ef
  - name: poll.StartedAt
    type: DateTime
    description: The timestamp that the poll was created
    value: 8/4/2023 10:56:06 AM
  - name: poll.Duration
    type: int
    description: The duration of the poll in seconds
    value: 300
  - name: poll.DurationRemaining
    type: int
    description: The remaining time in milliseconds
    value: 0
  - name: poll.choices.count
    type: int
    description: The number of choices in the poll
    value: 3
  - name: poll.choice#.title
    type: string
    description: The title of this choice
    value: Choice 1
  - name: poll.choice#.votes
    type: int
    description: The number of regular votes of this choice
    value: 10
  - name: poll.choice#.rewardVotes
    type: int
    description: The total number of reward based votes of this choice
    value: 7
  - name: poll.choice#.totalVotes
    type: int
    description: The total number of votes for this choice
    value: 17
  - name: poll.votes
    type: int
    description: The total number of regular votes
    value: 30
  - name: poll.rewardVotes
    type: int
    description: The total number of reward based votes
    value: 19
  - name: poll.totalVotes
    type: int
    description: The total number of votes
    value: 49
  - name: poll.endedAt
    type: DateTime
    description: The timestamp that the poll ended
    value: 8/4/2023 10:56:06 AM
  - name: poll.winningIndex
    type: int
    description: The index of the winning choice
    value: 2
  - name: poll.winningChoice.id
    type: string
    description: The id of the winning choice
    value: 34f544d0-93ab-48bb-9f25-095071604cbd
  - name: poll.winningChoice.title
    type: int
    description: The title of the winning choice
    value: Choice 2
  - name: poll.winningChoice.votes
    type: int
    description: The number of regular votes from the winning choice
    value: 20
  - name: poll.winningChoice.rewardVotes
    type: int
    description: The number of reward based votes from the winning choice
    value: 10
  - name: poll.winningChoice.totalVotes
    type: int
    description: The total number of votes for the winning choice
    value: 30
  - name: poll._json
    type: string
    description: All the variables in a JSON Object
commonVariables:
  - TwitchBroadcaster
---
