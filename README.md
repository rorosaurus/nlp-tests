# Natural Language Processing Tests
A sort-of Turing Test for virtual assistants who utilize Natural Language Processing

## Handling imperfect phrases/phrasing
* "OK Google, remind me at like 3pm tomorrow to call Dad."
* "Remind me in the morning to xyz."
  * This is particularly interesting in the scenario when the reminder is requested after midnight.
* "Remind me I have a meeting tonight."
  * Most assistants will create a reminder that says "I have a meeting tonight" instead of "You have a meeting tonight."

## Contextual information surfacing
* "Hey Siri, remind me tomorrow to call and place that dinner reservation."
  * Assistant should know what dinner you mean based on conversations/events and pre-populate the phone number, etc.

## Complex chains
* "Cortana, message Eric on whatever messaging app he messaged me on most recently, and send him the address for dinner."
* "Siri, what's that Thai place I went to with Erin for dinner last week?"
* "OK Google, navigate to the address of the last event I attended that was hosted by Alex."
* "Remind me next time I'm near the mall to pick up xyz."
* "Can you message everyone and tell them I'm running late?"
