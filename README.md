# Natural Language Processing Tests
### A sort-of Turing Test for virtual assistants who utilize Natural Language Processing.

Here are some phrases I think most virtual assistants will fail to handle correctly, most of which are fairly common and not unreasonable to dictate to a human assistant.

## Handling imperfect phrases/phrasing
* "OK Google, remind me at like 3pm tomorrow to call Dad."
* "Remind me in the morning to xyz."
  * This is particularly interesting in the scenario when the reminder is requested after midnight.
* "Remind me I have a meeting tonight."
  * Most assistants will create a reminder that says "I have a meeting tonight" instead of "You have a meeting tonight."
* "Remind me later today to call Andrew."

## Special case handling / exceptions
* "Hey Siri, schedule a meeting every Tuesday and Thursday with Sara at 2pm, except skip every other Thursday, starting next week."

## Contextual information surfacing
* "Hey Siri, remind me tomorrow to call and place that dinner reservation."
  * Assistant should know what dinner you mean based on conversations/events and pre-populate the phone number, etc.

## Complex chains
* "Cortana, message Eric on whatever messaging app he messaged me on most recently, and send him the address for dinner."
* "Siri, what's that Thai place I went to with Erin for dinner last week?"
* "OK Google, navigate to the address of the last event I attended that was hosted by Alex."
* "Remind me next time I'm near the mall to pick up xyz."
* "Can you message everyone and tell them I'm running late?"
* "Cortana, message everyone in the concert group chat and remind them to pick up their tickets."
