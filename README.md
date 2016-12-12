The 3e core Charms chapter has 116000 words, 784 charms.

You may wish to use this version instead. It weighs in at 47000 words, 557 charms. Consider it a complete replacement for chapter six and part of seven.

This project is ongoing! Feel free to hop into the [forum thread|http://forum.theonyxpath.com/forum/main-category/exalted/804702-how-i-wish-charms-were-written] or the issue tracker here. Did I cut your favorite charm? Is the wording unclear? Have an awesome new idea for a charm?

With this rewrite I hope to:

- Clarify rules and standardize terminology. You should always be able to tell, at a glance, the mechanical effect of a charm. These are, above all, rules widgets, and they're presented that way.
- Remove non-charm dice and speed bumps. There are so many ways to add non-charm dice in the basic rules that they hardly feel special anymore. There are also charms that do basically nothing other than provide a discount on the excellency in a certain situation.
- Remove stunting from charm texts. Some people will disagree with this approach, but I've aimed for dry, clear, simple language which tells you what happens, rather than what it looks like. Different characters will use the same charms in different ways.
- Remove unthematic charms. Solars do not mess with fate, they do not inhabit clone bodies, they do not cause natural disasters by research.
- Shorten the chapter. The charm descriptions are generally 1/2 to 1/5th the original length.
- Being a queer woman myself, I have experience with some of the issues around gendered language, but in this case I've preferred brevity and clarity over gender-neutrality. The Solar is still always referred to as she/her, everyone around her as he/him/they. (if you want to refer to me, she/her is good, thanks )

Feedback is welcome. This is, however, an opinionated rewrite - I will not spend much time arguing over my opinions about what is Solar and what I want from the charms chapter.

## Full book or house rules?
This project can be compiled in two ways: as a standalone housrule supplement, or as a complete sourcebook.

As a standalone supplement - which is the version included here as Charms.pdf - the PDF contains references to Ex3 page numbers for several house rule alterations, and then a full rewrite of the charms chapter. Sorry for the strange PDF bookmarks, I had trouble getting it to conditionally include bookmarks at compilation time.

As a complete sourcebook, it is a complete rulebook, which can be handed to players who have never played Exalted before, or used as a table-top reference. Since this version copies hundreds of pages from the Ex3 corebook, it is not distributed in this repository - you'll have to compile it yourself.

## Compiling
You can probably make this work on any operating system using broadly similar steps. On linux:

1. Install latex + xeletex. On a debian-based linux: `$ sudo apt-get install texlive-latex-extra texlive-xeletex pdftk`
2. Install the fonts under resources/ on your system.
3. OPTIONAL: If you want a "full book", place your Ex3 book here - `cp /path/to/Ex3 ./Ex3Final.pdf`
3. The charmTrees/*.pdf files can be rebuilt using Inkscape or another svg editing program. Open the corresponding .svg file and export it as a pdf of the same name. Don't rasterize anything.
4. Building Charms.pdf is simple: `xelatex -halt-on-error Rewrite.tex`
5. Build it a second time, exact same command as the first. This will add the pdf bookmarks.

6. OPTIONAL: If you're editing things a lot, it may be helpful to have the pdf automatically recompile. `while inotifywait -e attrib Charms.tex; do xelatex -halt-on-error Charms.tex; done` This may not work for people using systems other than mine, so no promises.

## Charm Cards
Making charm cards for a character is simple. Copy any charms the character has from Charms.tex or MAcharms/* into CharmCards.tex (near the bottom there is a location shown), then compile it. `xelatex -halt-on-error CharmCards.tex`. This outputs CharmCards.pdf - there you go!

## Credits

- Sanctaphrax: large amounts of feedback and editing, many of the Craft charms, and God-General's Command in War.
- Irked: the excellent Irked Reads thread on the Onyx Path forums, and an inspirational post over on RPG.net.
- Chejop Kejak: much feedback.
- SaintedPhysician: Glorious General's Charge and Golden Army of the Sun-King in War.
- oohprincediamond: Hell-Conquering Legion Spirit in War
