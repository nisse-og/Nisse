Nisse Study — WebP animation build

This package contains the offline Study Nisse site and its transparent animated WebP assets.

Files:
- index.html — main app
- study_loop_clean.webp — study loop
- page_turn.webp — page-turn reaction
- head_tap.webp — head-tap reaction
- head_return.webp — return from head tap
- one_hour.webp — one-hour reaction
- hour_return.webp — return from one-hour reaction

Important:
- Keep all files in the same folder.
- Open/deploy index.html as the site entry point.
- The animation layer is hidden while the timer is stopped, so the idle desk does not show a broken-image placeholder.
- Animation URLs are stable so the browser can cache the large WebP files instead of downloading them again for every reaction.

This package has been statically validated (HTML asset references and inline JavaScript syntax). Full device/browser interaction testing still needs to be done on the target phone/browser.
