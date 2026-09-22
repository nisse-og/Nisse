STUDY NISSE — CLEAN WEBP ANIMATION TEST

This is a TEST package. Do not upload it to GitHub yet.

Root cause found:
The clean source animations are transparent RGBA WebPs. The later WebM conversion dropped the alpha channel. The visible rectangular/colored corruption was introduced in that conversion, not in the original animation drawings.

This test deliberately uses the clean RGBA WebP assets directly and removes the Canvas/video rendering path for the Study scene.

Files:
- index.html
- study_loop_clean.webp
- page_turn.webp
- head_tap.webp
- head_return.webp
- one_hour.webp
- hour_return.webp

All seven visual assets are the clean animation material; the study loop is a ping-pong rebuild of the clean study animation so its loop boundary returns to the starting frame.

The current GitHub repository is NOT modified by this package.
