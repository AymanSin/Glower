# Glowjar

A nightly word hunt in a jar of fireflies. Seven categories, thirty seconds each. Every new letter in your answer flies into the jar, rare letters glow brighter, and catching all 26 seals the jar for a bonus.

**Play:** https://aymansin.github.io/Glower/

**Play with friends:** press *Play with friends*, then *Copy invite link* and send it. Friends land straight in your party, no account needed. Everyone gets the same category at once, and matching answers score half.

The whole game is one file, `index.html`, with no build step. Multiplayer runs over a free public MQTT relay (EMQX, with HiveMQ as backup), so don't put anything private in your player name. Stats and streaks are saved in each player's browser.
