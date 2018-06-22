---
title: "how to submit to iOS Apple App store"
tags: [ "ios", "moejoe" ]
author: Rob Nugen
date: 2018-06-19T08:32:50+09:00
---

## 08:32 Tuesday 19 June 2018 JST

I know I wrote something like this before, but now I cannot find it.   I looked in bitbucket, github gists, but not redmine, which I cannot seem to find now at redmine.robnugen.com.  I also checked in https://new.robnugen.com/toots 

((Below is adapted from https://code.tutsplus.com/tutorials/how-to-submit-an-ios-app-to-the-app-store--mobile-16812 and https://www.raywenderlich.com/184709/submit-app-apple-no-account-app-store-part-1))

I am writing this copy in https://new.robnugen.com/toots/submit-to-ios-app-store/
and maybe also in
https://wiki.robnugen.com/wiki/Programming:How_to_publish_an_iOS_app_as_of_2018

1) https://developer.apple.com/

2) Click (Account) in top right

3) Login as rob@cf.com

4) Change top right to ist

## Create APP ID

https://developer.apple.com/account/ios/identifier/bundle/create

App ID Description:   ConSwi first try 2018 June 19

Bundle ID:   com.cf.conswi.2018june19

App Services: (default: Game Center and In-App Purchase)

(Continue)

(Register)

    This App ID is now registered to your account and can be used in your provisioning profiles.

(Done)

5) https://developer.apple.com/account/ios/identifier/bundle

6) Click on the new bundle name and find the Prefix and ID.

## Add to Godot (Godot300 game dev engine thingie)

7) Open Godot Project -> Export

8) Copy the Prefix 99PU... into App Store Team Id in Godot

