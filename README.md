# The Promised Offspring

![GitHub Release](https://img.shields.io/github/v/release/kreier/promised-offspring)
![GitHub License](https://img.shields.io/github/license/kreier/promised-offspring)

Visualizing the lineage of Jesus, starting with Adam and connecting families and prophecies. Latest versions:

- [English version](latest/en.pdf)
- [German version](latest/de.pdf)

## Motivation

For people of Israel 2000 years ago it was of big importance to trace their family back in a genealogy. This was important to have a part in inherited land, or enjoy certain privileges. For example, after the exile in Babylon the families of _Habaiah_, _Hakkoz_, and _Barzillai_ who could not find their genealogical records. (Ezra 2:61-63, Nehemiah 7:63-65) Because they could not prove their lineage, they were excluded from the priesthood and forbidden to eat the sacred food until a priest could determine their status using the Urim and Thummim.

<img src="history/1x1.png" width="5%"><img src="history/latest.jpg" width="40%"><img src="history/1x1.png" width="5%"> <img src="history/promised_seed_2005.png" width="44%">

Of even greater importance was the lineage of the promised Messiah. He needed to be a son of Abraham, Judah and David. Therefore both Matthew and Luke include a geneaology of Jesus Christ. But if you look at them, you will find some differences. The more details one unveils, the more interesting and connected to world history this lineage becomes. Hence this project to condense and visualize some findings of this study. But first we have to think about size:

## Size consideration

In many digital documents you can zoom in 600%, with Affinity even more. But my goal was a possible printout, and this generates tangable constrains. I tested font sizes and consider 10 pt still to be good readable. The standard line distance is then 12 pt. So how many lines or rows are necessary?

### Account of Luke in 12 pt

The account of Luke lists 75 individuals. If we put each father in one line, we need 75 lines with the height of 12 points.

| from - to          | Luke | Matthew | maternal | legal | TPS1 | TPS2 |
|--------------------|:----:|:-------:|:--------:|:-----:|:----:|:----:|
| Adam - Noah        |  10  |         |    10    |   10  |  10  |  10  |
| Noah - Abraham     |  10  |         |    10    |   10  |  10  |  10  |
| Abraham - David    |  13  |    13   |    13    |   13  |  13  |  38  |
| David - Exile      |  20  |    14   |    19    |   17  |  21  |  34  |
| Exile - Zerubbabel |   2  |    2    |     3    |   3   |      |      |
| Zerubbabel - Jesus |  20  |    11   |    20    |   11  |  11  |  20  |
| sum                |  75  |    40   |    75    |   64  |  65  |  112 |

Matthew only begins with Abraham and describes the paternal or legal side of Jesus lineage. It includes many kings of Judah and has in total 40 persons. The account of Luke starts with Adam and has therefore 20 more names. From Zerubbabel the lineage is significantly longer (20 instead of 11 individuals) and concludes after 75 generations. Another project includes many more extra lines for other children and relatives. This requires an estimated 112 lines for all the information.

One point is 0.3528 millimeter large. 12 points equals 4.23 millimeter and 75 lines require 317.52 millimeter. A4 portrait has a height of 297 mm, A3 has 420 mm.

### Extra space for parent - children lines

I want to include some extra lines to connect parents to their childen. With just 12 pt line height this would be to cramped. I decided to increase the line height to 14 pt. The results can be found in this table:

| number of   lines |  10 pt |  12 pt |  14 pt |  16 pt |
|:-----------------:|:------:|:------:|:------:|:------:|
|         1         | 3.53   | 4.23   | 4.94   | 5.64   |
|         66        | 232.85 | 279.42 | 325.99 | 372.56 |
|         75        | 264.60 | 317.52 | 370.44 | 423.36 |
|         85        | 299.88 | 359.86 | 419.83 | 479.81 |
|        112        | 395.14 | 474.16 | 553.19 | 632.22 |

The new 14 pt line height is good for 85 lines. But we need only 75 for the geneaology of the promised offspring. This leaves room to move content further down if I want to insert some interesting details.

## History of this "The Promised Seed" repository

The motivation came from my old [timeline project](https://github.com/kreier/timeline) here on GitHub, that actually started with some curated HTML files in 2006. Over time it grew to a detailed chart of human history for the last 6000 years. From paper versions, html, OpenOffice spreadsheets, OpenOffice vector drawings to finally a Python program generated PDF of 1208x210 mm (or four A4 papers in landscape).

About the same time others started a related project, but focused on the lineage of Jesus and historic events related to "the promised seed". Their project has the size of 864x1118 mm (34x44 inch) and was created 2002-2005. Its final version looks like this:

<img src="history/1x1.png" width="20%"><img src="history/promised_seed_2005.png" width="60%">

I had heard about this project since 2023, and in 2025 I got a digital copy. But it is not intended to be shared online. Therefore there is only a rather fuzzy image embedded in this repository. 

### November 2025 - Repository for "promised-seed"

So I thought about creating a similar document. The authorship was one consideration. The size was another consideration. The size of 864x1118 is very close to the size of A0 (841 x 1189 mm) and usually the largest size for a print shop. Still some parts are not easy to read. Could I create a smaller version that still would be readable? I certainly had to leave out some information of the original document. 

And I would have to check out the information for myself. Both as a study project, and to import the references in the dictionary files to help later in translations. A broad assumption: If I organize the data better, and leave out both timeline aspects (contemporary part and kings/prophets northern and southern kingdom) I might reduce the needed area to A1. Now reducing the information in the right column and leave out most of first and second generation children of the 12 tribes, getting another 50% and down to A2. Now split some information into two pages (like the two legends, some other large family side tree) and I'm at two A3 papers. Let's check:

### Is it possible to have the family history of Jesus on one A3 portrait page?

The vertical size of portrait A3 is 420 millimeters (297 mm wide). Since my timeline project is 210 millimeters high and can have 46 horizontal text lines in text size 10pt (12 pt line height, see [here for the calculation](https://github.com/kreier/timeline?tab=readme-ov-file#decision-on-the-dimensions-for-this-project)) this A3 paper can have up to 92 lines. But how many do we need?

The project above has 10 lines Adam-Moses, then 10 lines to Abraham, and 11 (4) lines to Judah.  A large block follows with 27 (9) lines to Jesse, the father of David. Then 9 (1) lines to Solomon, 25 (20) to Zerrubbabel and finally 20 (11) lines to Jesus. So a total of 10+10+11+27+9+25+20=112 lines that would not fit, but also 10+10+ 4+ 9+1+20+11=65 that would fit. It's promising!

### May 2026 - renamed to "promised-offspring"

The Hebrew word used for **seed** can also mean **offspring**. But in English the word "seed" is no longer used for humans, similar in German. It appears in many verses (Genesis 1:11; 22:17; 48:4; Matthew 22:24; John 8:37 and the Edenic promise Genesis 3:15) and would be better translated as offpring. See also [Appendix A2](https://www.jw.org/en/library/bible/study-bible/appendix-a/nwt-revision-features/). So the project name changed, and the content inside was updated.

### Current size

The large A0 project from 2005 was mentioned above. With a double-sided A3 paper I have the area of A2, only 25% of the 2005 project. But I got the lineage of Jesus in, all 12 tribes and 12 judges, many woman in the geneaology and the line of high priests. The entire content of the right column fits on the backside. Even when printed out in only 70% on A4 the information is still good readable. In comparison, it would look like this:

<img src="history/latest.jpg" width="20%"><img src="history/promised_seed_2005.png" width="58%"><img src="history/page2.jpg" width="20%">

### June 2026

Planned updates:

- red/purple line of Aarons descendants as levites/priests to the first century

### Additional content from the reference map

- Chart of contemporary ages: Adam to Joseph with Jacob moving to Egypt at the age of 130: 34 lines, 144 mm
- Kings and Prophets from the division of the kingdom 997 BCE to Malachi 443 BCE: 61 lines, 258 mm

### Page 2

The current placeholder splits page 2 in a left and right section. It is good readable in A4 and the fontsize appears to be larger that page 1. In 2025/11/29 I changed to 14 pt line height while maintaining a reference 10pt font. This gives 85 lines.

#### Left: 4026 - 1473 BCE

- 12 time specific times, bold year with left indentation
- 6 red lines where the offspring was in danger
- 7 blue lines for covenants
- 4 + 10 + 4 + 7 + 6 + 3 + 3 + 4 + 7 + 3 = 51 lines for text
- total 76 lines

If limited to 1513 BCE it will be 13 lines less, only 63 lines.

#### Right: 1473 BCE - 36 CE

- 23 time specific times, bold year with left indentation (+1)
- 9 red lines where the offspring was in danger
- 5 blue lines for covenants (+2)
- 1 + 4 + 7 + 2 + 4 + 5 + 5 + 4 + 4 + 4 = 40 lines for text (+10)
- total 77 lines

If extended back to 1513 BCE it will have 13 lines more, total 90 lines. Calculation: 24 + 9 + 7 = 40 lines with 14 pt plus 50 lines with 12 pt (text) equals a height of 560 pt + 600 pt = 1160 pt = 409.25 mm. 1 pt = 0.3528 mm. This would fit. The line values just have to be entered in 0.85 line height increments for 12 pt instead of the standard 14 pt.

But for simplicity I could assume the 50 lines with 12 pt as being 90% of the 14 pt lines. That would be 12.6 pt or 630 pt in total. With the 14 pt that's 1190 pt or 419.8mm. It still fits.

What happens to left? That's 11 + 6 + 5 = 22 lines with 14 pt plus 41 with 12 pt for combined 264 + 492 = 756 pt = 266.7 mm. 150 mm space for other content.
