# Workflow for Capturing Homeric Quotations

## Set Up

1. Open the [Google Doc listing quotations](https://drive.google.com/folderview?id=0BzbUiC-X1utCNFJ4ckZDejAwMkU&usp=drive_web)
1. Get the Kaibel and Gulick editions of the *Deipnosophistae*.
1. Open the file `draft-ath.xml`.
1. You will probably want to [open the Perseus text of the *Iliad*](http://www.perseus.tufts.edu/hopper/text?doc=Perseus:text:1999.01.0133)
1. Open the [Homer directory in the Github site](https://github.com/OpenGreekAndLatin/DigitalAthenaeus/tree/master/homer)
	- Click to open the file `htr.csv`.

## Find a Homeric Quotation

1. Find the next Homeric quotation on the Google Doc.
1. Note the Causabon page number, and the Homeric citation.
1. Find that Causabon page in Kaibel's and Gulick's editions of Athenaeus. Highlight it on paper.
1. Identify the Homeric quotation.
1. Find the associated passage in the *Iliad*.
1. Compare them. 

## Document

1. Identify the Kaibel citation to Athenaeus.
	- For example, there is a Homeric quotation at (Causabon) 9c.
	- That corresponds to Kaibel 1.16 (cf. p. 20 in Kaibel's printed edition).
1. Find that passage in the file `draft-ath.xml`. 
1. Identify the citation to Homer. 
	- The quotation from Athenaeus 1.16 is at *Iliad* 24.262.
1. **Look carefully at the text of Athenaeus, the Homeric text, and all citations.**
1. On the GitHub site, click to edit file `htr.csv`.
1. Enter data (see below).
1. When you are done, click "Commit Changes". 
1. If the result is not a neat table, you have made a mistake. Fix it.


You will enter four pieces of information, wrapped in quotation marks, separated by commas:

1. ID
1. Athenaeus Citation
1. Text Content
1. Homer Citation

Example of Athenaeus citation:

> `"urn:cts:greekLit:tlg0008.tlg001.berti:1.16@ἀρνῶν[1]-1.16@ἁρπακτῆρες[1]",`

Example of Text Content:

> `"ἀρνῶν ἠδ᾽ ἐρίφων ἐπιδήμιοι ἁρπακτῆρες.",`

Example of Homeric Citation:

> `"urn:cts:greekLit:tlg0012.tlg001.ogl01:24.262"`



