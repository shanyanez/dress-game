# Notes

This file keeps track of what has been done on the dress game and what comes next.

## Asked for by Nez

- Let people pick any color they like, in addition to the ready-made thread spools.
  Keep the spools, and add a way to choose a custom color (for example a spool you can
  dye any shade). It should fit the sewing-room look. (Done 2026-11-14, in the preview.)

## Done

- 2026-11-12: You can now color the bodice, skirt and trim separately. Small tags above the
  spools choose which part the next color lands on. Checked in a test render (blue skirt,
  plum bodice, gold trim). This is in the preview copy (next/index.html), not the live page yet.
- 2026-11-14: Added a "dye your own" spool at the end of the thread rack. It starts as plain
  undyed cotton with a little drop of dye drawn on it; tapping it opens the phone's or computer's
  own color picker, and the spool takes on that shade and throws it at whichever part is chosen.
  Checked in test renders on a desktop-sized and a phone-sized screen: a custom green landed on
  just the skirt and the gown still looks right. On phones the spool is at the far end of the
  rack, so you scroll the rack sideways to reach it (same as the last few spools already).
  Preview only, not live yet.
- 2026-11-16: Four necklines to choose from: Sweetheart (the original), Straight, V-neck and Boat neck.
  They are picked with little tissue-paper pattern pieces pinned down the left side, each cut in
  the shape of the bodice front with its neckline along the top. The ruffle follows whichever
  neckline is chosen, and colors already thrown on the bodice stay put when you switch. Checked in
  test renders (V-neck and Boat neck up close, and a phone-sized screen, where the patterns sit
  small on the wall to the left of the dress). Preview only, not live yet.
- 2026-11-16 (later, Nez asked for it right away): Sleeves or straps. A second column of pattern
  pieces next to the necklines: Bare, Straps (thin ribbons over the shoulders that tuck under the
  bodice front and back) and Puff sleeves (gathered puffs sitting just off the shoulder, since the
  form has no arms). They're cut from the same cloth as the bodice and take the bodice's color.
  Checked in test renders: straps and puffs up close, V-neck with straps in velvet, and puffs on a
  phone-sized screen. Preview only, not live yet.

- 2026-11-17: Skirt shapes. A third column of pattern pieces (little flat skirt panels) picks
  Ball gown (the original), A-line (straight sides that flare evenly to the floor) and Tea length
  (a shorter, softer bell that stops at mid-calf). Underneath, each one changes the hoops the cloth
  hangs on and how long the cloth is cut; when you switch, the skirt gets a quick shake so it falls
  fresh over the new shape instead of landing in crumpled flaps. Checked in test renders: all three
  shapes in satin, the A-line in velvet from the side, tea length in tulle on a phone-sized screen,
  and clicking from A-line to tea length to ball gown in a live browser with no errors.
  Preview only, not live yet.

- 2026-11-19: Fabric prints. A row of little carved wooden printing blocks sits under the fabric
  samples (on phones they stand in a column at the top right): Plain, Stripes, Dots and Florals.
  The print is stamped over whatever color the cloth is dyed, so it always takes on the dress's own
  shade: stripes are a darker band with cream threads either side (ticking), dots are cream polka
  dots, and florals are small cream flowers with dark hearts and leaves. It goes on the bodice,
  skirt, straps and sleeves; the trim stays plain. The skirt is now laid out as 16 tall panels for
  the print, like a real gown, so the print runs straight down each panel instead of twisting round
  the skirt (stripes meet in soft chevrons at the seams). The plain dress looks the same as before.
  Checked in test renders: dots and florals on the ball gown, stripes on the A-line from the side,
  florals on velvet with puff sleeves, dots on a phone-sized screen, and clicking through the blocks,
  skirts and cloths in a live browser with no errors. Preview only, not live yet.

- 2026-11-21: Bows, the first decoration. Two new notions sit under the sewing buttons (on phones,
  under the printing blocks): a ribbon Bow and a seam ripper called Unpick. Pick up the bow and a tap
  on the dress ties a bow there instead of throwing color; tap the bow again to put it down. Unpick
  takes all the bows off. Bows are cream satin, the same ribbon as the waist sash, so they go with
  any color. Each bow is tied to its spot on the cloth, so it swings with the skirt when it twirls and
  stays put when the neckline or skirt shape changes. Checked in test renders (a row of bows on satin
  and velvet from the front, tulle A-line from the side, a phone-sized screen) and by clicking in a
  live browser (tie, twirl, unpick) with no errors. Preview only, not live yet.

- 2026-11-23: Cloth-covered buttons. A little card of buttons now sits between the Bow and the seam
  ripper. Pick it up and each tap on the dress sews on a small domed button (tap the card again to put
  it down; picking up the bow puts the buttons down and the other way round). The buttons are covered
  in the trim's cloth, so they always match the ruffle and change color whenever the trim is redyed.
  Like the bows, they ride along with the cloth when the skirt moves, and Unpick now takes off bows and
  buttons together. Checked in test renders (a row down the bodice front in satin and velvet up close,
  buttons and bows together from the side, a phone-sized screen) and by clicking in a live browser
  (sew buttons, switch to the bow, tie one) with no errors. Preview only, not live yet.

- 2026-11-25: Lace trim. A little card wound with scalloped lace sits between the Buttons and the seam
  ripper. Pick it up and a tap on the skirt lays a band of ivory lace all the way round at that height
  (a plain heading with eyelets, a fine net with a small flower in each scallop, and a picot edge). Tap a
  band again to take it off; Unpick takes off the lace along with the bows and buttons. Up to six bands.
  Each band is laid over the cloth every frame, so it folds and swings with the skirt and follows it when
  the skirt shape changes. Lace goes on the skirt only (the bodice already has its ruffle). Checked in test
  renders (a band halfway down and one at the hem in satin from the front, velvet with dots from the side,
  tulle A-line on a phone-sized screen) and by clicking in a live browser (pick up the lace, lay two bands,
  twirl, unpick) with no errors. Preview only, not live yet.

- 2026-11-25 (later, Nez asked for it): Real-feeling cloth, twirling by hand, and a sparkle trail.
  Nez shared a screen recording of a dress whose cloth looked real and asked for ours to feel like
  actual fabric instead of plastic. What the recording shows: layers of sheer cloth you see through to
  each other, long soft folds that wind into spirals as it spins, a hem that trails behind and flares,
  no hard white shine anywhere, and fine glitter. Ours looked like plastic mostly because of white
  shiny highlights and a clear-coat layer. Changes, all in the preview:
  - Every cloth now has a tiny woven surface (long threads on satin, uneven slubs on silk, a crinkle
    on chiffon, a pile on velvet), so light breaks up across it like real thread.
  - The soft glow on the cloth takes the dye's own color instead of white, and highlights are half
    tinted too. Satin glows in long soft bands along the folds; silk has a liquid shimmer; velvet is
    deep and dark face-on and glows a lighter shade of itself at the edges, with no shine.
  - Chiffon and tulle are more see-through face-on and turn thick and milky where they curve away,
    like real sheer layers. The clear-coat and the glitter on satin, silk and velvet are gone (tulle
    keeps its glitter, chiffon a hint).
  - Each cloth moves more like itself: chiffon floats and settles slowly, silk pours and catches the
    breeze, velvet and sequins swing heavily with their own weight.
  - Grab the dress and drag sideways to spin it by hand (mouse or finger); let go and it keeps turning
    and slows down. Dragging beside the dress still looks around the room. The Twirl button still works.
  - A trail of tiny soft twinkles (ivory, blush and pale blue) follows the mouse, or a finger while dragging.
  Checked in test renders side by side with the old version for satin, silk, chiffon, tulle, velvet and
  sequins, and in a live browser (hover trail, grab-and-fling spin) with no errors. Tulle is better but
  still flatter than the recording; a next step could be giving it real separate layers with their own folds.

- 2026-11-25 (later again, Nez asked: "ours looks flat and boring", with a second recording): Dimension.
  What made the recording's dress feel full and real, and ours flat: their hem stops at the floor so the
  skirt stays a round dome, while ours was cut long and a ring of cloth lay flat on the floor; their cloth
  is much wider than the hoops so it gathers into deep folds with shadow inside them; it puffs out right
  below the waist instead of starting as a cone; and its sheer layers move separately, trailing each
  other when it spins. Changes, all in the preview:
  - The ball gown is cut to just brush the floor (so the hem can swing up when it twirls) and the hoops
    puff out sooner below the waist, so the skirt is round and filled.
  - The cloth is cut a third to two thirds wider than the hoops, and the hoops are fluted more deeply,
    so the skirt hangs in deep folds.
  - The hollows between folds are shaded darker and the crests a touch lighter, worked out every frame,
    so the folds read even on plain satin and keep moving as it swings.
  - The layers under chiffon and tulle hang slightly turned from each other, so you see folds at
    different depths through the sheer cloth, and when it spins each layer trails further behind.
  Checked side by side with the old version (satin, tulle, velvet), A-line in silk, tea length in
  chiffon, tulle spinning on a phone-sized screen, and a live grab-and-fling in a browser with no
  errors. While it's flung hard the very bottom edge (the petticoat frill) gets a bit ragged for a
  moment before it settles; that could be smoothed next.

## Next ideas

1. Save a dress and share it as a link (include the neckline, sleeves, skirt shape, print, the dyed shade, the lace bands and where the bows and buttons are)
2. A "take a picture" button
3. Maybe let bows and lace take the chosen thread color too, instead of always ivory
4. Maybe more prints later (gingham, a bigger rose print), or printing just the skirt or just the bodice
5. Maybe more sleeve styles (flutter sleeves, a halter strap) and skirts (mermaid, high-low hem)
6. Maybe a gentler change between necklines (it swaps instantly right now)
