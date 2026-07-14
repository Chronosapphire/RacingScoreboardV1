Updates — [14/7/2026]
Added

-Tap-to-count entry UI — replaced manual number typing with a circular layout of player avatars around a central Confirm button. Tap an avatar to +1, tap the −1 button to decrement. Impact: faster, error-resistant input — no more typos from a numeric keypad, and it works great on touchscreens.

-Simultaneous entry — removed turn-by-turn ("X's Turn") sequencing; any player's count can be adjusted at any time before confirming. Impact: matches how these games are actually played at the table — everyone calls out their number around the same time.

-Live running total — a badge above the circle updates in real time as counts change. Impact: players can see at a glance where the group total stands before locking anything in.

-Visual "locked" state — the Confirm button turns red and disables when the prediction total would equal the forbidden round value. Impact: makes an easy-to-miss rule impossible to miss.

-Buzz + haptic feedback — a synthesized buzzer sound and phone vibration fire if Confirm is tapped while locked. Impact: immediate, unmistakable feedback without needing to read an alert box.

-Prediction reference badge — during the Actual Result phase, each player's locked-in prediction now shows next to their avatar. Impact: no more forgetting what you predicted by the time actuals are being counted.

-Home screen with New Game / Resume Game — plus full game-state persistence via localStorage, autosaving after every action, and a "Save & Exit" button mid-game. Impact: a browser refresh, closed tab, or accidental navigation no longer wipes out a game in progress.

-End-game stats & podium — 🥇🥈🥉 podium plus stat cards for Most Accurate predictor, "Wooden Spoon" (least accurate), and Biggest Single Round. Impact: adds replay value and a fun wrap-up beyond just the final score table.

Changed

Full visual redesign — moved from a generic dark-theme look to a motorsport-inspired identity: checkered-flag accents, condensed racing-style headings, a digital-dashboard mono font for numbers, and distinct "driver colors" per player avatar. Impact: the app now has a distinctive, on-brand look instead of a templated dark UI.
Rule enforcement moved to Confirm — the "predictions can't sum to the round value" rule is now checked once at Confirm time (since entry is simultaneous) instead of only on the last player's turn.


