---
title: Booking a visit (or not)
description: Exploring a new calendar component
date: 2021-08-06
---

## Calendar component

- Problem: 80% of our users book visits on a mobile device. The current/standard calendar picker is too small to fit on a mobile screen, reducing accessibility and user experience
- Needed to explore alternatives to a traditional calendar that could work across screens
- Took inspiration from NHS and Covid vaccine booking - using an accordion to show available dates
- Also looked at holiday bookings, flights, lots of booking services
- Explored a few options:
    - Day view
    - Two-step filtering
    - Filters on an accordion
- Specific problem in that people are likely to want to visit on a specific day of the week - offering the same time on a different day unlikely to be a helpful option
    - Have to test to understand what people want/what is most useful
- Decided to test accordion version with some basic filters
    - Day of the week
    - Time of day
- Able to test this on desktop at call centre as part of assisted digital
- Also aiming to test it with friends & family in person on mobile devices 

## Testing

Call centre staff were very positive about seeing all available slots on one page. They currently have to check multiple screens and felt the proposed design would make the task quicker and easier.

They told us that it’s important to know how many spaces remain for each time slot to give them confidence that they’re not overbooking - even if the new system is designed to avoid this.

Staff liked the idea of filtering to help find suitable slots, so this is a feature we’ll explore further in new designs and test again.
