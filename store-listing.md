# Store listing copy — Indian Guy: Rich Simulator

Everything below is ready to paste into the Indus / PhonePe App Store developer console, field by field.
Package name in every field: `com.dudumonulife.app`

---

## App name (max ~30 chars on most stores)

```
Indian Guy: Rich Simulator
```

Alternates if the name is taken:
```
Indian Guy - Rich Simulator
Indian Guy: Life & Rich Sim
```

## Short description (max 80 chars)

```
Grow up as Dudu or Monu. Jobs, cars, homes, reels, manhwa — one Indian life.
```

Tight variant (60 chars):
```
One Indian life to build: jobs, vehicles, homes, reels, manhwa.
```

## Full description

```
Indian Guy: Rich Simulator is a Hindi-English life simulator where you raise one character from a
small beginning to a life you actually built — and you decide the order you do it in.

CHOOSE YOUR GUY
Play as Dudu or Monu. One choice, one life. Close the app and it opens straight back into the same
life, exactly where you left it — no re-choosing every launch.

LIFE AND MAZA, NOT HP
Every month of your life moves two meters: LIFE (how well you are doing) and MAZA (how much you are
enjoying it). Grind income and ignore Maza and your guy burns out. Chase fun and ignore money and
the bills catch up. Balance is the game.

WORK YOUR WAY UP
Start at street jobs — car wash, chai, small shifts — and climb into offices, businesses and the
big roles. Each job pays differently and demands differently, and partial effort gives partial pay.

ROAD, SEA AND AIR
Buy the vehicle you actually want and it shows up in your world, not in a menu. Two-wheelers, cars,
and the sky-and-water toys for when you have made it.

PROPERTY THAT EXISTS IN THE SCENE
Homes you buy are physically there. Partners you get are there with you. Nothing is a toggle icon.

MANHWA, REELS AND THE FAME LOOP
Your guy gets screen time: manhwa episodes, reels and sponsor slots. Fame pulls events, and events
pull money and trouble in equal measure.

SAVE BUBU
Bubu is the one person who calls at 2 a.m. When she is in danger, the timer is real and your next
move matters. Losing her is not a death screen — it is a consequence.

NO DEATH SCREEN, JUST CONSEQUENCES
Fail and your life does not restart to zero. Your meters drop, doors close for a while, and you get
to work back up from where you fell.

PLAY OFFLINE
The city runs without internet. Come back after a few hours and your properties pay out what they
earned while you were away.

ADVERTISING, AND WHY IT IS HERE
The game is free and made by one person with no budget. Ads are opt-in: every reward button says AD,
you only see one by tapping it, and full-screen ads appear at natural breaks — never during a video,
never during the Bubu rescue timer, never in your first minute. No purchase, no account, no login,
and your save never leaves your phone.

Your progress is stored on your own device. One-time character choice is remembered, so you do not
have to pick again each time you open the app.
```

## Category / tags

- Primary category: **Games → Simulation**
- Secondary: **Casual**
- Tags/keywords if the form allows: `life simulator`, `indian game`, `rich simulator`, `tycoon`,
  `hindi game`, `offline game`, `manhwa`, `open world life`

## Content-rating answers (expect a questionnaire)

Truthful for this build:
- Violence: mild / cartoonish only (no gore, no blood shown).
- Sexual content: none.
- Strong language: occasional mild Hindi/English slang in dialogue.
- Gambling / simulated real-money gambling: none. (Money in this game is earned by jobs and property, never by wagering.)
- Controlled substances: references to chai/smoke as lifestyle flavour text only; no use depicted.
- In-app purchases: **none**. Advertising: **yes, third-party ads (Unity LevelPlay / Unity Ads).**
- Target age: **not directed at children**; suitable for teens and adults.

## Asset requirements (as stated by the store at submission time)

| Asset | Spec you should aim for | Status |
|---|---|---|
| Launcher / store icon | 512×512 PNG, 32-bit, ≤1024 KB, transparency allowed | Ready: `assets/app_icon.png` (512×512, 323 KB) |
| Screenshots | 4–8, portrait 9:16 (1080×1920 ideal), from the real app | Ready: `screenshots/01…07` — all exactly 1080×1920 PNG, captured from the shipped build |
| Feature graphic | 1024×500 PNG, no alpha | Ready: `assets/feature_graphic.png` (1024×500, 140 KB) |
| Privacy policy URL | public, permanent | Ready: `https://rafikulislammollaq-dev.github.io/dudumonulife-site/privacy-policy.html` |
| Support email | must be real and monitored | Ready: `personalcomputerofrajib@gmail.com` |
| Data-safety form | list ad SDK collection | See "Data safety" below |

Screenshots, in the order to upload them (each one sells a different promise):

1. `01_choose_dudu_or_monu.png` — the two playable heroes.
2. `02_hustle_from_gully.png` — the core loop, HUD, tabs, the rewarded "AD · FREE PASA" pill.
3. `03_50_vehicles.png` — Activa to Maruti Swift, 50 vehicles with real art each.
4. `04_story_episodes.png` — the manhwa-style story panels.
5. `05_save_bubu.png` — the Save Bubu rescue mission with its danger timer.
6. `06_life_and_maza.png` — Jeena: party, beach, Holi, Diwali, cricket.
7. `07_gf_said_yes.png` — the girlfriend reveal moment.

## Data-safety / data-collection declaration

Collect the truth: the game itself collects nothing. Declare the ad SDK only:

- Collected: device/advertising identifier (GAID), IP address, device model + OS + screen + language +
  carrier + network type, app package/version, ad interaction events (impression, click, completion,
  reward), crash/diagnostic logs.
- Purpose: advertising / ad fraud prevention / stability.
- Not collected: name, email, phone, contacts, camera, microphone, location (GPS), photos, files,
  calendar, call log, messages.
- No account system, no in-app purchases, no player-to-player communication.

## Release notes for version 1.0

```
First public build.

- The game now opens straight back into your life instead of asking you to choose a character again.
- NEW: Settings → MAIN MENU returns you to the character screen without touching your save.
- Rewarded ads are opt-in and every reward button is labelled.
- Offline earnings, jobs, vehicles, homes, reels, manhwa episodes and the Bubu rescue arc are all live.
```

## Field to paste once GitHub Pages is on

```
Privacy policy: https://<your-github-username>.github.io/dudumonulife-site/privacy-policy.html
```
