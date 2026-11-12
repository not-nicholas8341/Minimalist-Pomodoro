# Pixel Sunset Pomodoro

A minimalist Pomodoro timer over a hand-drawn 8-bit landscape. Focus in daylight, rest under the stars, and sail a little closer to the island with every completed focus session.

Open `index.html` in a browser. It needs no build step and no dependencies.

## Features
- Three pixel-art sceneries in Settings: Coast, Forest, and Storm Lake. Your choice is saved, and switching scenery keeps your timer and voyage intact.
- Focus stays in daylight throughout the session. Short and long breaks bring moonlight, stars, and reflections, with smooth transitions between day and night. Long breaks reveal taller mountains.
- Palms and seabirds on the open coast; layered firs, curved riverbanks, and nighttime fireflies in the forest; dark cloud shelves, rugged peaks, falling windblown rain, and choppy water on Storm Lake. Occasional lightning lights nearby clouds and reflects on the lake. The storm is silent. All scenes keep the same pixel grid, with animation at 24 fps.
- Saved **Animate scenery** and **Animate storm** controls are enabled by default. Scenery animation brings swaying firs, drifting leaves, butterflies, wandering fireflies, river mist, rolling coastal surf, occasional jumping fish, a fluttering sail, and a fading boat wake. Storm animation controls rain, clouds, and lightning independently. Turn both off for still landscapes.
- Forest frames the river with overlapping distant treelines, dense groves, tall foreground firs, and mossy banks. At night, 32–64 fireflies glow along the shore and over the water, with small pixel halos and reflections.
- Coast has a curved sandy beach, turquoise shallows, reflective wet sand, rolling foam lines, and a tide that washes up and recedes. Shells, pebbles, a starfish, driftwood, and dune grass sit beneath the palms. Scenery, sun transitions, and storm effects move at a calmer pace without changing the timer speed; rain keeps its own independent speed.
- With scenery animation enabled, changing between focus and break eases through a 12-second sunrise or sunset, with warm twilight, a rising moon, and gradually appearing stars. Sun and moon reflections shimmer slowly without rapidly changing rows of light. Turning scenery animation off switches day/night immediately.
- Focus, short break and long break modes. A long break comes after every N focus sessions.
- Peek at another mode while a session runs. The timer keeps counting, and a gold dot marks the running tab.
- Settings for durations, auto-start and the 8-bit end chime. Settings and today's totals are saved in your browser.
- Running and paused sessions survive refreshes and browser restarts. An elapsed session is credited once; the next session waits for you to return.
- Only completed focus sessions advance the voyage. Cycle rewards show the actual completed focus minutes; skips do not earn progress.
- Keyboard shortcuts: `Space` starts or pauses, `S` skips, `R` resets, and `1` `2` `3` switch modes.
- The time left shows in the tab title. The countdown stays accurate when the tab is in the background.
