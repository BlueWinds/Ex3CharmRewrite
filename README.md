The 3e core Charms chapter has 116000 words, 784 charms.

There are two versions of this rewrite:
- "master", which you're looking at now. It is rather close to Ex3 core, though cleaned up withmore precise language and removing some problematic charms. It weighs in at 47000 words, 557 charms.
- ["no-dicetricks"](https://github.com/BlueWinds/Ex3CharmRewrite/tree/no-dicetricks). It weighs in at 31000 words, 319 charms. It is quite different from Ex3 core - it cuts each ability down to 11-13 charms, almost all of which provide *new capabilities* rather than *enhancing dice rolls.* It also contains several other house rules you may wish to use.

With this rewrite I hope to:

- Clarify rules and standardize terminology. You should always be able to tell, at a glance, the mechanical effect of a charm. These are, above all, rules widgets, and they're presented that way.
- Remove non-charm dice and speed bumps. There are so many ways to add non-charm dice in the basic rules that they hardly feel special anymore. There are also charms that do basically nothing other than provide a discount on the excellency in a certain situation.
- Remove stunting from charm texts. Some people will disagree with this approach, but I've aimed for dry, clear, simple language which tells you what happens, rather than what it looks like. Different characters will use the same charms in different ways.
- Remove unthematic charms. Solars do not mess with fate, they do not inhabit clone bodies, they do not cause natural disasters by research.
- Shorten the chapter. The charm descriptions are generally 1/2 to 1/5th the original length.
- Being a queer woman myself, I have experience with some of the issues around gendered language, but in this case I've preferred brevity and clarity over gender-neutrality. The Solar is still always referred to as she/her, everyone around her as he/him/they.

Feedback is welcome. This is, however, an opinionated rewrite - I will not spend much time arguing over my opinions about what is Solar and what I want from the charms chapter.

## Compiling
You can probably make this work on any operating system using broadly similar steps. On linux:

1. Install latex + xeletex. On a debian-based linux: `$ sudo apt-get install texlive-latex-extra texlive-xetex`
2. Install the fonts under resources/ on your system.
3. The charmTrees/*.pdf files can be rebuilt using Inkscape or another svg editing program. Open the corresponding .svg file and export it as a pdf of the same name.
4. Building Charms.pdf is simple: `$ xelatex -halt-on-error Charms.tex`

## Credits

- Sanctaphrax: large amounts of feedback and editing, many of the Craft charms, and God-General's Command in War.
- Irked: the excellent Irked Reads thread on the Onyx Path forums, and an inspirational post over on RPG.net.
- Chejop Kejak: much feedback.
- SaintedPhysician: Glorious General's Charge and Golden Army of the Sun-King in War.
- oohprincediamond: Hell-Conquering Legion Spirit in War
