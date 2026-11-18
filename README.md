# RoninRhythm

Dance instruction, DJ sets and music production from a nomadic partner dancer: Bachata, Kizomba and Fusion, plus Bachazomba and Kizchata, my own blend of the two. Some Salsa and Zouk too.

A [RoninSec](https://r0n1n9.github.io/roninsec/) brand. Live at https://r0n1n9.github.io/roninrhythm/

Single static `index.html`, no build step. `.nojekyll` tells GitHub Pages to serve it as-is.

## Editing links

The `CONFIG` block at the top of the script in `index.html` holds the booking email, Instagram handle, RoninSec link and the **Sway** link. Paste Sway's live URL into `swayUrl` and the "Find events" section switches from "In development" to a live "Open Sway" button.

## Booking form

The form emails bookings to you through a form service, since GitHub Pages can't send email itself.

1. Sign up at [Web3Forms](https://web3forms.com) (or [Formspree](https://formspree.io)) with the inbox you want bookings sent to.
2. Paste the Access Key (Web3Forms) or form ID (Formspree) into `formKey` in `CONFIG`, and set `formService` to match.

Until `formKey` is set, or if a send fails, the form shows an **Open in email** button with the message ready to send, plus **Copy message**.
