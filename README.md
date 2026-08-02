<p align="center">
  <img src="sentrybot.ico" alt="SentryBot — Last War: Survival bot for Windows (auto farm, alliance help, zombie hunting)" width="130">
</p>

<h1 align="center">SentryBot — Last War: Survival Bot</h1>

<p align="center">
  <b>The auto-farm bot for Last War: Survival on Windows.</b><br>
  It farms while you sleep — and never touches your gems.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.5.4-F2811D?style=flat-square" alt="Version 1.5.4">
  <img src="https://img.shields.io/badge/platform-Windows%2010%2F11-2b2f20?style=flat-square" alt="Windows 10/11">
  <img src="https://img.shields.io/badge/duties-23%20automated-2b2f20?style=flat-square" alt="23 automated duties">
  <img src="https://img.shields.io/badge/trial-2%20days%20free-F2811D?style=flat-square" alt="2-day free trial">
  <a href="https://discord.gg/cd9zPVgJ56"><img src="https://img.shields.io/badge/Discord-join%20%26%20get%20a%20key-5865F2?style=flat-square&logo=discord&logoColor=white" alt="Join the SentryBot Discord and get a free key"></a>
</p>

<p align="center">
  <a href="https://dl.sentrybot.uk/SentryBot.zip"><b>⬇️ Download SentryBot for Windows</b></a> ·
  <a href="https://sentrybot.uk"><b>🌐 sentrybot.uk</b></a> ·
  <a href="https://discord.gg/cd9zPVgJ56"><b>💬 Discord</b></a>
</p>

---

## What is SentryBot?

SentryBot is an **automation bot for Last War: Survival** that plays the
daily grind for you — collecting resources, training troops, healing,
recruiting survivors, claiming alliance gifts, hunting zombies and
joining every rally, **24/7**. You log in to spend power, not to farm it.

It's an external **pixel bot**: it looks at the screen and moves the
mouse, exactly like a player. It finds every button by **image
recognition** — no fixed click positions, no memory reading, no game
file modification, no APK mods. And it is built around one hard rule:
**it never spends a single gem.**

## What's new in v1.5.4

- 🔬 **New duty: technology research** — collects a finished research,
  starts the one the game recommends and asks the alliance for help,
  for one research centre or two. Never Quick Research, never gems.
- 🎖️ **Your trained troops get collected** — a full barracks shows a
  different badge from an idle one, and the bot only knew the idle one,
  so it walked past your finished troops. It now empties the barracks
  and starts the next batch.
- 🏴‍☠️ **Truck raiding goes in the front door** — the fixed sidebar icon
  instead of hunting a bubble that looks exactly like the freight one
  and hides wherever your camera isn't. 12 targets weighed up and 3
  trucks looted in testing, with no camera hunting at all.
- 🔢 **Enemy power read three ways** — one uncertain digit used to throw
  away the whole reading and skip a target the bot could have beaten.
  The number now counts only when two independent readings agree.
- 🚚 **The armoured truck reward is collected** — it was hunting for a
  marker that never keeps the same shape.
- 🪟 **A window over the game no longer blinds the bot** — it reads the
  screen, so anything on top of the game was being read instead of it,
  silently. It now brings the game back to the front first.
- 🗺️ **Base ⇄ world switching waits for the camera** instead of claiming
  it had arrived the instant it clicked.

## What's new in v1.5.3

- 🏴‍☠️ **Truck raiding finally raids** — it used to give up in silence,
  looking for the station only where the camera happened to point and
  walking away while the battle screen was still being drawn.
- 🔍 **It searches your base like a person** — zooms out, moves the
  camera around, and tries both a wider and a closer view to find the
  station, the freight trucks, your finished-building parcels and the
  survivors at your gates.
- ⏳ **It waits for screens to open** instead of looking a moment too
  early and abandoning the job.
- 🪟 **An open screen gets used, not closed** — truck reward, trade
  panel, station platform or raid list: if it's already there, the bot
  finishes the job straight away.
- 👹 **Your boss gets picked up sooner** — the bot checks your "My
  Discoveries" list after **every** golden zombie it kills, not once
  per round, and rallies as soon as a boss of yours is there.
- 🚂 **Freight train trade** — loads the trucks parked by the station and
  ships them, taking the free re-roll when the cargo isn't worth sending.
  Never a paid re-roll.
- 🏴‍☠️ **Truck raiding** — goes after other players' richest loaded trucks,
  reads both army strengths first, and walks away from a fight it would
  lose.
- 🎫 **Ride the train** — boards the last carriage while the train waits
  and thanks the driver, donating only the passes you already own, never
  the ones the game offers to sell you.
- 🌟 **Golden zombies** — during the Zombie Invasion event it hunts the
  golden ones, one march at a time, waiting for each squad to land before
  sending the next. Normal zombie hunting steps aside while the event is
  running, so your stamina goes to the rewards that expire.
- 👹 **Zombie boss** — once you've found a boss, the bot organises the
  rally on it and invites your alliance.
- ⚡ **Smarter about stamina** — it now sees that stamina has run out
  before it even tries to march, tops up from the free refill and from
  your reserve packs, and goes straight back to hunting. Gems are never
  touched.
- 🔧 **Event screen fixes** — the bot no longer gives up when the event
  panel reopens on the page you left it on, and no longer abandons a
  target it would have beaten.

## Earlier, in v1.4

- 🖥️ **Any window size, any resolution** — fullscreen or windowed, big or
  small. The bot measures how the game is drawn on your screen and adapts
  by itself. Tested from 998x604 up to 4K.
- 🔍 **Windows display scaling supported** — 125%, 150%, 200%: no setup needed.
- 🤝 **Alliance help after healing** — allies can speed up your hospital again.
- 💰 **Tech donation until the bar turns grey** — it no longer stops early.
- 🛡️ **Tougher** — a failing duty can't take the whole bot down anymore.

## Features — 23 automated duties

| Duty | What it does |
|------|--------------|
| 🤝 **Alliance Help** | Answers every help request instantly — top of the board, every day |
| 🚩 **Rally Joiner** | Joins alliance rallies before the countdown ends, even at 3 AM |
| 💰 **Resource Collection** | Harvests all 7 bubble types, whatever your base layout |
| 🏗️ **Building Upgrades** | Starts the recommended upgrade whenever a builder is free, covers what's missing with your own resource crates, asks the alliance for help on long builds, and opens the parcels finished buildings leave — never gems, never a paid queue |
| 🎖️ **Troop Training** | Collects finished troops and restarts training the moment a barracks frees up, then asks the alliance for help |
| 🔬 **Technology Research** | Collects a finished research and starts the recommended one, for one research centre or two, then asks the alliance for help — never Quick Research, never gems |
| 🏥 **Hospital Healing** | Heals wounded troops automatically and requests alliance help to speed it up |
| 🧍 **Survivor Recruiting** | Spots every survivor at your gates by icon — zooms and pans the camera to find them all |
| 📬 **Mail, VIP & Free Stamina** | Claims all mail, the daily VIP pack & chest, and free stamina |
| 🧪 **Tech Donation** | Donates to every recommended alliance tech until daily attempts run out — gold only |
| 🎁 **Alliance Gifts** | Claims both tabs: "Claim All" on regular, one-by-one on premium — before they expire |
| 📡 **Radar Missions** | Clears radar targets and collects **every** reward badge, with any base skin |
| 🕵️ **Secret Missions** | Claims completed secret missions and dispatches heroes on new ones |
| 🚚 **Armored Truck** | Collects the truck's accumulated resources on schedule |
| 🧟 **Zombie Hunting** | Farms your chosen elite zombie level, managing its own stamina |
| 🚂 **Freight Train Trade** | Loads the station trucks and ships them, taking the free re-roll when the cargo is poor — never a paid one |
| 🏴‍☠️ **Truck Raiding** | Hits other players' richest loaded trucks, reading both army strengths first and walking away from a losing fight |
| 🎫 **Ride the Train** | Boards the last carriage while the train waits and thanks the driver, donating only passes you already own |
| 🌟 **Golden Zombies** | Hunts the event's golden zombies one march at a time, and lets the normal hunt stand aside while the event runs |
| 👹 **Zombie Boss** | Organises the rally on the boss you found and invites the alliance |
| ♾️ **24/7 Scheduler** | Runs it all with human-like pacing, night sleep and lunch breaks |

## Plays like a person, not a script

Bots get caught by their perfection. SentryBot was built deliberately
imperfect:

- **Curved, decelerating mouse movement** — never clicks the same pixel twice
- **Human schedule** — sleeps 7–8 h a night at a random time, takes lunch breaks
- **Human brake** — if the game shows a verification check, it stops and alerts you
- **Icon-based vision** — buttons are recognized wherever they appear, at any camera zoom, window size or screen resolution

## What it will never do

- ❌ Spend gems or real money
- ❌ Delete your mail or use speed-ups
- ❌ Change your formations, zombie level or settings
- ❌ Touch the game's files, memory, network traffic or your account data

## How to set up the Last War bot

1. **⬇️ [Download SentryBot](https://dl.sentrybot.uk/SentryBot.zip)** for Windows and unzip it
2. **💬 [Join our Discord](https://discord.gg/cd9zPVgJ56)** and grab a **free 2-day trial key**
3. Run **SentryBot.exe**, paste the key, press **Start** — that's it

## Pricing

| Plan | Price | |
|------|-------|--|
| **Recon** | Free | 2-day trial, full access, one per PC |
| **Patrol** | €14.99 / month | All duties, all updates |
| **Campaign** | €39 / 3 months | Best value — all duties, priority support |

Keys are handed out on our **[Discord](https://discord.gg/cd9zPVgJ56)**.
Payment in crypto (USDT / USDC).

## Requirements

- Windows 10 or 11
- Last War: Survival running on the same PC
- Game interface set to **Italian** *(more languages coming soon)*
- **Any window size or resolution** — windowed or fullscreen, at any
  Windows display scaling *(since v1.4)*
- Any base skin — the bot doesn't care how your base looks
- The PC should be free while it runs — it uses the real mouse

## FAQ

**Is there a bot for Last War: Survival?**
Yes — SentryBot automates the daily farming of Last War: Survival on
Windows: resources, training, healing, rallies, radar, gifts and zombie
hunting, around the clock.

**Can my account get banned for using a bot?** The risk is never zero —
automation is against the game's Terms of Service. That's why SentryBot
behaves like a human and hands control back on verification checks. The
free trial lets you judge the risk on your own account.

**Will it spend my gems?** No — not spending your resources is its
founding rule.

**Does it work while I'm AFK or asleep?** That's the whole point: it
farms 24/7 with a human-like schedule, and stops itself if the game asks
for a verification.

**Does it work at my resolution, or in fullscreen?** Yes. Since v1.4 the
bot measures how large the game is drawn on your screen and adapts to it,
so any window size, any resolution and any Windows display scaling work —
and you can resize the game while the bot is running.

**One key, how many PCs?** One key = one PC. It locks to the first
computer that activates it.

**What about game updates?** We update the bot to match — updates are
included in every active plan.

---

> ⚠️ **Disclaimer** — SentryBot is an independent, unofficial tool. It is
> not affiliated with, endorsed by, or connected to the publishers of
> *Last War: Survival*. Third-party automation violates the game's Terms
> of Service; using it is a choice you make for your own account, at your
> own risk.

<p align="center">
  <a href="https://sentrybot.uk">sentrybot.uk</a> ·
  <a href="https://discord.gg/cd9zPVgJ56">Discord</a> ·
  <a href="https://dl.sentrybot.uk/SentryBot.zip">Download</a>
</p>
