<img src="logo.svg" alt="ChemTrain logo" height="110" align="right">

# Reactivity Learn

Reactivity Learn is a Quizlet-style trainer for nucleophilicity, electrophilicity, regioselectivity, radical philicity and redox potentials in organic chemistry, built on Mayr's reactivity scales and on published electrochemical data. Everything is in one HTML file.

**Play it here:** https://chemtrain.github.io/reactivity-learn/reactivity_learn.html

You can also download `reactivity_learn.html` and open it in any browser.

## What's inside

- 240 cards in 11 sets: 175 nucleophiles with their N and s<sub>N</sub> (π-nucleophiles, amines and N-heterocycles, phosphines and ylides, hydride donors, carbanions, anions in DMSO and in MeCN, nucleophiles in water) and 65 electrophiles with their E (carbocations and iminium ions, Michael acceptors, heteroatom electrophiles)
- 143 redox cards in 6 sets: metal photocatalysts (Ru, Ir and Cu, each with its excited- and ground-state potentials), organic photocatalysts (acridinium, 4CzIPN, eosin Y and others), reagents and metal couples (metallocenes, magic blue, amines, Hantzsch ester, halides, iodine(III), nickel and copper), substrates to oxidise and to reduce, and textbook standard potentials in water; shown vs SCE or, with one click, vs Fc⁺/Fc
- A 2D structure for each molecule, with the atom that attacks, or is attacked, highlighted; metal complexes drawn with their ligands fanned around the metal
- Learn: give the N, E or redox potential of each card (multiple choice, then typed), or name the molecule or couple that has a given value; cards are mastered after two right answers in a row
- Rank: deal 5, 10 or 15 cards from a set and put them in order of N, E or potential; nucleophiles and potentials are only compared within one solvent
- Most reactive: 38 molecules with two to four labelled atoms; pick the one that attacks, or is attacked by, the named partner
- Reacting?: a nucleophile and an electrophile, and Mayr's rule of thumb (N + E > −5 at 20 °C); the answer works out log k = s<sub>N</sub>(N + E) and the half-life. In Electron transfer mode: a donor and an acceptor (photocatalysts, reagents, substrates); is the electron transfer downhill?
- Photoredox: 18 published reactions (which quenching cycle, or energy transfer?), plus generated questions on which photocatalyst can both oxidise one substrate and reduce another, and which partner turns the catalyst over
- Regioselectivity: 70 questions on aromatic substitution, additions to alkenes and alkynes, radical additions and hydrogen-atom transfer (Minisci, Giese), enolates and carbonyls, epoxide opening and eliminations, and the protection, deprotection and oxidation of primary, secondary and tertiary alcohols
- Radicals: is a radical nucleophilic or electrophilic? 29 carbon- and heteroatom-centred radicals, each with the reason, and 12 polarity-matching questions (which of two partners a radical reacts with faster)
- Flashcards, a browsable list of cards, and a Theory page: how N, s<sub>N</sub> and E are measured, how to read them, ambident reactivity, the conceptual DFT indices (μ, η, ω and Domingo's N) computed from HOMO and LUMO energies, radical philicity, redox potentials (E½ and Eₚ/₂, reference electrodes, excited-state potentials, ΔG of electron transfer) and photoredox cycles, with references
- Easy and Hard levels: compared values are at least 2.5 units (0.5 V) apart on Easy and 1 unit (0.2 V) on Hard, and Easy leaves out the harder Most reactive, Regioselectivity, Radicals and Photoredox questions

## Sources

Every N, s<sub>N</sub> and E value comes from [Mayr's Database of Reactivity Parameters](https://www.cup.lmu.de/oc/mayr/reaktionsdatenbank/) (LMU München). Each card names its database entry and the paper the value was published in; please cite those papers when you use the values, as the database asks. Only entries rated two stars or more are used.

Redox potentials come from J. K. Prier, D. A. Rankic, D. W. C. MacMillan, *Chem. Rev.* **2013**, 113, 5322 (photocatalysts, Table 1, and quoted values); H. G. Roth, N. A. Romero, D. A. Nicewicz, *Synlett* **2016**, 27, 714 (half-peak potentials of substrates and reagents, from its Supporting Information); N. G. Connelly, W. E. Geiger, *Chem. Rev.* **1996**, 96, 877 (metallocenes, magic blue and the ferrocene offsets); the standard potentials tabulated on Wikipedia; and primary papers named on each card. The photoredox questions follow the papers they cite.

The site and regioselectivity questions and their explanations were written for this app; the explanations of ambident reactivity follow H. Mayr, M. Breugst, A. R. Ofial, *Angew. Chem. Int. Ed.* **2011**, 50, 6470. The radical philicity questions follow F. Parsaee, M. C. Senarathna, P. B. Kannangara, S. N. Alexander, P. D. E. Arche, E. R. Welin, *Nat. Rev. Chem.* **2021**, 5, 486 ([doi:10.1038/s41570-021-00284-3](https://doi.org/10.1038/s41570-021-00284-3)). The Theory page lists its references. Structures are drawn with [RDKit](https://www.rdkit.org).

## How to cite

If you use Reactivity Learn in a course, a worksheet or a paper, please cite it:

> Bindschaedler, Q. *Reactivity Learn* (2026). ChemTrain. https://github.com/ChemTrain/reactivity-learn

GitHub's **Cite this repository** button (from `CITATION.cff`) gives the same reference in APA and BibTeX.

## License

- Code (the HTML, CSS and JavaScript): [MIT](LICENSE).
- Content (the selection of cards, the questions, notes, explanations and Theory text): [CC BY 4.0](LICENSE-CONTENT.md). You may reuse and adapt it, as long as you credit Reactivity Learn.
- Logo (`logo.svg`): the locomotive is adapted from [Twemoji](https://github.com/jdecked/twemoji), © Twitter, Inc and other contributors, licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/); the benzene-ring smoke was added for ChemTrain.

The N, s<sub>N</sub> and E values and the redox potentials are measurements published by others; please cite their sources as well.
