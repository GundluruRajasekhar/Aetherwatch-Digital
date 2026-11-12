# Requirements — AetherWatch AI

## Functional
1. Live digital clock with a greeting below it: Morning 5:00–11:59, Afternoon 12:00–16:59, Evening 17:00–20:59, Night 21:00–4:59.
2. Date and day (WED 11/11/2026 in the preview) and a weather widget.
3. Weather modes: sunny, cloudy, rainy, storm, cold. The face tint and icon change automatically.
4. Health hub: heart rate, steps, sleep score, activity score, hydration, stress level, wellness index.
5. Health score out of 100 from activity, sleep, hydration, heart rate and consistency, with a step-goal recommendation.
6. AI personalisation by time of day: morning health widgets, afternoon productivity, evening fitness, night sleep preparation.
7. Activity rings (steps, move, stand) and a steps arc on the bezel.
8. Battery indicator and Battery AI screen with saver mode below 25%.
9. Ambient mode: monochrome, outline clock, low refresh, essential indicators (Screen, Health Score, Status, Battery AI).
10. Customisation: three fonts, two layouts, five themes, Auto AI colour.
11. SOS: one tap, 5 second countdown, cancel, contact notified.
12. AI Diet Coach for sugar and BP: meal plans (morning, lunch, snack, dinner), avoid list, AI recommendation, meal ticks, 2.5 L water goal, water tracker, weekly nutrition report.
13. Start Tour: 15 steps, automatic advance, spoken narration and chimes; Stop Tour ends it immediately; Sound on/off.
14. Navigation: swipe, arrow buttons, keyboard arrows; 24 screens with a sliding page-dot indicator.
15. Voice AI assistant: mic button using speech recognition where supported; quick-question chips as fallback; answers shown on screen and spoken when Sound is on. Intents: health score, diet plan, medicine, sleep, water, family, weather, emergency.
16. Medication reminders: morning, afternoon and night doses; tap to tick; next dose shown; doctor-plan note.
17. Emergency SOS: one tap, 5 second countdown, Cancel, "Contact notified. Location shared."; reachable by voice.
18. Weekly health report: 7-day score bars and highlights.
19. AI health predictions: stress, sleep, BP and glucose trend alerts shown as Low, Medium or High with an action; labelled not a diagnosis.
20. Family health mode: three sample members with heart rate, steps, medicine status and attention alert.
21. Sleep intelligence: recovery score, deep, light and REM breakdown.
22. Design system screen and a documented Figma design system (typography, colour, components, accessibility).

## Non-functional
- Single `index.html` (HTML, CSS, JavaScript); no build step; no external data
- Updates under 100 ms; clock accurate to the second
- Works offline apart from Google Fonts (system fallbacks provided)
- Chrome, Edge, Safari and Firefox current versions

## Accessibility
- Text 21 px or larger on the watch, icons 25 px or larger
- Touch targets 44 px or larger
- High contrast (light text on black); colour is never the only signal
- Visible keyboard focus; `prefers-reduced-motion` respected
- Narration has a captioned text equivalent; Sound can be turned off
- Wellness text states it is not medical advice
- Risk levels use a word as well as colour
- Family mode uses sample data; real use needs each person's consent

## Responsive design
- 466 × 466 round canvas scaled to 92% of viewport width on small screens
- Control panel stacks below the watch under 900 px
- No horizontal scrolling

## Battery optimisation
- Pure black background in ambient mode (AMOLED pixels off)
- Outline digits, hour markers only, no colour, 1 fps
- Sensors and brightness reduced below 25% battery
- Battery AI predicts remaining hours and recommends actions

## Sound
- Audio starts only after a user click (browser autoplay rule)
- Web Speech API for narration; Web Audio API for chimes
- Fallback to timed steps when no voice is available

## Voice
- Speech recognition uses the Web Speech API (Chrome, Edge); microphone permission is required
- No audio is stored or sent by the prototype
- Fallback chips give the same answers without a microphone
