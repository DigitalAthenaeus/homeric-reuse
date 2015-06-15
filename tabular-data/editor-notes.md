# Notes for Editors

## Links

- [GitHub Site](https://github.com/OpenGreekAndLatin/DigitalAthenaeus)
- [Google Doc listing Iliadic Quotations](https://docs.google.com/spreadsheets/d/1rTRbkMAeymckZDqiJwF-hT1ZeVm-QmbHtjRxRJDjtTw/edit?usp=sharing)

## Tasks

- Document Homeric Quotations in Athenaeus.
- Look at and fix the XML text of Athenaeus.

## Notes on Editing

Three columns of data:

1. **ID**. A unique identifier for this instance of Homeric text-reuse. This will be automatically generated anon.
1. **Athenaeus URN**. A CTS URN identifying the precise span of text in question.
1. **Text Content**. The portion of the Athenaeus text, identified above, that is the Homeric text-reuse. This may be the whole of text identifed by the CTS URN, or may be a portion of it.
1. **Homer URN**. A CTS-URN identifying book and line of the Homeric poem quoted or paraphrased.

### Example

| Field | Content |
|-------|---------|
| ID | `urn:cite:digAth:reuse.ih1` |
| Athenaeus Urn | `urn:cts:greekLit:tlg0008.tlg001.berti:1.5@πλεῖαί[1]-1.5@κλισίαι[1]` | 
| TextContent | `πλεῖαί τοι οἴνου κλισίαι` | 
| New Edition Urn | `urn:cts:greekLit:tlg0012.tlg001.ogl01:9.71` |
| Alignment URN | `urn:cts:greekLit:tlg0012.tlg001.perseus-grc1:9.71@πλεῖαί-9.71@κλισίαι` |

## Editorial Principles

- If the Homeric passage is lengthy and intact (like a whole line of the *Iliad*), just define the Athenaeus URN based on its limits.

	> "ἀρνῶν ἠδ᾽ ἐρίφων ἐπιδήμιοι ἁρπακτῆρες"

	> `urn:cts:greekLit:tlg0008.tlg001.berti:1.16@ἀρνῶν[1]-1.16@ἁρπακτῆρες[1]`

- If the Homeric passage is broken, short, or otherwise difficult, if possible include in the Athenaeus URN the text that marks it as "text-reuse". 

	> "**Ἑλλήσποντον** δὲ Ὅμηρος **ἰχθυόεντα** προσαγορεύων" (Homeric words in bold.)

	> `urn:cts:greekLit:tlg0008.tlg001.berti:1.16@Ἑλλήσποντον[1]-1.16@προσαγορεύων[1]`

	> Text-content: "Ἑλλήσποντον ἰχθυόεντα"

- Likewise, if the grammar and syntax of the "reused" text has changed because of context in Athenaeus---e.g. direct speech turned into indirect speech---if possible, the Athenaeus URN should identify the syntactic context of the paraphrase.

	> "οὐκ ἂν γὰρ Ἀχιλλεὺς τὸ ζωρότερον κεραίρειν διέστειλε" (Ath. 1.17) ("Achilles would not have ordered [him] to mix the more pure [wine]…"

	> Homer has Achilles order Patroclus: "ζωρότερον δὲ κέραιε," ("Mix the more pure [wine]!").



