# Whispering Woods

A fairy-tale memory race for 2–6 players, each on their own phone. Peek under the enchanted pines, remember what you saw, and be first to tell the King where his treasures hide.

**Play:** https://amirhm1362.github.io/whispering-woods/

- Online play: one player taps *Create an online game* and shares the invite link or 6-letter code.
- One-phone play: pass a single phone around (or practise solo).
- 3D forest walk: tap the **3D** button beside the board (or Menu → Easier to see → View) to follow your piece through the forest, with a little map in the corner showing where everyone is. Each phone picks its own view, so flat-board and 3D players share the same game, and a peek under a pine is shown only on the phone of the player who lifted it.

Everything — board, pines, treasure tokens, cards, movers and dice — is drawn in code inside `index.html`; the 3D forest is built at runtime with three.js (loaded from jsDelivr). Online moves travel through free public MQTT relays (EMQX and HiveMQ); no accounts needed.
