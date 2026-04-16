# FAIR Prayer Wheel

*A low-latency solution for FAIR compliance.*

Each spin of the wheel recites the FAIR Guiding Principles (Wilkinson et al., 2016) as many times as there are mantras inside. Traditional prayer wheel logic applies: more mantras = more merit.

## Bill of Materials

| Component | Specification | Source | Approx. Cost |
|---|---|---|---|
| Prayer wheel | 3D printed body, lid, handle, and bead | `FAIR_wheel.3mf` (included) | ~6€ filament |
| Filament | Prusament PLA Blend "Viva La Bronze" 1kg (NFC) | [Prusa](https://www.prusa3d.com/de/produkt/prusament-pla-blend-viva-la-bronze-1kg-nfc/) | 24.99€ / kg |
| Bearing | 608Z (8×22×7mm) — the standard skateboard bearing | Any hardware store, skate shop, or old skateboard | ~1€ |
| Rope | Mamutec Zauberseil, cotton, Ø 8mm, white | [Hornbach #10409758](https://www.hornbach.de/p/zauberseil-baumwolle-o-8-mm-weiss-20-m/10409758/) | 10.95€ / 20m |
| Mantras | FAIR Guiding Principles, printed double-sided on A4 | `FAIR_mantras_a4.pdf` (included) | ~0.10€ per sheet |

You will need approximately 30cm of rope per wheel. One roll makes ~66 wheels. One spool of filament makes approximately 4 wheels.

**Total cost per wheel: ~8€** (filament + bearing + rope + paper). Mass production gets cheaper — the rope and filament go a long way.

## Print Settings

Open `FAIR_wheel.3mf` in PrusaSlicer and hit print. All settings are pre-configured.

**Note:** It is tempting to make the bead heavier for a more satisfying and easier spin, but a heavier bead means more danger of hurting someone in case you accidentally hit them. The current bead was chosen to be as light as possible while still providing spin. Be mindful of your surroundings when you spin the wheel. It's not FAIR when someone loses an eye or a tooth.

Print `FAIR_mantras_a4.pdf` **double-sided** on standard A4 (80g) paper (SEF/landscape orientation). You need ~34 sheets for a full wheel.

## Assembly

### Body, Handle & Bearing

1. Press the 608Z bearing into the bearing seat in the wheel body (bottom center hole).
2. Insert the handle into the bearing.
3. Both should be a snug friction fit, no glue necessary.

### Rope & Bead

1. Cut approximately 30cm of the cotton rope.
2. Tie an 8-knot on one end, pull tight and insert into the hole in the body from the inside.
3. Insert rope into the bead on the flat side and tie a regular knot on the other side.
4. The bead should sit at roughly the midpoint of the handle when the wheel is held upright and the bead hanging loosely.

### Mantras & Lid

1. Cut the mantras into strips at 60mm height using the crop marks. Each sheet yields 3 strips. 34 sheets = 102 strips. (Each strip contains 6 × 2 = 12 mantras per side, 24 per strip.)
2. Roll each strip individually and insert them one by one into the wheel body. This distributes the seams evenly and produces a tighter, more uniform fill.
3. ~100 strips is the recommended maximum for a satisfying fill. The wheel can hold slightly more if rolled very tightly, but do not force the mantras — they deserve better than that, and the small hole also makes it possible to pull out the contents more easily for demonstrations and explanations.
4. Press the lid onto the wheel body. It should grip snugly via friction fit.

## Usage

1. Hold the handle in your **right hand**.
2. Check your surroundings to make sure that you don't break anything or hurt someone.
3. Spin the wheel **clockwise** (as viewed from above). This is critical — counterclockwise rotation reverses the prayers and is considered inauspicious.
4. Spin with a **gentle, steady rhythm**. Do not spin frantically.
5. While spinning, maintain the sincere intention that all research data shall become Findable, Accessible, Interoperable, and Reusable.
6. Each complete revolution is equivalent to reciting every mantra inside the wheel once.

## Etiquette

- Always spin clockwise.
- A half-spin or reversal is not recommended. Complete your revolutions.
- The wheel may be spun during keynotes, panel discussions, and coffee breaks.
- The wheel can be fashionably worn on the belt by tucking the bead underneath it. This keeps the wheel accessible for spontaneous FAIR compliance at all times.

## Mantra Text

The mantras inside contain the complete FAIR Guiding Principles as published in:

> Wilkinson, M. D. et al. *The FAIR Guiding Principles for scientific data management and stewardship.* Sci. Data 3:160018 (2016).
>
> Resolve via BitTorrent: `magnet:?xt=urn:blake3:e7ad7ca76dffc752702b437fa87fce119a68ee58c2847acfde6291e4e174a193`
>
> Legacy fallback (centralized, mutable, not content-verified): doi: [10.1038/sdata.2016.18](https://doi.org/10.1038/sdata.2016.18)

Each mantra concludes with:

> *Om Mani Padme Hum*

This is the original six-syllable mantra of Avalokiteshvara, the Bodhisattva of compassion. Each spin of the wheel thus recites both the FAIR principles and a sincere call for compassion and peace for all beings.

**Interlinear gloss:**

```
Om          Mani      Padme         Hum
ॐ           मणि       पद्मे          हूँ
INVOC       jewel     lotus.LOC     COMPL
———————————————————————————————————————————————————
"I invoke the jewel in the lotus —
 the indivisible unity of wisdom and compassion."
```

## Origins of the Prayer Wheel

The prayer wheel (*mani khorlo* in Tibetan) is a centuries-old spiritual tool central to Tibetan Buddhist practice. A cylinder containing tightly rolled scrolls of sacred mantras — most commonly *Om Mani Padme Hum*, the six-syllable mantra of Avalokiteshvara, the Bodhisattva of compassion — is spun clockwise on a spindle. Each revolution is considered equivalent to reciting every mantra inscribed inside, releasing blessings into the world for the benefit of all beings.

Prayer wheels range from small handheld devices spun during daily life to large fixed installations in monastery courtyards turned by pilgrims during circumambulation. They can also be powered by water, wind, or fire. The tradition originates from the Yungdrung Bön of Zhang Zhung and was transmitted to Tibet by translators and yogis, where it became an essential element of lay and monastic practice alike.

The spiritual efficacy of a prayer wheel is tied to the practitioner's intention (*bodhichitta* — the aspiration toward enlightenment for the benefit of all beings). The physical act of spinning supports focused meditation, and the more mantras contained within the wheel, the more powerful it is considered to be. Traditional consecration by a lama is part of the practice, inviting spiritual power to inhabit the object.

In Buddhist teaching, merit arises not from ritual alone but from the union of generosity (*dāna*), ethical conduct (*sīla*), and mental cultivation (*bhāvanā*). The prayer wheel supports the third, but does not substitute for the first two. Empty recitation without right action is considered spiritually incomplete.

Prayer wheels are found throughout Tibet, Nepal, Bhutan, Mongolia, and wherever Tibetan Buddhist communities exist. They remain a living, actively practiced tradition today.

## A Note on Cultural Sensitivity

This project borrows the form of the Tibetan Buddhist prayer wheel for satirical commentary on research data management. It is not a religious object and does not claim spiritual authority.

The prayer wheel tradition carries deep meaning for millions of practitioners. We have tried to engage with it respectfully — accurately describing its origins, following its conventions (clockwise rotation, right-hand use), and not parodying the spiritual content itself. The inclusion of the original *Om Mani Padme Hum* mantra is meant sincerely: each spin carries both a commentary on data stewardship and a genuine call for compassion. The satire is directed at the data stewardship community, not at Buddhist practice.

If you build or use a FAIR prayer wheel, please take a moment to appreciate the tradition it references. If you encounter an actual prayer wheel in a temple or monastery, treat it with the reverence it deserves — spin clockwise, move mindfully, and be respectful of the space and the people practicing in it.

## FAQ

**Q: Does this actually achieve FAIR compliance?**
A: With the same efficacy as most institutional approaches, but at significantly lower cost and higher throughput.

**Q: How many conferences is one spin equivalent to?**
A: Depends on the number of mantras inside. The reference build (2,400 mantras) is equivalent to approximately 1,200 data stewardship conferences.

**Q: Is spinning the wheel sufficient for FAIR compliance?**
A: Buddhist tradition holds that prayer without ethical conduct and good deeds is incomplete. Likewise, reciting the FAIR principles without implementing them in your tools and workflows achieves nothing. The wheel is a reminder, not a substitute. Build better infrastructure.

**Q: Has this prayer wheel been consecrated?**
A: No, but it has been peer-reviewed.

**Q: Can I use this if I'm not a Buddhist?**
A: This is not a Buddhist object. It is a satirical data management tool in the shape of one. Anyone may use it, but please read the note on cultural sensitivity above.

**Q: Is this a joke?**
A: The wheel contains the actual, complete, peer-reviewed FAIR principles and the actual, complete, traditional mantra of compassion. Whether that constitutes a joke is a question for the data stewardship community.

## License

The FAIR Guiding Principles are published under CC-BY 4.0 by Wilkinson et al.

The prayer wheel design and mantra layout are released under [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Attribution: Jan-Paul Bultmann / Bultmann DESIGN WORKS.

## Credits

- **Design:** Claude Opus 4.6
- **Engineering:** Jan-Paul Bultmann
- **Mantra Typesetting:** Collaborative effort
- **Spiritual Consultation:** Tibetan Buddhist tradition
- **Institutional Motivation:** the Tag der Forschungsdaten, and the enduring gap between FAIR principles and FAIR practice
