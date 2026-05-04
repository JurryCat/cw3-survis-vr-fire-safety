# CW3 SurVis / Figure Asset Pack

## What this pack contains

- `papers_metadata.csv`: master metadata table for the 14 reviewed papers.
- `extraction_matrix.csv`: CW3-oriented extraction matrix for paper summaries and categorization.
- `references_survis.bib`: BibTeX entries with keywords and short summaries. Use this as the literature input for SurVis.
- `apa_references_draft.txt`: APA-style reference list draft, alphabetically ordered by first-author surname.
- `publication_year_histogram.png`: required publication-year histogram for Section 1.
- `literature_classification_matrix.png`: classification matrix/table for Section 3.
- `article_screening_flow.png`: optional article statistical analysis flow figure for Section 2.3.

## Recommended SurVis tags

review, meta-analysis, safety-training, fire-safety, fire-extinguisher, evacuation, evacuation-drills, serious-games,
immersive-vr, non-immersive-vr, display-fidelity, presence, procedural-learning, conceptual-learning, retention,
self-efficacy, haptic-feedback, thermal-cues, multimodal-vr, realism, transfer, vulnerable-users, npc.

## Suggested SurVis workflow

1. Create a new GitHub repository, for example `cw3-survis-vr-fire-safety`.
2. Download or fork the official SurVis project.
3. Replace or add the bibliography file with `references_survis.bib`.
4. Configure SurVis so that the bibliography and keyword fields are loaded.
5. Commit and push the files.
6. Enable GitHub Pages from the repository settings.
7. Open the public GitHub Pages URL and verify:
   - all 14 papers appear;
   - tags/keywords are visible;
   - each paper has a DOI;
   - summaries are readable;
   - the page is public in an incognito/private browser.
8. Take a screenshot for CW3 Section 3 and paste the public URL below it.

## Figure captions to use in the report

Figure 1. Publication years of the 14 reviewed papers, showing that most selected work was published between 2020 and 2024.

Figure 2. ConnectedPapers graph generated from Scorgie et al. (2024), used as the survey-seed map to identify and cross-check related VR safety training, evacuation, and fire-safety studies.

Figure 3. Screening process used to select the final reviewed literature from an initial pool of candidate papers.

Table/Figure 4. Classification matrix of reviewed papers by category, method, application domain, evidence type, and technology level.

Figure 5. SurVis visualization of the reviewed literature, hosted through GitHub Pages.
