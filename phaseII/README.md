# Phase II: Refining interaction and designing wireframes

## Introduction

The AroundU app is designed to help users discover local events by showing relevant event details like time, date, and distance from the user’s location, with the goal of connecting users to local activities. In phase II we aimed to address usability concerns identified in Phase I and from recent cognitive walkthroughs and informal feedback. The key objectives were to enhance user navigation, improve visual aids, improve event filtering options, and ensure that event hosts have clear control over event information.

## Methods

For this phase of our analysis on AroundU, we conducted a cognitive walkthrough with an external UX evaluator, a CSCI431W student (n=1). The evaluator followed a persona named Cruz to guide their experience through the app. The walkthrough involved assessing how well users could complete specific tasks without confusion, such as locating events on a map, filtering events by category, and securing a ticket.
The evaluator used the document [AroundU Cognitive Walkthrough](../Cognitive%20Walkthrough%20-%20AroundU(Cruz).pdf) following the streamlined two-question approach using the app's wireframe. This document details the steps for each task, the persona's goals, and questions to ask at each stage. The questions focused on whether the user understood each action, if there was adequate feedback for their choices, and any points of confusion or hesitation. Notes were taken on navigation confusion, lack of feedback cues, and areas where clearer guidance was needed.

We also received informal feedback of AroundU. We gathered input from Software Engineering students (n=65) who were given a demonstration of the app. Their feedback focused on initial impressions, ease of navigation, and the intuitiveness of key features, such as viewing upcoming events, understanding event details, and navigating back to the main dashboard. During this process, users were encouraged to express any points of confusion, advice on design choices, and areas that felt unintuitive.

## Findings

Through the cognitive walkthrough, we discovered two key issues related to user guidance and feedback. First, the user reported difficulty in understanding how to access the map feature while searching for events. This feedback highlighted a need for clearer prompts or visual cues to guide users to this functionality. Additionally, after securing a ticket, users did not receive any form of confirmation or feedback, which led to uncertainty about whether their action had been successfully completed. This lack of feedback suggests the need for a confirmation message or visual indicator to reassure users that their ticket has been secured. These findings emphasize the importance of providing both directional guidance within the app and real time feedback to enhance user confidence in the system.

During informal feedback, we asked, “Do you see yourself using this app in your daily life? If not, what would make it more useful for you?” and “How intuitive did you find the app’s user interface? Were you able to navigate without confusion?” Responses to the first question suggested features that would enhance the app’s usability, such as integrating the Google API for improved information windows, a “preview mode” for events that expands to a more detailed view, and event icons that populate and aggregate for easier browsing. Also, participants suggested including expiration dates for events to automatically remove outdated listings, support for recurring events, and an advanced filtering system to find specific categories. A search function that allows keyword-based filtering was also recommended to help users quickly find relevant events.

## Conclusions

Our analysis of AroundU showed the need for improved navigation, feedback, and visual organization. Wireframes should be updated to include clear prompts for accessing the map, confirmation messages for bookings, and advanced filtering options, such as list views and categorized icons. Incorporating the Google API will improve event discovery by adding markers, info windows, and location indicators. Together, these improvements can create a more organized, user friendly experience, making AroundU a valuable tool for daily event discovery.

## Caveats

One limitation of our research is sample bias, as our feedback mainly came from computer science students. This demographic may not fully represent the diverse user base of AroundU, which includes families, young professionals, and community newcomers. The technological background of our participants means that our insights may be skewed toward users who are already comfortable with app navigation, potentially overlooking the needs and challenges faced by less technical individuals. Expanding testing to include a wider range of users would provide a more broad understanding of AroundU’s usability and accessibility.
