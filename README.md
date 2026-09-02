diff --git a/README.md b/README.md
index 6d9ec61159aa293be40de6f26a6ba3ef7424c0ba..4d22c0f1fd772366f160a2b26adbfd90ff70c968 100644
--- a/README.md
+++ b/README.md
@@ -1 +1,17 @@
-# testr
\ No newline at end of file
+# NOCTURNE — Offline Arcade
+
+NOCTURNE is a premium, private arcade app with **12 playable mini games** across Arcade, Puzzle, and Zen moods. It has no accounts, advertisements, trackers, or runtime dependencies.
+
+## Play locally
+
+Open `index.html` in a modern browser, or serve the directory for the full installable offline experience:
+
+```bash
+python3 -m http.server 4173
+```
+
+Then visit `http://localhost:4173`. After the first visit, the included service worker caches the app shell so the arcade remains available without a network connection. Best scores are stored only in the browser's local storage.
+
+## Included games
+
+Starlight, Pulse Runner, Golden Hour, Tide Pool, Orbit, Sunset Loop, Moon Match, Bloom, Deep Signal, Velvet Dice, Lucid, and Afterglow.
