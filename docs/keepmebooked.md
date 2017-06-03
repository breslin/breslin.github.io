# Keepmebooked: B2B Property Management Software
Our business objective was to transition the product from focusing on customers in the hotel industry to those in the vacation rental industry. This migration also came with the technical challenge of scaling a legacy codebase to a userbase of 50,000+ (from under 1,000).

**My role**: Hands-on Managing Director leading a team of 10 developers and designers.
**Platform**: Web & Native Mobile.

## Understanding the customer

!> **Task #1**: understanding the customer

`customer development` `interviews` `key jobs` `pains` `gains`

```
1. 📝 Interview target customers
2. 🔎 Discover key jobs, pains and gains
3. 👥 Identify customer segments
```

> Interview target customers 📝

I conducted over 20 hours of interviews in person and on Skype with vacation rental customers to understand their distinct needs.

<img src="/images/kmb-customer-dev-one.jpg" width="100%">
*A summary slide from one of the customer interviews*

> Discover key jobs, pains and gains 🔎

From those interviews, customer key jobs, pains and gains were identified. This information was used to determine our core product and the changes needed to make to the existing product suitable.


<img src="/images/kmb-customer-dev-two.jpg" width="100%">
*Key customer jobs, pains and gains for one customer segment*


> Identify customer segments 👥

Due to this research and analysis 3 customer segments were defined as well as the features and benefits of value:

1. Owners of 1 property
2. Multiple property owners (2 - 20 properties)
3. Operator/manager (5 - 40 properties)


 With these segments we were able to determine our product roadmap and develop our business model with great confidence. Initally we focused on the second segment as our existing product could be shaped to match their requirements without huge difficulty. The first segment was ruled out as the majority of users did not need a solution like Keepmebooked and those that did would not support our business model.

<img src="/images/business-model-canvas.png" width="100%">
*Business model canvas*

---

## UX wireframes and flows

!> **Task #2**: develop UX flows

`omnigraffle` `user journeys` `logic flows` `user stories`


### User stories

With a firm understanding of the customer jobs, pains and gains I came up with a number of user stories, for example:

* As a user I want to view bookings for my properties
* As a user I want to enter bookings from guests over the phone
* As a user I want to sync my calendar with Booking.com

By understanding the user types and stories we can optimise how the software is used. The next step was to design the user journeys (the flows through the application we want a user to take) and logic flows. The aim of our user journey was to ensure the user sees value in the product as quickly as possible. This was a challenge as the on-boarding effort was high and to fully complete would take a number of days due to external integrations.

<img src="/images/web-app-flow.png" width="100%">
*Web app UX flow*


___


!> **Task #3**: develop UX wireframes

With the user journey laid out and features clear we moved on to the UX wireframes. They are used by a designer to create a style guide and design the user interface.

## Experimentation and iteration

Once the general layout for key screens were in place we shared with a group of users for feedback - we were fortunate to have a number of our target customers already using the legacy platform. We used their responses and our own intuition to refine our designs.

<img src="/images/template.png" width="100%">
*UX Template*

The images below illustrate an example of our experimentation. A key user story was for the user to have quick access to booking information as they scrolled through and reviewed their calendar. The original UX was to have a tooltip pop-up over the booking on click. We realised this design was limited in that the booking information wasn't always consistent (eg. some would have long notes, some would have short and some none at all). We thought we could improve, whislt keeping the speed and ease of accessing this information. The second image shows the preferred solution - a sliding panel. The sliding panel allowed an appealing structure whilst promoting key information and actions (eg. send the guest a message).

<img src="/images/calendar-tootlip-one.png" width="100%">
*Tooltip to display booking information*

<img src="/images/calendar-tootlip-two.png" width="100%">
*Dedicated panel to display booking information*

**Further refinement**

The UX changed again slightly post design - the booking sliding panel was moved to the right hand side. We discovered through user testing and screen recordings that users typically interacted with the left hand side of the calendar where todays date (and immediate future/past days) was displayed.

<img src="/images/user-flow.gif" width="100%">
*UX interactive wires created using Balsamiq*
___


## UI Refresh

**The original user interface**

As you can see the original user interface was outdated. It was also clumbsy without a coherent structure to the user flow. Our UX work fixed the user flow, now to the design.

<img src="/images/keepmebooked-original.png" width="100%">

