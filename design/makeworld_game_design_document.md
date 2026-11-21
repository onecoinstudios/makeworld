# MakeWorld — Game Design Document

**Working title:** MakeWorld
**Genre:** Hybrid casual (creative make-and-play sandbox × collection / evolution meta)
**Status:** Concept / pre-production design
**Author:** One Coin Studios — design track
**Date:** 20 Nov 2026

---

## 1. Executive summary

MakeWorld is a hybrid casual game where the player **creates** (outfits, scenes,
creations) and the game turns those creations into a **living collection** that
evolves.

- **Core loop:** Make → Play / Use → Collect & Evolve → Share
- **Session length:** 1–3 minutes
- **Platform:** HTML5 / WebGL browser build (Playgama-class portal), cross-platform to mobile + desktop
- **Business model:** Free-to-play with optional ad-supported meta progression / cosmetic layer; eligible for portal embed monetization

### The one-line pitch
*Create anything. Watch it come alive. Collect the evolution.*

---

## 2. Market context & design rationale

### 2.1 Research basis (Playgama, Nov 2026)

| Signal | Finding |
|---|---|
| Official Top Playgama leaderboard (`/category/top_playgama`) | #1 Piece of Cake: Merge & Bake · **#2 TB World** |
| TB World engagement | "The hottest game right now", **~18k votes**, **4.6★**, categorized Top Playgama + Trending now, dev used **Construct**, Toca Boca creative lineage |
| Millionaire Life | ~**18k votes**, tycoon / life-sim progression |
| Adjacent tier | Hedgies (~9k) · PVZ Fusion Cheats (~9k) · Find the Frog (~9k) · Hidden Object: My Hotel (~8k) · Idol Livestream (~5k) · Good Sort Master (~5k) |

### 2.2 Design insight

Two top-10 performers converge on one structural pattern:

1. **Creative / expressive sandbox** — low skill ceiling, high UGC potential (TB World).
2. **Progression / meta layer** — collection, evolution, life-sim-adjacent growth (Millionaire Life).

Separating those into a single game is the natural **hybrid-casual** synthesis
and is already validated by two independently top-ranked titles on the platform.

---

## 3. Vision

> Players should feel that everything they make is **alive** — and that their
> library of makes is a **thing that grows**.

The fantasy is self-expression plus ownership: *I made this, and now it has a
life / a place / a story.*

---

## 4. Pillars

1. **Expressive creation, gentle difficulty.** Creation is the hook; no fail
   state. The fun is in the making.
2. **Evolution is the retention engine.** Creation → collection → evolution →
   new creative tools. Pure creative games stall; meta compounds.
3. **Shareability.** Designs are social objects — remix, collections, showcases.
4. **Snappy sessions.** Under 2 minutes of meaningful play; easy to return to.

---

## 5. Core gameplay

### 5.1 Core loop
```
Make (create a design) → Use / Play (the creation gets life)
      → Collect (add to collection / album)
      → Evolve (unlock next stage / new tools via progression)
      → Share / Remix → back to Make
```

### 5.2 Creative toolset (initial scope)
- Parts palette (body / costume / accessory slots)
- Color & material variation
- Pose / scene composition
- Template starting points (sandbox presets)
- Export / share artefact (image / link)

### 5.3 Meta layer (hybrid-casual differentiator)
- **Creation albums / collections** — each creation is a collectible entry.
- **Evolution stages** — creations progress through stages (e.g. New → Used →
  Evolved → Legend) driven by usage, completion, or remixing.
- **Cross-pollination** — designs feed back into new content (e.g. a player-made
  outfit becomes a playable character; a scene becomes a playable level).

---

## 6. Progression & economy

### 6.1 Player progression
- Collection count / albums completed
- Evolution stages unlocked
- Mastery of creative tools

### 6.2 Meta / spend progression
- Cosmetic or ad-supported unlocks for meta layer (evolution boosts, exclusive
  parts, album skins).

---

## 7. Content & UGC pipeline

- UGC creation + sharing loop
- Curated template packs (weekly / themed)
- Seasonal / event collections

---

## 8. Monetisation

- Free core (create + play + collect)
- Optional meta cosmetics / progression aids
- Ad-supported optional layer
- Portal embed monetization (post-launch, Playgama developer program)

---

## 9. Platform & technical fit

- HTML5/WebGL for browser portal (Playgama)
- Cross-platform mobile + desktop
- Lightweight creative UI (performance-sensitive; avoid heavy UI frameworks)
- Engine: lightweight (Construct-class) for content velocity; consider heavier engine if meta systems grow

---

## 10. Art & audio direction

- Bright, playful, toy-like aesthetic (matches TB World / Toca-adjacent creative space)
- Stylised sound design; minimal UI

---

## 11. Success metrics

- D1 / D7 retention
- Session length & frequency
- Collection / evolution progression depth
- UGC / remix rate
- ARPDAU / ad inventory where applicable

---

## 12. Risks & mitigations

| Risk | Mitigation |
|---|---|
| Pure creative games lack retention | Strong evolution meta (core design pillar) |
| UGC supply / moderation | Template packs + curated seeding |
| Browser performance | Lightweight creative renderer |

---

## 13. Suggested production milestones

1. **Concept validation** — paper prototype of Make/Use/Collect/Evolve loop
2. **Core creative sandbox** — single-platform prototype
3. **Evolution meta** — collection + evolution systems
4. **WebGL browser build** — portal-ready
5. **Launch + iterate**

---

*Next steps: prototype the Make → Use → Collect → Evolve loop; lock creative toolset scope.*
