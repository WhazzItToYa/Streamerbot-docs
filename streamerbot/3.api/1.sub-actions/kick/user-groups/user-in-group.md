---
title: User in Group
description: Check if a Kick user is a member of a given group
parameters:
  - name: User Login
    type: String
    required: true
    description: can be a user name or a variable like `%userName%`
    value: GenericUser
  - name: Group Name
    type: String
    required: true
    description: can be a specific group name or a variable
    value: BestFriends
variables:
  - name: inGroup
    type: bool
    description: indicator whether the user is in the specified group or not
    value: True/False
  - name: foundUser
    type: string
    description: the user's display name
    value: GenericUser
  - name: foundUserName
    type: string
    description: the user's login name
    value: genericuser
  - name: foundUserId
    type: string
    description: the user's ID
    value: 12345678
  - name: foundUserType
    type: string
    description: the user's platform
    value: kick
---
