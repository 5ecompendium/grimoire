# Grimoire

Grimoire is a searchable, mobile-friendly 5e spellbook that organizes spells by class and level.

See the latest compiled build here: [https://5ecompendium.github.io/grimoire/](https://5ecompendium.github.io/grimoire/)

Grimoire is forked from [thebombzen/grimoire](https://github.com/thebombzen/grimoire/).

## Structure
Spells can be found inside `_spells/`. Each spell gets its own post, written and stored as a [Markdown](https://daringfireball.net/projects/markdown/basics) file.

To add spells, make a new file inside `_spells/` for each new spell, and copy the formatting from another spell.

To add tags, make a new file inside `_tags/` for each new tag, and copy the formatting from another tag.

## Build Instructions
If you've got [Jekyll](https://jekyllrb.com) set up locally, the following should create the build from your friendly command line terminal:
`jekyll serve`