# Keepmebooked: B2B Property Management Software
Our business objective was to transition the product from focusing on customers in the hotel industry to those in the vacation rental industry. A secondary objective was to overhaul the user experience and refresh the user interface. This migration also came with the technical challenge of scaling a legacy codebase to a userbase of 50,000+ (from under 1,000).

**My role**: Hands-on Managing Director leading a team of 10 developers and designers.

**Platform**: Web & native mobile.

## Task #1: Understanding the customer

`customer development` `interviews` `key jobs` `pains` `gains`

```
Method:
1. 📝 Source and interview target customers
2. 🔎 Discover key jobs, pains and gains
3. 👥 Identify customer segments
```

> Source and interview target customers 📝

I conducted over 20 hours of interviews in person and on Skype with vacation rental customers to understand their distinct needs. These customers were sourced from our partner HouseTrip and existing Keepmebooked members.

<img src="/images/kmb-customer-dev-one.jpg" width="100%">
*A summary slide from one of the customer interviews*

> Discover key jobs, pains and gains 🔎

From those interviews, customer key jobs, pains and gains were identified (examples shown on image below). This information was used to determine our core product and the changes required to make to the existing product suitable.


<img src="/images/kmb-customer-dev-two.jpg" width="100%">
*Key customer jobs, pains and gains for one customer segment*


> Identify customer segments 👥

From this research and analysis 3 customer segments were defined in addition to the features and benefits that would be of greatest value:

1. Owners of 1 property
2. Multiple property owners (2 - 20 properties)
3. Operator/manager (5 - 40 properties)


 With these segments we were able to determine the product roadmap and develop a business model with confidence. Initally we focused on the second segment (Multiple property owners) as our existing product could be shaped to match their requirements. The first segment was ruled out as the majority of those users did not need a solution like Keepmebooked and those that did would not support our business model.

<img src="/images/business-model-canvas.png" width="100%">
*Business model canvas*

---

## Task #2: UX wireframes and flows

`omnigraffle` `user journeys` `logic flows` `user stories` `balsamiq`


> User stories 👥

With a firm understanding of the customer jobs, pains and gains I came up with a number of user stories, for example:

* As a user I want to view bookings for my properties
* As a user I want to enter bookings from guests over the phone
* As a user I want to sync my calendar with Booking.com

> User journey's 🚶

By understanding the user types and stories we can optimise how the software is used. The next step was to design the user journeys (the flows through the application we want a user to take) and logic flows. The aim of our user journey was to ensure the user sees value in the product as quickly as possible. This was a challenge as the on-boarding effort was high and to fully complete would take a number of days due to external integrations.

The image below illustrates a user onboarding onto the platform:

<img src="/images/web-app-flow.png" width="100%">
*Draft web app UX flow - developed in partnership with our UX designer Ricky Faria*


___


## Task #3: Develop UX wireframes

With the user journey laid out and features clear we moved on to the UX wireframes. They are used by a designer to create a style guide and design the user interface. Each screen was mocked up individually, including user interactions and feedback.

<img src="/images/kmb-ux-draft.png" width="100%">
*Keepmebooked UX draft screen*

<!-- <img src="/images/template.png" width="100%">
*UX Template* -->

> Experimentation and iteration

First the first few drafts for key screens in place we shared with a group of users for feedback - we were fortunate to have a number of our target customers already using the legacy platform. We used their responses and our own intuition to refine the designs.

**Example experiment: Toolip or sliding panel?**

A key UX requirement was for the user to have quick access to booking information as they scrolled through and reviewed their calendar. The original UX was to include a tooltip pop-up over the booking on user click. We realised this design was limited in that the booking information wasn't always consistent (eg. some bookings have long notes, some short and others none at all). We thought we could improve, whislt keeping the speed and ease of accessing this information. The second image shows the preferred solution - a sliding panel. The sliding panel offered a practical and appealing structure whilst promoting key information and actions (eg. send the guest a message).

<img src="/images/calendar-tootlip-one.png" width="100%">
*Tooltip to display booking information*

<img src="/images/calendar-tootlip-two.png" width="100%">
*Dedicated panel to display booking information*

**Further refinement**

The UX changed again slightly post design - the booking sliding panel was moved to the right hand side. We discovered through user testing and screen recordings that users typically interacted with the left hand side of the calendar where todays date (and immediate future/past days) was displayed.

<img src="/images/user-flow.gif" width="100%">
*UX interactive wires created using Balsamiq*
___


## Task #4: Mobile


!> In reality mobile was an integral part of the previous tasks, however, I've separated here to keep things simple.

It became obvious that mobile was critical to the success of Keepmebooked being adopted by vacation rental customers. These customers were much more likely to be 'out and about' and working on the go in comparison to hotel and BnB owners.

A vacation rental owner typically meets the guest for check-in at a location which could be a distance away from their home, office or other properties in their portfolio. They needed to handle guest enquiries, cleaning operations, view critical information and much more on the go. As we worked through the proposition we realised that mobile offered a different challenge but opened up valuable opportunities in comparison to the web application.

**Example challenge: creating a booking**

To create a booking on the web app the user scrolled to the correct date on the calendar, clicked on the check in date and dragged to the check out date. On web this offered a quick, easy and intuitive method of creating a booking. The user could see at a glance if there was availability on any of their properties and could respond to the potential guest immediately if they were on the phone and quickly via email.

A similar interaction with the calendar on mobile would not work. The view was too small (up to 7 days where a booking would often be 2 weeks or more) and dragging was clumbsy. To achieve the goal of 'quickly assessing availability and creating a booking' we took an entirely different approach. On mobile a user would:

1. select 'new booking' (a primary action button)
2. select the date of check in, the booking duration and any other key info (eg. # of guests)
3. be shown a list of properties available and their total price

The user could then relay the options to the guest and create the booking in seconds. Below is a very early draft:

<img src="/images/add_booking_dates.png" width="33%">
<img src="/images/add_booking_guests.png" width="33%">
<img src="/images/add_booking.png"width="33%">

*Early draft of adding a booking on mobile*


> Mobile UX Mockup screens

As with the web app, each screen was mocked-up with annotations (examples below). Once the first draft was complete it was shared with our iOS developer to get feedback from an iOS standard perspective. I find that this step provides great value so we avoid designing elements that are impractical or don't translate well to different screen sizes. An example of the feedback from the iOS designer was to remove 'pop-up' screens - which we did.

The next draft of screens were shared with our customer testing group using Invision so they could test the flow as well in addition to the information and actions on each screen. We iterated again based on their feedback.

<img src="/images/mobile-one.png" style="border: 1px solid #e1e1e1;" width="100%">

<img src="/images/mobile-two.png" style="border: 1px solid #e1e1e1;" width="100%">

<img src="/images/mobile-three.png" style="border: 1px solid #e1e1e1;" width="100%">

> User interface design

With the final screen mockups completed our designer got to work on the user interface (example screens below). Our iOS developer then started building the app - happy they had been briefed during the early design process, eliminating any nasty surprises resulting in required design edits on our part.

<img src="/images/calendar_mobile.png" width="33%">
<img src="/images/trap_day.png" width="33%">
<img src="/images/Success.png" width="33%">



