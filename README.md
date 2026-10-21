# Stitch Notebook

A colorwork chart designer for knitters. Draw a fair isle motif square by square, see it as knit stitches, and get a chart sheet you can knit from. There is one more chart hidden inside, and it opens after you finish your own.

Runs in any phone or laptop browser. No account, no app, nothing to install. Your work saves in your browser so you can put it down and pick it back up.

## Open it

https://drewosi.github.io/stitch-notebook/

Or download `index.html` and open it in a browser.

## How to use it

**Design**

1. Pick stitches across and rows. 32 across repeats well on a hat or sock; 60 is a scarf panel. Choose in the round or flat.
2. Tap a yarn in the tray, then tap or drag on the grid to color squares.
3. Tools:
   - **Paint** colors one square at a time.
   - **Fill area** colors a whole connected area, like a paint bucket.
   - **Mirror** paints both halves at once, so symmetrical motifs stay symmetrical.
   - **Show stitches** redraws the grid as knit stitches so you can see the fabric, not just squares.
   - **Undo** steps back. **Clear** wipes the grid.
4. The repeat preview underneath shows three repeats side by side as stitches.
5. When the motif feels done, tap **Finish this chart**.

**Chart sheet**

The chart with row numbers, stitch numbers every five, a color key with stitch counts per yarn, the longest float (catch anything over five), and cast-on math for a hat (four repeats) or socks (two). Below it, every row written out as "3A, 2C, 3A..." in knitting order. Tap **Copy rows** to paste it into your notes.

Screenshot the chart sheet to print it.

**The locked tab**

Finish your own chart and it opens. A second chart knits itself row by row, with a note at the end. Open it as a chart sheet to knit it for real.

## For whoever set this up

The hidden chart and its message live in a block at the top of the script in `index.html`, marked `Personalize here`. Edit `title`, `message`, and the `chart` rows. Each row is a string of characters; `.` `#` `o` map to yarn names in `yarns`. Rows run top to bottom. Keep every row the same length.

Yarn colors and names are in the `YARNS` list right below it.
