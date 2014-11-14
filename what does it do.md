### time2talk - how will it work

once downloaded the app will guide the user through the registration process, which we divided into four parts:

 - setting up of a `public profile` (1-2min)
 - setting up of a `private/admin only profile` (5 min)
 - setting up two preferred `meeting places` (3 min)
 - moderation of content submitted by others (3 min)

each of these will be looked at in greater detail either below, in separate posts or on wiki pages for the code repository. In the meantime, we have the user just finishing the registration process and one it's completed the user can immediately start using the app. 

In most general terms this will involve taking one of the three actions:

 - search local area for someone available to talk and send `request2talk`, 
 - set the status as `available2talk` and leave the app, or 
 - set the status to `unavailable` and leave the application.

![enter image description here](http://www.time-to-change.org.uk/sites/default/files/roxanne_and_charlie.png)

The last of the three doesn't require any more attention, the user logs off and all the processes are being shut down. See you next time!

The remaining two options I will break down into more detail just to give a feel how the basic use of the app would look like - there are plans on doing some work in regards to graphics which will make dumping these assets into Muse, Edge Animate or GWD all too easy and which inevitably will result in a working prototype but in the meantime below description should suffice. 

So the workflow/customer journey will follow one of the two scenarios:

### `request2talk` 

First scenario will involve a user opening an app and sending a `request2talk` to one of the users who appear on their map as `available2talk` the request triggers an action setting up a meeting in one of the available `meeting places`, sets up a time for the meeting taking into account the distance both users will have to travel to get there. it then sends notifications to both users with information about the meeting, time and best ways to get there. 


![enter image description here](https://raw.githubusercontent.com/weAreThePlayMakers/time2talk/master/_assets/exampleMap.png)

> Here's our early artistic vision with `available2talk` users pasted on
> top of visualisation platform built with polymer featuring aggressively styled 
> google map layer


### `available2talk`

In the second scenario user opens the app and toggles the status from `unavailable` to `available2talk` which will make their `public profile` visible to other users within the area.

> **Important!** throughout this whole time a user will have to be somewhere within the area of their registration and will have to be able to leave whatever they are doing at very short notice (10 min) in response to `request2talk` from other users. 

### let's talk

Responding to `request2talk` will involve meeting with someone from their local community for a chat, walk in the park or anything else that might be helpful and was agreed upon prior to the meeting. There always will be some travel involved to specified in the request `meeting place` but presumably the distances will be small and the places will be rather familiar to users. 

The primary target users are people suffering from depression or other mental health conditions and who might not have anyone to talk to and who could use some friendly and positive talk about the weather or anything really. the app could be made available as part of Mind's current #timetotalk campaign.


> written by [rafszul](https://github.com/rafszul) and [weAreThePlayMakers](http://wearetheplaymakers.com/) with [StackEdit](https://stackedit.io/).




