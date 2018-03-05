---
layout: index
---

#### Overview

Data is eating the world and developing next generation data-driven applications and systems for working with data is more important than ever before.  In addition, the lines between research, applications, and industry are increasingly blurred.

This course will survey modern research in data management -- from large scale data processing, modern database engines, to data cleaning and visualization, to secure data management.  To ground the discussion, we will host invited speakers that have (or are) transitioned their research work from academia to industry.   Depending on timing and interest,  select students may be invited to join the speakers for more in-depth discussions over dinner after class.  

Students are expected to actively participate in discussions.   
<small style="color: grey">Course capped at 25.  If waitlist is huge, a small assignment will be used to choose participants.</small>


#### Recent Announcements

* Added questions for first reading below
* Updated [extra credit](./syllabus#ec) part of syllabus


#### Schedule

1/17: Introduction
* Presenter: Eugene

1/24: Human-Assisted AI at B12
* Presenter: [Adam Marcus](http://marcua.net/)
* Reading: [Crowdsourced Data Management: Industry and Academic Perspectives](http://marcua.net/papers/crowd-book.pdf)
  * Skim chapter 3, stopping after completing section 3.3
  * Skim chapter 4, stopping after completing section 4.2
  * Read the executive summary of chapter 5
* Reading Questions: <small>Since the reading is not a paper, answer the following questions</small>
  * What is the type of problem that crowd-powered algorithms and systems are uniquely meant to solve?  Don't use any jargon
  * Imagine and describe the craziest/most impactful application for which crowdsourcing would be a necessary component.
    * What does the application do?
    * Who cares?
    * Why is crowdsourcing needed?
* Assignments
  * Project Presentations batch 1.  [Sign up here](https://calendar.google.com/calendar/selfsched?sstoken=UUlmUlc5VDIwWDJwfGRlZmF1bHR8MTUwY2E3NDBiMDNhMTU4ZDIyODhlMjFlZTAzZGMyZTU)

1/31: Secure Databases
* Presenter: [Frank Wang](https://frankwang.org/)
* Readings
  * [Differential privacy primer](https://people.eecs.berkeley.edu/~stephentu/writeups/6885-lec20-b.pdf)
  * [CryptDB summary](https://mshcruz.wordpress.com/2016/06/24/summary-cryptdb/)
  * [Envisioning the Hack That Could Take Down NYC](http://nymag.com/daily/intelligencer/2016/06/the-hack-that-could-take-down-nyc.html)
  * (optional) [smcql: Secure Querying for Federated Databases](http://users.eecs.northwestern.edu/~jennie/pubs/smcql.pdf)
* Reading Questions: <small>Since the readings are summaries, answer the following questions</small>
  * Describe concrete scenarios of problems that each of the first two readings seeks to address.
    * Are they realistic in practice?  
    * Or do they limit functionality or not fully protect what they promise or both?
  * The NYMag article is a chilling read.  Do the readings help?  What could one do?
  * Frank has experience in cybersecurity startups and research, come up with 1+ questions for him
* Assignments
  * Project Presentations batch 2.  [Sign up here](https://calendar.google.com/calendar/selfsched?sstoken=UUlmUlc5VDIwWDJwfGRlZmF1bHR8MTUwY2E3NDBiMDNhMTU4ZDIyODhlMjFlZTAzZGMyZTU)


2/07: GPU Databases
* Presenter: [Todd Mostak](https://www.mapd.com)
* Readings
  * Required: [Accelerating SQL Database Operations on a GPU with CUDA](./files/papers/todd-bakkum_sqlite.pdf)
  * Required: [Hashing out Perfect Group-Bys in a GPU-accelerated database](./files/papers/todd-perfect-hashing.pdf)
  * Optional: [Efficient Query Processing in Co-Processor-accelerated Databases](./files/papers/todd-coprocessor.pdf)
  * Optional: [Massive Throughput Database Queries with LLVM on GPUs](https://www.mapd.com/blog/2016/04/27/massive-throughput-database-queries-with-llvm-on-gpus/) 
  * Optional: [End-to-end Computation on the GPU with the GPU Data Frame (GDF)](https://www.mapd.com/blog/2017/05/30/end-to-end-on-the-gpu-with-the-gpu-data-frame-gdf/)
  * Optional: [Vega makes visualizing BIG data easy](https://www.mapd.com/blog/2017/07/22/vega-makes-visualizing-big-data-easy/)
* [See Syllabus for Reading Questions](./syllabus#reading)
* Assignments
  * Project Presentations batch 3. [Sign up here](https://calendar.google.com/calendar/selfsched?sstoken=UUlmUlc5VDIwWDJwfGRlZmF1bHR8MTUwY2E3NDBiMDNhMTU4ZDIyODhlMjFlZTAzZGMyZTU)
  * Prospectus due 2/11

2/14: The future of data interaction
* Presenter: Eugene Wu
* Readings (optional)
  * [Smoke: fast lineage](https://arxiv.org/abs/1801.07237)
  * [Precision Interfaces](https://arxiv.org/abs/1712.00078)
  * [Scorpion: explaining outliers](http://sirrice.github.io/files/papers/scorpion-vldb13.pdf)

2/21: TileDB 
* Presenter: Stavros Papadopoulos
* [TileDB codebase](https://github.com/TileDB-Inc/TileDB)
* Reading: [The TileDB Array Data Storage Manager](https://people.csail.mit.edu/stavrosp/papers/vldb2017/VLDB17_TileDB.pdf)
* Optional Reading:
  * Main discussion: [Dynamic Prefetching of Data Tiles for Interactive Visualization](http://www.cs.tufts.edu/~remco/publications/2016/SIGMOD2016-ForeCache.pdf)
  * Related: [Distributed and Interactive Cube Exploration](http://arnab.org/files/dice.nandi_.pdf)


2/28: Instabase: Turing your research into a startup
* Presenter: Anant Bhardwaj and Edward Benson
* Readings
  * [The Datahub Paper](http://db.csail.mit.edu/pubs/datahubcidr.pdf) that started instabase
  * [Quilt](http://edwardbenson.com/papers/uist2014-spreadsheet-driven-web-apps.pdf)
  * (Optional) [Ajax-based Report Pages as Incrementally Rendered Views](http://db.ucsd.edu/wp-content/uploads/pdfs/350.pdf)
  * (Optional) [Collaborative Data Analytics with DataHub (Demo)](http://www.vldb.org/pvldb/vol8/p1916-bhardwaj.pdf)
* Reading Questions:
  * For both papers:
    * What concrete problem did the datahub paper set out to solve?
    * What technical idea seems promising (irrespective of the problem statement described in the papers)?
    * Do you think the problem is real?  If so, describe an impactful scenario for it.  If not, describe why not and what aspects of the paper could be impactful.  (Be sure to be clear about what impactful means)
  * One or more questions for the speakers
    

3/07: Cockroach Labs: Raft Made Complex
* Presenter: Ben Darnell
* Readings
  * [The original Raft paper](https://raft.github.io/raft.pdf)
  * (Optional) [Viewstamped Replication Revisited](http://pmg.csail.mit.edu/papers/vr-revisited.pdf)
  * (Optional) [Living Without Atomic Clocks blog post](https://www.cockroachlabs.com/blog/living-without-atomic-clocks/)
  * (Optional) [Raft Refloated](http://www.cl.cam.ac.uk/~ms705/pub/papers/2015-osr-raft.pdf) 
  * (Optional) [Google's Paxos Made LIve](https://research.google.com/archive/paxos_made_live.html)
* Reading Questions:
  * Provide a simple example of how Raft recovers from a leader failure.  A simple way is to list the state at each node at every time step, and use english to describe what happens between each time step.
  * Suppose the clocks on all nodes are _perfectly synchronized_ (e.g., node i's clock is exactly the same as node j's clock).  Which part of raft is still necessary?
  * Raft argues that it is more understandable.  What evidence would be sufficient to show that this is the case?  How does it compare with what the authors show?
  * Why did the authors develop raft in the first place?
  * Include 1+ question to ask the speaker.

3/14: Spring Recess

3/21: Midterm

3/28: TBA
* Presenter: [Juliana Freire](https://en.m.wikipedia.org/wiki/Juliana_Freire)

4/04: 3 Timeless ideas in SQLite
* Presenter: [Richard Hipp](https://en.m.wikipedia.org/wiki/D._Richard_Hipp)
* Readings and Questions
  * [No Silver Bullet - Essence and Accident in Software Engineering](http://worrydream.com/refs/Brooks-NoSilverBullet.pdf)
    *  What accidental complexities in database systems have been mitigated by the SQL language?
    *  What additional accidental complexities have not been addressed by SQL?
    *  Can the query planner in an SQL database engine be considered an example of an AI or Expert System or as an implementation of an Automatic Programming system?
  * [About SQLite](https://sqlite.org/about.html)  -- it's pretty amazing!
  * [Appropriate Uses for SQLite](https://sqlite.org/whentouse.html)
    * Some applications transfer information between client and server by
      stuffing the content into an SQLite database and sending the database
      file over the wire. What are some advantages and disadvantages to
      this approach compared to sending the content as JSON, a ZIP Archive,
      or a bespoke binary format?
		*  Git, the most widely used distributed version control system today,
   	   uses a bespoke key/value database format call a "pack-file" both
   	   to store content and to transfer content over the wire when syncing
   	   or cloning. The value for each entry is either the content of a file
   	   being versioned, or a binary object describing relationships between
   	   files. The key is a SHA1 hash of the content. What if Git had been
   	   designed to use SQLite, or some other embedded relational database,
   	   instead of a key/value store? Would Git be a better or a poorer product
   	   if it used an SQLite database in place of pack-files? What
   	   impact would using SQLite versus pack-files have on performance,
   	   reliability, storage efficiency, and extensibility? If you were
   	   designing a replacement or follow-on to Git, what kind of database
   	   would you use for local storage, server-side storage, and for transfer?
  


4/11: LogicBlox
* Presenter: Molham Aref
* Reading: [Design and Implementation of the LogicBlox System](http://www.cs.ox.ac.uk/dan.olteanu/papers/logicblox-sigmod15.pdf)

4/18: TBA
* Presenter: [Evan Jones](http://www.evanjones.ca/)
* Reading: TBA

4/25: Project presentations

