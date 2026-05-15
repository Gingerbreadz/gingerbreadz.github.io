---
title: "Hi There, I'm Anatole"
#news: "I am actively **looking for a post-doc** in the broad area of **(distributed) systems**. Should you have matching interests, please, **drop me an e-mail**."
about: "I am a Postdoctoral Resarcher at the [Systems Research Group](https://dse.in.tum.de/) of the [Technical University of Munich](https://www.tum.de/), hosted by [Prof. Pramod Bhatotia](https://dse.in.tum.de/bhatotia/)   \nMy current projects revolve around CXL-based disaggregated memory systems for heterogeneous compute architectures."
interests: "Distributed Systems, Distributed Computing, Persistent Memory, Concurrency, Language Runtimes, Cloud Infrastructures."
note: "I'm definitely not a web person/artist. This website was built with minimal efforts, using [Hugo](https://gohugo.io/)  and the [motherfuckingwebsite](https://github.com/gingerbreadz/hugo-theme-motherfuckingwebsite) theme."
footer: "Cheers, you just reached the bottom of the page! Hope you enjoyed your read!"
last_update: "Dec. 1st, 2025"
toc: false
toc_inline: false
---

## Bio

> **TL;DR** --- **Computer Science Ph.D.** in 2023 and **Dipl. Ing.** in 2018.

I completed my *Ph.D. in Computer Science* at [Institut Polytechnique de Paris](https://www.ip-paris.fr/en) in March 2023,
advised by [Pierre Sutra](https://sites.google.com/site/0track/) and [Gaël Thomas](https://www-public.imtbs-tsp.eu/~thomas_g/).  
My thesis was about **unlocking programming support for persistent memory** (e.g., Intel's Optane DC PMEM) **natively in Java**.

I prepared my thesis from 2018 to 2022, as a member of the [Parallel and Distributed Systems Group](https://www.inf.telecom-sudparis.eu/pds/),
in the [CS Department](https://www.inf.telecom-sudparis.eu/) at [Télécom SudParis](https://www.telecom-sudparis.eu/en).  
There, I broadly explored **theoretical and practical aspects** of **persistent memory programming**, but also specificities of **managed languages** and their **execution runtimes**.

<!--
I ended up designing and implementing novel persistent objects for Java, that efficiently access PMEM as off-heap memory, through Java's direct-access interface -- `sun.misc.Unsafe`.
Atop that, I built off-the-shelf container and collection types (akin to those in `java.util`)
-->

Before that, I was in 2018 a *Research Intern* at the [IMDEA Software Institute](https://software.imdea.org/) for 6 months,
where I worked with [Alexey Gotsman](https://software.imdea.org/~gotsman/) on **WB-amcast -- a novel fault-tolerant genuine atomic multicast protocol**.

I earned my « *Diplôme d'Ingénieur* » (*M.S. Eng.*) from [Télécom SudParis](https://www.telecom-sudparis.eu/en) in 2018.
My major was *Parallel Systems and Distributed Computing* ([*ASR*](http://asr.telecom-sudparis.eu/)) and I graduated *first in my class*.

I did the rest of my undergrad studies in 2015-2018 at [Télécom SudParis](https://www.telecom-sudparis.eu/en),
in 2013-2015 at the [Lycée Camille Guérin de Poitiers](https://lyc-camilleguerin.fr/) (*CPGE* -- *MPSI/MP\**).
I received my *Science « baccalauréat »* (*high-school grad.*) in 2013. I was a high-school student at the [Lycée Pilote Innovant et International](https://lp2i-poitiers.fr/).

## Publications

### International Conferences

| | |
|---: | :---: | :---|
| **[ASPLOS'26]** | &nbsp;&nbsp;&nbsp;&nbsp; | [*vCXLGen: Automated Synthesis and Verification of CXL Bridges for Heterogeneous Architectures*](https://dl.acm.org/doi/10.1145/3779212.3790245?cid=99659898506)
| Best paper award | | **Anatole Lefort**, Julian Pritzi, Nicolò Carpentieri, David Schall, Simon Dittrich, Soham Chakraborty, Nicolai Oswald, Pramod Bhatotia
| | | Pittsburgh (PA), USA, March 2026.
| | | [[PDF]](/papers/vcxlgen-asplos26-preprint.pdf) -- [[Slides]](/papers/vcxlgen-asplos26-slides.pdf) -- [Talk] -- [[Code]](https://github.com/TUM-DSE/vcxlgen)
| &nbsp; | |
| **[HPCA'26]** | &nbsp;&nbsp;&nbsp;&nbsp; | [*C3: CXL Coherence Controllers for Heterogeneous Architectures*](https://ieeexplore.ieee.org/document/11408469)
| | | **Anatole Lefort**, David Schall, Nicolò Carpentieri, Julian Pritzi, Nicolai Oswald, Pramod Bhatotia
| | | Sydney, Australia, February 2026.
| | | [[PDF]](/papers/c3-hpca26.pdf) -- [[Slides]](/papers/c3-hpca26-slides.pdf) -- [[Code]](https://github.com/TUM-DSE/C3)
| &nbsp; | |
| [**Thesis**] | &nbsp;&nbsp;&nbsp;&nbsp; | [*A Support for Persistent Memory in Java*](https://www.theses.fr/s209722)
| | | **Anatole Lefort**
| | | Ph.D. thesis, Institut Polytechnique de Paris, March 2023
| | | [[PDF]](/papers/thesis-anatole.pdf) -- [[Slides]](/papers/thesis-anatole-slides.pdf) -- [[Talk]](https://bbb-node.imtbs-tsp.eu/playback/presentation/2.3/74fc0fc86f9a8c34a6db85966d573b27be7cc424-1679644962657)
| &nbsp; | |
| **[SOSP'21]** | &nbsp;&nbsp;&nbsp;&nbsp; | [*J-NVM: Off-heap Persistent Objects for Java*](https://dl.acm.org/doi/abs/10.1145/3477132.3483579)
| | | **Anatole Lefort**, Yohan Pipereau, Kwabena Amponsem, Pierre Sutra, Gaël Thomas
| | | In *Proceedings of the ACM SIGOPS 28th Symposium on Operating Systems Principles (SOSP)*, Virtual Event, October 2021.
| | | [[PDF]](/papers/sosp21-jnvm.pdf) -- [[Slides]](/papers/sosp21-jnvm-slides.pdf) -- [[Poster]](/papers/sosp21-jnvm-poster.pdf) -- [[Talk]](https://youtu.be/6RcV9PSsub8) -- [[Live Q&A]](https://youtu.be/6OZ_WC-xD4k) -- [[Code]](https://github.com/jnvm-project/jnvm)
| &nbsp; | |
| **[DSN'19]** | | [*White-box Atomic Multicast*](https://ieeexplore.ieee.org/document/8809528)
| | | Alexey Gotsman, **Anatole Lefort**, Gregory Chockler
| | | In *Proceedings of the 49th Annual IEEE/IFIP International Conference on Dependable Systems and Networks (DSN)*, Portland (OR), USA, June 2019.
| | | [[PDF]](/papers/dsn19_wb-amcast.pdf) -- [[Extended version on arXiv]](https://arxiv.org/abs/1904.07171) -- [[Code]](https://github.com/imdea-software/atomic-multicast)

### International Journals

| | |
|---: | :---: | :---|
| **[TOCS]** | &nbsp;&nbsp;&nbsp;&nbsp; | Invited extended journal version of *vCXLGen: Automated Synthesis and Verification of CXL Bridges for Heterogeneous Architectures*
| | | **Anatole Lefort**, Julian Pritzi, Nicolò Carpentieri, David Schall, Simon Dittrich, Soham Chakraborty, Nicolai Oswald, Pramod Bhatotia
| | | forthcoming, 2026.

<!--
## International Conferences

| | |
|:--- | :---: | :---|
| **[SOSP'21]** | &nbsp;&nbsp;&nbsp;&nbsp; | [*J-NVM: Off-heap Persistent Objects for Java*](https://dl.acm.org/doi/abs/10.1145/3477132.3483579)
| | | **Anatole Lefort**, Yohan Pipereau, Pierre Sutra, Gaël Thomas
| | | In *Proceedings of the ACM SIGOPS 28th Symposium on Operating Systems Principles (SOSP)*, Virtual Event, October 2021.
| | | [[PDF]]() -- [[Slides]]() -- [[Video]]() -- [[Code]]()
| &nbsp; | |
| **[DSN'19]** | | [*White-box Atomic Multicast*](https://ieeexplore.ieee.org/document/8809528)
| | | Alexey Gotsman, **Anatole Lefort**, Gregory Chockler
| | | In *Proceedings of the 49th Annual IEEE/IFIP International Conference on Dependable Systems and Networks (DSN)*, Portland, OR, June 2019.
| | | [[PDF]]() -- [[Slides]]() -- [[Code]]()

## Workshops

| | |
|:--- | :---: | :---|
| **[NVMW'22]** | &nbsp;&nbsp;&nbsp;&nbsp; | [*J-NVM: Off-heap Persistent Objects for Java*](http://nvmw.ucsd.edu/program-2022/#paper-22)
| | | **Anatole Lefort**, Yohan Pipereau, Pierre Sutra, Gaël Thomas
| | | In *the 13th annual Non-Volatile Memories Workshop*, San Diego, CA, May 2022
| | | [[PDF]]() -- [[Slides]]() -- [[Poster]]() [[Talk (Short)]]() -- [[Talk (Full)]]()

## Misc.

| | |
|:--- | :---: | :---|
| **Thesis** | &nbsp;&nbsp;&nbsp;&nbsp; | [*A Support for Persistent Memory in Java*](https://www.theses.fr/s209722)
| | | **Anatole Lefort**
| | | Ph.D. thesis, Institut Polytechnique de Paris, March 2023
| | | [[PDF]]() -- [[Slides]]() -- [[Talk (Short)]]() -- [[Talk (Long)]]()
-->

## Talks
| | |
| ---: | :---: | :---|
| **[HMEM'22]** | &nbsp;&nbsp;&nbsp;&nbsp; | [*J-NVM: Off-heap Persistent Objects for Java*](https://www.bsc.es/news/events/3rd-workshop-heterogeneous-memory-systems-hmem-2022/agenda)
| | |
| | | At the [*3rd Workshop on Heterogeneous Memory Systems (HMEM 2022)*](https://www.bsc.es/news/events/3rd-workshop-heterogeneous-memory-systems-hmem-2022), Virtual Event -- Collocated with ICS'22, July 2022.
| | | [[Slides]](/papers/hmem22-jnvm-slides.pdf)
| &nbsp; | |
| **[NVMW'22]** | &nbsp;&nbsp;&nbsp;&nbsp; | [*J-NVM: Off-heap Persistent Objects for Java*](http://nvmw.ucsd.edu/program-2022/#paper-22)
| | |
| | | At [*the 13th annual Non-Volatile Memories Workshop*](http://nvmw.ucsd.edu/home-2022), San Diego (CA), USA, May 2022
| | | [[PDF]](/papers/nvmw22-jnvm.pdf) -- [[Slides]](/papers/nvmw22-jnvm-slides.pdf) -- [[Poster]](/papers/nvmw22-jnvm-poster.pdf) -- [[Talk (5min)]](https://youtu.be/ha6W0iWf0dg) -- [[Talk (Full)]](https://youtu.be/SChlHo7ShiI)

## Prizes and Awards

- **Laureate of “Engineers of the Future Awards”**, *Engineers for Research* category, Dec. 2022.  
Sponsored & Issued by l'[*Usine Nouvelle*](https://www.usinenouvelle.com/)  
[[Press Article]](https://www.usinenouvelle.com/article/ingenieur-recherche-2022-anatole-lefort-exploite-les-atouts-de-la-memoire-persistante.N2067502) -- [[3min Pitch]](https://content.jwplatform.com/previews/VtPS3YnL) -- [[Pic]](/pictures/tif22-jnvm-photo.jpg)
- **Best student publication in ICTs at Institut Polytechnique de Paris**, Sep. 2022.  
Sponsored & Issued by [*Labex Digicosme*](https://digicosme.cnrs.fr/en/),
[*Institut Polytechnique de Paris*](https://www.ip-paris.fr/en),
and [*Université Paris Saclay*](https://www.universite-paris-saclay.fr/en)  
[[Slides]](/papers/sticsaclay23-jnvm-slides.pdf)

## Grants

- **Humboldt Research Fellowship for Postdocs** from *the Alexander von Humboldt Foundation*, 2023-2025.
- **NVMW Student Travel Grant** to attend [*NVMW'22*](http://nvmw.ucsd.edu/home-2022/) (San Diego, CA, USA, 2022).
- **Fully-Funded Ph.D. Scholarship** from [*Institut Mines-Télécom*](https://www.imt.fr/en/), [“Future & Rupture”](https://www.fondation-mines-telecom.org/en-actions/innover/futur-ruptures/) campaign (2018),  
Awarded on *Academic Excellence* criteria, ranked 1st for *Télécom SudParis*.

## Teachings
- Télécom SudParis (2019-2021):
  - [*System Programming Introduction ~ Unix & Shell scripting*](http://www-inf.telecom-sudparis.eu/COURS/CSC3102/Supports/) -- **Bash**  
L3 level --- Fall 2019, Fall 2020  
  - [*Java Introduction ~ Data Structures & Algorithms*](https://www-inf.telecom-sudparis.eu/COURS/CSC3101/Supports/fise/) -- **Java 1**  
L3 level --- Fall 2020
  - [*Software Engineering for Object-Oriented Programming*](https://www-inf.telecom-sudparis.eu/COURS/CSC4102/) -- **Java 2**  
M1 level --- Spring 2020, Spring 2021

# Besides Work or Research
----------------------------

I truly enjoy any kind of *problem solving*, *tinkering*, or *experimentation* activities.
Not necessarily related to computers, but really anything where I can also get creative and crafty.
*Cooking* comes up first in mind, but that also includes various *DIY projects*.
For instance, I designed and sew [my own custom frame bags](/pictures/bike-frame-bag-2020.jpg) to fit on my bike.

When I grow [tired of sitting at my desk](/pictures/batman.jpg), working on my computer, or just being indoors; I usually go outside and do [stupid things](https://www.strava.com/activities/7206716430):
- **Cycling**: (*Road*, *MTB*, *Touring & Bikepacking holidays*)
- **Running**: (*Road* & *Trail*)
- **Hiking**: (from *Day-Hikes*, to *Weeklong Alpine Backpacking trips*)
- **Skiing and Snowboarding**: (resort-only, for now)

I'm not doing any of those competitively; but just for leisure, on my own, or with friends.
At least once a day, to preserve my sanity.

Cities are boring, remote places are beautiful.

I might someday log here the routes and trips I liked doing the most --- you know, just for bragging purposes, 'cause ima show-off.

At some point, for some reason, I also learned how to ride weird **Freeline Skates** on [flats](https://youtu.be/jhnFwMh8EOQ) and [downhills](https://youtu.be/R5XPHowLpd0).

As a kid and teenager, I was also fond of **Gymnastics**, **Tennis** and **Judo**, which I practiced in sports clubs.  

I also played music for many years: **Percussion Instruments** (*drums*, *marimba*, *timpani*, and various other *orchestral percussions*).
