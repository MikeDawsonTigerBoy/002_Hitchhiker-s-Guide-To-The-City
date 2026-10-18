# 002 Hitchhiker's Guide to the City

A travel app that gives you personalised recommendations along your route.

> **Draft for review.** Built from Mike's one-line brief and the related deTour work (003). Lines tagged *(proposed)* are Claude's suggestions. **Mike to fill in** the details of the hackathon build. Section 10 lists the questions to settle first.

## Status

- **Focus: active.** This is one of three featured prototypes, alongside 001 and 004.
- Started at the September 2026 hackathon.
- **Code: none in this repo yet.**

## 1. Problem statement

*(proposed)* Navigation and travel apps treat every traveller the same: fastest route, most popular places. They don't know what you care about, so the best stops for you, the ones that match your interests, are invisible along the way.

## 2. Target audience

*(proposed)* Leisure travellers on a route, such as road-trippers, visitors exploring a city on foot or by car, and weekend drivers, who have time to stop and want suggestions that suit them.

## 3. Value proposition

*(proposed)* A guide that knows you, suggesting the right stops along the way you're already going.

## 4. Core functionality

*(proposed)*
- Set a route, or a start and end point.
- A short taste profile covering interests, budget, pace and who you're with.
- Personalised recommendations along the route, each showing how much time it adds.
- Save or skip each one, and the suggestions learn from what you choose.

## 5. Key user journeys

*(proposed)*
1. A traveller sets up a profile in 30 seconds (coffee, architecture, under an hour of extra time).
2. They enter a destination and get three stops along the way that suit them.
3. They pick one and save it to the trip.

## 6. Non-goals

*(proposed)*
- Not a turn-by-turn navigation engine.
- Not a booking platform.
- No social feed.

## 7. Feasibility

*(proposed)*
- Map and routing APIs cost money at scale.
- Personalisation can start simple, with a profile and AI ranking, before any machine learning.
- Content quality decides whether people trust the app.

## 8. Assumptions and risks

*(proposed)*
- Travellers will spend a minute on a profile.
- The recommendations are noticeably better than Google Maps "places along route".

## 9. Success metrics

*(proposed)*
- Acceptance rate of recommendations.
- Stops visited per trip.
- Repeat use within 30 days.

## 10. Open questions and challenges

1. **How is this different from 003 deTour?**
   - deTour is curated detours along a route that lead to hidden local gems, with cities paying to spread visitors to small businesses.
   - This is personalised recommendations along a route.
   - They are very close. One option: 002 is the traveller-facing app and deTour's business model is how it makes money. Another: merge them into one repo. Decide this before building, or you'll build the same thing twice.
2. **Mike to add:** what was built at the hackathon? Is there a demo, a deck or a link?
3. **What does "personalised" mean in practice?** Is it a profile you fill in, past behaviour, or AI reading what you type? Each one is a different build.
4. **What does the name promise?** Is there a playful, guidebook tone to lean into?

## 11. Tech approach

*(proposed)*
- Expo (React Native), the portfolio standard.
- A map and routing API.
- AI-ranked recommendations.

## 12. Roadmap

To be decided once section 10 is settled.
