# Dirt-samples

- any `*k` suffix folder will contain kicks
- any `*s` suffix folder will contain snares
- any `*h` suffix folder will contain hats
- any `*p` suffix folder will contain percs
- any `*f` suffix folder will contain foleys or various noises
- any `*c` suffix folder will contain claps

Made for my own use + 2Mo with Tidalcycles / SuperDirt, but feel free to use them

Usual and painless location on a Debian or \*ubuntu derivative  is `~/.local/share/SuperCollider/downloaded-quarks/Dirt-Samples/`, increase the buffer and memory size in your SuperCollider startup file or SuperDirt options, if needed

Most likely stereo, 44.1 KHz 16 bit, fits your hardware sampler if needed

# [`tidal-autocode`](https://github.com/kindohm/tidal-autocode) 
- If you plan to use the [_**tidal-autocode**_](https://github.com/kindohm/tidal-autocode) Atom package, here's a snippet I paste in `Packages > Tidal Autocode > Settings > Samples` (adapt to your own samples, see below) :

> `31, 626, 808, 909, ac, af, ag, ah, ak, amencutup, aol, ap, as, atm, b, bag, bass1, bass3, bass4, basss, bbss, bc, bf, bh, bin, birds, birds3, bk, bm, bottle, bp, brb, breaks125, breaks152, breaks157, breaks165, breaks175, brf, broh, brok, brop, bros, brp, bs, bt, can, cf, ch, ck, claps, clic, comb, cp, crow, cs, d, dc, df, dh, dk, donk, dp, ds, dt, eau, el, ex, foleyperc, future, gbass, glasso, grcm, grcp, grh, grk, grprc, grsn, hats, hhh, hits, hold, hoover, if, ifdrums, impact, impacts, jpnperc, jungbass, jungle, junk, k, kicks, kusa, l, layer, meca, moto, nice, notif, odx, pad, pads, percs, pl, pm, pp, prof, ps, psr, r0, r1, r2, rave, rave2, rave3, ravebreaks, repetition, rs, rst, s, sbreaks, scapes, sd, sfx, shout, sine, snares, sphere, stab, stabs, stomp, strings, sub, t, tables, tc, tcp, temph, tempk, tempp, temps, tempt, tf, tk, tn, toms, tp, ts, tv, ugclap, ugcrash, ughat, ugkick, ugslam, ugsnare, v1, v2, v3, v4, v5, vk, win, xcp, xcy, xh, xk, xs`

- A basic trick is to create a .txt file from a rep in CL:

> `$ ls ~/.local/share/SuerCollider/downloaded-quarks/Dirt-Samples/ > ~/Location/Filename.txt`

Then edit it in Atom: from the second word, select all (`Ctrl + A`), go to `Selection > Split into lines`, go to `Selection > Select to beginning of line`, type a comma and a space, go to `Selection > Select to beginning of line` again (or this time you could use the Page begin button), delete the line return so that you get a huge text line, compoare to the formatting above, and voilà.
