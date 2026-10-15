# Reinventing the "Steal an X" Formula — Deep Research Report (v1)

**Date:** 2026-10-15 · **Scope:** Roblox "Steal a Brainrot / Steal an Egg"–style games and adjacent collection loops · **Status:** v1. The market research is complete for this pass. The dedicated competition sweep for each final concept is **pending** (see [Research limitations](#research-limitations--what-is-still-pending)).

> **How to read the evidence labels**
> - **[V]** verified: two or more independent sources agree.
> - **[S]** single source.
> - **[I]** my inference or analysis.
> - **[BG]** my background knowledge, not re-checked in this session.
>
> Player counts come from third-party trackers (RoWatcher, Rolimons, RoVitals, RoMonitor, rblxstat, Endgametools, profitable.app). Those trackers often **disagree**; where they do, I give both values.

---

## Executive summary

1. **Your core belief is correct, and the market has just proven it at the largest scale.** The #1 Roblox game from late August to mid-October 2026, **Steal an Egg**, is not a re-skin of Steal a Brainrot. It changed *how* you get collectibles:
   - In Steal a Brainrot you **buy** brainrots from a conveyor and **raid** other players' bases.
   - In Steal an Egg you **raid NPC nests**, and a **guardian chases you** home.
   - A **trainable speed stat** decides which biome, and so which rarity tier, you can survive.

   Steal an Egg holds roughly **1–1.6M concurrent users (CCU) on normal days**, and trackers show **12–14M on event Saturdays** [V for the baseline; the event peaks are from trackers only]. Before it, **Escape Tsunami for Brainrots** turned getting brainrots into a timed run out and back, and briefly passed Steal a Brainrot as #1 in January 2026 [S].
2. **The re-skins are dead on arrival.** Dozens of "Steal a [new noun]" games and second-wave copies of a proven verb peak in the **hundreds to low thousands** of players:
   - Steal a Fish Egg peaked at 378.
   - Tsunami clones peaked at 7 and 23.
   - A developer's "Steal An Ore" "miserably failed".

   Developers say on the Roblox DevForum that players are "tired of seeing 'steal a'" [V].
3. **The crowded axis is "*where* you go"**: depth, distance and biomes, through dive, dig, swim, tsunami and swing games. **The open axis is "*how the thing behaves while you take it and bring it home*"**. Across ~37 searches covering the main acquisition verbs, I found no hit where rarity changes how the collectible itself moves, resists, hides or travels. Rarity only ever changes the guardian, the depth or the container's toughness [I, medium confidence].
4. **The platform rules changed in 2026, and that should drive the choice of concept.**
   - From mid-June 2026 (after tests that began in April), Roblox moved its recommendation algorithm from a 7-day to a **28-day retention** view.
   - It now weights play-through rate, **first-play bounce rate** (players who leave within 60 seconds or within 61–180 seconds), play days and playtime per user, and counts co-play days with friends.
   - In its Q2 letter, Roblox said engagement shifted *away from "high monetizing, 2025-vintage viral games"* [V].
   - New **Roblox Kids** and **Roblox Select** catalogs, and a ban on reward-driven media feeds (triggered by Steal an Egg's "Reels" treadmill), raise the cost of manipulative design [V].

   A new game needs a fun first minute and a reason to come back for weeks, not just a spike from an "admin abuse" event.
5. **My recommendation (provisional until the competition sweep runs) is PARADE THIEVES.**
   - Every creature you catch **follows you home in a conga line**.
   - Your line is at once your **loot**, your **lasso** (you circle fleeing rares with it to catch them) and your **weak point**: anyone who runs through it **steals everything behind the cut**.
   - A "Robin Hood" rule lets players cut only lines *longer* than their own. This turns theft into a catch-up mechanic and stops bigger players from bullying smaller ones.
   - It is joystick-only, easy to read in a 5-second clip, and technically light.
   - Runners-up: **Hide the Goods**, a prop-hunt base where your rarest pet is disguised among decoys, and **Body Snatch**, where you *become* the creature you steal and have to get it home using its movement.

---

## Table of contents

- [Part A — Market intelligence](#part-a--market-intelligence)
- [Part B — The opportunity map](#part-b--the-opportunity-map)
- [Part C — The strongest original concepts](#part-c--the-strongest-original-concepts)
- [Part D — Ruthless ranking](#part-d--ruthless-ranking)
- [Part E — Deep dive into the top 3](#part-e--deep-dive-into-the-top-3)
- [Part F — Final recommendation](#part-f--final-recommendation)
- [Research limitations & what is still pending](#research-limitations--what-is-still-pending)
- [Sources](#sources)

---

# Part A — Market intelligence

## A.1 The genre timeline: each big jump changed the *verb*, not the noun

| When | Game | What changed | Scale (tracker figures) |
|---|---|---|---|
| May 2025 | **[Steal a Brainrot](https://en.wikipedia.org/wiki/Steal_a_Brainrot)** (SpyderSammy / DoBig Studios, a.k.a. Spyder Games) | Buy brainrots off a conveyor; they earn cash every second; raid other players' bases and carry stolen brainrots home slowly while exposed | **25.4M** CCU on 7 Oct 2025 ([PocketGamer.biz](https://www.pocketgamer.biz/robloxs-steal-a-brainrot-becomes-first-game-to-surpass-25m-concurrent-players)) and **25,836,222** on 11 Oct 2025 during the "Yin Yang" event ([Rolimons](https://www.rolimons.com/game/109983668079237), [RoWatcher](https://rowatcher.com/news/is-the-brainrot-trend-dying-what-ccu-data-from-three-top-games-reveals)) [V, ~25.4–25.8M] |
| Mid 2025 | **[Grow a Garden](https://en.wikipedia.org/wiki/Grow_a_Garden)** | Crops grow in real time, including offline; weather mutations; stealing crops from other plots | ~21–21.6M on 21 Jun 2025 [V]; **22.3M** on 23 Aug 2025 during the "admin war" with Steal a Brainrot, when the platform hit ~47.3M ([Lenovo](https://gaming.lenovo.com/roblox/post/roblox-just-shattered-the-all-time-record-for-concurrent-players-8s7u0nswtSVrLpi), [Tubefilter](https://www.tubefilter.com/?p=188004)) [V] |
| Late 2025 – Jan 2026 | **[Escape Tsunami for Brainrots](https://rowatcher.com/games/9363735110/escape-tsunami-for-brainrots)** | Collecting becomes a **run out and back under a timed threat**: sprint out, grab, get back before the wave | Briefly **#1 on Roblox in Jan 2026**, ahead of Steal a Brainrot [S, RoWatcher]. ~5M peak per a RoWatcher profile [S]. ~164K later in 2026 [S] |
| Feb 2026 | **[Swing Obby for Brainrots](https://rowatcher.com/games/9753814298/swing-obby-for-brainrots)** | Collecting becomes **rope-swing traversal**; missing a swing loses the run's haul | 87K peak, ~57K around week 5 [S]. Later snapshots: 24.7K, then 807 [S] |
| Apr–May 2026 | **[Kick a Lucky Block](https://rowatcher.com/games/10004244222/kick-a-lucky-block)** | **Kick** a lucky block (distance comes from trained "legs"), roll a brainrot, survive the tsunami the kick sets off | **~1.7M** peak in May 2026 [S, RoWatcher] |
| Jul–Oct 2026 | **[Steal an Egg](https://www.rolimons.com/game/107778070777162)** (group "and Collect Rare Pets"; promoted by Misfits Gaming) | **Raid guarded NPC nests**; the guardian chases you home; a **speed stat trained on a treadmill** decides which biome you can survive; eggs hatch into pets that earn money; other players can tackle you on the way home | #1 on Roblox from ~21 Aug 2026 ([Misfits on X](https://x.com/MisfitsGG/status/2090785862632038706), 371K) [S]. ~1.6M and #1 on 30 Sep 2026, ~5× Brookhaven ([StudioKrew](https://studiokrew.com/blog/top-roblox-games-september-2026/), with a rblxdb cross-check) [V]. Tracker all-time highs: **14.27M** on 19 Sep 2026, the "Sammy Is Coming" crossover event ([RoVitals](https://rovitals.com/game/107778070777162)), and 14.31M ([RoMonitor](https://romonitorstats.com/experience/107778070777162/)). No press outlet confirms the eight-figure peaks, and RoWatcher lists a 2.2M all-time high. ~1M on 14 Oct 2026 [S] |

**What the timeline says [I].**
- Each step-change kept the same backbone: collection, income per second, a base, and theft or exposure on the way home.
- What each one changed was **the activity of getting the item**: buy → timed run → swing → kick → heist against a guardian.
- Steal an Egg is the clearest evidence so far. It turned buying into a **chase**, added a **visible progression stat** (speed) that opens new places, and kept theft from other players on the trip home.

**A caution about Steal an Egg's numbers.**
- Its treadmills originally ran a **"Reels" short-video feed** that rewarded watching.
- Roblox pulled the game around 24 Aug 2026 while it had more than 500K CCU. It came back within hours without the feed, at about 800K ([Kotaku](https://kotaku.com/roblox-cracks-down-on-doomscrolling-games-like-steal-an-egg-that-forces-players-to-watch-reels-while-running-on-a-treadmill-2000727952), [GamesRadar](https://www.gamesradar.com/games/simulation/roblox-takes-down-controversial-doomscrolling-game-promises-to-remove-others-that-reward-watching-a-continuous-feed-of-content-as-theyre-not-appropriate-for-younger-users/)) [V].
- It **kept growing after the feed was removed**, so the chase loop carried it, not the feed [I].
- It also had help that is not about mechanics:
  - a publisher-style portfolio (Misfits Gaming);
  - an **official crossover with Steal a Brainrot's developer** (the "Sammy Is Coming" event, 19–20 Sep 2026, [GameBoost](https://gameboost.com/blog/steal-an-egg-sammy-is-coming-event-details)), which coincides with its tracker peak;
  - weekly Saturday updates.
- Do not assume a new mechanic alone reproduces those numbers.

## A.2 The decay pattern: hype spikes, then sharp declines

- **Steal a Brainrot today (Oct 2026):**
  - Weekdays: ~85K–140K (85K on 6 Oct 2026 per [Endgametools](https://endgametools.com/en/roblox/players/steal-a-brainrot); ~140K per [rblxstat](https://rblxstat.com/games/7709344486)).
  - Event days: still **0.6–1.3M**. Rolimons showed a 24-hour peak of 625,839 around 14 Oct, and rblxstat's tracked record is 1,304,032 on Sat 3 Oct 2026.
  - That puts it about **95–99% below its October 2025 peak** [V for the order of magnitude].
- RoWatcher reads this as the brainrot genre "not dying, normalizing". It notes that **each event spike was followed by a steeper drop than the last** [S, [RoWatcher](https://rowatcher.com/news/is-the-brainrot-trend-dying-what-ccu-data-from-three-top-games-reveals)].
- **Every record CCU came from a scheduled live event, mostly on Saturdays:**
  - Admin War, 23 Aug 2025
  - Extinct, 13 Sep 2025
  - Yin Yang, 11 Oct 2025
  - the Bruno Mars concert, 17 Jan 2026 (12.86M, [Guinness](https://www.guinnessworldrecords.com/world-records/782027-largest-music-concert-in-a-videogame-by-a-single-artist))

  [V for the pairing of events and peaks.]
- **Revenue:** Bloomberg (24 Mar 2026), citing RoMonitor, estimates **>$64M** in real-money purchases since launch ([Bloomberg](https://www.bloomberg.com/news/articles/2026-03-24/roblox-s-hit-game-steal-a-brainrot-battles-its-many-imitators)) [S]. Modeled tracker figures, such as $574.6M "lifetime" on profitable.app, conflict by an order of magnitude; ignore them.
- **Grow a Garden's developer** ([GamesBeat interview](https://gamesbeat.com/janzen-madsen-interview/)) built the game around **weekly Saturday 7am PST updates with a "celebratory gift"**. By Aug 2025 he admitted weekly events had become hard to keep fresh and pivoted to "more depth" ([NME](https://www.nme.com/news/gaming-news/roblox-grow-a-garden-major-changes-coming-update-cooking-3884432)) [S].
- **[I] Takeaway:** live events produce peaks, but by the developers' own account they are a treadmill. Under the 28-day algorithm (A.6), the steady baseline matters more than the peak.

## A.3 The variant ecosystem, organized by acquisition verb

(Sources: the agent sweep of ~37 queries; full links are in [Sources](#sources).)

| Acquisition verb | Representative games | What rarity changes | Best evidence | Saturation |
|---|---|---|---|---|
| **Out-and-back under a hazard** (tsunami, parting sea, sharks, mines, rocks) | Escape Tsunami for Brainrots; [Open Sea for Brainrots](https://insider-gaming.com/roblox-open-sea-for-brainrots-codes/) (part the sea, grab, get back before it closes, ~9K); 4+ shark/sea-monster games; Bike Escape; Avoid Mines | Distance | Tsunami was #1 in Jan 2026 [S]. Clones peak at **7 and 23** [S] | **Very high.** The format is sold as ready-made templates on BuiltByBit ("Escape Rock For Brainrots", "1 Speed Brainrot Escape") [V] |
| **Raid a guarded nest; speed stat gates the tier** | Steal an Egg; [Jump To Steal An Egg](https://www.dexerto.com/roblox/jump-to-steal-an-egg-codes-3410137) (train jump height, 45K peak); RUN For Eggs; [Steal a Giant Egg](https://rowatcher.com/games/10764907628/steal-a-giant-egg) (**rarity = physical size**, ~10K peak); Steal The Lucky Eggs (~5K) | Biome / guardian | Steal an Egg is #1 [V]. Copies reach 5–45K | **Very high and rising** (Aug–Oct 2026) |
| **Break or shoot the container** | [Break and Steal an Egg](https://bloxodes.com/wiki/break-and-steal-an-egg) (pickaxe power vs egg toughness, then guards chase); [Shoot For Eggs](https://bloxodes.com/articles/shoot-for-eggs-beginner-guide) (tankier rarer eggs) | Toughness | No numbers found | Medium, emerging |
| **Swing / obby / jump** | Swing Obby for Brainrots (87K); [Swing For Eggs](https://www.aprasi.com/blogs/trending-topics/swing-for-eggs-roblox-guide-all-eggs) (~9.8K); Feed a Brainrot; Rope Bridge | Reach | 87K peak, then a steep fall [S] | Medium |
| **Dig / mine to depth** | [Dig DEEPER for Brainrots](https://rotrends.com/game/9797688646) (56.9K peak); [Dig and Hatch a Brainrot](https://progameguides.com/roblox/dig-and-hatch-a-brainrot-beginners-guide/) (dig up eggs; hit carriers with a bat to steal); Mine for Brainrot (1K); +1 Mine (404) | Depth | 57K was the best found [S] | High |
| **Dive / swim / sail to depth** | Dive For Brainrots; Diving For Brainrots; Cave Dive (3K); Deep Sea Diving (448 visits); Sail For Brainrots | Depth | No breakout | High |
| **Fishing** | Reel a Brainrot; [Fish a Brainrot](https://deltiasgaming.com/?p=331108); My Fishing Brainrots; a Steal a Brainrot fishing event. Outside the genre: Fish It! (~2.7M peak) and Fisch (reeling minigame) | Bait / cast power | No genre numbers. Fishing as a category is large and durable on Roblox [S] | Medium |
| **Lasso / catch / tame** | [Rope a Brainrot](https://tryhardguides.com/rope-a-brainrot-codes/); [Catch and Feed a Brainrot](https://www.sportskeeda.com/roblox-news/how-master-catch-feed-brainrot) (hold until a bar fills); [Catch a Brainrot](https://www.dexerto.com/roblox/robloxs-catch-a-brainrot-is-pokemon-meets-tung-tung-tung-sahur-3384317/) (Pokémon-style); Tame Faster (7K visits); Lasso dev (2 visits) | Lasso level | The failures are documented; there are no numbers for the bigger games | Medium |
| **Stealth past sleeping guardians** | [Don't Wake the Brainrots!](https://www.sportskeeda.com/roblox-news/don-t-wake-brainrots-a-beginner-s-guide) (+ a Spooky spin-off) | Tier | Getting a spin-off suggests decent traction [I] | **Low** |
| **Kick / launch for distance** | Kick a Lucky Block (~1.7M) | Distance | 1.7M [S] | Rising |

**Your three example games could not be located.** "Eggs That Run Away", "Fish an Egg" and the deep-water pool with depth sectors did not surface under several phrasings, including two extended queries. They are probably small or very new [I]. The agents' conclusion still stands: **a collectible whose own behavior scales with rarity is under-exploited** [I, medium confidence].

**The pattern behind the hits and flops [I].**
- Every hit kept the **"risky trip out, safe base home"** tension.
- The **first game** to pair a fresh verb with that tension took most of the audience: Tsunami, Swing Obby, Steal an Egg, Kick a Lucky Block.
- Second-wave copies of the same verb mostly stay in the hundreds to low thousands.
- **Implication:** being first with a *new verb* is worth more than polishing an existing one, and the verb should have enough skill depth to survive the clones that will follow within weeks.

## A.4 Why the formula works: the three loops and the psychology underneath

I separate the formula into three loops, because the hits differ in which loop they innovate.

### 1. The acquisition loop (seconds to minutes): how an item enters your possession
- **In Steal a Brainrot this loop is shopping.** You watch a conveyor and buy. Its emotional engine is **scarcity theater**: a rare unit walks past, you can't afford it, someone else buys it, and envy and urgency follow. Agency is low, but the moment reads instantly [I].
- **Escape Tsunami and Steal an Egg turned acquisition into a short "heist" with a story.** Each item now comes with an anecdote: "I barely made it." Effort plus narrow escapes raise how much the item feels worth. This is the effort-justification / IKEA effect at work. It also gives the 10–20 seconds of tension that becomes a clip [I].
- **A speed or strength stat makes progress *physical*.** In Steal an Egg the speed number decides *where you can go*; in Kick a Lucky Block, leg power decides *how far you kick*. Progression you can feel in the world is more motivating than a bigger number on a menu [I].

### 2. The collection and progression loop (minutes to weeks): what owning things means
- **Rarity tiers are a legible status language.** Common → Secret is understood without reading. Color, glow and sound encode value for 8-year-olds and spectators alike [I].
- **Income per second turns a collection into one comparable number,** and the base displays it publicly. Your base is a trophy shelf that other players walk past [I].
- **Offline income and real-time growth** (Grow a Garden crops, Steal a Brainrot cash) create the **check-in loop**: come back, collect, react. That matters more than ever under 28-day retention scoring (A.6) [I].
- **Multiplier layers** add surprise inside a familiar loop. Mutations (Gold/Diamond/Rainbow), event-only traits, and rebirths that wipe your cash for a permanent multiplier all do this. A DevForum reviewer of a clone wrote that the original "smartly combined stealing, brainrots, traits, mutations, rebirths, gears, effects"; copies that keep only "steal from conveyor" feel "lifeless" ([DevForum](https://devforum.roblox.com/t/test-my-steal-a-brainrot-type-game-outdated-i-made-new-forum/4013209), [DevForum](https://devforum.roblox.com/t/again-test-my-roblox-game-like-steal-a-brainrot/4216656)) [S each].

### 3. The social / steal loop: what other players can do to your stuff
- **Theft is a catch-up mechanic.** This is the most under-appreciated reason the genre retains new players. In minute two, a brand-new player can walk into a rich player's base and leave with a top-tier unit. No other Roblox genre offers a new player a path to the top of the ladder in their first session [I].
- **Loss aversion gives possessions stakes.** Because your Secret can be taken, owning it *matters*, and idle time becomes guarding time. The evidence that the felt loss is real and intense:
  - viral videos of children crying over "admin abuse" ([Fox syndication](https://www.fox26houston.com/news/what-is-brain-rot-ai-kids));
  - Japanese press reporting school conflicts that started with in-game theft ([Automaton](https://automaton-media.com/en/news/roblox-steal-a-brainrots-huge-popularity-among-japanese-kids-raises-concerns-over-school-violence-microtransactions-and-excessive-play-sessions/));
  - real-money resale of rare units on eBay [V].
- **The carry home is public theater.** In Steal a Brainrot the thief is slowed, can't use items, the owner is alerted, and one hit returns the unit ([allthings.how](https://allthings.how/?p=6441)). Those 10 seconds have a pursuer, a target, an audience and a binary outcome, which is the ideal clip structure [I].
- **Synchronized scarcity** puts everyone in one place: Steal an Egg's rare egg every ~5 minutes with a chat announcement, and timed admin events. That raises conflict density, which produces stories [S/I].

### Answers to your specific psychology questions (condensed, [I] unless cited)
- **Why rarer things feel rewarding:**
  - Variable-ratio reinforcement.
  - A legible status ladder.
  - Each step up re-frames everything below it as "beneath you", so the bar for satisfaction keeps rising and pulls the player forward.
- **Why stealing excites:**
  - Agency over another real person.
  - A forbidden-act frisson.
  - Asymmetric stakes: the thief risks little, the owner risks a lot.
  - A live audience.
- **Why people keep playing after getting valuables:** the valuable becomes something to *defend*, which flips the player from hunter to guardian, and rebirths reset them back to hunter.
- **Addictive vs boring:**
  - Addictive versions keep the **steal run** dramatic: slowed, visible, interruptible.
  - They stack 3+ multiplier systems, and they make the **first income tick land within seconds**. One clone found 47% of players quit before earning their first egg because of a bug ([DevForum](https://devforum.roblox.com/t/suggestions-on-how-to-improve-d1-retention/4369566)).
  - Boring versions make acquisition instant or passive and have nobody nearby to interact with.
- **Why players switch to a variation:**
  - The *activity* itself is novel.
  - The theme is current: brainrot in 2025, eggs and pets in 2026.
  - **YouTubers need new content.** Creator migration is a supply-side driver of player migration.
- **Anticipation:** visible rare spawns with countdowns, rumors of secret conditions, and a rare unit walking past *before* you can act.
- **Making collecting itself enjoyable:**
  - Make it a **skill** with variance: near-misses, escapes.
  - Make **rarer things behave differently**, so the 500th catch isn't the 1st catch again.
- **Skilled / clever / lucky / powerful:**
  - Speed stats feel powerful.
  - Escapes feel skilled.
  - Ambush steals feel clever.
  - Rolls and mutations feel lucky.

  The best hits deliver all four within the first 10 minutes.
- **Shareable moments:** a steal at the last second, a victim's reaction, a rare reveal, huge numbers, trolling.
- **What makes people invite friends:** co-op advantage (defend together, raid together), private servers for events, and showing off a base. The algorithm now counts **intentional co-play days** (A.6).
- **Tension without frustration:**
  - Risk should be **opt-in and bounded**.
  - Loss should be **recoverable**: drop on hit, a chase-back window.
  - Offline holdings should be **protected**.
  - Failure should be **funny** rather than punitive.
- **Meaningful after hours or days:** rebirth tiers, index completion, event-limited items, base customization, social rank, and a skill ceiling.

## A.5 Where the formula breaks: frustrations and failure modes

- **Pay-to-win and selling power.**
  - Polygon's criticism, as summarized on Wikipedia, is that "the best items are only available for cash", including **server-admin abilities**.
  - Tecnobits says these are tied to a $49.99 Robux pack ([Wikipedia](https://en.wikipedia.org/wiki/Steal_a_Brainrot), [Tecnobits](https://tecnobits.net/?p=83977)) [V].
- **Exploits and server-hopping.**
  - Script sites sell "Auto Steal, Auto lock", plus server-hop tools ([rscripts](https://rscripts.net/script/steal-a-brainrot-auto-steal-auto-lock-and-more-9cVt)).
  - Guides recommend hopping "20–50 servers per hour" to find loaded bases ([LDPlayer](https://www.ldplayer.net/blog/steal-a-brainrot-stacked-servers-guide.html)) [V].
- **Lock-timer exploits that punish slow devices.**
  - Players beat locks with the "clone method" and bodyswap tricks.
  - A 30-second anti-steal cooldown "can still work if the target is laggy enough to take over 30 seconds to load" ([fandom wiki](https://stealabrainrot.fandom.com/wiki/Methods_Of_Stealing)) [S].
  - Kids on cheap phones are the most exposed [I].
- **Griefing of absent owners.**
  - Until 31 Jan 2026, hitting a thief whose victim had left the server **deleted** the brainrot permanently.
  - The "Ay Mi Gatito" update made it drop on the ground for anyone to grab ([Roonby](https://roonby.com/2026/02/01/steal-a-brainrot-how-the-new-anti-griefing-system-works/), [TechWiser](https://techwiser.com/steal-a-brainrot-anti-griefing-system-guide/)) [V].
- **Limits on theft are becoming the norm.** Grow a Garden 2 restricts raids to **night windows** with a countdown, locks your base while you stand inside your fence, and makes thieves **drop everything when hit** ([AllThingsHow](https://allthings.how/stealing-in-grow-a-garden-2-how-night-raids-and-garden-defense-work/), [NerdsChalk](https://nerdschalk.com/grow-a-garden-2-roblox-how-to-steal-plants-strategies-for-stealing-and-defending/)) [V]. **[I] Design implication:** build fair theft in from day one: bounded loss, a recovery window, and protection while offline.
- **Clone fatigue and weak onboarding.**
  - One Steal-a-style clone reported **2.5% D1 retention** with ~5-minute sessions ([DevForum](https://devforum.roblox.com/t/how-should-i-improve-these-stats/3978686)) [S].
  - DevForum rules of thumb are **≥10–15% D1** and **≥8 minutes** of playtime [S].
- **Legal moat.**
  - Steal a Brainrot's owners have filed **at least four lawsuits** since Nov 2025, including one over 12 near-identical copies.
  - The suits rest on UI, layout and art. The brainrot characters themselves are AI-meme derivatives that the plaintiffs say are uncopyrightable ([Aftermath](https://aftermath.site/brainrot-roblox-court/), [Bloomberg](https://www.bloomberg.com/news/articles/2026-03-24/roblox-s-hit-game-steal-a-brainrot-battles-its-many-imitators)) [V].
  - **[I]** Don't copy their UI, and don't rely on brainrot IP as a moat.

## A.6 The 2026 platform shifts that change what "success" means

1. **Retention-weighted discovery.**
   - From ~15 Jun 2026, Recommended For You looks at **Day 1, Day 2–7 and Day 8–28** windows.
   - Signals: playtime, play days, qualified play sessions, **co-play days**, spend days, Robux spent.
   - Qualified play-through rate was replaced by **play-through rate** and **first-play bounce rate**, with bounce windows of <60s and 61–180s.
   - Sources: [DevForum announcement](https://devforum.roblox.com/t/recommended-for-you-algorithm-improvements-that-better-value-long-term-retention/4684575), [Roblox newsroom](https://about.roblox.com/newsroom/2026/06/optimizing-discovery-great-games-reach-millions-players-roblox), [Discovery FAQ](https://create.roblox.com/docs/discovery-faq) [V].
   - The newsroom says tests showed that over-weighting short-term engagement **favored flashy thumbnails over lasting games**.
2. **Money followed the algorithm.**
   - The Q2 2026 shareholder letter: bookings grew 8% (the low end of guidance) because of "a greater than expected shift of engagement from high monetizing, **2025-vintage viral games**, to both new and evergreen games with lower hourly monetization".
   - Q3 bookings were guided down 14–18% YoY and the full-year outlook was withdrawn ([SEC 8-K](https://www.sec.gov/Archives/edgar/data/0001315098/000162828026051059/ex991-robloxq22026earnin.htm), [Motley Fool](https://www.fool.com/investing/2026/07/31/roblox-guided-bookings-down-as-much-as-18-and-with/)) [V].
   - A lower-authority source claims Escape Tsunami–style games lost **50–90% of traffic overnight** ([creation.dev](https://www.creation.dev/learn/roblox-algorithm-update-filtering-brain-rot-games-april-2026)) [S, unverified].
3. **Roblox Kids (5–8) and Roblox Select (9–15)** accounts arrived from June 2026. They show only Minimal/Mild-rated games that pass a selection process ([BusinessWire](https://www.businesswire.com/news/home/20260413497398/en/Roblox-Introduces-New-Age-Based-Accounts-and-Expanded-Parental-Controls-for-Users-Under-16)) [V].
4. **Ban on reward-driven media feeds** in Kids and Select (late Aug 2026). The combination of a feed, autoplay or infinite scroll, and rewards for watching is barred. Rewarded video ads are exempt ([PocketGamer.biz](https://www.pocketgamer.biz/roblox-restricts-reward-driven-media-feeds-in-kids-and-select/)) [V].
5. **Age checks for chat** have been global since Jan 2026 ([Roblox](https://about.roblox.com/newsroom/2025/11/roblox-requires-age-checks-limits-minor-and-adult-chat)) [V]. **[I]** Design for play without text chat.
6. **A +42% DevEx rate on spend by age-checked US players 18+** in eligible games ([Roblox newsroom](https://about.roblox.com/newsroom/2026/04/roblox-fuels-high-fidelity-games-over-18-players-increases-qualifying-devex-rate-42)) [V]. This pulls studios toward older audiences.
7. **Server Authority with client prediction and rollback** (Jul 2026) makes responsive, cheat-resistant movement and physics far more practical than before ([Roblox newsroom](https://about.roblox.com/newsroom/2026/07/creating-responsive-cheat-resistant-games-roblox-server-authority), [docs](https://create.roblox.com/docs/projects/server-authority)) [V]. This matters directly to the concepts in Part C.
8. **Paid random items policy** (page updated 19 Aug 2026): numerical odds in percentages, restrictions for ineligible users via `PolicyService`, and trading limits ([docs](https://create.roblox.com/docs/production/monetization/paid-random-items)) [V].

**[I] What this means for you.**
- The 2025 recipe was: meme IP, a monetized idle loop and admin-abuse spikes.
- That recipe is now **penalized**.
- The winning profile for 2026 has four parts:
  1. a first minute that is fun with no tutorial;
  2. a reason to come back on day 8–28;
  3. play with friends;
  4. monetization that doesn't sell power.

## A.7 Signals from outside Roblox (what the broader market rewards in 2025–26)

- **Hide-in-plain-sight is 2026's Steam phenomenon.**
  - [Meccha Chameleon](https://store.steampowered.com/app/4704690/MECCHA_CHAMELEON/) (June 2026): hiders paint and pose to blend into the stage while seekers hunt. It passed **1M sales within days** [V].
  - Windows Central reports 15M copies in about a month and 340K CCU [S, treat with caution].
- **Physics hauling of fragile loot:** R.E.P.O. (~230K CCU at launch [S]); [Burglin' Gnomes](https://wnhub.io/news/stores-and-publishing/item-50229), a co-op gnome burglary game that was the #2 demo at a 2026 Steam fest [S].
- **Co-op climbing and traversal:** PEAK sold **5M within about a month** [V].
- **Split-information co-op:** BOMBANANA!, where each of three monkeys is missing a sense, was the #1 demo of Steam Next Fest June 2026 in most rankings [conflicting].
- **Observation / anomaly detection on Roblox:**
  - **Animal Hospital (Anomaly)** (May 2026) reached **~1.2–1.3M CCU** in July 2026 [V].
  - The loop: treat animal patients on a night shift and spot the ones that are subtly "off" ([AllThingsHow](https://allthings.how/animal-hospital-anomaly-on-roblox-how-the-night-shift-and-anomalies-work/)).
- **Evergreen social deduction:** Murder Mystery 2 hit an all-time record of **1,349,555** during its Aug 2026 summer event [S].

**[I] The common thread:** cheap, readable games where **failure is funny to watch** (physics, social deception) are winning outside Roblox. Inside Roblox, **perception and deception loops** (anomaly spotting, hide-and-seek, MM2) are surging alongside steal games.

## A.8 Interpretation: what's really going on in this niche

1. **The genre has moved from noun to verb.**
   - Noun swaps (fish egg, ore, ball, giant egg) peak in the hundreds to low thousands.
   - Verb changes (timed run, swing, kick, nest heist) produced every hit since Steal a Brainrot [V for the examples; I for the rule].
2. **The innovation has so far been about *where* and *how fast*, not *how*.**
   - Nearly every variant scales rarity by distance, depth or toughness and gates it with a stat.
   - The item itself is a passive object you pick up and walk home with.
   - The **trip home** is the most dramatic moment in the genre and is almost unexplored as gameplay. It is still "hold the item and run" [I].
3. **Theft is being domesticated.** Night windows, drop on hit, and anti-griefing changes show that the market wants theft that is **dramatic but fair** [V].
4. **The algorithm now rewards depth and return visits over spikes.** The next breakout needs a core activity that is **fun with the rewards removed**: something people do for its own sake, with collection layered on top [I].
---

# Part B — The opportunity map

## B.1 Proven mechanics (demonstrated at scale; use them as the backbone)

| Mechanic | Evidence | How to use it |
|---|---|---|
| Collectible → passive income → visible base display | Steal a Brainrot, Steal an Egg, Grow a Garden (all >10M peaks) [V] | Keep it. This is the "why": the economy every concept plugs into. |
| A risky trip out, then a safe base back home | Escape Tsunami (#1 in Jan 2026), Steal an Egg (#1 Aug–Oct 2026) [V] | Keep the tension, but **make the trip home itself the gameplay**. |
| A trained stat that opens new places (speed, jump, legs) | Steal an Egg (speed by biome), Kick a Lucky Block (~1.7M), Jump To Steal An Egg (45K) [S/V] | Use one "feel-it-in-your-body" stat that unlocks rarer zones. |
| Theft from players while they carry an item home | Steal a Brainrot, Steal an Egg, Grow a Garden 2 [V] | Keep it, but put limits on it (B.5). |
| Mutations, traits and rebirths as multiplier layers | Steal a Brainrot; the DevForum view of why the original beats its clones [S] | Ship at least 2 multiplier layers at launch. |
| Scheduled spectacle (weekly update plus an event) | All record peaks were event days [V] | Plan a weekly cadence, but don't rely on spikes (the 28-day algorithm cares about the baseline). |
| Skill-bar minigames (fishing, forging) | Fish It! (~2.7M peak), The Forge (~1.1M peak) [S] | Fine as a sub-system; not a differentiator. |

## B.2 Early signs of potential (real but not yet dominant)

| Signal | Evidence | Opportunity |
|---|---|---|
| **The collectible's own behavior** (fleeing, hiding, resisting) | The acquisition sweep found **no hit** where rarity changes how the collectible behaves. Your "eggs that run away" example exists but is apparently small [I, medium confidence] | **Biggest open axis.** Make rarity change *how* you take something, not only *where* it is. |
| **Hide-in-plain-sight / anomaly spotting** | Meccha Chameleon (Steam, 1M+ sales in days) [V]; Animal Hospital (Anomaly) ~1.3M CCU [V]; MM2 record [S] | Perception and deception verbs are hot, and nobody has fused them with a steal-and-collect economy (pending check). |
| **Stealth against guardians** | Don't Wake the Brainrots (+ spin-off) [V for the games existing] | Low saturation, but "sneak past a sleeper" is thin on its own. |
| **Physics carrying / fragile loot** | R.E.P.O., Burglin' Gnomes on Steam [S]; Grow a Garden 2's drop-on-hit [V] | Strong comedy, but Roblox physics replication and touch controls are risky. |
| **Rarity shown as physical size** | Steal a Giant Egg (~10K) [V] | A nice visual idea; on its own it is still a reskin. |
| **Limits on theft** (raid windows, base locks, drop-on-hit) | Grow a Garden 2, Steal a Brainrot's anti-griefing update [V] | Make fairness a selling point: "theft that's fun even when it happens to you." |
| **Co-op as a ranking signal** | Roblox counts "intentional co-play days" [V] | Give a mechanical advantage for playing with friends (combine, relay, carry together). |

## B.3 Untested but compelling combinations (my hypotheses; Part C develops them)

1. **The loot follows you** (snake / conga line). The thing you're carrying is a vulnerable, visible chain that rivals can cut. Built on .io-game PvP [BG: slither.io's virality].
2. **You *become* the loot** (possession). Each rarity is a different body to pilot home.
3. **The base is a hide-and-seek puzzle.** The owner disguises valuables among decoys and the thief must spot the real one. Built on prop hunt and anomaly spotting.
4. **Throwing the loot home.** Distance, aim and interceptions; passing to friends.
5. **Fragile loot.** Impacts downgrade rarity; heavy items need two people to carry.
6. **Steal by charm.** Lure rivals' pets with better care; loyalty meters; non-violent theft.
7. **Every rarity is a different hunt.** Each tier has a behavior archetype; secret catch conditions.
8. **Your collection is your character** in asymmetric hunt rounds.

## B.4 Oversaturated or weak: avoid

| Avoid | Why |
|---|---|
| **"Steal a [new noun]" reskins** | Peaks of 378, "miserably failed", "people are getting tired of seeing 'steal a'" [V]. |
| **"Escape [hazard] for [X]"** | Sold as templates; clones peak in single or double digits [V]. |
| **Dive / swim / dig "go deeper" reskins** | High saturation, no breakout found except Dig Deeper (57K) [S]. |
| **Guardian-chase plus speed treadmill** | Steal an Egg owns it; copies peak at 5–45K. Competing head-on with the #1 game is a losing bet [I]. |
| **Lasso click-mash** | Tame Faster (7K visits) and Lasso dev (2 visits) flopped [S]. |
| **Watch-to-earn / media-feed treadmills** | Banned from the Kids and Select catalogs [V]. |
| **Selling admin powers or theft immunity** | The most-cited fairness complaint, plus press backlash [V]. |
| **Gambling-adjacent acquisition** (claw machines, coin pushers, wagers on Robux-bought items) | Paid-random-item rules, odds disclosure, regional restrictions [V]; reputational risk [I]. |
| **Pure brainrot IP as the selling point** | The theme is fading (RoWatcher; its creators declared it dead in Dec 2025 [S]), it can't be copyrighted, and lawsuits fly over UI copies [V]. |

## B.5 Design principles that came out of the research (apply them to every concept)

1. **Change the verb, keep the economy.**
2. **Make rarity change behavior**, not just the number and the zone.
3. **Make the trip home the game.** It's the genre's most dramatic moment and it is underused.
4. **Fair theft:**
   - Risk is opt-in (you choose how much you carry).
   - Loss is bounded (part of your haul, not all of it).
   - Recovery is possible (a chase-back window).
   - Offline holdings are safe or only partly at risk.
5. **The first 60 seconds work with no tutorial and no text chat.**
6. **Give a mechanical bonus for playing with friends** (the co-play signal).
7. **Choose a verb with a skill ceiling,** so fast clones copy the surface but not the feel.
8. **Keep it theme-agnostic,** so the collectible can follow the trend (eggs and pets now; whatever is next later).
---

# Part C — The strongest original concepts

## C.0 How these survived

I generated a pool of about 35 mechanics. Sources:
- every acquisition verb in A.3;
- the Steam and Roblox mechanics in A.7;
- real-world activities: herding, pickpocketing, metal detecting, rodeo, claw machines, beekeeping, smuggling, auctions;
- your prompt questions, for example "what if finding is easy but bringing it home is hard?".

I put each one through your 20 questions. The ones I discarded, and why, are listed in [C.9 The graveyard](#c9-the-graveyard-ideas-i-eliminated-and-why). Eight concepts survived. They are ordered roughly by my final ranking in Part D.

**Competition status.**
- For every concept below, I state what I know from this pass. A dedicated competition sweep (searching each concept's gameplay under several descriptions) is **still pending** because the search cap ran out.
- Where I say "not found", I mean "not surfaced in the ~180 searches run so far, which were not targeted at this concept". That is not "verified absent".
- Originality is therefore marked **[UNCERTAIN]** until the sweep runs.

---

## C.1 PARADE THIEVES
*Alternative titles: "Steal a Parade", "Follow Me Pets", "Conga Thieves".*

**The hook:** Every pet you catch follows you home in a conga line, and anyone who runs through your line steals everything behind the cut.

**Core gameplay.**
- **Setup:** a round map with 12–16 players. Player bases ring the edge. Wild zones go inward in rings: Meadow → Marsh → Canyon → Volcano core, so rarity rises toward the center.
- **Catching:** baby creatures ("hatchlings") wander the zones. You run into one, it pops a little heart, and it falls into line behind you, stepping exactly in your footsteps. That's the whole control scheme: joystick and one ability button.
- **Line length:** your line grows up to your **Charisma** cap. You start at 8 and upgrade toward 100+.
- **Banking:** steer the line through your base gate. The creatures hop one by one onto pedestals and start earning $/s. Long parades bank with a **combo multiplier** (10+ = ×1.5, 25+ = ×2 …), so greed is rewarded.
- **Your line as a lasso:** if your line closes a loop around something, you capture it. That is how you catch fast, fleeing rares. Loop around a rival and they're dizzy for 2 seconds.
- **Your line as a weak spot:** if another player's body crosses your line between two followers, **everything behind the cut** spins, looks confused, and re-imprints on them.

**The collection mechanic.**
- Discover creatures by roaming the rings.
- Obtain them by touching them, or by looping around them for skittish types.
- Secure them by bringing them through your gate.
- Progression runs through pedestal income, base expansion (more pedestals), Charisma (line cap) and Stride (speed). It continues through a family-based index, mutations from events (Golden, Rainbow, Neon), and rebirths that reset your base for a permanent multiplier and a parade cosmetic.

**Rarity integration (rarity changes behavior, not just value).**

| Tier | How it behaves in the wild | Why it matters |
|---|---|---|
| Common | Joins on touch | Fills your line |
| Uncommon, "Skittish" | Flees when you get close; must be cornered or looped | Teaches the lasso |
| Rare, "Picky" | Joins only if your line already holds 2+ of its family | Creates set-building decisions |
| Epic, "Heavy" | Slows your whole line 10% but is worth ×5 | A greed decision |
| Legendary, "Status-seeker" | Joins only lines of **20+** | You must already be rich and exposed to get one |
| Mythic, "Stampede" | Runs in herds during events; you must loop several at once | Server-wide moments |
| Secret | Hidden condition (for example, a heart-shaped loop at night) | Rumors and YouTube "how to get" videos |

**Escorts: rarity also changes strategy.**
- Before heading out, you can slot up to 3 creatures from your base into your line as escorts with abilities:
  - **Turtle:** the 3 followers behind it can't be cut for 5s.
  - **Skunk:** anyone who cuts within 2 slots of it is stunned.
  - **Magnet Cat:** pulls stray hatchlings into your line.
  - **Decoy Duck:** if you're cut here, the thief only gets ducks.
- **Line order becomes a team-building puzzle.**
- Escorts can be stolen too. That gives you an extraction game's "gear fear" in a form an 8-year-old can understand.

**The stealing / social element (theft is essential, but bounded).**
- **Robin Hood rule:** you can only cut a line **longer than yours**. Theft flows from rich to poor. A newcomer can ambush a whale; a whale can't bully a newcomer.
- **Scramble window:** for 1.5s after a cut, the cut followers are "confused", and the first leader to touch them gets them. So the victim can immediately win them back, and you get frantic scrambles.
- **Hot potato:** the thief's line is now longer, so it's a target for everyone with a shorter line. Loot circulates until someone banks it.
- **Parade Night:** every ~8 minutes, for 90s, base gates open. Thieves can whistle up to 3 pedestal creatures out, and owners can cut them back inside their own base. Outside these windows, and while you're offline, pedestals are safe.
- **Link Up:** friends can attach their lines into one mega-parade. You get a combined bank multiplier, and also a bigger target. This is a mechanical reason to play with friends (the co-play signal).

**Why it's fun.**
- It's slither.io's emergent spatial play: anyone can read it in a second, and it takes real skill to master.
- Add push-your-luck greed ("one more loop through the canyon?").
- Add a constant, visible drama of steals happening *in the open field*, not only at bases.
- Being cut is less bitter than being robbed offline: you saw it coming, you chose the risk, you can scramble to win it back, and the thief is now the hunted.

**Replayability.**
- Stat ladders: Charisma, Stride, pedestals.
- An escort meta: which abilities, in what order.
- Family index completion.
- Rotating events: Stampede, Golden Hour, Parade Night.
- Rebirth titles ("Grand Marshal").
- Seasonal species.
- Skill growth: looping, cut timing, defensive weaving.

**Viral moments.**
- A 150-creature glowing parade snaking around the map.
- A newbie slicing a whale's mega-parade one step from their gate.
- A Secret caught by looping the whole map.
- A stolen tail changing owners 5 times in 20 seconds.
- Players drawing shapes and names with their parades. That's creative expression, and the Secret condition rewards it.

**Existing competition [UNCERTAIN, pending sweep].**
- Mechanical ancestors outside Roblox [BG]: slither.io (2016) and the "crowd runner" hyper-casual genre (Crowd City, Count Masters).
- On Roblox I expect snake-style or "crowd" games to exist [BG]. I found none combined with a collect-earn-steal economy in this pass.
- A RoWatcher listing for "Brainrot Army" ([link](https://rowatcher.com/games/9296995367/brainrot-army)) has an **unknown mechanic** and must be checked first.
- Pet Simulator-style pets *follow* you, but not as a cuttable, stealable chain [BG].

**Development difficulty: medium.**
- **Followers are cheap.** Each follower is a point along its leader's recorded path, so clients render followers from the leader's already-replicated movement. Only line composition and cut events cross the network.
- **Cut detection is server-side** segment-vs-polyline checks with spatial hashing at 10–20 Hz, with about 120ms of lag compensation. That is feasible.
- **Main risk: rendering** up to about 1,500 small animated creatures on low-end phones. It needs simple rigs (no Humanoids), `BulkMoveTo`, and level-of-detail and impostor tricks.
- **Anti-cheat** means server speed validation. Roblox's 2026 Server Authority with prediction helps here.

**Potential weaknesses.**
1. "It's a snake game" could read as dated if the theme and polish don't modernize it.
2. Cut-rage if Robin Hood and scramble are tuned badly.
3. Unreadable chaos in a crowded core.
4. .io games are historically shallow over the long term, so retention must come from the base, escort and collection layers.
5. Performance on low-end phones.

**Overall potential: highest of the set.**
- It's the only concept where **one rule** (the line) is acquisition, transport, theft, defense *and* spectacle at once.
- The evidence base:
  - the out-and-back tension that carried Tsunami and Steal an Egg;
  - an open "how the thing behaves" axis (A.3);
  - a mobile-first audience;
  - feasibility.
- Still uncertain: competitors, and whether it holds 30 minutes and more.

---

## C.2 HIDE THE GOODS
*Alternative titles: "Hide & Steal", "Steal the Real One", "Disguise a Pet".*

**The hook:** Your base is a hide-and-seek puzzle. Your rarest pet is disguised as a lamp, a toilet or a slice of pizza, and thieves have to guess which one.

**Core gameplay.**
- **Your base** is a themed room (bedroom, kitchen, garage, museum) where you place props.
- **Disguise forms:** each pet unlocks 2–6 forms with rarity. Rarer pets get smaller and stranger forms.
- **Setting up:** you arrange real disguised pets among plain decor and **decoys**. Some decoys are traps, such as a squeaky toy that honks.
- **Raiding:** during open windows, a thief walks in with a **Suspicion meter** of 3 strikes and taps a prop to inspect it.
  - A real pet pops out and must be carried home through the usual chase: you're slowed, can be tackled, and drop it.
  - A decoy costs a strike, honks loudly and pings the owner. Three strikes and you're ejected and marked.
- **Defending is active.** Thieves can disguise **themselves** as props inside your base to wait out your lock. Owners **sweep** by tapping props to unmask lurking players. This is prop hunt, inside a tycoon.

**The collection mechanic.**
- **Mimic Zones:** shared areas (Junkyard, Museum, Kitchen, Toy Store) where wild creatures hide as props among real props.
- Spot one, tap it, and it's yours. You still carry it home, so you can still be tackled.
- Zones reshuffle every few minutes and the whole server races to spot the new mimics.
- That is the anomaly-spotting loop that drove Animal Hospital (Anomaly) to ~1.3M (A.7).

**Rarity integration.**
- Rarer creatures:
  - have **fewer tells** (common mimics breathe visibly; legendary ones only blink when nobody's looking);
  - have **smaller forms** (a sock, a coin);
  - can **move between disguises** when unobserved.
- Gadgets let you investigate: a Sniffer pet reveals one tell, and a flashlight catches a wrong shadow at night.

**The stealing / social element (essential).**
- It's an asynchronous duel of wits: the owner designs, the thief deduces.
- **Raid logs** show "Thief X found your Mythic (disguised as: Trash Can) in 9s", or "3 thieves failed against your base today".
- Leaderboards: "Longest unfound pet" and "Master Thief".

**Why it's fun.**
- Hide-and-seek is a universal childhood game.
- Deduction feels clever.
- Reveals are funny.
- Designing a devious base is creative, and the trolling writes itself.
- It answers the genre's dead time: **defending becomes active play.**

**Replayability.**
- Every base is a new puzzle, so content is player-made and endless.
- You iterate your design after reading the raid logs.
- New prop themes each update.
- Mimic Zones rotate.
- The rank ladder for thieves and hiders.

**Viral moments.**
- "I hid my Secret pet as a toilet and nobody found it for 3 days."
- "The lamp was a player the whole time."
- A pro thief clearing a base in 10 seconds.
- An owner sweeping and unmasking 4 hidden thieves in a row.

**Existing competition [UNCERTAIN, pending sweep].**
- Roblox has long-running hide-and-seek and prop-hunt games [BG]. Meccha Chameleon (Steam, 2026) proves the appetite [V].
- "Find the Brainrot" is a find-the-X hunt with no economy [S].
- I found **no steal-tycoon with disguised bases** in this pass. This needs a dedicated check under "prop hunt tycoon", "disguise pets roblox", "hide your pets steal", "mimic".

**Development difficulty: medium.**
- Systems needed:
  - a placement and editing system (standard in tycoons);
  - prop-form swapping;
  - tells (subtle animation and shadows);
  - strike logic;
  - an event-based raid log (no video needed).
- **Mobile:** tap targets need generous hitboxes, and some tells (fine detail) won't read on small screens, so favor motion and sound tells.

**Potential weaknesses.**
1. **First-minute clarity.** You have to teach hiding *and* seeking, so there is a real risk of bounce under 60 seconds.
2. A slower pace than chase games.
3. Brute-force guessing (the strike system must be tuned).
4. Some owners won't want to arrange a base (provide "auto-hide").
5. It reads well in clips only when the reveal is staged.

**Overall potential: high, with the best retention structure of the set** (player-made puzzles, async rivalry, active defense). The biggest risk is first-session onboarding.

---

## C.3 BODY SNATCH
*Alternative titles: "Become It, Steal It", "Possess a Pet".*

**The hook:** You don't carry what you steal. You *become* it, and you have to get it home on its legs, wings or wobble.

**Core gameplay.**
- **Possessing:** tap a creature and hold for 1.5s (interruptible) to **possess** it. The camera swoops in and you *are* the creature, with its movement style.
- **Getting it home:** steer it to your base. Every few seconds the creature **resists**, and a quick tap-timing prompt keeps you in control. Rarer creatures resist harder and more often.
- **Getting knocked out:** other players can bonk you to **eject** you. The creature bolts for 3s, then anyone can possess it.
- **Banking:** reach your base and the creature settles onto a perch and earns $/s.
- **Raiding:** possess a creature *on someone else's perch* and walk it out of their base.

**Movement archetypes (about 10, reused across many species).**
- **Waddler:** slow and steady.
- **Hopper:** big arcs, precise landings.
- **Roller:** momentum; can't stop; flies downhill.
- **Glider:** must climb to launch.
- **Flier:** flaps on stamina.
- **Slitherer:** fits through pipes, which are shortcuts.
- **Burrower:** goes underground, invisible but slow.
- **Bouncer:** jelly; ricochets off walls.
- **Giant:** knocks players over; too big for narrow gates.
- **Swimmer:** fast in water, flops on land.

**The collection mechanic.**
- The map is designed for **archetype routes**: pipes for slitherers, cliffs for gliders, rivers for swimmers, slopes for rollers.
- Knowing the best route home for each body is the skill.
- Collection, index and mutations work as usual.

**Rarity integration.**
- **Rarity is the control scheme.** Commons are waddlers and hoppers. Legendaries are gliders, burrowers and rollers: faster and more extreme, but harder to control. Secrets have unique movement, for example a teleporting blink.
- Rarer creatures also resist possession more.
- This is the strongest answer in the set to "what if rarity directly changed how the gameplay works?"

**The stealing / social element (essential).**
- Bonk-to-eject on the trip home.
- Possession raids during open windows.
- **Swap steals:** possess the creature a thief is currently piloting to hijack it.
- Defensive guard creatures at your base auto-bonk intruders.

**Why it's fun.**
- The physical comedy of Goat Simulator, and the variety of Mario Odyssey's "capture" (each body is a new toy) [BG].
- The constant question "what's the best route for *this* body?"

**Replayability.**
- Every content update adds new *toys* rather than just new numbers.
- Time trials per creature: "fastest Roller home".
- Mastery of the hard archetypes.
- Collection and rebirth.

**Viral moments.**
- A giant whale flopping across dry land, chased by six kids.
- A glider sailing over the entire map into its base.
- A burrower popping up inside an enemy base.
- A hijack mid-flight.

**Existing competition [UNCERTAIN, pending sweep].**
- Morph and "Be a ___" games are common on Roblox [BG].
- Possession as the acquisition step in a steal economy did not surface in this pass.
- Check "possess", "become a brainrot", "morph steal", "control the pet".

**Development difficulty: high.**
- About 10 bespoke movement controllers, each needing great feel on touch.
- Animation for each.
- Prediction and anti-cheat for unusual locomotion (Server Authority helps).
- Level design for each archetype's routes.
- Content cost is the main threat for a small team, even with AI coding tools: *feel* tuning is human-time-heavy.

**Potential weaknesses.**
1. Production cost and quality of feel.
2. Novelty can fade once the archetypes are known.
3. Slow archetypes can make trips home tedious.
4. Balance between archetypes.

**Overall potential: highest "wow" and clip potential in the set, but the riskiest to build and to retain players.** Strong for the thumbnail, weaker over 28 days than C.1 or C.2.

---

## C.4 LONG SHOT
*Alternative titles: "Throw It Home", "Yeet a Pet".*

**The hook:** Grab it, then **throw it home**. A full-map throw into your base hoop banks it instantly, but anyone can intercept it mid-air.

**Core gameplay.**
- **Carrying:** grab a collectible in the wild or from an enemy base. Carrying slows you. At any moment you can **aim and throw**: drag back, see the arc, release.
- **Scoring:** landing in your base's goal banks it with a **distance bonus**, so longer shots pay more.
- **Missing:** the item lands loose and anyone can grab it.
- **Interception:** rivals can jump to catch it in flight.
- **Relays:** friends can catch and pass it on.
- **Throw Power** is a trained stat, the same pattern as Steal an Egg's speed and Kick a Lucky Block's legs.

**Rarity integration.** Rarer items fly differently:
- **Heavy:** short range.
- **Squirmy:** curves unpredictably.
- **Bouncy:** rebounds off the rim.
- **Floaty:** drifts with the wind.
- **Fragile:** cracks down a tier if it hits the ground.

**The stealing / social element.**
- Throw stolen items over enemy walls; defenders try to block or catch.
- Interceptions in open play.
- Co-op relays (the co-play signal).

**Why it's fun.** Throwing and catching is universal. Trick shots, near-misses and buzzer-beaters are intrinsically satisfying.

**Replayability.**
- Throw mastery.
- Map-specific trick lines.
- Collection.
- A "Highlight" leaderboard for longest banked throw.

**Viral moments.**
- A half-map buzzer-beater as the gate closes.
- An interception of a Secret by a newbie.
- A three-friend relay.

**Existing competition [UNCERTAIN].** Kick a Lucky Block (~1.7M peak, May 2026, [S]) owns "launch for distance". Throwing *as the way you bank and steal* did not surface in this pass, but this verb is adjacent to a big hit, so clones are likely.

**Development difficulty: low to medium.** Server-authoritative projectiles and catch windows. Latency fairness on catches is the hard part.

**Potential weaknesses.**
1. Close to the "launch" trend, so less differentiated.
2. Aim-assist and aimbot exploits.
3. Throwing could make the carry-home chase trivial (needs a min range and arming time).

**Overall potential: medium.** Fun and feasible, but more of a **feature** than a franchise. Its throw-and-relay idea could be bolted onto C.1 or C.2.

---

## C.5 EVERY CATCH IS DIFFERENT
*Alternative title: "Wild Tiers".*

**The hook:** Commons walk into your arms. Legendaries burrow, mimic, fly or fight back. Every rarity tier is a different hunt.

**Core gameplay.** One world where each tier has a distinct **catch verb**:
- **Common:** docile; just grab.
- **Uncommon:** skittish; crouch-sneak from behind.
- **Rare:** runner; chase and dive-tackle.
- **Epic:** burrower; find the mound, stomp to pop it out.
- **Legendary:** mimic; disguised as a rock (spot it).
- **Mythic:** flier; place bait, then time a net swing.
- **Secret:** a unique **ritual condition** that players must discover.

After the catch: carry it home, earn income, and other players can steal it on the way.

**Rarity integration:** the tier *is* the verb.

**Stealing:** classic carry-home tackles plus base raids.

**Why it's fun.** Variety, and the discovery of hidden conditions, which drives guide videos: "HOW TO GET THE SECRET ___" is a staple Roblox YouTube format [BG].

**Replayability.** New species bring new behaviors. Secrets fuel community detective work.

**Viral moments.**
- The first person to discover a Secret's ritual.
- A diving tackle on a runner just before it escapes.

**Existing competition [partially known].**
- Your "eggs that run away" example covers the fleeing tier.
- [Catch a Brainrot](https://www.dexerto.com/roblox/robloxs-catch-a-brainrot-is-pokemon-meets-tung-tung-tung-sahur-3384317/) does Pokémon-style catching.
- [Don't Wake the Brainrots](https://deltiasgaming.com/?p=333913) covers stealth.
- This concept **bundles** verbs that each exist somewhere, so its originality is moderate.

**Development difficulty: medium-high.** Many behavior AIs, each needing polish.

**Weaknesses.** Jack of all trades: each mini-verb is shallow, and there's no single signature image for a thumbnail.

**Overall potential: medium.** The *principle* (rarity changes behavior) is excellent and is already built into C.1, C.2 and C.3. As a standalone game it lacks one iconic verb.

---

## C.6 HANDLE WITH CARE

**The hook:** Every treasure is fragile. Bump it and it drops a rarity tier, so getting a Mythic home in one piece *is* the game.

**Core gameplay.**
- Loot is a physical object with **integrity**. Hard impacts downgrade it: Mythic → Legendary → … Commons are sturdy; rares are glass.
- Big rares need **two players to carry**. That is a co-op signal and a source of slapstick.
- Thieves don't need to grab: they **bump** you to break or drop the item.
- Upgrades include bubble wrap, padded carts and carry stability.

**Rarity integration:** rarer means more fragile, heavier and more awkwardly shaped.

**Stealing:** bump-to-drop; scoop up whatever falls.

**Why it's fun:** the R.E.P.O.-style physics comedy and shared tension [S on R.E.P.O.'s scale].

**Viral moments.** Breaking a Secret on the doorstep. Two friends carrying a giant egg down a staircase.

**Existing competition [UNCERTAIN].** R.E.P.O.-inspired games on Roblox are likely [BG]. Grow a Garden 2 already uses drop-on-hit [V].

**Development difficulty: high.** Roblox physics ownership and replication for carried objects, especially two-player carries, is notoriously jittery on mobile. You'd fake most of it with server-side "carry states".

**Weaknesses.** Physics jank, kids' frustration at losing tiers, touch controls.

**Overall potential: medium-low for Roblox** despite strong comedy. It's better as a **sub-system**: one fragile "Secret-class" item type in another game.

---

## C.7 CHARMED
*Alternative title: "Steal Their Heart".*

**The hook:** You can't grab other players' pets; you have to make them like you more.

**Core gameplay.**
- Pets have **Loyalty** to their owner.
- **Taming wild creatures:** each species has favorite foods, toys and music, discovered by experimenting. You set out a lure, then stay still and quiet while it approaches.
- **Stealing:** at rival bases you toss treats and toys to tempt a pet. If your lure beats its loyalty, it trots over and follows you home, and the owner can counter-lure in real time.
- **Building loyalty:** daily care (feeding, petting, playing).

**Rarity integration:** rarer pets are pickier (combined habitat requirements, as in Viva Piñata [BG]), more fickle, and need longer care streaks.

**Why it's fun:** nurturing plus a gentle rivalry. **It's the only concept whose theft is non-violent**, which suits the Kids and Select catalogs and parents.

**Replayability:** care routines are a natural D8–D28 driver (the Adopt Me pattern [BG]).

**Viral moments:** weaker. "My legendary left me for my best friend" works, but the action isn't visual.

**Existing competition [UNCERTAIN].** Adopt Me covers care. Lure-based theft did not surface.

**Development difficulty: medium.**

**Weaknesses.** Low adrenaline, slow first minute, weak clips, and "my pet left me" can feel worse than theft.

**Overall potential: medium-low as a breakout; interesting as a retention module.**

---

## C.8 HUNTED
*Alternative title: "Bring Your Best".*

**The hook:** Bring your rarest pet into the hunt. Survive and it levels up; get caught and the hunter keeps it.

**Core gameplay.**
- Rounds of 1–2 hunters against 6–8 runners. Runners **play as a creature from their own collection**, with abilities by rarity: a Legendary can teleport once, a Common is just fast.
- Runners collect shards and reach the exit. Hunters catch runners, which steals the creature (or, kinder, a "soul shard" copy).
- **Risk ladder:** bring a safe Common or a powerful Legendary.

**Rarity integration:** rarity is your character kit.

**Why it's fun.** Asymmetric chase is a proven Roblox genre: Forsaken (138K+ peak, [S]), MM2 (1.35M record, [S]) and Flee the Facility [BG]. It adds an extraction game's gear fear.

**Viral moments.** A Common outplaying a hunter. A hunter catching a Secret.

**Existing competition [UNCERTAIN].** The asymmetric genre is crowded; the collection-as-roster plus stakes combination did not surface.

**Development difficulty: high** (round systems, hunter AI or balance, ability kits).

**Weaknesses.** Losing your best pet is brutal for kids, round-based games fit poorly with idle income, and balance is hard.

**Overall potential: medium-low.** Better as a **weekly event mode** inside a winning concept.

---

## C.9 The graveyard: ideas I eliminated, and why

| Idea | Why it died |
|---|---|
| **Wobble Stack** (loot stacks on your head; balance; bump to topple) | Fun for minutes; balance feels like luck; shallow PvP. C.1 does "the more you carry, the more vulnerable you are" better. |
| **Peekaboo** (creatures move only when unobserved; turn your back to lead them home) | A clever single trick, not a 30-minute loop. **Kept as a module** (a C.2 tell; a rarity behavior in C.1 and C.5). |
| **Titan Nests** (eggs on giant walking beasts you climb) | Big spectacle, but characters standing on fast-moving models are jittery on Roblox, and climbing on touch screens is hard. Better as an event map. |
| **Split-information heist crew** (one sees, one acts) | Needs communication. Voice is age-gated and typing is slow on mobile. Too much for the core audience. |
| **Bubble Float** (trap a creature in a bubble and steer it home) | Cute, but there's not enough depth. |
| **Rodeo ride-home** | Lasso games are already crowded (Rope a Brainrot, Catch and Feed); it's a 30-second minigame. |
| **Vacuum tug-of-war** (Luigi's Mansion style) | Ghost Simulator (BIG Games, 2020) already did vacuum collecting [BG]; the tug-of-war is only a feature. |
| **Boids herding** (sheepdog) | Server AI cost, finicky for kids. **Folded into C.1** as Stampede events. |
| **Paper.io loop capture** | **Folded into C.1** (loop your line around a creature to capture it). |
| **Photo safari** (photo quality = value) | The theft loop is weak; moderating images is a burden. |
| **Echolocation darkness** | Niche. Could be a night biome. |
| **Crowd pickpocketing / blending into NPCs** | Deception is too hard for young players; mimicking NPC behavior is fragile. Partly **folded into C.2**. |
| **Auctions / haggling / bluff wagers** | Gambling optics, policy risk, low action. |
| **Claw machine / coin pusher / plinko acquisition** | Paid-random-item policy; passive. |
| **Airdrop races** | Steal an Egg already announces a rare egg every ~5 minutes [S]. |
| **Kick/launch for distance** | Proven (Kick a Lucky Block) and already being copied. |
| **New noun reskins** ("Steal a ___") | See B.4. |
---

# Part D — Ruthless ranking

**Scale:** 1–10. A 5 means "ordinary for Roblox". I avoided inflating scores, and only one concept gets an 8 overall.

**The score most likely to change: Originality.** Every Originality score is **provisional**: if a direct competitor turns up, that concept drops 2–3 points there and 1–2 points in Overall.

| Rank | Concept | Originality | Immediate fun | Retention / replay | Viral | Market opportunity | Feasibility | **Overall commercial** |
|---|---|---|---|---|---|---|---|---|
| 1 | **Parade Thieves** | 8 | 8 | 7 | 8 | 8 | 7 | **8** |
| 2 | **Hide the Goods** | 7 | 6 | 8 | 8 | 7 | 6 | **7** |
| 3 | **Body Snatch** | 9 | 8 | 5 | 9 | 6 | 4 | **6** |
| 4 | Long Shot | 6 | 7 | 5 | 8 | 5 | 8 | **5** |
| 5 | Every Catch Is Different | 5 | 7 | 6 | 7 | 6 | 5 | **5** |
| 6 | Handle With Care | 5 | 7 | 5 | 7 | 5 | 4 | **4** |
| 7 | Charmed | 7 | 4 | 7 | 4 | 5 | 7 | **4** |
| 8 | Hunted | 6 | 7 | 6 | 6 | 5 | 4 | **4** |

## How I weighted the dimensions (not equally)

Under the 2026 discovery algorithm, three dimensions decide success. That is why "Overall" is not an average.

- **Immediate fun**, because of first-play bounce.
- **Retention**, because of 28-day play days.
- **Feasibility**, because a half-polished version of a great idea loses to a polished simple one.

**Viral** matters for the initial spike. **Originality** matters only insofar as it creates the first-mover advantage described in A.3.

## Reasoning per concept, and the decisive dimension

1. **Parade Thieves (decisive: immediate fun × feasibility).**
   - It's the only concept that scores ≥7 on every dimension.
   - It is controlled with **movement only**, and its theft is **built into movement**, so it can't be skipped or ignored.
   - Its biggest uncertainty is whether the .io core holds up past 30 minutes. Its retention score of 7 assumes the escort and family layers work.
2. **Hide the Goods (decisive: retention vs. first-minute bounce).**
   - It has the best long-term structure: player-made puzzles, active defense, an asynchronous rivalry.
   - It has the worst first minute among the top three.
   - **If a prototype shows the 60-second onboarding works, this concept could overtake #1.** I'm putting it second only because it is less certain, not because I think it's less good.
3. **Body Snatch (decisive: feasibility).**
   - **Uncomfortable conclusion: this is the idea most likely to make you say "that's insanely clever"**, with the best thumbnail and clip potential.
   - It is also **the worst bet for a small team** under a retention-weighted algorithm.
   - Roughly 10 movement controllers have to feel great on touch, and once players have tried each body, novelty fades.
   - Build it only if you can afford a long feel-tuning phase, or lift its best idea (possessing one special "Legendary" class) into another game.
4. **Long Shot (decisive: differentiation).** It is fun and cheap, but it sits next to a large launch-verb hit (Kick a Lucky Block) and reads as a feature. It's best **bolted onto #1 or #2**, for example by letting you throw a single creature over a gate.
5. **Every Catch Is Different (decisive: identity).** The principle is right, but each sub-verb exists somewhere (fleeing, Pokémon-style catching, stealth) and there's no single iconic image. Its best ideas are already folded into #1–#3.
6. **Handle With Care (decisive: feasibility).** The comedy is proven on Steam, but Roblox physics on mobile is a trap. Use it as a sub-system.
7. **Charmed (decisive: immediate fun).** It is the kindest design and the most suitable for the Kids and Select catalogs, but it is too slow and too quiet to break out.
8. **Hunted (decisive: fit).** Asymmetric rounds conflict with an idle-income economy. It's great as a **weekly event mode**, poor as a core.

## Uncomfortable conclusions

- **None of these concepts will reproduce Steal an Egg's numbers through mechanics alone.** Steal an Egg had a publisher-style portfolio, a crossover with Steal a Brainrot's developer, weekly events and timing. A great mechanic gets you into the recommendation algorithm; live operations keep you there.
- **The #1 concept is a remix of a 2016 web game's core rule (slither.io).** Its originality lies in the combination: your line is the loot, the lasso and the weak point at once, together with the Robin Hood rule. That's legitimate innovation, but it is not a mechanic nobody has ever seen. It is also the kind of thing a competent team could clone within weeks, so being first plus the skill ceiling are the moat.
- **The genre's original sin, theft that hurts children, is still present in every concept.** The research strongly suggests the next winner will be the one where theft is *fun even for the victim*. Parade Thieves gets closest; Body Snatch and Hide the Goods need explicit fairness tuning.
---

# Part E — Deep dive into the top 3

## E.1 PARADE THIEVES

### 1. The full moment-to-moment loop

**A typical 60–120 second "run":**
1. **Leave the gate.** Your 2 escorts (say, a Turtle and a Magnet Cat) fall in behind you. The UI shows `🐣 2/14`.
2. **Sweep the Meadow ring.** Each hatchling you touch pops with a rising chime and joins at the back. The Magnet Cat pulls in strays within a few studs. The line count ticks up.
3. **A Skittish creature bolts** as you approach. You arc around it and your line's glow trail shows the loop closing, then **"LOOPED!"** and it joins.
4. **A rare "Picky" creature in the Marsh** shows its condition above its head: "needs 2 Frog-family". You have one. You decide to go deeper and risk a longer route.
5. **Your line turns red at the edges.** That is the **Robin Hood indicator**: two nearby players have shorter lines and are allowed to cut you. One sprints at your mid-line, so you curl tight and the Turtle's shell protects the segment behind it.
6. **The attacker clips your tail.** Four followers spin, "confused", with a 1.5-second scramble window. You whip around and touch two back; the attacker keeps two. Their line just got longer, so now *they* glow red to everyone smaller.
7. **Your gate.** The parade streams in. The creatures hop onto pedestals one by one, with ascending notes, and a **"PARADE ×1.5!"** banner appears. Income per second jumps.
8. **Spend.** You buy +2 Charisma (a longer line) or +1 Stride (more speed) or a new pedestal row, and check the Family Index.
9. **Repeat.** Each run goes slightly deeper and greedier.

**Server rhythm:**
- Every ~8 minutes, **Parade Night** opens base gates for 90 seconds. You can raid, or race home to defend.
- About every 20 minutes there's a **Stampede** event: a herd of Mythics crosses the map, and the whole server tries to loop them.

### 2. The first 60 seconds (no text tutorial; this targets first-play bounce)

| Time | What happens | Why |
|---|---|---|
| 0–5s | You spawn at your gate **with one starter hatchling already following you**. A glowing path points to the Meadow. | Instant ownership and an instant read: "it follows me!" |
| 5–20s | You touch 3–4 commons. Each one pops, chimes and adds +1. | The core verb is learned without being taught. |
| 20–30s | Your line hits its starting cap (deliberately small, 6). The gate pulses with "Bring them home!" | A short first loop. |
| 30–40s | You bank. Pedestals light up, money starts ticking, and "PARADE ×1.2!" appears. | The first reward in under 40 seconds. |
| 40–55s | An NPC **"Bandit Raccoon"** cuts your next line. You see the tail switch, a "SCRAMBLE!" prompt appears, you touch them back, and the game shows "SAVED!". | Cutting and scrambling are taught **with no real loss**. |
| 55–60s | Your first upgrade is affordable. In the center, a **Legendary glows with "Only follows parades of 20+"**. | A long-term goal is visible in the first minute. |

### 3. Minutes 10–30

- **Min 1–5:** Meadow loops. Charisma goes from 6 to 12. You catch your first Skittish creature and get your first human cut, in either direction.
- **Min 5–10:** The Marsh ring opens (Stride level gate). Picky Rares appear, and the Family Index begins: completing a family gives a pedestal multiplier.
- **Min 10–15:** Your first Parade Night, so you experience a raid from both sides. Your first escort slot unlocks (Turtle).
- **Min 15–20:** The Canyon ring opens and Epic "Heavy" decisions appear. A **Parade Partner** prompt offers a Link Up with a nearby player for a shared multiplier.
- **Min 20–30:** Your first attempt at a Legendary (you need a 20+ line). This is the big, scary, exposed run. A Stampede event hits around minute 25. The first rebirth requirement becomes visible.

### 4. What keeps experienced players

- **The escort meta and line ordering.** Which three abilities, and where in the line?
- **Secret hunting.** Hidden conditions such as loop shapes, times, or 50 of one color produce community discovery and guide videos.
- **Rebirth tiers** that unlock **parade floats**, the vehicle at the front of your line: a brass-band float, a dragon float.
- **Leaderboards:** longest parade banked, cleanest steals, biggest Stampede loop.
- **Weekly species drops and seasonal ring themes.**
- **The "Grand Parade" server event.** Everyone Links Up into one giant parade for a shared jackpot. It's a cooperative climax that produces screenshot-worthy images.
- **Mastery:** tight loops around fast creatures, cut timing, defensive weaving, reading the red indicators.

### 5. How collectibles, rarity and stealing work together

- **Rarity** sets three things:
  - **how you get a creature** (its behavior);
  - **what it does for you** (escort ability);
  - **what it earns** (pedestal income).
- **Stealing** happens in two bounded places:
  - **field cuts**, which push loot from rich to poor and turn the thief's line into a hot potato;
  - **Parade Night raids**, which are time-boxed and defended.
- **Collection** (pedestals, families, mutations) gives you the reason to keep going out.
- **The loop sustains itself:** greed → exposure → cut → scramble or revenge → bank → greed. Every arrow in it is something the player *does*, not something that happens to them while they're away.

### 6. The most satisfying moments

- Closing a loop around a fleeing Mythic.
- Banking a 40-creature parade with fireworks.
- Slicing a whale's line at their gate.
- Winning a scramble.
- Being the bodyguard who saves a friend's mega-parade (see 7).
- Discovering a Secret condition before anyone else.

### 7. Multiplayer: competition and cooperation

**Competition:**
- The Robin Hood rule creates natural rivalries: newcomers hunt whales, and whales hunt mid-tier lines.
- Hot-potato tails create brief alliances of convenience.

**Cooperation:**
- **Emergent roles.** Under the Robin Hood rule, a player with a *short* line can cut anyone with a longer line. So **a friend carrying almost nothing is the perfect bodyguard**: any attacker going for your mega-parade has a line longer than your guard's, so your guard can cut the attacker.
- The game naturally produces **Carrier + Guard** pairs, and that is a mechanical reason to bring a friend. This feeds the co-play-days signal.
- **Link Up:** friends merge their lines into one parade for a combined bank multiplier.
- **Party rules:** friends can't cut each other.

### 8. Monetization (fair, cosmetic-heavy)

**Sell:**
- **Parade cosmetics:** parade floats, confetti and glow trails, line music (marching band, EDM, lo-fi), hatchling hats, gate fireworks. Parades are inherently *showy*, so cosmetics are seen by everyone [I].
- **Convenience:** +1 escort slot, VIP (+10% income, a nameplate flair), private servers.
- **Boosts:** 2× income timers and rare-spawn luck boosts. Luck boosts count as **paid random items** under Roblox policy, so odds must be disclosed ([policy](https://create.roblox.com/docs/production/monetization/paid-random-items)).
- **A seasonal "Parade Pass"** with cosmetic tracks and an exclusive species.

**Don't sell:**
- cut immunity;
- Charisma above earnable caps;
- admin powers;
- anything that blocks the Robin Hood rule.

**Test carefully:** a once-a-day "Insurance" that returns one stolen creature. It sells peace of mind without blocking play.

### 9. Why it's visually attractive and instantly understandable

- **One image tells the whole game:** a kid leading a long, glowing, wiggling line of cute creatures, with another kid sprinting at it. Ducklings following their mother is a universally understood picture.
- **Lines are color-coded per player.** A cut is a burst of hearts as the tail flips to the thief's color.
- **Banking** is a satisfying sequential hop-and-chime.
- **Thumbnail:** two parades crossing, with a big "✂️" at the intersection.

### 10. The minimum viable version (to test whether the core is fun)

**Build only:**
- 1 map with 2 rings;
- about 12 creatures in 3 behaviors (Common, Skittish, Legendary "Status-seeker");
- follow, cap, loop capture, cut with the Robin Hood rule and the scramble window;
- pedestals and income; one upgrade (Charisma);
- mobile controls; 12-player servers;
- the NPC tutorial thief.

**Leave out:** escorts, Parade Night, Link Up, monetization.

**Estimate:** about 2–4 weeks for one developer with AI coding tools [I].

**Test with:**
- in-person and Discord playtests on phones;
- a small sponsored-ads run.

**Watch:**
- first-play bounce under 60 seconds;
- average session length (target ≥8 min);
- D1 (target ≥15%, against the DevForum norms of 10–15%);
- the share of sessions with at least one cut;
- **leave-within-30s after losing ≥50% of a line** (the rage-quit metric);
- runs per session ("one more run").

### 11. The biggest design risks and how to test them

| Risk | Test or mitigation |
|---|---|
| A competitor already exists | **Run the pending competition sweep before writing code** (queries listed in the limitations section). |
| Cuts feel unfair | A/B the Robin Hood threshold (strictly shorter vs. 20% shorter), scramble duration, and cooldowns. Track the rage-quit metric. |
| Chaos in the center | Tune map size against player count. Color-coded lines. Cap visible lines. |
| Phone performance | Stress-test 16 players × 60 followers on a low-end Android. Use impostors for distant followers. |
| Shallow after 30 min | Measure session 2 and session 3 return. Add escorts plus the family index in v2 *only if* the core holds. |
| Latency fairness | Test at 200ms ping. Server-side lag compensation. Show "near miss" feedback so players understand outcomes. |
| Zig-zag griefers | Cutters must have at least 1 follower. Per-target cut cooldown. The Robin Hood rule. |

### 12. Why it could outperform the competition

- In Steal an Egg the trip home is essentially "run, and hope your speed stat is high enough". In Parade Thieves the trip home is **skill, choice and spectacle**.
- **Theft happens to active players who chose the risk**, and they can recover from it. That's a fairer feeling, which should mean better D8–D28 retention.
- The Carrier + Guard roles produce **real co-play**.
- **Joystick-only** suits a mobile-majority audience.
- It's **theme-agnostic**: pets now, whatever is trending at launch.
- The visual is **instantly readable** in thumbnails and Shorts.

---

## E.2 HIDE THE GOODS

### 1. The full moment-to-moment loop

There are four interlocking phases, and the player moves between them freely:
- **Hunt (Mimic Zones).** Enter the Toy Store zone, scan the shelves, notice a teddy that *breathes*, tap it: it's a mimic and it pops out. Carry it home, where you can be tackled and drop it.
- **Hide (your base).** Place the new pet, pick its disguise (a lamp), and maybe swap a decoy. Income starts.
- **Raid (rival bases during open windows).** Enter with 3 strikes, read the room, and look for tells: a shadow that doesn't match, a blink when you turn away, a faint purr when you stand close. Tap. Then either grab and flee, or *HONK*, a strike, and the owner is pinged.
- **Defend.** When pinged, rush home and **sweep** the props to unmask lurking thieves disguised as furniture. Read the raid log afterward and redesign.

### 2. The first 60 seconds

| Time | What happens |
|---|---|
| 0–8s | You spawn in your empty room with three identical gift boxes. One blinks; you tap it and get your first pet. ("Find the odd one" is understood instantly.) |
| 8–30s | A glowing door leads to the Toy Store Mimic Zone, where starter mimics have **big tells** (wiggling, giggling). You catch 2 more. |
| 30–45s | Back home, **auto-hide** places them in disguise and income ticks. You're shown "Your pets are hidden as: Lamp, Clock, Pillow". |
| 45–60s | An **NPC thief** sneaks in and taps the wrong prop: *HONK!* It flees and drops coins. You've now seen both sides of the game without losing anything. |

### 3. Minutes 10–30

- **Min 1–10:** More mimic zones open. You unlock disguise forms and decoys, and your first trap prop (a squeaky toy).
- **Min 10–15:** The first real **Raid Window** (every ~10 min). You raid someone and use your strikes.
- **Min 15–25:** You're raided. You read the log ("found in 14s – Lamp") and **redesign**: this is the hook.
- **Min 25–30:** You unlock a gadget (Sniffer: reveals one tell per raid) and a second room theme.

### 4. What keeps experienced players

- **Base design meta:** decoy density, misdirection, trap placement.
- **Thief and Hider ranks** with seasonal resets.
- **"Unfound streak"** leaderboards.
- **New prop themes** every update: museum, haunted house, space station.
- **Tournaments:** the Hide & Seek Cup.
- **Rare pets that move between disguises,** which turns a raid into a live game of whack-a-mole.

### 5. How collectibles, rarity and stealing work together

- **Rarity sets three things:**
  - how hard a creature is to find in the wild (fewer, subtler tells);
  - how well it hides in your base (more forms, smaller forms, the ability to move);
  - its income.
- **Stealing is a puzzle** whose difficulty the owner designs.
- **The collection is also your defense:** more pets means more disguise options.

### 6. The most satisfying moments

- The owner's moment: watching a thief burn all 3 strikes on decoys.
- The thief's moment: finding a Secret disguised as a sock on the first try.
- Unmasking 4 lurking thieves in a row during a sweep.

### 7. Multiplayer

- **Co-op raids.** One player "pings" a decoy, the alarm pulls the owner's attention, and the partner grabs the real target.
- **Co-op defense.** Friends share sweep duty.
- **Friend bases** as a social showcase.
- **"Hide it at a friend's":** store one pet in a friend's base for safekeeping, which builds trust and social glue.

### 8. Monetization

- **Room themes and prop packs.** Decorating is a proven Roblox spend driver [BG: Bloxburg, Adopt Me].
- **Cosmetic disguise forms** (a golden trophy, a gaming chair).
- **Gadget charges** that can also be earned, VIP, private servers, a season pass.

**Don't sell:** permanent tell-hiding or unlimited strikes.

### 9. Visual / instant understanding

- **Thumbnail:** "WHICH ONE IS THE PET?" over a room of props. It's a puzzle the viewer plays in their head, which drives clicks.
- Reveals pop with confetti and a goofy sound.

### 10. Minimum viable version

- 1 room theme and about 15 props;
- 8 creatures with 2 forms each;
- 2 tell types (breathing, blinking);
- 1 Mimic Zone;
- raid windows, the strike system and the NPC tutorial thief;
- an event-based raid log;
- mobile tap targets.

**Estimate:** about 3–5 weeks [I].

### 11. Risks and tests

| Risk | Test or mitigation |
|---|---|
| First-minute confusion (bounce) | Test the gift-box opener against a "spot the mimic" opener. Measure under-60s bounce. |
| Brute-force guessing | Tune strikes, decoy density and the "suspicion" UI. Track raid success rate (target about 35–55%). |
| Tells unreadable on phones | Favor **motion and sound** tells over fine visual detail. Test on a 6-inch screen. |
| Owners don't engage with hiding | Auto-hide by default. Show "your base defended X raids" to reward light engagement. |
| Slow pace | Keep Mimic Zones dense and fast. Each spot-and-grab should take under 15 seconds. |

### 12. Why it could outperform

- It fixes the genre's dead time by making **defense active**.
- Its **content is player-made** and endless.
- It rides two 2026 tailwinds: hide-in-plain-sight (Meccha Chameleon) and anomaly spotting (Animal Hospital).
- Its clips are **puzzles the viewer plays along with**, which is one of the stickiest short-video formats [I].

---

## E.3 BODY SNATCH

### 1. The full moment-to-moment loop

1. Spot a creature and tap-and-hold to possess it (1.5s, interruptible).
2. The camera swoops and you are now a **Roller** armadillo.
3. Pick your route home: the downhill canyon is fast but has a jump you might miss; the road is safe and slow.
4. Every ~6s a **resist** prompt appears. Tap on the beat to keep control. Miss twice and you're ejected.
5. Rivals try to **bonk** you out. If one succeeds, the armadillo bolts and becomes up for grabs.
6. Roll through your gate. It settles on a perch, you pop out, and income starts.
7. Upgrade **Willpower** (resist strength) or **Grip** (bonk resistance), and unlock new routes.

### 2. The first 60 seconds

| Time | What happens |
|---|---|
| 0–10s | A chicken next to your spawn shows "TAP TO BECOME". You're a chicken, flap-hopping home. The comedy is immediate. |
| 10–25s | You bank the chicken and money ticks. A frog sits at the pond. |
| 25–45s | As the frog, you hop across lily pads home: a different body and a different skill. |
| 45–60s | On a cliff, a **Legendary Glider Owl** is labeled "Willpower 5 required". That's the long-term goal. |

### 3. Minutes 10–30

- One new archetype unlocks about every 5 minutes.
- You learn the route network: pipes, cliffs, rivers.
- Your first raid, possessing a creature on someone else's perch.
- Your first **hijack**, possessing the creature a thief is currently piloting.

### 4. What keeps experienced players

- Mastering hard archetypes (Glider, Burrower, Bouncer).
- Per-creature time trials.
- Secret creatures with unique movement.
- New "toys" each update.

### 5. How collectibles, rarity and stealing work together

- Rarity is the body you pilot.
- Theft is a contest of control (bonk, hijack) during the trip home and during raids.
- Collection is a garage of bodies you've mastered.

### 6. The most satisfying moments

- Gliding over the whole map into your base.
- A whale flopping home on land.
- Hijacking a thief's Legendary one meter from their gate.

### 7. Multiplayer

- **Pantomime Giant:** the Giant archetype needs **two players**, one possessing the front legs and one the back. It's co-op comedy and a co-play hook.
- Friends can escort each other by body-blocking bonks.
- Relay races.

### 8. Monetization

- Creature skins, possession effects, trails, perch decorations, VIP, private servers, season pass.

**Don't sell:** Willpower or Grip.

### 9. Visual / instant understanding

- **Thumbnail:** "I BECAME A CHICKEN TO STEAL IT", with a kid's avatar dissolving into a chicken. The fantasy of *becoming* something is one of the most-clicked framings on Roblox [BG].

### 10. Minimum viable version

- 3 archetypes (Waddler, Hopper, Roller) and 9 creatures;
- 1 map with a route for each archetype;
- resist prompts, bonk-eject, perches and income.

**Estimate:** about 4–6 weeks [I], dominated by movement feel.

### 11. Risks and tests

| Risk | Test or mitigation |
|---|---|
| Movement feel on touch | Playtest each archetype alone. Is it fun with no reward, for 2 minutes? If not, cut it. |
| Tedium | Cap any trip home at about 40s. Make slow bodies valuable but short-range. |
| Content treadmill | Budget about one new archetype per month. Reuse archetypes across species. |
| Retention past novelty | Measure D7 *after* all MVP archetypes have been tried. |

### 12. Why it could outperform

- Nothing else in the genre makes **rarity a new way to move**.
- Every catch is a different mini-game.
- Its clips are funnier and more varied than any chase.

**Why I still rank it third:** cost and long-term retention.
---

# Part F — Final recommendation

## Build PARADE THIEVES, but only after the competition sweep clears it

### Why it beats the other finalists

1. **It changes what the player *does* in all three loops with a single rule.**
   - The line is how you **acquire** (touching, looping).
   - It is how you **transport** (it follows you, exposed).
   - It is how you **steal** and **defend** (cuts, guards, escorts).

   Simple to understand, satisfying to play, hard to exhaust. That is the bar you set.
2. **It targets the open axis the research found.** The crowded axis is *where* you go (depth, distance, biome). The open one is *how the collectible behaves while you take it home* (A.3, A.8).
3. **It keeps the tension that powered the two biggest 2026 steal hits.**
   - Escape Tsunami: #1 in Jan 2026.
   - Steal an Egg: #1 from Aug to Oct 2026.
   - Both rest on a risky trip out and a safe base back home.

   Parade Thieves turns the trip home from "hold forward" into a skill-and-choice game.
4. **It fits the 2026 algorithm better than its rivals.**
   - **First-play bounce:** the core verb is understood within 5 seconds, and the first reward lands within 40.
   - **Co-play days:** the Carrier + Guard roles and Link Up give a mechanical reason to bring friends.
   - **28-day return:** escorts, families, rebirth floats, the Secret hunt and seasonal species.
5. **Its theft is the fairest in the genre.**
   - Theft happens to **active** players who **chose** their risk.
   - Loss is **partial** (only the tail behind the cut).
   - It is **recoverable** (the scramble window).
   - It flows from **rich to poor** (the Robin Hood rule).

   The research shows unfair theft is the genre's main source of churn and bad press (A.5).
6. **It's the most feasible of the top three.** It is joystick-only, followers are rendered client-side from replicated movement, and server cut checks are cheap. A small developer with AI coding tools can realistically ship a polished minimum viable version.
7. **It's theme-agnostic.** Launch with hatchling pets to ride the current egg-and-pet wave, and reskin species seasonally.

### What evidence supports it

| Claim | Status |
|---|---|
| Changing the acquisition verb (not the noun) is what produced the 2025–26 hits | Observed [V] |
| The out-and-back trip with theft on the way home is the genre's core tension | Observed [V] |
| Behavior-based rarity is under-exploited | Medium-confidence inference from about 37 acquisition searches |
| The platform rewards retention and co-play | Primary sources [V] |
| Unbounded theft drives backlash, and the market is moving to bounded theft | Observed [V] |
| A follower chain you can cut, combined with a steal economy, would be fun | **A hypothesis**, backed by slither.io's history [BG] but not yet tested in this genre |

### What remains uncertain

1. **Competition.** A Roblox game with this exact mechanic may exist. "Brainrot Army" is the first thing to check. → Run the sweep before any code.
2. **Fun over time.** Whether the .io core still holds after 30 minutes and on day 8.
3. **Fairness feel.** Whether cuts feel fair to 9-year-olds on phones with 150ms of latency.
4. **Phone performance** with many followers on screen.
5. **Live operations.** Steal an Egg had publisher-style help and a crossover. A great mechanic alone won't produce 1M+ CCU.

### The single most important thing to prototype first

**The cut.** Build a grey-box: 1 map, 12 players on phones, follow, loop, cut with the Robin Hood rule and the scramble window, and bank. Then answer one question:

> **Do players who just lost half their line laugh and chase, or do they leave?**

**Instrument it:**
- the leave-within-30-seconds-after-a-cut rate;
- the scramble success rate;
- runs per session;
- whether players *voluntarily* take longer, riskier runs.

**Decision:**
- If being cut produces a chase rather than a quit, and sessions run 8 minutes or more with no other content, the concept has a real core. Build the escorts, the families and Parade Night on top of it.
- If not, try the Robin Hood and scramble variants once. If it still fails, **switch to Hide the Goods**, the stronger retention design, and run the same "first-60-seconds" test on it.
---

# Research limitations & what is still pending

## How the research was done

- I ran six parallel research tracks:
  - the core Steal-X market;
  - acquisition-mechanic variants;
  - 2026 Roblox trends and platform changes;
  - player psychology and frustrations;
  - cross-genre and Steam mechanics;
  - platform rules (algorithm, policy, tech), which I covered myself.
- Together they used the full **200-searches-per-turn cap** (about 180 queries plus mine).

## Limitations you should weigh

1. **No direct page access.**
   - This environment's network policy blocked direct fetches of roblox.com, rowatcher.com, pcgamesn.com and similar sites.
   - Every finding comes from search-engine extracts of those pages, so I could not watch gameplay videos, open Roblox experience pages or read Reddit threads.
   - Mechanics were therefore verified through **2+ independent written guides** rather than video.
   - To give this session direct access, allow those domains in the environment's network settings ([docs](https://code.claude.com/docs/en/cloud-environments#network-access)).
2. **Reddit, TikTok and YouTube content is missing.**
   - Reddit could not be searched (the search tool's user agent is blocked).
   - TikTok and YouTube appear only as titles.
   - Player sentiment therefore comes from the DevForum, the press and guides, which skews toward developers and parents.
3. **Tracker numbers disagree.**
   - Steal an Egg's all-time peak is given as 2.2M by RoWatcher and as 12.4–14.3M by RoVitals, RoMonitor and rblxstat.
   - Steal a Brainrot's current CCU ranges from 85K to 626K depending on the tracker and the day.
   - I give the range and the date rather than pick one.
4. **Your three example games were not located:** "Eggs That Run Away", "Fish an Egg" and the deep-pool depth-sector game. If you have links, they would sharpen the competition picture.
5. **The concept-specific competition sweep has not run yet.** This is the most important gap. Your brief makes it mandatory. Concept originality is marked [UNCERTAIN] until it runs.
6. **About half of the acquisition-verb families were never searched** because the cap ran out: claw/vacuum, cannon/slingshot/golf, heist/vault, delivery/train, cooking/crafting, auctions, tower defense, racing, puzzles/rhythm, physics building.

## Next research pass (ready to run when you reply)

Per your brief, each concept will be searched under several gameplay descriptions, not just its name. Planned queries:

- **Parade Thieves:**
  - "roblox pets follow you in a line steal"
  - "roblox conga line game"
  - "roblox snake game collect pets"
  - "roblox crowd city"
  - "roblox cut line steal followers"
  - "roblox duckling follow game"
  - "Brainrot Army roblox gameplay"
  - "roblox parade game"
  - "slither roblox brainrot"
  - "roblox pikmin game"
- **Hide the Goods:**
  - "roblox hide your pets steal"
  - "roblox prop hunt tycoon"
  - "roblox disguise brainrot as object"
  - "roblox mimic pets find real one"
  - "steal a brainrot hide decoy"
  - "roblox hide and seek steal"
- **Body Snatch:**
  - "roblox possess animals steal"
  - "roblox become a brainrot"
  - "roblox control the pet to steal"
  - "roblox morph steal a brainrot"
  - "roblox be the egg escape"
- **Long Shot:**
  - "roblox throw brainrot into base"
  - "throw for brainrots"
  - "yeet a brainrot"
  - "roblox basketball steal pets"
- **The four smaller concepts:** the same approach, 3–5 queries each.
- **Also:**
  - the unsearched verb families above;
  - Reddit-free sentiment on Steal an Egg vs Steal a Brainrot;
  - the current state of Roblox snake/.io games;
  - mechanics of the user's three example games.

---

# Sources

Every source below was reached through web-search extracts (see Limitations).

## Platform, policy, finance
- Roblox newsroom, *Optimizing Discovery* (Jun 2026): https://about.roblox.com/newsroom/2026/06/optimizing-discovery-great-games-reach-millions-players-roblox
- DevForum, *Recommended For You Algorithm Improvements That Better Value Long-Term Retention*: https://devforum.roblox.com/t/recommended-for-you-algorithm-improvements-that-better-value-long-term-retention/4684575
- Creator Docs, Discovery and Discovery FAQ: https://create.roblox.com/docs/discovery · https://create.roblox.com/docs/discovery-faq
- Roblox Q2 2026 shareholder letter (SEC 8-K): https://www.sec.gov/Archives/edgar/data/0001315098/000162828026051059/ex991-robloxq22026earnin.htm
- Motley Fool on Q3 guidance: https://www.fool.com/investing/2026/07/31/roblox-guided-bookings-down-as-much-as-18-and-with/
- GodIsAGeek on the algorithm change and market cap: https://godisageek.com/2026/08/roblox-9-billion-algorithm-change/
- Kotaku on the $9B drop: https://kotaku.com/roblox-tanked-9-billion-in-a-single-day-after-the-company-admitted-it-was-directing-fewer-kids-toward-viral-games-that-emphasize-short-term-monetization-2000722002
- creation.dev (lower authority): https://www.creation.dev/learn/roblox-algorithm-update-filtering-brain-rot-games-april-2026
- RoWatcher opinion, *What the Roblox Algorithm Actually Rewards in 2026*: https://rowatcher.com/news/what-the-roblox-algorithm-actually-rewards-in-2026-not-ccu
- Roblox Kids and Select (BusinessWire): https://www.businesswire.com/news/home/20260413497398/en/Roblox-Introduces-New-Age-Based-Accounts-and-Expanded-Parental-Controls-for-Users-Under-16
- Reward-driven media feed restriction: https://www.pocketgamer.biz/roblox-restricts-reward-driven-media-feeds-in-kids-and-select/
- Age checks for chat: https://about.roblox.com/newsroom/2025/11/roblox-requires-age-checks-limits-minor-and-adult-chat
- DevEx +42% for 18+: https://about.roblox.com/newsroom/2026/04/roblox-fuels-high-fidelity-games-over-18-players-increases-qualifying-devex-rate-42
- Server Authority: https://about.roblox.com/newsroom/2026/07/creating-responsive-cheat-resistant-games-roblox-server-authority · https://create.roblox.com/docs/projects/server-authority
- Paid random items policy: https://create.roblox.com/docs/production/monetization/paid-random-items
- Roblox Fall 2026 games preview: https://about.roblox.com/newsroom/2026/09/roblox-fall-games-preview
- Deconstructor of Fun, *How to Build a Real Business on Roblox in 2026*: https://www.deconstructoroffun.com/blog/how-to-build-a-real-business-on-roblox-in-2026

## Steal a Brainrot
- Wikipedia: https://en.wikipedia.org/wiki/Steal_a_Brainrot
- PocketGamer.biz, 25M: https://www.pocketgamer.biz/robloxs-steal-a-brainrot-becomes-first-game-to-surpass-25m-concurrent-players
- Rolimons: https://www.rolimons.com/game/109983668079237
- RoWatcher, *Is the Brainrot Trend Dying?*: https://rowatcher.com/news/is-the-brainrot-trend-dying-what-ccu-data-from-three-top-games-reveals
- Endgametools: https://endgametools.com/en/roblox/players/steal-a-brainrot · rblxstat: https://rblxstat.com/games/7709344486
- Lenovo (record day): https://gaming.lenovo.com/roblox/post/roblox-just-shattered-the-all-time-record-for-concurrent-players-8s7u0nswtSVrLpi · Tubefilter: https://www.tubefilter.com/?p=188004
- Bruno Mars concert (Guinness): https://www.guinnessworldrecords.com/world-records/782027-largest-music-concert-in-a-videogame-by-a-single-artist
- Bloomberg, imitators and revenue: https://www.bloomberg.com/news/articles/2026-03-24/roblox-s-hit-game-steal-a-brainrot-battles-its-many-imitators
- Aftermath, lawsuits: https://aftermath.site/brainrot-roblox-court/
- Mechanics: https://allthings.how/?p=6441 · https://deltiasgaming.com/?p=259152 · https://stealabrainrot.fandom.com/wiki/Methods_Of_Stealing
- Anti-griefing update: https://roonby.com/2026/02/01/steal-a-brainrot-how-the-new-anti-griefing-system-works/ · https://techwiser.com/steal-a-brainrot-anti-griefing-system-guide/
- Criticism and fallout: https://tecnobits.net/?p=83977 · https://www.fox26houston.com/news/what-is-brain-rot-ai-kids · https://automaton-media.com/en/news/roblox-steal-a-brainrots-huge-popularity-among-japanese-kids-raises-concerns-over-school-violence-microtransactions-and-excessive-play-sessions/
- Kotaku review: https://kotaku.com/steal-a-brainrot-roblox-empire-review-popular-memes-1851787027

## Steal an Egg and the egg wave
- Rolimons: https://www.rolimons.com/game/107778070777162 · RoWatcher: https://rowatcher.com/games/10563114921/steal-an-egg · RoVitals: https://rovitals.com/game/107778070777162 · RoMonitor: https://romonitorstats.com/experience/107778070777162/
- Misfits Gaming on X: https://x.com/MisfitsGG/status/2090785862632038706
- StudioKrew, September 2026: https://studiokrew.com/blog/top-roblox-games-september-2026/
- Biomes and mechanics: https://bloxodes.com/articles/steal-an-egg-biomes-speed-requirements · https://games.gg/roblox/guides/steal-an-egg-biomes-guide/ · https://allthings.how/every-steal-an-egg-biome-and-its-speed-requirement/ · https://clip.dor.gg/en/blog/steal-an-egg-roblox-guide
- Reels takedown: https://kotaku.com/roblox-cracks-down-on-doomscrolling-games-like-steal-an-egg-that-forces-players-to-watch-reels-while-running-on-a-treadmill-2000727952 · https://www.gamesradar.com/games/simulation/roblox-takes-down-controversial-doomscrolling-game-promises-to-remove-others-that-reward-watching-a-continuous-feed-of-content-as-theyre-not-appropriate-for-younger-users/
- Sammy event: https://gameboost.com/blog/steal-an-egg-sammy-is-coming-event-details
- Variants:
  - Jump To Steal An Egg: https://www.dexerto.com/roblox/jump-to-steal-an-egg-codes-3410137
  - Steal a Giant Egg: https://rowatcher.com/games/10764907628/steal-a-giant-egg
  - Break and Steal an Egg: https://bloxodes.com/wiki/break-and-steal-an-egg
  - Shoot For Eggs: https://bloxodes.com/articles/shoot-for-eggs-beginner-guide
  - Swing For Eggs: https://www.aprasi.com/blogs/trending-topics/swing-for-eggs-roblox-guide-all-eggs
  - Steal a Fish Egg: https://rowatcher.com/games/10759695969/steal-a-fish-egg

## Other variants by verb
- Escape Tsunami for Brainrots: https://rowatcher.com/games/9363735110/escape-tsunami-for-brainrots
- Open Sea for Brainrots: https://insider-gaming.com/roblox-open-sea-for-brainrots-codes/
- Swing Obby for Brainrots: https://allthings.how/how-to-play-swing-obby-for-brainrots-upgrades-rebirth-and-mutations-explained/
- Dig DEEPER for Brainrots: https://rotrends.com/game/9797688646
- Dig and Hatch a Brainrot: https://progameguides.com/roblox/dig-and-hatch-a-brainrot-beginners-guide/
- Dive / Diving / Cave Dive: https://gamerant.com/roblox-diving-for-brainrots-codes/ · https://rowatcher.com/games/9937018508/cave-dive-for-brainrots
- Fishing: https://deltiasgaming.com/?p=331108
- Lasso and catch:
  - https://tryhardguides.com/rope-a-brainrot-codes/
  - https://www.sportskeeda.com/roblox-news/how-master-catch-feed-brainrot
  - https://www.dexerto.com/roblox/robloxs-catch-a-brainrot-is-pokemon-meets-tung-tung-tung-sahur-3384317/
  - https://rowatcher.com/games/10102718647/tame-faster-brainrot-ride-escape
- Stealth: https://www.sportskeeda.com/roblox-news/don-t-wake-brainrots-a-beginner-s-guide
- Kick a Lucky Block: https://rowatcher.com/games/10004244222/kick-a-lucky-block
- Brainrot Army (mechanic unknown, to check): https://rowatcher.com/games/9296995367/brainrot-army
- Templates: https://builtbybit.com/resources/escape-rock-for-brainrots.114977/ · https://builtbybit.com/resources/fish-for-brainrots.113670/

## 2026 Roblox landscape
- Animal Hospital (Anomaly): https://allthings.how/animal-hospital-anomaly-on-roblox-how-the-night-shift-and-anomalies-work/ · https://knowyourmeme.com/memes/subcultures/animal-hospital-roblox
- Grow a Garden 2: https://www.gosugamers.net/entertainment/news/78614-grow-a-garden-2-has-launched-on-roblox-here-s-everything-new-added-in-this-sequel · https://allthings.how/stealing-in-grow-a-garden-2-how-night-raids-and-garden-defense-work/
- Grow a Garden developer interview: https://gamesbeat.com/janzen-madsen-interview/ · NME: https://www.nme.com/news/gaming-news/roblox-grow-a-garden-major-changes-coming-update-cooking-3884432
- MM2 record and August 2026 overview: https://studiokrew.com/blog/top-roblox-games-august-2026/
- Fish It!: https://rowatcher.com/games/6701277882
- Forsaken: https://rowatcher.com/news/forsaken-s-floral-update-drives-the-survival-horror-hit-past-86k-players
- ASMR tower trend: https://rowatcher.com/news/roblox-week-of-july-18-asmr-towers-algorithm-spikes-a-big-forsaken-crash

## DevForum (developer voice)
- https://devforum.roblox.com/t/test-my-steal-a-brainrot-type-game-outdated-i-made-new-forum/4013209
- https://devforum.roblox.com/t/again-test-my-roblox-game-like-steal-a-brainrot/4216656
- https://devforum.roblox.com/t/suggestions-on-how-to-improve-d1-retention/4369566
- https://devforum.roblox.com/t/how-should-i-improve-these-stats/3978686
- https://devforum.roblox.com/t/how-do-slop-games-do-so-well/4510868

## Outside Roblox
- Meccha Chameleon: https://store.steampowered.com/app/4704690/MECCHA_CHAMELEON/ · https://gamerant.com/steam-co-op-party-game-meccha-chameleon-sales/ · https://www.windowscentral.com/gaming/the-viral-hit-of-2026-has-sold-15-million-copies-in-a-month-on-steam-costs-usd5-and-was-made-by-2-people
- R.E.P.O.: https://en.wikipedia.org/wiki/R.E.P.O.
- PEAK: https://www.pcgamesn.com/peak/major-sales-milestone
- Burglin' Gnomes: https://wnhub.io/news/stores-and-publishing/item-50229
- BOMBANANA!: https://gg.deals/gaming-news/these-were-the-50-most-played-demos-of-steam-next-fest-june-2026/
- Arc Raiders: https://www.gematsu.com/2026/01/arc-raiders-sales-top-12-4-million
- Lethal Company: https://en.wikipedia.org/wiki/Lethal_Company
- Task Bar Hero: https://allthings.how/task-bar-hero-tops-526000-concurrent-steam-players-amid-mixed-reviews/
