# Lab Meeting Bingo
### Tychele N. Turner, Ph.D.
### June 23, 2018


#### Description: 
It can be really fun to come up with games to play during lab meeting. Lab meeting Bingo and / or conference Bingo games are fairly popular. Herein, I describe how I've done this in one of my lab meetings. The goal was to keep people engaged and excited about the research. 


#### Card setup: 
I created the Bingo cards using Microsoft Publisher (lab_meeting_bingo_template.pub). The dimensions were set so that the cards could be printed out on [Avery 8387 Matte White Postcards](https://www.avery.com/products/cards/8387). In the repository there is also a pdf template (lab_meeting_bingo_template.pdf) that should work as well.


#### Words for the card: 
There were two presenters at my lab meeting so I selected a set of words from both our presentations, as well as, some generic words in our field. I then strategically placed them around the card so "hopefully" the winner would have to listen to both talks to win. As an example, the words for my talk were:

```
tntwords <- c("de novo", "genome", "CNV", "SNP", "indel", "Illumina", "QC", "autism", "PCA", "variants", "father", "exome", "validation", "pedigree", "burden", "regulatory", "SFARI")
```

Since, the lab meeting was for a fairly large group I made 9 different cards. Using [R's](https://www.r-project.org/) `sample` function I picked a random subset of these words for the card as follows:

```
forcardstnt <- sample(tntwords, 12)
```

Obviously, you may pick words any way you want. This is just how I did it.

#### Markers: 
For some bit of fun for the players I got [Crayola Stampers](http://shop.crayola.com/color-and-draw/markers/10ct-ultra-clean-expression-stamper-marker-5881480002.html) for people to mark off their cards. 


#### Have Fun!

##### Blank template:
![](lab_meeting_bingo_template_for_readme.png)

##### Example card:
![](example_card.png)


