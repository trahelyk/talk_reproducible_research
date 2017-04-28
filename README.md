---
title: "Reproducible Research"
date: "03 May 2017"
author: Kyle Hart (hartky@ohsu.edu)
output:
	ioslides_presentation
---

# Kyle who?

<img src="gfx/me.jpg" alt="me." style="width: 200px;"/>

* MS in Biostatistics from OHSU in June 2014
* 2014 – 2016: Statistician at OHSU Department of Surgery
* 2013 – 2014: Data manager at the VA Portland Health Care System
* 2004 – 2013: Data manager in industry

---
	
# Why I act this way
	
* I've been writing code since I was 8; I see all this through the eyes of a programmer.
* I'm deeply committed to R.
* I'm cautiously optimisitc about the Hadley Wickham/tidyverse/RStudio movement.
* It's all about literatre programming.

---

# (with applications in R)

---
This talk will focus on applications in R. 
* I think implementations in SAS and Stata are clunky and immature. 
* SPSS, as far as I can tell, isn't even really trying. 
* Also, because I use R and I think it's nifty. 

---

Research presentations:
	* Journal article
	* Book
	* Web site
	* Slide deck
	
These things are not research; they are advertising for research. Research is "the full software environment, code, and data that produced the results." (Claerbout, 1992)

---
Gold standard: Replicability
The research includes enough stuff that a different researcher can follow the same procedures in a new sample and come up with the same results.

Hard to do if the original study used the whole population or if there isn't funding to replicate the results.

Perhaps journals are culpable here because "statistically significant, novel, and theoretically tidy results are published more easily than null, replication, or perplexing results" (Miguel et al). 

---
Next-best thing: Reproducibility
Peng: When replicability is not feasible, reproducibility is a minimum standard for judging scientific claims.

The research includes enough stuff that a different researcher can follow the same procedures in the same sample and come up with the same results.

---
Why is reproducibility important?
Reproducible does not mean results aren't wrong.
Reproducible does not mean results are credible. 
Reproducibility does not mean results are not sensitive to methods.
But it exposes these things so peers can spot them and improve scientific consensus.

---
Why is reproducibility important?
Improves collaboration
Who is your most important collaborator? (Future You)
If you know somebody else might look, your code might magically become more organized
You could get hit by a bus; in that case, we will obviously be most concerned about moving forward with your research. 
Revise and resubmit. Make it easier for Future You.


---
Traditional (non-reproducible) workflow

---
Reproducible workflow

---
Minimum components of a reproducible workflow
	* Data
	* Code
	* Software (including versions)
	* Presentation (manuscript, slide deck, or whatever)
	* Documentation that explains how all the pieces are connected
	
---
Tools:
	Data:
		X Drive
	Code:
		R
	Software:
		R
		Code comments or MS Word to keep track of versions
	Presentation:
		MS Word
		MS Powerpoint
		Whatever
	Documentation:
		MS Word
		Code comments

---
More ideal components of a reproducible workflow
	* Data
	* Code
	* Software (including versions)
	* Presentation (manuscript, slide deck, or whatever)
	* Documentation that explains how all the pieces are connected
	* An elegant way to package all of this
	
---
Tools:
	Data:
		Git/GitHub
		Make files and R make-like files
	Code: 
		RStudio (is anybody using R without RStudio?)
		tidyverse
		Master script
	Software:
		R
		packrat
	Presentation:
		knitr
		RMarkdown
		LaTeX
	Documentation:
		knitr
		RMarkdown
		Git/GitHub

---	
File management
Working folders, relative paths, getwd(), and setwd()
RStudio projects

---
Git/GitHub

---
knitr and LaTeX

---
knitr and RMarkdown

---
packrat


---
Thanks
I borrowed the concept for the workflow figures from Ben Chan, Stephanie Renfro, and Thomas Meath at the Center for Health Systems Effectiveness (CHSE). 