---
layout: post
title: "Breville Barista Express Steam Wand & Pressure Gauge Fix"
description: "Weak steam, or a pressure gauge that won't hit the espresso range? How to check and fix both on a Breville Barista Express, using the manual."
last_updated: "2026-10-12"
---

Steam wand sputtering, or the pressure gauge sitting low while your shot races through in a few seconds? Both happen on the Breville Barista Express, and here's the reassuring part: most of the time it isn't a broken machine. It's usually a blocked steam tip or a grind that's drifted. Let's take them one at a time.

I use this machine too, so I've written this the way I'd explain it to a friend. The steps come from Breville's instruction book for the BES870, the standard Barista Express. If your model has different buttons, check your own manual. Where the book doesn't say something, I'll tell you instead of making it up.

The trouble people bring here is nearly always one of the same two things: a steam wand that's gone quiet, or a pressure gauge that won't sit where it should.

## First, work out which problem you're dealing with

The two sit on different sides of the machine, so they rarely have anything to do with each other.

- **Steam wand:** no steam, weak steam, sputtering, or water where steam should be
- **Pressure gauge:** the needle reads low, reads high, or doesn't move at all during a shot

If your machine won't build any pressure and the water just runs straight through, that's a related but different problem. I'll cover that separately.

## Steam wand: no steam, weak steam, or sputtering

### Give it heat and a purge first

Turn the steam dial to the steam mark and let the machine come up to temperature. Steam comes from the thermocoil, and if the machine isn't hot enough yet, you'll get a weak, watery burst instead of proper steam. That's normal, not a fault.

Once it's hot, purge for a couple of seconds into a jug or over the drip tray before you steam any milk. That clears the condensation sitting in the wand, and it's the easiest fix for sputtering.

{% assign steam_dial_photo = site.static_files | where: "path", "/photo-steam-dial.jpg" | first %}
{% if steam_dial_photo %}
<figure>
<img src="{{ '/photo-steam-dial.jpg' | relative_url }}" alt="Steam dial turned toward the steam setting on a home espresso machine" loading="lazy">
<figcaption>The steam dial in position before purging or steaming.</figcaption>
</figure>
{% endif %}

Then wipe the tip after every single use. Dried milk is the most common reason a steam wand stops steaming, and once it sets inside the hole, steam can't get through.

### If the tip is blocked

Follow the manual here, because the wand gets hot.

1. Turn the steam dial back to its resting position, switch the machine off, and let it cool down.
2. Clear the blocked hole with the pin on the end of the cleaning tool that came with the machine.
3. Point the tip over the drip tray and run steam for a moment to push out anything loose.

If that doesn't clear it, take the tip off. The cleaning tool has a spanner built into it for exactly this. Soak the tip in hot water, clear the holes with the pin, then screw it back on. This routine is part of the everyday steps in our [full cleaning guide]({{ '/how-to-clean-breville-barista-express/' | relative_url }}), if you'd rather see the wand alongside everything else.

### If it still won't steam

Two things left to think about.

Water coming through instead of steam usually just means the machine isn't hot enough, so purge a little longer and give it another minute. If it stays watery while the machine is clearly hot, that's worth a call to Breville Consumer Support.

Weak steam that never picks up can be scale building up inside the machine rather than in the tip. Scale is what descaling removes, and the [descaling guide]({{ '/how-to-descale-breville-barista-express/' | relative_url }}) walks through the cycle step by step. The manual asks for Breville's own descaling powder, and if you need it, the <a href="https://link.amazon/B02YxFxo0" target="_blank" rel="sponsored nofollow noopener">Breville descaling powder on Amazon</a> is the one to use.

## Pressure gauge: reading low, high, or not moving

The pressure gauge isn't warning you that something has broken. It's showing how hard the pump is pushing water through the coffee, so the reading depends on your grind and your dose more than anything else. Change one of those and the needle moves.

That makes the gauge a dial-in tool as much as a fault clue. If you haven't adjusted your grind in a while, the shot itself will usually tell you as much as the needle does.

{% assign gauge_photo = site.static_files | where: "path", "/photo-pressure-gauge.jpg" | first %}
{% if gauge_photo %}
<figure>
<img src="{{ '/photo-pressure-gauge.jpg' | relative_url }}" alt="Pressure gauge on a home espresso machine during a shot" loading="lazy">
<figcaption>A pressure gauge reading during espresso extraction.</figcaption>
</figure>
{% endif %}

### Gauge sitting low, shot running fast

A low needle with a fast, watery shot almost always comes back to the grind.

- Grind finer
- Add a little more coffee to the basket
- Use beans that aren't too old
- Check you've got the right basket in for the dose

### Gauge sitting high, shot dripping or choking

Here the coffee is being pushed too hard, and it's the other way around.

- Grind coarser
- Use a little less coffee

### Gauge that never moves

If the needle doesn't move at all during a shot, that's where it stops looking like a grind problem and starts looking like a machine one. I wouldn't open the gauge up myself. At that point, I'd get in touch with Breville Consumer Support.

If the grinder is also acting up, my [grinder troubleshooting guide]({{ '/barista-express-grinder-not-working/' | relative_url }}) covers the burr and chute issues that can throw everything off. And if the machine keeps asking for cleaning after you've already done it, the [Clean Me light fix]({{ '/breville-barista-express-clean-me-light-wont-turn-off-fix/' | relative_url }}) explains the difference between cleaning and descaling.

## Quick reference

| What you see | Likely cause | What to do |
|---|---|---|
| No steam at all | Dial off steam, or machine not hot yet | Turn the dial to steam, wait for heat, purge |
| Weak or sputtering steam | Condensation, or a partly blocked tip | Purge longer, clear the tip with the pin |
| Steam stops mid-use | Dried milk inside the tip | Cool, remove the tip with the spanner, soak, clear |
| Water instead of steam | Condensation, or not hot enough | Purge longer, check the machine is up to temperature |
| Gauge low, shot fast | Grind too coarse or dose too small | Grind finer, dose a little more |
| Gauge high, shot slow | Grind too fine or dose too large | Grind coarser, dose a little less |
| Gauge never moves | Possible machine fault | Contact Breville Consumer Support |

You can read the steam wand cleaning and gauge notes for yourself in <a class="ext" href="https://www.breville.com/content/dam/breville/us/en/assets/miscellaneous/instruction-manual/espresso/BES870-instruction-manual.pdf" target="_blank" rel="noopener">Breville's BES870 instruction book</a>, in the Care & Cleaning and Troubleshooting sections.

For the rest of the common fixes in one place, browse the [Troubleshooting]({{ '/troubleshooting/' | relative_url }}) hub.
