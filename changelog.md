# Food Grade — Changelog

## v6.2
- Removed legend from header (kept in welcome screen)
- ADD TO SHOP button now has visible border and toggles state immediately on tap
- ADD TO SHOP button no longer stretches full width — hugs text tightly
- Shopping list rows are now fully tappable to toggle checkbox (not just the small box)
- Calorie flags now fire on all modes (CUT/MAINTAIN/BULK) with appropriate thresholds
- Welcome screen slide 4 updated — shopping list instruction corrected, Build a Plate explained, meal score logic explained
- Returning users will see updated welcome slides automatically

## v6.1
- Build a Plate feature — add foods with S/M/L portions, get calorie-weighted meal score
- Calorie-weighted SAT/PRO/MIC scoring — larger portions carry proportional weight
- Meal score displayed prominently with color coding (green/yellow/red)
- Tier-aware plate flags — Avoid foods named explicitly, Moderation-heavy plates flagged
- Cart button removed from food rows — moved inside expanded card
- ADD TO SHOP and ADD TO PLATE buttons inside expanded card
- ADD TO PLATE no longer auto-opens panel — adds silently with badge count
- Panel title updates correctly when switching between SHOP and BUILD A PLATE tabs
- CLEAR PLATE button fixed
- FAB always visible showing both SHOP and PLATE badge counts independently

## v5.2
- Build a Plate panel tab added alongside SHOP
- FAB updated to show 🛒 SHOP · 🍽 PLATE
- Plate search, S/M/L portion selector, calorie range display
- Plate persistence via localStorage
- ADD TO PLATE button in expanded food cards

## v5.1
- Full macro data added to all 72 foods (carbs, fat, fiber, sugar per 100g)
- + MORE DETAIL button in expanded card — shows full macros and WHY tier explanation
- Welcome screen updated to 4 slides including mode system explanation
- iOS overlay bug fixed — welcome screen no longer blocks taps on load
- Welcome screen shows on first visit only, accessible anytime via ? button

## v5.0
- Cut / Maintain / Bulk mode system
- Mode-aware scoring weights (SAT/PRO/MIC shift per mode)
- Tier overrides per mode — 24 foods change tier based on goal
- Mode tag on food rows showing ▲/▼ when tier changes
- Mode bar below header with color-coded buttons
- Tier chip counts rebuild automatically on mode switch

## v4.4
- 3-slide welcome screen accessible via ? button
- Tiers explained first, then score, then what this is
- Bold claims toned down (liver, tomatoes, potatoes)
- Search expanded to cover name, category, notes, and micros
- localStorage persistence for shopping list and checked items

## v4.3
- Full rewrite of event handling — iOS-safe event delegation throughout
- Single delegated listener on stable parent containers
- All inline onclick attributes removed
- Keyboard now opens correctly on search input tap
- touch-action: manipulation on all interactive elements

## v4.2 / v4.0
- iOS touch fix — touch-action: manipulation added
- dvh units replacing vh for Safari address bar compatibility
- GPU layer on sticky header (-webkit-transform: translate3d)
- Cart button hit area expanded
- onclick="" on delegated containers for Safari event bubbling
