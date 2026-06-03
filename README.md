# Clash of Realms — Core Rules
**Version 1.5**

---

## 000. Fundamental Rules

### 001. Golden Rule
**001.1.** Card text supersedes rules text. Whenever a card's text directly contradicts these rules, the card's text takes precedence.

**001.2.** Cards do as much as they can. If a card's effect becomes partially impossible to execute, all possible parts of the effect are still applied. Impossible instructions are ignored.

**001.3.** "Can't" beats "Can." A card or rule that forbids an action supersedes one that permits it.

---

### 002. Silver Rule
**002.1.** Card text may use simplified or evocative language. It should always be interpreted in accordance with these rules rather than literally.

**002.2.** If a card is played and countered, or its targets become illegal, the card still resolves. Effects that cannot be applied are suppressed; all other effects apply normally.

**002.3.** A card's cost must be fully payable at the moment it is declared played. If a cost — including additional costs — cannot be met, that card cannot legally be played.

**002.4.** If a cost was valid when a card was played but becomes unavailable at the moment of resolution (e.g. a required sacrifice target no longer exists), the card still resolves. Effects tied to that cost are suppressed; all other effects apply normally.

**002.8.** "Destroy" only applies to cards currently on the Battlefield. A card that is in a hand, deck, or the Graveyard cannot be "destroyed." A card effect that says "destroy target unit" has no effect if the target is not on the Battlefield at the time of resolution.

**002.5.** Card Playing Timing: A player may not play cards from their hand or activate non-Reaction abilities except during the Main Phase of their own turn, while the game is in an Open State. Reaction cards and Reaction abilities may be played at any time during a Closed State (Chain), regardless of which phase or whose turn it is. Shards may be exhausted for mana at any time a player holds priority (see rule 205.6).

**002.6.** Dependent Effects: When a card contains two effects linked by the phrase "if you do," the second effect only resolves if the first was successfully executed. If the first effect is suppressed or fails, the second is also suppressed. Example: "Discard a card; if you do, draw a card" — if no card can be discarded, neither effect resolves.

**002.7.** Sequential Effects: When a card contains two effects linked by the word "then," each effect is treated independently. The first is resolved as fully as possible. If the first fails or is suppressed, the second still resolves independently. Example: "Discard a card, then draw a card" — if no card can be discarded, the draw still resolves.

---

### 003. Bronze Rule
**003.1.** Cards in Clash of Realms use one of three narrative voices depending on their card type. All three are valid and equivalent in rules terms — the voice is a stylistic choice that reflects the nature of the card, not a mechanical distinction.

**003.2.** First Person — Units speak as themselves. Battalions and Commanders use "I," "me," and "my" to refer to the card itself. Example: "When you play me, I enter Ready" or "If I survive combat, draw a card." In these cases, "I" and "me" always refer to the card bearing the text.

**003.3.** Second Person — Actions speak to the controller. Maneuvers and instant effects use "you" and "your" to address the player controlling the card. Example: "You draw 3 cards" or "Your units gain +1 Power until end of turn." In these cases, "you" always refers to the controller of the card at the time of resolution (see rule 105.6).

**003.4.** Third Person — Neutral effects describe outcomes. Cards that affect targets, zones, or players in general use neutral language. Example: "Target player discards a card" or "Destroy target unit." In these cases no specific player is implied by the grammar — the effect applies to whoever or whatever meets the stated criteria.

**003.5.** If a card mixes voices within the same text box, each sentence is interpreted according to its own voice. The presence of one voice on a card does not override the interpretation of another sentence using a different voice on the same card.

**003.6.** Voice is never used to determine rules interactions. If a card's meaning is ambiguous due to its narrative voice, it is interpreted in the way most consistent with these rules and the card's evident intent.

---

## 100. Game Concepts

### 101. Overview
**101.1.** Clash of Realms is a two-player Trading Card Game. Each player controls a Realm and fights to reduce their opponent's Realm Integrity to zero.

**101.2.** The game is played on a board divided into three parallel Zones. Each player has three Zone positions. For rulebook reference purposes these are labelled A, B, and C, but in physical play they are positional — each player's three Zones are laid out side by side facing their opponent's three Zones. A unit may only move into the Zone directly opposite its own across the board. There are no cross-zone attacks. Each Zone contains one Location card per player.

**101.3.** A player loses the game if any of the following occur:
- Their Realm's Integrity is at zero or below after a Chain has fully resolved and both players have passed priority.
- They are required to draw a card from an empty Main Deck.

**101.4.** Loss conditions are checked as **State-Based Effects** — they are evaluated after each Chain fully resolves and the game returns to an Open State. They are not checked mid-chain. Card effects that prevent or replace a loss (e.g. "if your Realm would reach 0, set it to 1 instead") follow the Golden Rule and take precedence over this rule.

**101.5.** If both players' Realms are at zero or below when State-Based Effects are checked, the game ends in a **Draw.** Neither player wins.

---

### 104. Cards and Objects

**104.1.** A **card** is the fundamental game object in Clash of Realms. Every card has a name, a card type, an Identity Color or Colors (except Shards), a mana cost, and a rules text box. Some cards also have Power or Integrity values.

**104.2.** A card exists in exactly one zone at all times. Moving a card from one zone to another follows the rules for that transition.

**104.3.** **Permanents** are cards that remain on the board after being played or deployed. Permanents include: Locations, Commanders (when deployed), Battalions, Artifacts, and Shards. A permanent in play can be the target of effects and interacts with the game state continuously.

**104.4.** **Non-permanents** are cards that resolve their effect and immediately leave the board. Maneuvers are non-permanents. When a Maneuver resolves, it is placed in its owner's Graveyard.

**104.5.** Cards not in play (in a player's Hand, Deck, Graveyard, or the Commander Zone) are not permanents and are not considered "in play." Effects that target permanents cannot target cards in these zones unless specifically stated.

**104.6.** A card's **name** is its full printed name. Two cards share a name if and only if their full names are identical. Card names are used to enforce copy limits and for effects that reference cards by name.

**104.7.** A card **enters play** the moment its cost has been fully paid and it is physically placed in its designated zone. At the instant of entering play, the card is targetable, affected by all in-play effects, and any triggered abilities that read "when this card enters play" fire immediately, opening a new Chain.

---

### 105. Ownership and Control

**105.1.** The **owner** of a card is the player who included that card in their deck, Location selection, or Commander selection at the start of the game. Ownership never changes during a game.

**105.2.** The **controller** of a card in play is the player who is currently directing its effects and making decisions for it. By default, a player controls all cards they own that are in play.

**105.3.** Card effects may transfer control of a permanent from one player to the other. When a player gains control of an opponent's permanent, they become its **controller** for as long as the effect lasts. The **owner** does not change.

**105.4.** When a permanent leaves play — whether destroyed, discarded, or returned to a non-board zone — it always goes to its **owner's** corresponding zone, not the controller's. Example: if a player gains control of an opponent's Battalion and that Battalion is later destroyed, it goes to the **opponent's** Graveyard, not theirs.

**105.5.** Commanders that are destroyed return to their **owner's** Commander Zone (see rule 203.7). This applies even if the Commander was under the opponent's control when it was destroyed.

**105.6.** The word **"you"** on a card always refers to that card's **controller**. The word **"opponent"** always refers to the other player relative to the controller.

**105.7.** When a control-changing effect ends, the permanent immediately returns to its owner's control if it is still in play.

---

### 106. Targets

**106.1.** A **target** is an object, player, or zone explicitly designated by a card's effect or ability using the word "target" or any phrasing that requires selecting a specific object to receive the effect.

**106.2.** A target must be **legal** both at the time it is declared and at the time the effect resolves:
- **106.2.1.** At declaration: the target must exist, be in the correct zone, and meet all requirements stated by the card.
- **106.2.2.** At resolution: if the target no longer exists, has moved to a different zone, or no longer meets the requirements, it is an **illegal target** and the effect is suppressed for that target. All other effects on the card still apply (see rule 002.2).

**106.3.** A card effect that does not use the word "target" is not a targeted effect. It affects all valid objects matching its description without requiring a selection. Such effects cannot be "responded to" on the basis of targeting.

**106.4.** Only cards and objects **in play** (on the board) may be targeted by effects unless the effect specifically states it may target a card in another zone (e.g. "target a card in a Graveyard").

**106.5.** A player may always be a legal target for effects that target players, as long as the player is still in the game.

**106.6.** Effects that say **"choose"** follow the same rules as targeted effects for the purpose of legality, even if the word "target" is not used.

---
**102.1.** There are five Identity Colors in Clash of Realms, each associated with a symbol and a mana type:

| Color  | Shorthand |
|--------|-----------|
| Yellow | [Y]       |
| Red    | [R]       |
| Green  | [G]       |
| Blue   | [B]       |
| Purple | [P]       |

**102.2.** Every card except Shards belongs to one or more Identity Colors. These are printed on the card.

**102.3.** A card with multiple Identity Colors requires all of those colors to be present in your Realm's identity (see rule 103).

---

### 103. Deck Construction
**103.1.** To play Clash of Realms, each player must prepare the following:
- 1 Realm Card
- 3 Location Cards (all different; no duplicates allowed).
- 3 Commander Cards (all different; no duplicates allowed).
- A Main Deck of exactly 40 cards (Any combination of Battalion, Maneuver and Artifact cards).
- A Side Deck of exactly 10 Shard cards. (Any combination of Battalion, Maneuver and Artifact cards).
- A Shard Deck of exactly 10 Shard cards.

**103.2.** Realm Card
- **103.2.1.** The Realm card defines your deck's Identity: the set of Identity Colors your deck may use.
- **103.2.2.** Your Realm's identity is the combination of all Identity Colors printed on it.
- **103.2.3.** Every card in your Main Deck, Location selection, and Commander selection must comply with your Realm's identity.

**103.3.** Identity Compliance
- **103.3.1.** A card is identity-compliant if every one of its Identity Colors is present in your Realm's identity.
- **103.3.2.** A card with a single Identity Color is compliant if that color matches at least one of your Realm's colors.
- **103.3.3.** A card with multiple Identity Colors is compliant only if **all** of its colors are contained within your Realm's identity.
- **103.3.4.** A **Colorless** card (no colored symbols in its cost) is always identity-compliant with any Realm. It may be freely included in any Main Deck, Location selection, or Commander selection regardless of Realm identity.
- **103.3.5.** Example: A Realm with [Y][R] identity allows [Y] cards, [R] cards, [Y][R] cards, and any Colorless cards. It does not allow [Y][G] cards, because [G] is not part of the Realm's identity.

**103.4.** Copy Limits
- **103.4.1.** A Main Deck may include a maximum of **3 copies** of any card with the same name.
- **103.4.2.** Location cards must all have different names. No two Locations in the same setup may share a name.
- **103.4.3.** Commander cards must all have different names. No two Commanders in the same setup may share a name.

**103.5.** Commander Cards
- **103.5.1.** A player must select exactly 3 Commander cards for their starting setup.
- **103.5.2.** These are not shuffled into the Main Deck. They begin the game set aside.
- **103.5.3.** Commanders must be identity-compliant with the Realm.

**103.6.** Location Cards
- **103.6.1.** A player must select exactly 3 Location cards for their starting setup.
- **103.6.2.** These are not shuffled into any deck. They begin the game set aside.
- **103.6.3.** Locations must be identity-compliant with the Realm.

**103.7.** Shard Deck
- **103.7.1.** The Shard Deck contains exactly 10 Shard cards. It is kept separate from the Main Deck.
- **103.7.2.** Shards do not have Identity Colors and have no identity restrictions.
- **103.7.3.** Shards have **no copy limit** in the Shard Deck.

**103.8.** Side Deck
- **103.8.1.** The Side Deck contains exactly 10 cards. It is kept separate from the Main Deck.
- **103.8.2.** Side Deck cards can be exchanged by cards from the Main Deck. Tournament rules may restrict the Side Deck use.

---

## 200. Card Types

### 201. Realm
**201.1.** The Realm card is a player's core game object. It represents their faction and serves as the primary win/loss condition.

**201.2.** Each Realm card has an **Integrity** value — its starting hit points. Integrity is persistent; it does not reset between turns or phases.

**201.3.** The Realm card is placed in the Realm Zone at the start of the game and cannot be moved or played.

**201.4.** If a Realm's Integrity reaches zero, its controller loses the game immediately.

**201.5.** Realms are never healed by end-of-turn healing effects unless a card specifically states otherwise.

---

### 202. Location
**202.1.** Each player has three Location cards, one per Zone (A, B, C).

**202.2.** Each Location card has an **Integrity** value. Location Integrity does not recover at end of turn.

**202.3.** Locations cannot attack or move.

**202.4.** Locations may have Passive, Triggered, or Activated abilities as printed on the card. Activated abilities may have mana costs.

**202.5.** A Location is **Destroyed** when its Integrity reaches zero. When a Location is destroyed:
- **202.5.1.** The Location card is flipped face-down. It remains in its Zone for the rest of the game and is still considered a Location — it retains its Zone designation (A, B, or C) and can still be attacked.
- **202.5.2.** All printed abilities on that Location are permanently suppressed for the rest of the game.
- **202.5.3.** A destroyed Location provides no Integrity protection. Attacks into that Zone deal damage directly to the Realm (see rule 707).

**202.6.** Locations are never healed by end-of-turn effects unless a card specifically states otherwise.

---

### 203. Commander
**203.1.** Commanders are powerful named units set aside before the game begins. They are not part of the Main Deck.

**203.2.** Each Commander has a **Power** value. Power serves a dual purpose: it is both the damage the Commander deals in combat and the maximum damage it can absorb before being destroyed.

**203.3.** At the start of the game, all three of a player's Commanders are placed face-up in their **Commander Zone**. They are visible to both players but are **not in play**.

**203.4.** Deploying a Commander: During the Main Phase, a player may pay a Commander's mana cost to deploy it from the Commander Zone to any friendly Location Zone of their choice. The Commander enters that Location Zone **Exhausted** unless it has the Haste keyword.

**203.5.** A Commander in the Commander Zone is not in play and cannot be targeted by card effects or abilities unless a card specifically states it may target cards in the Commander Zone.

**203.6.** Once deployed to a Location Zone, a Commander is a permanent in play. It can be moved to other Location Zones (see rule 504.2), attack, and defend.

**203.7.** Commanders and the Graveyard
- **203.7.1.** When a Commander is destroyed (by combat damage or a card effect that uses "destroy"), it is returned to its **owner's Commander Zone** — not the Graveyard. When it returns, it is fully reset: all damage is removed, all temporary effects end, and any Equipment attached to it is destroyed (see rule 206.3.5). It may be deployed again by paying its cost.
- **203.7.2.** If a Commander would be placed in the Graveyard by any means (discarded from hand, sent there by a card effect, etc.), its owner may choose to send it to the Commander Zone instead. This choice is made at the moment the card would enter the Graveyard. The Commander arrives in the Commander Zone fully reset.
- **203.7.3.** Commanders are never permanently removed from the game except by card effects that explicitly state "remove from game" or similar language.
- **203.7.4.** A Commander may be Removed from Game (see rule 302.6). When it returns, it goes to the Commander Zone fully reset.

**203.8.** Commanders must be identity-compliant with the Realm.

---

### 204. Battalion
**204.1.** Battalions are the primary combat units of the game. They are played from hand to a Location Zone during the Main Phase.

**204.2.** Each Battalion has a **Power** value. Power serves a dual purpose: it is both the damage the Battalion deals in combat and the maximum damage it can absorb before being destroyed.

**204.3.** Battalions enter play **Exhausted** in a Location Zone of the controller's choice.

**204.4.** When a Battalion is destroyed, it is placed in its owner's Graveyard.

**204.5.** Battalions are fully healed at the end of each turn (see rule 506.3).

---

### 205. Shard
**205.1.** Shards are resource cards drawn from the Shard Deck and placed on the board during the Resource Phase. They are not part of the Main Deck.

**205.2.** Shards do not have Identity Colors. Any Shard can be included in any Shard Deck.

**205.3.** Each Shard specifies the mana it produces when exhausted. A Shard may produce more than one color of mana or have additional effects — all are described on the card.

**205.4.** To generate mana, the controlling player exhausts a Ready Shard (rotates it horizontally). It produces the mana as printed on the card.

**205.5.** Shards are readied at the start of their controller's Beginning Phase each turn.

**205.6.** Shards are the only permanent that may be exhausted to produce mana at **any time**, regardless of whose turn it is or whether a Chain is open or closed. A player may exhaust their Shards at any moment they hold priority — including during the opponent's turn to pay the cost of a Reaction.

**205.7.** Because 2 new Shards are added each turn, the total mana available to a player grows over the course of the game.

**205.8.** When the Shard Deck is empty, the player simply draws no Shards during the Resource Phase. This is not a loss condition. Existing Shards on board remain and continue to function normally.

**205.9.** Shards cannot be destroyed. A card effect that would remove a Shard from the board instead **Stores** it to the bottom of its owner's Shard Deck (see rule 001.4). It may be drawn again in a future Resource Phase. This is the standard de-ramp mechanic for Shards in Clash of Realms.

---

### 206. Artifact

**206.1.** Artifacts are permanent cards. They are played from hand during the Main Phase by paying their mana cost. There are two types of Artifacts: **Base Artifacts** and **Equipped Artifacts**, as determined by the card text.

**206.2.** Base Artifacts
- **206.2.1.** Base Artifacts are placed in the player's Base Zone when played.
- **206.2.2.** Base Artifacts are in play once placed. Their passive, activated, and triggered abilities are active.
- **206.2.3.** Base Artifacts can be targeted by card effects. If a Base Artifact is destroyed, it is placed in its owner's Graveyard.
- **206.2.4.** Base Artifacts are not units. They cannot attack, defend, or move unless a card effect specifically states otherwise.

**206.3.** Equipped Artifacts
- **206.3.1.** Equipped Artifacts carry the **Equip [cost]** keyword (see rule 001.6). To play one, the controller pays the Equip cost and declares a valid target as specified on the card. The target must be in play at the moment of playing.
- **206.3.2.** An Equipped Artifact is not placed in the Base Zone. It is physically placed on or beside its target and remains attached to it.
- **206.3.3.** The Artifact's effects apply to its equipped target and/or its controller as stated on the card.
- **206.3.4.** An Equipped Artifact cannot be unequipped or moved to a different target under normal circumstances. A card effect may permit this only if it explicitly states so.
- **206.3.5.** If the attached card leaves play by any means (destroyed, returned to hand, sent to Commander Zone, etc.), the Equipped Artifact is simultaneously destroyed and placed in its owner's Graveyard.
- **206.3.6.** An Equipped Artifact may be targeted and destroyed independently by card effects. If it is destroyed, its carrier is unaffected.

---

### 207. Maneuver
**207.1.** Maneuvers are non-permanent cards. Their effects resolve when played and the card is immediately placed in the Graveyard.

**207.2.** Maneuvers without the Reaction keyword may only be played during the controller's own Main Phase while the game is in an Open State.

**207.3.** The **Reaction** keyword may appear on any card type — Maneuvers, Artifacts, Battalions, Commanders, or activated abilities. Any card or ability with the Reaction keyword may be played or activated during a Closed State in response to an existing Chain Item, regardless of whose turn it is (see rule 803.2).

---

## 300. Zones

### 301. Battlefield Zones
**301.1.** The **Battlefield** is the entire physical play area where cards reside during active gameplay. All cards on the Battlefield are Public Information unless specifically noted.

**301.2.** Realm Zone — Each player has one Realm Zone housing their Realm card for the entire game.

**301.3.** Base Zone
- **301.3.1.** Each player has one Base Zone, placed adjacent to their Realm Zone.
- **301.3.2.** The Base Zone is where Artifacts are played. Artifacts in the Base Zone are considered **in play** and their effects are active.
- **301.3.3.** The Base Zone cannot be attacked. No combat or direct damage can be directed at cards in the Base Zone unless a card effect specifically states otherwise.
- **301.3.4.** Artifacts in the Base Zone are permanents and can be targeted by card effects unless they have protection.

**301.4.** Commander Zone
- **301.4.1.** Each player has one Commander Zone, placed adjacent to the Realm Zone.
- **301.4.2.** The Commander Zone houses a player's Commanders before deployment and after they are destroyed.
- **301.4.3.** Commanders in the Commander Zone are visible to both players but are **not in play**. They cannot be targeted by card effects or abilities unless a card specifically states it may target cards in the Commander Zone.
- **301.4.4.** The Commander Zone cannot be attacked. No combat or direct damage can be directed at it.

**301.5.** Location Zones
- **301.5.1.** Each player has three Location Zones. For rulebook reference these are labelled A, B, and C but in physical play they are positional — each faces the directly opposing Zone across the table.
- **301.5.2.** Each Location Zone contains one Location card.
- **301.5.3.** Battalions and Commanders present in a Location Zone are considered to be **defending** that Location.
- **301.5.4.** Any number of Battalions and Commanders may occupy the same Location Zone.

**301.6.** Shard Zone — Each player has a Shard Zone where deployed Shards are placed face-up.

---

### 302. Non-Battlefield Zones
**302.1.** When a card moves to a Non-Board Zone, all temporary modifications on it (damage, buffs, temporary effects) are immediately removed.

**302.2.** Hand
- **302.2.1.** Cards drawn from the Main Deck go to the Hand. Hand contents are Private Information.
- **302.2.2.** The number of cards in a player's hand is Public Information.
- **302.2.3.** There is no maximum hand size.

**302.3.** Main Deck — Kept face-down and shuffled. Contents are Secret Information. If a player must draw from an empty Main Deck, they lose the game.

**302.4.** Shard Deck — Kept face-down and separate from the Main Deck. Contents are Secret Information.

**302.5.** Graveyard
- **302.5.1.** The following cards go to the Graveyard: destroyed permanents, resolved Maneuvers, cards discarded from hand, and cards removed from the Battlefield by effects that do not specify another destination.
- **302.5.2.** Cards in the Graveyard are Public Information. Their order does not matter unless specified by a card effect.
- **302.5.3.** When a player is instructed to discard a card and their hand is empty, the effect is suppressed (see rule 002.2).

**302.6.** Removed from Game
- **302.6.1.** "Removed from Game" is a special suspended state. A card that is Removed from Game is not on the Battlefield, not in any deck, hand, or Graveyard. It is set aside in a designated area.
- **302.6.2.** Cards Removed from Game are Public Information (both players may see them).
- **302.6.3.** A card that is Removed from Game is not considered to be in play. It cannot be targeted, does not have active effects, and does not count as being in any zone for the purpose of game rules.
- **302.6.4.** Removal from the game is always paired with a return condition defined by the effect that caused the removal (e.g. "until this unit leaves the Battlefield"). When the return condition is met, the card returns to its **default zone**:
  - Commanders → Commander Zone (fully reset, see rule 203.7)
  - Base Artifacts → Base Zone (unequipped, in normal Base state)
  - Equipped Artifacts → Base Zone (no longer attached; returns as an unequipped Base Artifact)
  - Battalions → Graveyard (unless the returning effect specifies otherwise)
  - Locations → their Location Zone (face-up, with Integrity reset to the value it had when removed)
  - All other cards → the zone they occupied before being removed, unless the effect specifies otherwise.
- **302.6.5.** If an Equipped Artifact is Removed from Game, it loses its attachment. When it returns, it returns to the Base Zone as an unequipped Artifact. The unit it was attached to is unaffected.
- **302.6.6.** "Remove from Game" is not the same as "destroy." An Unperishable card may be Removed from Game.

---

## 400. Setup

### 401. Preparing the Game

**401.1.** Each player places their Realm card face-up in their Realm Zone.

**401.2.** Each player secretly assigns their three Location cards to Location Zones A, B, and C — one Location per Zone — placing them **face-down**. Assignments are made simultaneously and are not yet revealed.

**401.3.** Each player places their three Commander cards face-up in their **Commander Zone**. Commanders are visible to both players from the start of the game.

**401.4.** Each player shuffles their Main Deck and places it in their Main Deck Zone.

**401.5.** Each player shuffles their Shard Deck and places it in their Shard Deck Zone.

**401.6.** Determine the first player using any random method agreed upon by both players (e.g. coin flip, dice roll). The first player is the Turn Player for the first turn.

**401.7.** Each player draws an opening hand of 5 cards from their Main Deck.

**401.8.** Mulligan: Each player, starting with the first player, may perform one Mulligan.
- **401.8.1.** To Mulligan, a player selects any number of cards from their opening hand, places them on the bottom of their Main Deck in a random order, then draws the same number of cards from the top. The deck is **not reshuffled** after placing cards at the bottom.
- **401.8.2.** A Mulligan may only be performed once per game, before the first player's first turn begins.
- **401.8.3.** A player may choose not to Mulligan.

**401.9.** When the first player takes their first turn, **before the Beginning Phase begins**, all face-down Locations are simultaneously **flipped face-up** by both players. Both players' Location configurations are revealed at this moment.

---

## 500. Turn Structure

A turn consists of the following phases in order:

**Beginning Phase → Resource Phase → Draw Phase → Main Phase → (Combat Phase) → End Phase**

The Combat Phase only occurs when combat is triggered during the Main Phase.

---

### 501. Beginning Phase
**501.1.** All cards the Turn Player controls that are in an Exhausted state are **Readied** (returned to vertical position). This includes Shards, Commanders, Battalions, and any other exhausted permanents.

---

### 502. Resource Phase
**502.1.** The Turn Player **Catalyzes** 2 Shards: they draw the top 2 cards of their Shard Deck and place them face-up in their Shard Zone in a Ready state.

**502.2.** Exception — Second Player's First Turn: The player who goes second **Catalyzes 3 Shards** on their very first turn only, to partially offset the first-player advantage. From that player's second turn onward, the standard 2 Shards applies to both players.

**502.3.** If fewer cards remain in the Shard Deck than the player is entitled to Catalyze, they Catalyze as many as possible (including zero). This is not a loss condition.

---

### 503. Draw Phase
**503.1.** The Turn Player draws 1 card from the top of their Main Deck.

**503.2.** If the Main Deck is empty when the player must draw their mandatory 1 card per turn, that player loses the game immediately.

**503.3.** If a card effect instructs a player to draw multiple cards and the deck runs out mid-effect, the player draws as many cards as possible (applying rule 001.2 — do as much as you can). The effect then ends. When the Chain fully resolves, the loss condition is checked as a State-Based Effect (rule 101.4) — if the player was required to draw from an empty deck during that draw, they lose at that point.

---

### 504. Main Phase
**504.1.** The Main Phase is open-structured. The Turn Player may take any number of the following actions in any order, as long as they hold priority in an Open State:

- Play cards from hand by paying their cost (see rule 600).
- Perform Tactical Moves (see rule 504.2).
- Declare Attacks (see rule 504.3).
- Activate abilities of cards they control that are playable during the Main Phase.

**504.2.** Moving Units
- **504.2.1.** During the Main Phase, the Turn Player may move any number of Ready Battalions or Commanders, one group at a time. Moving a unit **Exhausts** it immediately.
- **504.2.2.** **Moving to a friendly Location Zone** (Repositioning): A Ready unit may be moved from any of the controller's Location Zones to any other of their own Location Zones. The unit ends its movement there and stays. No combat occurs.
- **504.2.3.** **Moving to the opposing Location Zone** (Attack): A Ready unit may only attack the directly opposing Zone across the board — the Zone that physically faces its own. It may not attack an opponent's Zone that is not directly opposite. This keeps combat lane-based.
- **504.2.4.** When one or more Ready units move into the opposing enemy Zone, this immediately triggers the Combat Phase for that Zone (see rule 700). Those units are Exhausted. The Combat Phase resolves fully, and surviving units are returned to their **Origin Zone** (the Zone they moved from).
- **504.2.5.** Multiple units from the same Origin Zone may be moved simultaneously into the opposing enemy Zone as part of one combined attack. Units from different Zones may not be combined into the same attack.
- **504.2.6.** A player may choose to send some units from a Zone while leaving others behind. Units left behind defend their Location normally.
- **504.2.7.** After one combat resolves, the Turn Player may move units from other Zones to initiate further combats, provided those units are Ready.

**504.3.** Defending While Exhausted
- **504.3.1.** A unit does not need to be Ready to defend. Any Battalion or Commander present in a friendly Location Zone — whether Ready or Exhausted — automatically participates as a Defender when that Zone is attacked.

**504.4.** Haste
- **504.4.1.** **Haste** is a keyword that may appear on Battalions or Commanders. A unit with Haste enters play in a **Ready** state instead of Exhausted.
- **504.4.2.** A unit with Haste may move (including into an enemy Zone) the same turn it enters play or is deployed.
- **504.4.3.** Haste does not grant a unit the ability to move or attack more than once per turn.

**504.5.** Ending the Main Phase — When the Turn Player has no further actions they wish to take, they declare the end of their Main Phase. Play proceeds to the End Phase.

---

### 505. Combat Phase
**505.1.** Triggered when a unit moves to an enemy Location Zone during the Main Phase.

**505.2.** Follows the rules of Section 700. Combat.

**505.3.** After the Combat Phase fully resolves, the game returns to the Main Phase.

---

### 506. End Phase

**506.1.** End Step — Any abilities or card effects that trigger "at the end of the turn" or "at the start of the End Phase" resolve now, following Chain rules (see rule 800).

**506.2.** Expiration Step — All unspent mana in **both players'** Mana Pools expires. All mana is lost regardless of who generated it or whose turn it is.

**506.3.** Healing Step — All Battalions and Commanders the Turn Player controls have all damage removed from them. They are fully healed.
- **506.3.1.** Locations and the Realm are **not** healed at the end of a turn unless a card effect specifically states otherwise.

**506.4.** State-Based Effects — Loss conditions are checked (see rule 101.3 and 101.4). If any Realm is at zero or below Integrity, the appropriate player loses. If both are at zero or below, the game is a Draw.

**506.5.** The Turn Player's turn ends. The opponent becomes the new Turn Player and begins their turn at rule 501.

---

## 600. Mana

### 601. Mana Types
**601.1.** Mana is the resource used to pay the costs of cards and abilities.

**601.2.** There are six types of mana in Clash of Realms:

| Type | Symbol | Usage |
|------|--------|-------|
| Colorless | [C] | Pays any generic (colorless) cost component |
| Yellow | [Y] | Pays [Y] cost components |
| Red | [R] | Pays [R] cost components |
| Green | [G] | Pays [G] cost components |
| Blue | [B] | Pays [B] cost components |
| Purple | [P] | Pays [P] cost components |

**601.3.** Colored mana may only be spent to pay cost components of the matching color unless a card effect states otherwise.

**601.4.** Colorless mana ([C]) may be spent to pay any generic (colorless) cost component. It may not pay colored cost components.

**601.5.** Reading a Card Cost: A cost written as **"3YR"** is shorthand for: pay 3 mana of any type or color (generic), plus 1 Yellow mana, plus 1 Red mana. The colored symbols define both the payment requirement and the card's Identity.

**601.6.** A cost written as **"4"** with no colored symbols means: pay 4 mana of any type. This card has a Colorless identity and may be included in any deck (see rule 102.5).

**601.7.** Colored mana of any type may always be used to pay generic (uncolored) portions of a cost. Only the specific colored components require matching mana types.

---

### 602. The Mana Pool
**602.1.** The Mana Pool is the conceptual store of mana available to a player at any given moment.

**602.2.** Mana is added when a Shard or other mana source is exhausted.

**602.3.** Mana can be spent at any time after being added, subject to timing restrictions.

**602.4.** Unspent mana expires at the **End Phase of every turn**, regardless of which player's turn it is. Mana generated during the opponent's turn (e.g. to pay for a Reaction) expires at the end of that opponent's turn if not spent.

---

### 603. Exhausting Shards
**603.1.** To generate mana, a player exhausts a Ready Shard they control by rotating it horizontally.

**603.2.** Each Shard produces the mana type printed on it when exhausted.

**603.3.** An already Exhausted Shard cannot be exhausted again until it is Readied.

---

## 700. Combat

### 701. Overview
**701.1.** Combat occurs when the Turn Player declares an attack from one of their Location Zones into the opponent's matching Location Zone.

**701.2.** The player who declared the attack is the **Attacker**. Their opponent is the **Defender**.

**701.3.** Combat proceeds through the following steps: Declaration → Showdown → Damage Assignment → Resolution.

---

### 702. Declaration Step
**702.1.** The Turn Player selects one or more Ready Battalions and/or Commanders from a single Location Zone. These become the **Attacking Units**.

**702.2.** The Attacking Units are moved to the opponent's Location Zone in the same Zone. They become Exhausted.

**702.3.** The player may choose which Ready units to send and which to leave behind in the same Zone. Units left behind continue to defend their Location.

**702.4.** Following the Declaration, the Chain opens and the Attacker receives priority (see rule 800).

---

### 703. Showdown
**703.1.** After the Declaration, a Showdown window opens. Both players may play Maneuvers or activate abilities via the Chain. The Attacker holds priority first.

**703.2.** All Battalions and Commanders already occupying the Defender's contested Location Zone are **Defending Units** for this combat. All present units automatically defend; the Defender does not choose.

**703.3.** If there are no Defending Units in the contested Location Zone, this is an **Undefended Attack** (see rule 701.2). The Showdown still opens and both players may play Reactions and activate abilities normally — the Defender may use this window to reduce the Attacker's Power, place units in the Zone, or play other effects. When the Showdown closes, all remaining Attacking Power is dealt directly to the Location's Integrity. If the Location is already destroyed, all Attacking Power is dealt to the Realm's Integrity. No Damage Assignment phase occurs — damage is automatic.
- **703.3.1.** An Undefended Attack is **not a Combat.** No player wins or loses a combat. Card effects that trigger on winning a combat, losing a combat, or surviving a combat do not activate as a result of an Undefended Attack, even if significant damage is dealt to the Location or Realm.
- **703.3.2.** If a Reaction played during the Showdown places one or more units in the contested Zone, the Undefended Attack becomes a regular Combat. Damage Assignment proceeds normally.

**703.4.** Once both players have consecutively passed priority with no further actions, the Showdown closes. If the Location is Undefended, rule 703.3 applies. Otherwise, Damage Assignment proceeds (rule 704).

---

### 704. Damage Assignment
**704.1.** Once the Showdown closes, Damage Assignment begins. This phase is a **Closed Window** — no cards, abilities, or triggered effects may be played or activated from the moment Assignment begins until it is fully resolved. Any triggered abilities that fire during this window are held and placed in a new Chain after Assignment concludes.

**704.2.** Mandatory-Lethal Assignment
- **704.2.1.** Damage may only be assigned to a unit in exactly the amount required to destroy it — equal to its remaining Power (its Power minus any damage already on it). Assigning more or less than the lethal amount to a single unit is not permitted.
- **704.2.2.** A unit is either assigned lethal damage (and destroyed) or receives no damage at all. Non-lethal assignments are not permitted.
- **704.2.3.** A unit whose Power has been reduced to zero by prior damage in the same turn is already destroyed before Assignment and is not a valid target.
- **704.2.4.** **Annihilate exception:** A unit with Annihilate is not bound by mandatory-lethal. Its controller may assign any non-zero amount of damage from it to a target enemy unit. That target is destroyed when damage resolves. Any unspent Power from the Annihilate unit flows to the Location or Realm as overflow per normal rules.
- **704.2.4.** A unit with **Unperishable** (see rule 001.10) that would be destroyed by lethal assignment is not destroyed. The assignment still occurs, but the destruction is prevented. That unit's damage resets at end of turn. Unperishable units still count as valid assignment targets and still absorb the damage assigned to them.

**704.2b.** Frontline and Backline Priority Order
- **704.2b.1.** When assigning damage to a group of units (defending or attacking), the assigning player must follow this priority order: **Frontline units first → regular units → Backline units last.**
- **704.2b.2.** A player may not assign damage to a regular unit or a Backline unit while any Frontline unit in the same Zone remains alive.
- **704.2b.3.** A player may not assign damage to a Backline unit while any non-Backline unit in the same Zone remains alive.
- **704.2b.4.** If the assigning player's total Power is insufficient to kill all Frontline units, they may kill as many Frontline units as possible (mandatory-lethal, choosing among them freely). Any remaining Power follows normal rules: if any unit (including Frontline) survives, no wall damage is dealt.
- **704.2b.5.** Frontline and Backline apply symmetrically: they affect both Attacker's assignment (targeting defenders) and Defender's assignment (targeting attackers).
- **704.2b.6.** Frontline and Backline also apply within the Advantage Window (rule 706.2).
- **704.2b.7.** If a unit has both Frontline and Backline simultaneously (via stacked effects), treat them as simultaneous keyword triggers. The controller of that unit decides which keyword applies by choosing the order in which the keywords take effect — the last one ordered overrides the previous. This follows the same rule as simultaneous triggered effects (rule 804.3).

**704.3.** Attacker's Assignment:
- **704.3.1.** The Attacker selects which Defending Units to kill and assigns exactly their remaining Power to each chosen unit.
- **704.3.2.** Remaining Attacking Power flows to the Location **only if all Defending Units have been assigned lethal damage** (i.e. all defenders are killed). If any Defending Unit survives the Assignment — whether because the Attacker lacked enough Power or chose not to target it — the Location receives **no damage**. Surviving defenders protect the Location entirely.
- **704.3.3.** If the Attacker lacks enough total Power to kill any single Defending Unit, no assignments can be made and the Attacker's Power is entirely absorbed. The Location takes no damage.

**704.4.** Defender's Assignment:
- **704.4.1.** The Defender simultaneously selects which Attacking Units to kill and assigns exactly their remaining Power to each, following the same mandatory-lethal rules.
- **704.4.2.** Any Defending Power not used in lethal kill assignments is wasted. It does not reach the Attacker's Location or Realm.

**704.5.** All Attacker and Defender assignments are declared simultaneously. Once declared, no assignment may be changed. Damage resolves simultaneously across all targets.

---

### 705. Combat Outcomes

**705.1.** Damage is applied to all targets simultaneously after Assignment.

**705.2.** A Battalion or Commander is **Destroyed** when the damage assigned to it equals its remaining Power. Destroyed units are immediately moved to their owner's Graveyard.

**705.3.** Location damage and Realm damage are applied as determined by rule 704.3.2.

**705.4.** Successful Attack — The Attacker **wins the combat.**
- **705.4.1.** A Successful Attack occurs when all Defending Units are killed. Remaining Attacking Power is dealt to the Location (or directly to the Realm if the Zone is Open). Any Location reduced to zero Integrity is Destroyed (see rule 202.5).
- **705.4.2.** Card effects that trigger on "winning a combat" trigger for the Attacker. Card effects that trigger on "losing a combat" trigger for the Defender.

**705.5.** Failed Attack — The Defender **wins the combat.**
- **705.5.1.** A Failed Attack occurs when one or more Defending Units survive after Damage Resolution.
- **705.5.2.** In a Failed Attack, the Location takes no damage regardless of how many Defending Units were killed.
- **705.5.3.** Surviving Defending Units remain in their Location Zone. Attacking Units destroyed by defenders are sent to the Graveyard. Surviving Attacking Units return to their Location Zone wounded (see rule 707).
- **705.5.4.** Card effects that trigger on "winning a combat" trigger for the Defender. Card effects that trigger on "losing a combat" trigger for the Attacker.
- **705.5.5.** Example: Attacker has total Power 5. Defenders have Power 4 and Power 3. Attacker kills the Power 4, but has only 1 remaining — not enough to kill the Power 3. The Power 3 defender survives. Location takes 0 damage.

**705.6.** Mutual Destruction — **No winner.**
- **705.6.1.** Mutual Destruction occurs when all Attacking Units and all Defending Units are destroyed simultaneously.
- **705.6.2.** No Location or Realm damage is dealt. All destroyed units go to their respective Graveyards.
- **705.6.3.** Neither player wins or loses the combat. Card effects that trigger on winning or losing a combat do not trigger.
- **705.6.4.** Example: Attacker has a single unit of Power 4. Defender has a single unit of Power 4. Both assign lethal to each other. Both are destroyed simultaneously. Location takes 0 damage. No combat winner.

**705.7.** Combat-Altering Effects
- **705.7.1.** Cards or abilities played during the Showdown (see rule 703) may alter the outcome of Damage Assignment before it begins.
- **705.7.2.** A unit affected by the **Stun** keyword or a Stun effect does not assign any damage during Damage Assignment. It contributes 0 Power to its side's assignments for this combat. A Stunned unit still receives damage normally from the opponent's assignments.
- **705.7.3.** Example: An Attacker has a Power 10 unit attacking a Power 4 Defender. During the Showdown, a Reaction Maneuver Stuns the Attacking unit. In Assignment, the Attacker assigns 0 (Stunned). The Defender assigns 4 to the Attacker. The Attacking unit takes 4 damage (now has 6 remaining Power). The Defender is not killed. The Location takes 0 damage. Combat ends.
- **705.7.4.** A Stunned unit that survives combat returns to its Location Zone with its accumulated damage. At end of turn, it is healed to its full Power.

**705.8.** Defending effectively rewards the Defender: surviving Battalions and Commanders are healed at end of turn (rule 506.3), while Location Integrity does not recover. A Location that takes no damage retains its full Integrity indefinitely.

---

### 706. Advantage

**706.1.** **Advantage** is a keyword that may appear on Battalions, Commanders, or card effects. A unit with Advantage deals its damage in a separate window that occurs **before** regular Damage Assignment.

**706.2.** Advantage Window:
- **706.2.1.** Before the regular Damage Assignment phase begins, an Advantage Window opens. All units with Advantage on both sides declare their assignments simultaneously, following the same mandatory-lethal rules (rule 704.2).
- **706.2.2.** If a player controls multiple units with Advantage in the same combat, that player decides the order in which their Advantage units assign damage within the Advantage Window. Both players declare their ordered assignments simultaneously before any damage is applied.
- **706.2.3.** Advantage damage from both sides resolves simultaneously. Destroyed units are removed from combat.
- **706.2.4.** A unit destroyed in the Advantage Window does not participate in regular Damage Assignment and deals no further damage this combat.

**706.3.** After the Advantage Window resolves, regular Damage Assignment proceeds (rule 704) with all surviving units. Units with Advantage do **not** deal damage again during regular Assignment — a unit deals damage only once per combat regardless of Advantage.

**706.4.** If both an Attacking unit and a Defending unit have Advantage, they both deal damage simultaneously in the Advantage Window.

**706.5.** Example: An Attacker has a Power 6 unit with Advantage. The Defender has a Power 4 unit without Advantage and a Power 3 unit without Advantage. In the Advantage Window, the Attacker assigns 6 to the Power 4 unit (lethal, destroying it, 2 overflow to Location). Regular Assignment follows: the Power 6 Advantage unit assigns nothing (already dealt damage). The Power 3 unit assigns its damage to the Attacker. The Location has already taken 2 damage from the Advantage Window.

---

### 707. Open Zone — Direct Realm Damage
**706.1.** If the Defender's Location in the contested Zone is already Destroyed (face-down) at the moment the attack is declared, the Zone is **Open**.

**706.2.** In an Open Zone, all Attacking Unit Power that is assigned to the "Location" is instead dealt directly to the Defender's Realm, reducing its Integrity.

**706.3.** Open Zone attacks follow all other combat rules normally. Defending Units, if present, still participate and deal damage back to Attacking Units.

**706.4.** If the Realm's Integrity reaches zero, that player loses the game immediately (rule 101.3).

---

### 708. Combat Resolution
**707.1.** After damage is fully applied and all Destroyed units are moved to the Graveyard, surviving Attacking Units are **returned** to their **Origin Zone** — the Location Zone from which they initiated their Move.

**707.2.** Returned units remain **Exhausted** until the Attacker's next Beginning Phase.

**707.3.** The Combat Phase ends and the Main Phase resumes.

---

### 709. Fight

**709.1.** A **Fight** is a direct damage exchange between two specific units, triggered by a card effect. Fights are distinct from Combat — no Location Zone is attacked, no Showdown phase occurs, and no player wins or loses a combat as a result of a Fight.

**709.2.** A Fight is initiated by a card effect that reads "this unit fights target [unit type]" or equivalent phrasing. The initiating unit is the **Fighter**; the selected unit is the **Fight Target.** The Fight Target must be a valid target at resolution (see rule 106).

**709.3.** Since the word "target" is used, Protection applies: a unit with Protection cannot be selected as a Fight Target by an enemy effect (see rule 001.9).

**709.4.** When a Fight is declared, a Chain opens. Both players may play Reactions and activate abilities before the Fight resolves. The player whose card initiated the Fight receives priority first.

**709.5.** When the Chain closes and the Fight resolves, both units simultaneously deal damage equal to their current Power to each other. Normal damage rules apply (Unperishable prevents destruction, etc.).

**709.6.** Advantage applies in a Fight: if the Fighter has Advantage, it deals its damage before the Fight Target deals damage back. If both units have Advantage, they deal damage simultaneously in an Advantage Window (see rule 706).

**709.7.** Frontline and Backline do not apply in a Fight — those keywords govern zone-wide assignment order and have no relevance in a one-on-one exchange.

**709.8.** A Fight does not trigger "win/lose a combat" or "survive a combat" effects. Card effects that reference Fights use the word "fight."

**709.9.** After a Fight resolves, both units remain in their respective zones (if they survived). Neither unit is moved or Exhausted by the Fight alone. Destroyed units go to the Graveyard (or Commander Zone for Commanders, per rule 203.7).

---

## 800. The Chain

### 801. Overview
**801.1.** The Chain is a temporary zone that exists whenever a card is played or an ability is activated or triggered.

**801.2.** The Chain uses Last In, First Out (LIFO) resolution — the most recently added effect resolves first.

**801.3.** While the Chain exists, the game is in a **Closed State.** Only cards and abilities with the **Reaction** keyword may be added to the Chain during a Closed State.

**801.4.** When no Chain exists, the game is in an **Open State.**

---

### 802. Priority
**802.1.** Priority is the exclusive right to take the next game action. Only one player holds Priority at any given time.

**802.2.** Priority is granted as follows:
- **802.2.1.** During the Main Phase in an Open State, the Turn Player holds priority.
- **802.2.2.** When a card is played or an ability is triggered or activated, the player who played or triggered it receives priority first.
- **802.2.3.** After each action or after priority is passed, priority transfers to the opponent.

**802.3.** A player holding priority may:
- Play a legally timed card.
- Activate a legally timed ability.
- Pass priority to the opponent.

**802.4.** If both players consecutively pass priority without adding anything to the Chain, the Chain **closes** and effects begin resolving (see rule 805).

---

### 803. Adding to the Chain

**803.1.** When a player plays a card or activates an ability, it is placed on the top of the Chain as a **Pending Item.** Priority then passes to the opponent.

**803.2.** Reactions:
- **803.2.1.** The **Reaction** keyword may appear on any card type — Maneuvers, Artifacts, Battalions, Commanders, or activated abilities on any card. Any card or ability with the Reaction keyword may be played or activated in response to an existing Chain Item, during a Closed State, even on the opponent's turn.
- **803.2.2.** Either player may play or activate a Reaction when they hold priority, as long as a Chain exists.

**803.3.** In combat, the Attacker receives priority first when the Showdown Chain opens.

**803.4.** Activated Ability Timing
- **803.4.1.** Activated abilities without the Reaction keyword may only be activated during the controller's own Main Phase in an Open State.
- **803.4.2.** Activated abilities with the Reaction keyword follow the same timing rules as Reaction cards — they may be activated at any time the controller holds priority during a Closed State.
- **803.4.3.** Shards are an exception: exhausting a Shard to produce mana is not an activated ability subject to these timing restrictions. Shards may be exhausted at any time a player holds priority (see rule 205.6).

---

### 804. Triggered Abilities
**804.1.** Triggered abilities automatically activate when a specified condition is met (e.g. "When a Commander enters a Location Zone...").

**804.2.** When a trigger condition is met, that ability is added to the top of the Chain as a Pending Item.

**804.3.** If multiple triggered abilities trigger simultaneously, the following order applies:
- **804.3.1.** The Turn Player adds their triggered abilities to the Chain first, in any order of their choice, followed by the opponent, in any order of their choice.
- **804.3.2.** If a single player controls multiple triggered abilities that trigger simultaneously, that player decides the order they are placed on the Chain. The order matters because the Chain resolves LIFO — the last ability placed resolves first.

**804.4.** A triggered ability that fires while a Chain is currently resolving does not interrupt the resolving Chain. It is held pending until the current Chain finishes resolving completely. At that point, the triggered ability starts a new Chain.

---

### 805. Resolving the Chain
**805.1.** When both players consecutively pass priority, the topmost item on the Chain resolves. Its instructions are executed in full.

**805.2.** After each item resolves, priority is passed again. If a player wishes to respond before the next item resolves, they may do so.

**805.3.** The Chain is fully cleared when it is empty and both players consecutively pass priority in the empty state. The game returns to an Open State.

---

### 806. Illegal Targets and Suppressed Effects
**806.1.** A target is **legal** if it meets all requirements stated by the card or ability at the moment of resolution.

**806.2.** If a target becomes illegal between the time a card was played and the time it resolves, the effect referencing that target is suppressed. All other effects on the card still apply normally.

**806.3.** If all of a card's effects are suppressed, the card is still considered played and resolved. It is placed in the Graveyard as normal.

**806.4.** If a cost payable at resolution (e.g. sacrificing a Battalion) is no longer available when the card resolves, the effect tied to that cost is suppressed. All other effects apply normally (see rule 002.4).

---

## 900. Keywords

Keywords are special rules that appear on cards as shorthand. Each keyword has a precise definition. Where a keyword appears on a card, it functions exactly as defined here unless the card's text overrides it (Golden Rule).

| Keyword | Definition |
|---|---|
| **Advantage** | This unit deals its damage in a separate window before regular Damage Assignment. A unit deals damage only once per combat regardless of Advantage. |
| **Annihilate** | When this unit deals any damage to an enemy unit, that unit is destroyed, regardless of remaining Power. May assign any non-zero damage to a target; mandatory-lethal does not apply to this unit. Unperishable prevents the destruction. |
| **Backline** | This unit may only be assigned lethal combat damage after all non-Backline units in the same Zone have been assigned lethal damage. If no Power remains after non-Backline units, this unit takes no damage. |
| **Catalyze** | Draw a Shard from the Shard Deck and place it in the Shard Zone in a Ready state. Standard rate: 2 per Resource Phase (3 for the second player on their first turn). May also appear on card effects as a bonus action. |
| **Equip [cost]** | A two-cost keyword on Artifacts. The play cost puts the Artifact in the Base Zone. The Equip cost (paid separately during your Main Phase, Open State) attaches it to a valid friendly target. Equip cost 0 = free attachment. No Equip keyword = cannot be attached. Not a Reaction. |
| **Examine [X]** | Look at the top X cards of your Main Deck. Place any number of them on the top and/or bottom of your deck in any order of your choice. Cards not placed on top go to the bottom. You do not reveal them to your opponent. |
| **Frontline** | This unit must be assigned lethal combat damage before any non-Frontline unit in the same Zone can be assigned damage. If multiple Frontline units are present, the assigning player chooses the order among them. |
| **Haste** | This unit enters play in a Ready state instead of Exhausted. It may move, attack, or be deployed and act the same turn it enters the Battlefield. |
| **Heroism** | Continuous passive. While this unit is in a Location Zone where at least one enemy unit has a base Power strictly greater than this unit's base Power, this unit gains +1 Power. Compared using base Power only. Flat +1 regardless of how many qualifying enemies are present. |
| **Last Breath [effect]** | Triggered keyword. When this unit is destroyed, the stated effect triggers. Held pending until the current Chain or damage resolution fully completes, then fires as a new Chain. The unit does not need to be on the Battlefield for the trigger to resolve. Triggers when a Commander returns to the Commander Zone via destruction. |
| **Protection** | This card cannot be selected as a target by enemy card effects or abilities. The owner may still target it with their own effects. Area-of-effect effects bypass Protection. Combat damage bypasses Protection. |
| **Reaction** | This card or ability may be played during a Closed State (Chain) on any player's turn. Shards do not need Reaction to produce mana at any time. |
| **Siege** | This unit deals double damage to Locations and Realms. When this unit's Power contributes to damage dealt to a Location's Integrity or a Realm's Integrity (overflow, undefended attack, Open Zone), that damage is doubled. Does not affect damage to units. |
| **Store [X]** | Place exactly X cards from the specified source on the bottom of the relevant deck in any order. No deck-searching exists in Clash of Realms; top-deck interactions use Examine or Store. |
| **Unperishable** | This card cannot be destroyed by combat damage or by any effect using the word "destroy." Destruction is prevented; the unit survives with damage, which clears at end of turn. Non-destruction removal (returning to hand, Removed from Game) still applies. May be permanent (printed on card) or temporary (granted by effect, expires end of turn). |

---

## 901. Key Terms

Game concepts and zone definitions used throughout these rules.

| Term | Definition |
|---|---|
| **Attacker** | The player who moved units into an enemy Location Zone, initiating combat. |
| **Base Zone** | A Battlefield Zone where each player's Artifacts are placed when played. Artifacts here are in play and can be targeted. Cannot be attacked. |
| **Battlefield** | The entire physical play area: all Location Zones, Base Zones, Commander Zones, Shard Zones, and Realm Zones of both players. A card "leaves the Battlefield" when it moves to the Graveyard, Hand, Deck, or Removed from Game. |
| **Chain** | The ordered stack of effects waiting to resolve. Resolves Last In, First Out (LIFO). |
| **Closed State** | A game state in which a Chain exists. Only Reactions may be played. |
| **Colorless** | A card or identity with no colored mana symbols in its cost. Colorless cards are identity-compliant with any Realm. |
| **Commander Zone** | A Battlefield Zone where each player's Commanders reside before deployment and after being destroyed. Commanders here are not in play and cannot be targeted. Cannot be attacked. |
| **Controller** | The player currently directing a permanent in play. Control can change via card effects. By default, a player controls all cards they own that are on the Battlefield. |
| **De-ramp** | Removing a Shard from the Battlefield. Shards are not destroyed; instead they are Stored to the bottom of the Shard Deck. |
| **Defender** | The player whose Location Zone is being attacked. |
| **Destroyed** | A unit with damage equal to or exceeding its Power is destroyed and sent to the Graveyard (or Commander Zone for Commanders). A Location whose Integrity reaches zero is flipped face-down with all abilities suppressed. |
| **Equipped Artifact** | A Artifact attached to a unit or Location via the Equip action. Cannot normally be unequipped or moved. Destroyed when its carrier leaves the Battlefield. |
| **Exhausted** | Horizontal card state. Cannot be used or exhausted again until Readied. |
| **Failed Attack** | A combat in which one or more Defending Units survive. The Location takes no damage. The Defender wins the combat. |
| **Fight** | A direct damage exchange between two specific units triggered by a card effect. Not a Combat. No Location is attacked, no Showdown occurs, and no player wins or loses a combat. Both units deal their Power to each other simultaneously. |
| **Graveyard** | The discard pile. Cards sent here lose all temporary modifications. |
| **Integrity** | The hit points of a Realm or Location. Does not reset between turns. |
| **Move** | Moving a Ready unit from one Location Zone to another. Exhausts the unit. Moving to a friendly Zone is a reposition. Moving to the directly opposing enemy Zone triggers combat. Cross-zone attacks are not permitted. |
| **Mutual Destruction** | A combat in which all Attacking and Defending Units are destroyed simultaneously. No Location or Realm damage is dealt. Neither player wins the combat. |
| **Open State** | A game state in which no Chain exists. The Turn Player may freely play cards and take actions. |
| **Open Zone** | A Zone where the defending Location has been destroyed. Attackers deal damage directly to the Realm. |
| **Origin Zone** | The Location Zone a unit moved from when initiating an attack. Surviving attackers return here after combat. |
| **Owner** | The player who included a card in their deck or selection at the start of the game. Ownership never changes. When a card leaves the Battlefield, it goes to its owner's corresponding zone. |
| **Power** | The single combat stat of a Battalion or Commander. Represents both the damage it deals and the maximum damage it can absorb before being destroyed. |
| **Ready** | Upright card state. The card is available to be used or exhausted. |
| **Removed from Game** | A suspended state outside all normal zones. Cards here are not on the Battlefield and cannot be targeted. Returns to its default zone when the removal condition ends. Not a destruction — Unperishable does not prevent it. |
| **Showdown** | The window during combat or an Undefended Attack where both players may play Reactions and activate abilities before damage is assigned or applied. The Attacker receives priority first. |
| **State-Based Effects** | Loss conditions checked after each Chain fully resolves. If a Realm is at zero or below Integrity, its controller loses. Both Realms at zero = Draw. |
| **Undefended** | A Location Zone with no Battalions or Commanders defending it. All Attacking Power flows directly to the Location or Realm. A Showdown still opens; no Damage Assignment phase occurs. Not a Combat — no combat win/loss triggers fire. |

---

*End of Clash of Realms Core Rules v1.5*
