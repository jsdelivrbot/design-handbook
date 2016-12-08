---
layout: page
title: Design Toolkit
---

The design process is a mix of a lot of smaller tasks. There’s no one-size-fits-all design process for every project. Every designer has to pick and choose which tasks will provide their team the most value for the project.

## Meeting: Design Workshops
Help teams get clarity and build consensus on projects

Design workshops are great at bringing a team together to focus on a problem from a design perspective. They are especially helpful when bringing in non-designers. These sessions build group consensus around how to solve the problem.

Each session can range from 10 minutes long to multi-hour brainstorming sessions. There are a lot of different design workshop for different goals, but some favorites are [6 Up/1 Up](http://goodkickoffmeetings.com/2010/04/design-studioprototyping-exercise/), [20 Second Gut Test](http://goodkickoffmeetings.com/2010/04/the-20-second-gut-test/), and [Card Sorting](http://gamestorming.com/core-games/card-sort/). This works best having everyone in the same room but there are tools to make this work better remotely.

More references: Gamestorming, Visual Meetings

## Meeting: Project Team Review
Get feedback on goals and implementation of proposed design solutions

Whenever a design artifact is complete it should be shown to the team so that everyone on the project is included in the process and can give feedback as early as possible. Depending on complexity, this could mean an actual meeting or just publishing to the projects Slack channels/project management tool for discussion.

The goal of this review is to gauge whether or not the design solution is appropriately meeting the business objectives of the project and fitting into the scope of the backend system. This is also an opportunity for the designer to go over any questions or suggested scope changes that may have appeared during the design process.

## Meeting: Design Team Review
Get feedback on consistency, usability, layout, etc

The design team review is very similar to the project team review, except with different goals. Bringing in other designers to view and discuss work opens up the design to fresh eyes who haven’t been focused on the project for weeks or months. Other designers will notice brand/visual consistency issues, bring up questions they would have if they were doing the work, and have suggestions for alternate design patterns.

## Design Artifact: Diagrams
Visualize a complex system or hierarchy

Diagrams illustrate a complex part of a system, whether it be a web page or a product, to help everyone on the team visualize the project. Commonly you’ll see these as sitemaps of a website or product, outlining the structure and density of content. Diagramming user journeys through a product or specific feature can also help provide clarity to the project and point out trouble spots where the user can become confused.

## Deign Artifact: Low Fidelity Mockups
Rough brainstorming of layout and content flow

Lo-fi mockups tend to take the form of sketches or wireframes. The goal of these mockups should be to only focus on layout, spacial relations and hierarchy of content. Images might be for-placement-only. Copy can be faked. This is to make sure that the idea will work and a user will be able to get to the features or information they’re looking for intuitively.

## Design Artifact: High Fidelity Mockups
Refined visuals representing close-to-browser look and feel

Hi-fi mockups are where the design details are polished. Visual consistency, color, typography, finding or illustrating the perfect icons, imagery, grids, etc. If a project requires key animations, this is where those prototypes would be created. The goal is to work towards presenting as close as possible to what a user will see in their browser, without having to get down into code.

## Design Artifact: Clickable Prototypes
Explain and test complicated user journeys to visualize through static mockups

Some projects are so complex that diagrams and static mockups aren’t enough to fully explain the user’s journey. Applications like Invision and Keynote will help turn a series of static mockups into something that resembles what the final product could be. This is helpful for running quick user tests on the potential solution or to help the team visualize how the interface all works together. This can also be done using code.

## Design Artifact: Production Front-end Code
Building the interface focusing on maintainability, componentization, accessibility, multiple browsers and screens

Front-end development tends to be the last deliverable of a project. If there is a good library of design patterns to pull from, jumping straight into code can be done instead of building out static mockups. When building the front-end, pay attention to writing maintainable code (Will this make sense a year from now?), componentizing design patterns so they can be reused for other projects, accessibility, and optimizing for multiple browsers and screen-sizes.

## Data: Surveys
Quantitative and maybe qualitative data from users to inform decision making

Surveys are great. You can get a lot of data relatively quickly with some solid questions and good user segmentation. Short surveys are answered more than long surveys. Rank-sorting, multiple choice and yes/nos will give good quantitative data. Letting the user freeform write will give good qualitative feedback.

## Data: Analytics
Quantitative data from user behavior to inform decision making

Analytics are used to inform decisions. We have Google Analytics on most of our properties so we can see traffic and time spent per page. On dreamhost.com we can follow a users trail all the way through signup and see where drop off points are. There’s a lot of data in here.

We currently use Hotjar for click analytics. (ex, heatmaps, user videos, forms, etc). Like CrazyEgg, you can use it to understand the microeconomics of user behavior in an app or website. While this data is incredibly useful for on-page content and other minutia, getting to the bigger picture requires additional input from analytic sources like Google Analytics; which excels at recording higher level user interaction data, but provides lackluster on-page insights as compared against Hotjar or CrazyEgg.

In a perfect world, tools like Google Analytics and Hotjar are used in coordination, for validation purposes.

## Data: Usability Testing
Testing a page or interface to validate the intuitiveness and assumptions of user behaviors and reactions

Usability testing is the act of putting something in front of users and watching them interact with it. In-person usability testing involves bringing people to a computer, watching them use an interface, and documenting the troubles they had in using it.

## Data: Personas
A representation of a cluster of users documenting their behaviors, goals and motivations

Personas are documents that help us understand an archetypal group of customers. It is an overview of that customer's buying habits, motivations, uses for your product, wants and needs. It can include personal information like hobbies and demographics about this fake person to increase our own empathy for that customer type.

## Data: A/B/n Split Testing
Testing variations of a design with real users to see which one is more effective, engaging

A/B/n testing is a good method to test small changes to a page. Tweaking copy, changing layout, etc. You can set up rules for what the win condition should be and let Google handle traffic to the variations. It’s best to leave tests running for 3 weeks or more, to avoid invalidating results based on seasonality. Most split testing facilitators include built-in algorithms that deduce “confidence” levels of a running test’s results. When available, it is recommended to wait for at least 95% confidence in results before completing a test.





