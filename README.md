# AetherWatch AI — Design Time, Health & Wellness Your Way

**Category:** AI + Wearables + HealthTech + Personalisation
**Author:** Gundluru Rajasekhar
**Challenge:** Titan Watch Face Design Challenge 2026 (Open Innovation)
**Pitch:** AetherWatch AI is an intelligent smartwatch experience that combines AI, machine learning, dynamic personalisation, contextual greetings, health monitoring, weather awareness, a diet coach, a voice assistant, medication reminders, sleep intelligence, health predictions, family mode and battery-efficient ambient displays in one luxurious, adaptive watch face.

## 1. Project overview
**Problem:** watch faces are static and generic. They look the same at 7 am and 11 pm, ignore the weather, and leave health data and diet guidance in other apps.
**Solution:** AetherWatch AI reads the time of day, weather and body signals, then changes its colours, widgets and advice. Luxury look: black AMOLED, gold accents, glass stats pill, steps arc on the bezel.

## 2. Design philosophy
- **Glanceable:** time first, three key numbers, one idea per screen
- **Luxury restraint:** gold on black, 30° hour markers, no clutter
- **Accessible:** text 21 px or larger, icons 25 px or larger, touch targets 44 px or larger, high contrast
- **Power aware:** ambient mode is monochrome, outline-only and 1 fps

## 3. User journey
1. Morning: "Good Morning", warm gold theme, health widgets (heart rate, steps, battery)
2. Afternoon: "Good Afternoon", cyan theme, productivity widgets (meeting, tasks)
3. Evening: "Good Evening", ember theme, fitness widgets (steps, calories)
4. Night: "Good Night", dim theme with moon, sleep preparation
5. Any time: swipe to Health hub, AI insights, Diet Coach, Water tracker or SOS

## 4. Contextual greetings
| Time | Greeting |
|---|---|
| 5:00 AM – 11:59 AM | Good Morning |
| 12:00 PM – 4:59 PM | Good Afternoon |
| 5:00 PM – 8:59 PM | Good Evening |
| 9:00 PM – 4:59 AM | Good Night |
The greeting sits directly under the digital clock and follows the system time.

## 5. Narrated Start Tour (with sound)
START TOUR plays 15 steps automatically. Each step shows its screen, plays a soft chime and speaks a short narration with the browser's built-in speech synthesis. The tour moves on when the narration ends (minimum 3.5 seconds per step). STOP TOUR silences it at once; the **Sound** button mutes chimes and voice.
1. Welcome to AetherWatch AI
2. Premium Watch Interface
3. Personalised AI Dashboard
4. Health Monitoring Widgets
5. Activity Tracking
6. Weather Intelligence
7. Battery AI Optimisation
8. Ambient Mode
9. Theme Personalisation
10. Sleep Intelligence
11. Medication Reminders
12. Voice AI Assistant
13. AI Health Predictions
14. Family Health Mode
15. Future AI Experience
Sound starts only after you press a button, which browsers require. Voices depend on the device; if none exists the tour still runs on timers.

## 6. Screens (24)
| # | Screen | # | Screen |
|---|---|---|---|
| 1 | Welcome | 13 | Nutrition dashboard |
| 2 | Main watch face | 14 | Water tracker |
| 3 | Health hub | 15 | Diabetes (sugar) care |
| 4 | Activity rings | 16 | Blood pressure care |
| 5 | AI insights | 17 | Weekly nutrition report |
| 6 | Weather intelligence | 18 | Sleep intelligence |
| 7 | Battery AI | 19 | Medication reminders |
| 8 | Personalise | 20 | Weekly health report |
| 9 | Theme gallery | 21 | AI health predictions |
| 10 | SOS and emergency contact | 22 | Family health mode |
| 11 | Ambient | 23 | Voice AI assistant |
| 12 | AI Diet Coach | 24 | Design system |
The pages run in this order in the prototype. Ambient is also reachable with the Ambient mode button.

## 7. AI features
- **AI personalisation:** theme, widgets and greeting follow time of day, weather and activity
- **Health hub:** heart rate, steps, sleep score, activity score, hydration, stress, wellness index
- **Health score engine:** activity 25%, sleep 25%, hydration 20%, heart rate 15%, consistency 15%
- **Recommendation example:** "Excellent activity level today. Complete 1,500 additional steps to reach your daily goal."
- **Weather intelligence:** sunny, cloudy, rainy, storm, cold; the face recolours automatically
- **Ambient mode:** monochrome, low refresh, simple outline clock, auto dim, essential indicators, battery tips

## 8. AI Diet Coach
**Blood pressure mode:** morning oats porridge, low-fat milk, banana, almonds; lunch brown rice, dal, spinach curry, cucumber salad; snack green tea, roasted chickpeas; dinner chapati, mixed vegetables, grilled paneer or fish. Avoid excess salt, processed foods, instant noodles, fried foods, soft drinks.
**Diabetes (sugar) mode:** morning vegetable omelette, oats, unsweetened tea; lunch whole wheat roti, dal, mixed vegetables, salad; snack sprouts, nuts; dinner millets, vegetable curry, soup. Avoid white sugar, sweets, cakes, white bread, sugary drinks.
**Widget:** condition, breakfast/lunch/dinner ticks (tap to toggle), water goal 2.5 L, health score, one-line suggestion.
*Wellness and diet content is general lifestyle guidance, not medical advice.*

## 9. Extended wellness features
**Voice AI assistant.** Tap the mic (or the Voice assistant button) and ask. Examples: "What is my health score?", "Show today's diet plan", "Next medicine?", "How did I sleep?", "How much water today?", "Check on my family", "Weather", "Emergency". The answer appears on the watch and is spoken when Sound is on; some answers open the matching screen. Speech recognition needs Chrome or Edge and microphone permission; without it, four quick-question chips run the same answers.
**Medication reminders.** Morning (8:00 AM), afternoon (2:00 PM) and night (9:00 PM) doses. Tap a dose to tick it; the screen shows the next dose. It uses generic dose labels and tells the user to follow their doctor's plan.
**Emergency SOS.** One tap starts a 5 second countdown with a Cancel button, then "Contact notified. Location shared." The emergency contact is shown as the Family contact. The Voice assistant can start it too.
**Weekly health report.** Seven-day health score bars with highlights: score trend, best sleep night, step-goal days.
**AI health predictions.** Trend-based risk alerts (stress, sleep, blood pressure, glucose) shown as Low, Medium or High with a short action. Early alerts only, not a diagnosis.
**Family health mode.** Check on parents or family members: heart rate, steps and medicine status, with an alert when someone needs attention. Sample members only; real use needs consent from each person.
**Sleep intelligence.** Recovery score plus deep, light and REM sleep in a stacked bar (sample: 1h 45m deep, 4h 50m light, 55m REM).

## 10. Machine learning engine (concept)
| Capability | What it does |
|---|---|
| Usage pattern learning | Learns when you check which screen |
| Personalisation prediction | Picks theme and widgets before you ask |
| Smart widget prioritisation | Puts the most useful widget first for the time of day |
| Wellness trend analysis | Tracks sleep, activity and stress trends |
| Battery optimisation prediction | Predicts drain and starts saver mode early |
| Context awareness | Combines time, weather and activity |
| User behaviour adaptation | Learns diet adherence, water habits and exercise completion |
Example insight: "You usually miss breakfast on weekdays. Consider a high-protein breakfast before 9 AM."
**Honest scope:** the prototype simulates these behaviours with rules and sample data. Real on-device models would replace the rules in production.

## 11. Figma design system
**Typography guide**
| Role | Font | Weight | Size on 466 px canvas |
|---|---|---|---|
| Time | Jost (or Bodoni Moda, JetBrains Mono) | 700 | 104 px |
| Greeting, date | Jost | 500–600 | 26–27 px |
| Data values | Jost | 700 | 22–24 px |
| Labels | Jost | 400–500 | 21 px minimum |
| Screen titles | Jost | 600, letter-spaced | 22 px |
**Colour system**
| Token | Hex | Use |
|---|---|---|
| Obsidian | #000000 | AMOLED background |
| Graphite | #14171B | Panels |
| Ink | #F5F1E8 | Main text (about 18:1 on black) |
| Mute | #8E98A8 | Secondary text (about 7:1) |
| Gold | #D9B46A | Morning, default accent (over 10:1) |
| Cyan | #4CC9E8 | Afternoon, water |
| Ember | #FF8A65 | Evening |
| Night blue | #8DA2C8 | Night |
| Alert red | #E8454F | SOS, High risk |
| OK green | #6FD0A0 | Low risk, battery |
**Component library:** time block, greeting, steps arc, glass stats pill, metric tile, activity rings, bar chart, stacked sleep bar, list row, chip, theme button, dose button, family row, SOS button, mic button, page dots, toast.
**Accessibility rules:** text 21 px or larger; icons 25 px or larger; touch targets 44 px or larger; contrast 4.5:1 or better; colour never the only signal (risk shows a word too); reduced motion respected; spoken output always has on-screen text.

## 12. Feasibility
- **Wear OS:** maps to Watch Face Format layers (time, complications, ambient layer); health values from Health Services
- **Battery:** black AMOLED, outline ambient layer, 1 fps, sensors slow below 25%
- **Privacy:** insights can run on the watch or phone with no cloud account

## 13. Roadmap
Glucose and BP sensor integration, weekly reports by email, medication reminders, meeting and task sync, voice assistant, cross-device sync with phone and car.

## 14. Files
| File | Purpose |
|---|---|
| index.html | Smartwatch UI, widgets, tour, navigation, AI cards (HTML, CSS, JavaScript) |
| README.md | This document |
| requirements.md | Functional, non-functional, accessibility, responsive and battery requirements |
| tasks.md | Checklists, milestones, testing, UX validation, submission |

## 15. Run it
Open `index.html` in a modern browser (Chrome or Edge recommended for voice). Press **START TOUR**. The preview date is fixed at 11/11/2026; the clock and greeting are live.
