# Translation completion audit

Audit date: 28 September 2026.

## Scope and result

The [Siku editorial notice](translation/preface.md) and all twelve juan have English translations. The scope is the thirteen textual regions identified in [SOURCE_MANIFEST.json](SOURCE_MANIFEST.json), preserved in the twelve files under `source/`. The completion review found no additional untranslated source passages. Prefaces or supplementary matter unique to other editions have not been imported into this Siku-based translation.

Every nonblank line inside those source regions is accounted for by the translation’s source-reference annotations. Those lines include original headings, commentary, volume labels, and classification text; they are not a count of sentences or independent passages.

| Source region | English file | Nonblank source lines | Unmapped lines | Endnotes |
|---|---|---:|---:|---:|
| Siku editorial notice | [preface.md](translation/preface.md) | 5 | 0 | 13 |
| Juan 01 | [juan-01.md](translation/juan-01.md) | 213 | 0 | 134 |
| Juan 02 | [juan-02.md](translation/juan-02.md) | 261 | 0 | 162 |
| Juan 03 | [juan-03.md](translation/juan-03.md) | 489 | 0 | 147 |
| Juan 04 | [juan-04.md](translation/juan-04.md) | 603 | 0 | 116 |
| Juan 05 | [juan-05.md](translation/juan-05.md) | 178 | 0 | 223 |
| Juan 06 | [juan-06.md](translation/juan-06.md) | 327 | 0 | 207 |
| Juan 07 | [juan-07.md](translation/juan-07.md) | 243 | 0 | 265 |
| Juan 08 | [juan-08.md](translation/juan-08.md) | 1,322 | 0 | 172 |
| Juan 09 | [juan-09.md](translation/juan-09.md) | 1,409 | 0 | 177 |
| Juan 10 | [juan-10.md](translation/juan-10.md) | 346 | 0 | 153 |
| Juan 11 | [juan-11.md](translation/juan-11.md) | 665 | 0 | 221 |
| Juan 12 | [juan-12.md](translation/juan-12.md) | 500 | 0 | 234 |

The complete set contains **2,224 translator’s endnotes**. Each note has a definition and a reference; duplicate definitions and unresolved note references were checked across all thirteen English files.

## Work completed in this pass

The new preface translation includes the classification heading, the editors’ assessment, the dated submission, and all four signatures. Its approximately 500 English words of translated source text are followed by thirteen endnotes. These distinguish textual repairs, bibliographical discrepancies, and the editors’ opinions from the compilation’s own arguments.

Legacy source-reference gaps were reviewed rather than assumed to be translation omissions. In juan one, the sixty-row inventory was already translated under a descriptive marker; the post-inventory discussion and first expanded entry had imprecise line labels, and the translated closing labels lacked a marker. These annotations were corrected. In juan two, twenty-five already translated bilingual headings received explicit line references. No new source prose was needed at those locations.

Outdated preface-status statements were replaced with links to the new translation. The twelve juan’s translated source passages remain unchanged. The only edits within those files are scope metadata, preface navigation/status wording, and the source-reference comments just described. Reversing the recorded maintenance edits reproduces each pre-existing file’s original SHA-256 checksum. All twelve Chinese source files, the source manifest, licence, and glyph assets are unchanged.

## What the checks do not establish

Source-line coverage is a structural check, not an automatic proof that every phrase has been translated without error. This completion pass is not a fresh word-by-word retranslation of the twelve juan or a comprehensive collation against historical facsimiles. The English continues to identify corrupt readings, uncertain interpretations, disagreements between authorities, and genuine gaps in the transmitted source. Such gaps are not filled by invention.

Chinese headings, quoted characters, and names retained beside English explanations are reading and textual-reference aids, not blocks left untranslated. A scan for substantial Chinese passages in the English bodies found the already explained historical stem and branch names in juan one, rather than an untranslated prose section. The Siku editors’ notice has its own voice and is not presented as an authorial preface by Wan Minying.
