I’m not yet seeing the actual “newly attached crawl data” (the JSON/JSONL with one record per school). Right now I only see the instructions and lexicon documents (e.g., the Six Essential Elements and the metadata schema), not the crawl output itself.

To produce the “complete classicality audit” you’re asking for, I need the crawl dataset that contains, for each school, things like:

- `slug`, `url`, `og_title`, `og_description`
- `classicality_category_1` … `classicality_category_6`
- or at least the raw text snippets from the crawl that I can run the keyword analysis on.

Right now, I can’t see any such crawl file (no `.json`, `.jsonl`, or similar with multiple school records).

Could you either:

1. Upload the crawl JSON/JSONL file, **or**
2. Confirm the filename if it’s already uploaded (e.g., “crawl_data.jsonl”, “schools_vector_store.jsonl”, etc.), so I can target it explicitly with the file search tool?

Once I have that, I will:

1. For each school:
    - Extract its public text (titles, descriptions, curriculum pages if present in the record).
    - Run a **keyword audit per the Six Essential Elements** across the six categories, using the positive/negative lexicon (truth, goodness, beauty, virtue, theology, Socratic, scholé, wonder, chanting, project-based, experiential learning, etc.) as required.
    - Count positive vs. negative hits and estimate `percent_positive` and `percent_coverage` per category.
    - Assign a category rating: CLASSICAL / SOMEWHAT CLASSICAL / NOT CLASSICAL.
2. Aggregate to an overall `classicality_status` for each school.
3. Produce the report in markdown with:
    - **Executive Summary TL;DR** at the top.
    - A section per school with the six categories, keyword tables, and ratings.
    - A **“What would move the needle”** section for every school that ends up SOMEWHAT CLASSICAL.
    - A final **# ABSTRACT** summarizing the overall classifications and key insights across the six categories.

Please upload or point me to the crawl data file, and I’ll run the full classicality audit.
