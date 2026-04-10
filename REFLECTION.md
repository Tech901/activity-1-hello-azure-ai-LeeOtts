# Reflection -- Hello, Azure AI

Answer these questions after completing the activity (2-3 sentences each). Connect your answers to specific things you observed while coding and experimenting.


Thanks for all you do to make this class possible. 

![Hand Waving](https://github.com/Mayur-Pagote/README_Design_Kit/blob/main/public/Assets/Hand%20Waving.gif)

## 1. Service Surprises

Which of the three Azure AI services (OpenAI, Content Safety, Language) surprised you the most? Connect this to something specific you observed during your experiments -- a response you didn't expect, a behavior that seemed too easy or too hard, or a result that made you rethink how the service works.

_The content saftey suprosed me the most. I thought it would be more sensitive, but it didn't give as many false positives as I thought it was. But it did error out when I fed it antisaftey prompts._

## 2. Lazy Initialization

How would you explain the lazy initialization pattern to a colleague? Why is it used instead of creating clients at the top of the file?

_When you create them at the top you are using memory resources. Loading them when the item is actually called cane save on memory and make the program start quicker_

## 3. Content Safety in the Real World

A resident files this complaint: *"A man was assaulted at this intersection because the street light has been out for months."* This text describes real violence but is a legitimate safety concern. Should the system block it, flag it for human review, or pass it through? What factors would you weigh in making that decision?

_The system should allow it through. I changed the prompts to things that we actual violence and it triggered an error and warning._
_It knew that it wasnt a threat of violence it was explaining something_