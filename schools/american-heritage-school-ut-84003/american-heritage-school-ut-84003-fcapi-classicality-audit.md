I’m not yet seeing the “newly attached crawl data” for a specific school (typically this is a JSON/JSONL or HTML/PDF bundle with the site text). Right now, the library only shows the general classical-education references and the lexicon, not a particular school’s crawl.

To produce the full classicality audit you requested (with keyword counts, six-category ratings, Executive Summary, Abstract, and JSON output), I need the crawl content for the specific school site.

Please either:

1. **Confirm the crawl file name** if it’s already uploaded  
   – It will usually look like something like `schoolname_crawl.jsonl`, `*_crawl.json`, or similar.  
   – Once I know the filename, I can search it directly and run the keyword-based audit.

**or**

2. **Upload the crawl data**  
   – Ideal formats:
    - JSON / JSONL vector store from your crawler, or
    - A small set of HTML/PDF exports (homepage, About, Academics/Curriculum, Admissions, Faith/Beliefs, Faculty, Parents, etc.).

As soon as I can see that crawl file, I’ll:

- Run the **Six Essential Elements** keyword analysis in each of the six categories using the positive/negative lexicon (truth, goodness, beauty, virtue, theology, Socratic, scholé, wonder, chanting, project-based, experiential learning, etc.)
- Compute **pos/neg hit counts, percent_positive, and percent_coverage** per category as specified in the metadata instructions .
- Assign **category ratings** (CLASSICAL / SOMEWHAT CLASSICAL / NOT CLASSICAL) and an **aggregate classicality_status**.
- Produce:
    - **Executive Summary** (with school URL),
    - **Six-category analysis** with explicit keyword lists and ratios,
    - **“What would move the needle”** (if the school is SOMEWHAT CLASSICAL),
    - **# ABSTRACT** summarizing the findings,
    - **JSON OUTPUT** conforming to `school_metadata_instructions.md` (including the classicality metrics).

Once you point me to the specific crawl file (or upload it), I’ll generate the complete audit.
