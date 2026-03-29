![Version](https://img.shields.io/static/v1?label=writingLogTemplateOrg&message=0.9.1&color=brightcolor)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)


# Writing project log template in org-mode

## What is this? A space for metacognition and storing metadata about one writing project

Use this template to store in one document outside of your writing project's main document (e.g., journal article, grant application, book chapter, book, lecture notes, seminar notes, talk notes, poster notes) the data and the thinking behind your writing project.
This document is meant to be specific to one project; create a separate document for additional projects.
This template addresses the problem of cluttering the writing project document with notes about decisions made and plans for the work.
This template provides a safe place for notes that tend to get deleted and lost upon manuscript submission.

Use this writing log in parallel to the main writing project document to support these workflows:

- project ideation and initiation (usually a 3-4 hour work session on day one)
- Data inventory (update as needed)
- Daily log to record decisions made, actions completed or attempted, and correspondence.
- Periodic project assessment against timeline with milestones (once a week, month, or quarter -- whatever is appropriate)
- Project completion and archiving (one to several days at manuscript submission or acceptance or a bit of both)

## Why use this writing project log?

- Eases restarting a project that has been interrupted.
- Supports working on several projects concurrently.
- Updates the fear of losing momentum.
- Abates the fear of forgetting where you left off.
- Supports the planning of related projects as you make progress on the current project. You will have a running start on the next writing project.

## What this is not

- This is not an extended annotated bibliography to store your thoughts about the literature you read. You can find elsewhere on the site repositories that support the assembly of classical annotated bibliographies. You will also find repositories for templates for modern bibliographies that support multi-paragraph entries illustrated with figures, tables, code listings, equations, and URLs to relevant websites, including videos.
- This is not an accountability tool where you record your minutes spent on words written per day across one or more writing projects. You can find several different approaches to writing accountability on this website and the corresponding tools to support those approaches. You can choose one approach that you think you can use daily. Do not try to use more than one approach at a time. You will exhaust yourself and give up. If you schedule your writing activities and show up at the appointed time, the need for tracking your progress will be diminished when following the writing schedule becomes a deeply ingrained habit.


## What is org-mode

[Org-mode](https://orgmode.org/) is a rich variant of markdown (see [cheatsheet](https://devhints.io/org-mode)) that can read some LaTeX code directly.
The remaining LaTeX code can be used in a code block for LaTeX.


## Features

- 20 considerations for planning a manuscript.
- A table of contents that is automatically generated and hyperlinked.
- An automatically generated index that is hyperlinked.
- Support for generating a references cited section from a BibTeX library.
- A writing log section for recording notes about each day's accomplishments.
- Plot of the word count by writing session to track your progress.
- Use org-clock and clock tables to track and summarize your effort.
- A GUIDANCE drawer that stores advice on how to use a section. The drawer is opened by placing the cursor on it and entering the tab.


## NEW in Version 0.9.1: AI Agent-Enhanced Writing Log Protocol

### Overview

The file `writingLogAIprotocol.org` is a comprehensive expansion of the writing log template that serves as a detailed protocol for manuscript assembly with integrated AI agent guidance.
It draws heavily on the book *Scientific Writing with Claude Cowork and Code: A Practitioner's Guide to AI-Aided Manuscript and Book Assembly* by Blaine Mooers (2026), integrating the book's twelve chapters of practical workflows, verification frameworks, and ethical guidance into a single actionable document.

The protocol reorganizes the writing log into fourteen phases that mirror the full lifecycle of a scientific writing project, from setting up the AI environment through submission, book-length scaling, and ethical compliance.

Each section has been augmented with three subsections:

1. **AI Agent Dos**: Six to twenty specific, actionable ways in which an AI agent (such as Claude, GPT-4, Gemini, or a local LLM) can assist with the tasks in that section.
2. **AI Agent Do-Nots**: Ways in which AI agents are especially unreliable, inappropriate, or risky for that section. These are the guardrails that prevent you from outsourcing judgment to a machine.
3. **AI Verification Chores**: Concrete steps you can take---often with AI assistance---to verify that what the AI returned is correct. Trust, but verify.

### The Fourteen Phases (Phases 0 through 13)

The protocol is organized into these phases:

0. **Foundations: Setting Up the AI-Assisted Writing Environment** --- Claude Cowork vs. Claude Code, the Model Context Protocol (MCP) with academic servers (PubMed, Semantic Scholar, CrossRef, ArXiv), session persistence and context management, the permission model and human-in-the-loop safety, the stochastic trap (converting repetitive tasks to scripts), and keeping local options open with Ollama.

1. **Project Initiation** --- Central question, rationale, audience, target journals, related projects, draft introduction, potential results and discussion, titles, keywords, abstract, abbreviations, collaborators/competitors/reviewers, cover letter, acknowledgments, and funding sources.

2. **Data Assembly** --- Data inventory and management, computational environment documentation (renv, conda, Docker), literate programming (org-mode Babel, Jupyter), FAIR compliance, and data availability statements.

3. **Plans to Support the Writing Project** --- Experimental and computational plans, literature retrieval with MCP server integration (PubMed MCP, Semantic Scholar MCP, CrossRef MCP, ArXiv MCP), bibliography management (Zotero + Better BibTeX, deduplication, normalization), literature matrices, annotated bibliographies, claim verification against sources, hallucination failure modes, document structure and version control (IMRAD variants, Git workflows, multi-pass LaTeX compilation, Overleaf integration).

4. **Project Management for Timely Completion** --- Manuscript completion checklist, timeline with milestones, periodic assessments, and progress tracking.

5. **Daily Log and Writing Sessions** --- AI-enhanced daily writing protocol with context management techniques ("Story So Far" pattern, progressive disclosure), custom slash commands (/audit-citations, /fixlatex, /structuralmap, /findgaps), the Hemingway bridge, and word count tracking.

6. **Draft Assembly** --- Methods, results, discussion, introduction, and abstract sections with prompt template library, the /rewritechapter six-phase skill workflow, grounding documents, shared resource files (acronyms, symbols, glossary), human-in-the-loop gates, and authorial voice preservation.

7. **Systematic Verification** --- Three-layer verification framework (citation, claim, logical), citation key extraction and audit, DOI resolution and validation, claim-source matching, hallucinated reference detection, logical analysis with structured prompts, sub-agent verification (dual-review pattern), domain-specific verification, and verification reports with confidence levels.

8. **Comprehensive Revision** --- Three levels of editing (developmental, copyediting, proofreading), structural mapping, topic gap detection, logical strengthening, style guide enforcement, readability analysis (Flesch-Kincaid, Gunning Fog), tracked changes with latexdiff, multi-perspective peer review simulation (three personas), and addressing reviewer comments with response templates.

9. **Finalizing the Manuscript for Submission** --- Formatting and style compliance, reference validation, proofreading, journal AI policy landscape (Nature, Science, JAMA, PLOS, Elsevier, IEEE, ACM), format conversion between journal templates, supplementary materials organization, expanded compliance checklist with CRediT taxonomy, word counting in LaTeX, conditional compilation for multiple journals, preprint archiving strategy, proof review, ethical compliance, and submission package assembly.

10. **Scaling to Book-Length Projects** --- Multi-chapter project structure, chapter briefs, chapter-by-chapter generation workflow, cross-chapter consistency, index generation, front and back matter, three collaborative labor division patterns (Traditional, Hybrid, Artifact-focused), six quality gate criteria, project timeline and sequencing, and automated build and verification.

11. **Future Additions, Tangents, and Spin-Offs** --- Capturing and organizing ideas for future work, spin-off project templates.

12. **Ethics, Policy, and the Future of AI-Assisted Scholarship** --- Professional organization guidelines (ICMJE, COPE, WAME), copyright and intellectual property, the risk of homogenization, bias propagation in AI-assisted literature reviews (language, citation, and institutional bias with mitigation strategies), AI in peer review, reproducibility and transparency requirements, institutional capacity building, emerging tools, and four core principles for responsible scholarship.

13. **Guidelines, Checklists, Protocols, and Helpful Hints** --- AI-enhanced daily protocol, AI disclosure protocol with structured interaction log, and the AI-Augmented Writer's Creed.

### Four Recurring Themes (from the Book)

The protocol is built on four themes that recur across all chapters of the companion book:

1. **Verification is not optional.** Every chapter that involves generating text, citations, or data includes a corresponding verification step. Verification of AI-generated content should be treated with the same seriousness that a laboratory scientist treats calibration of an instrument: if you have not verified the output, you do not know what you have.

2. **The human author remains the author.** ICMJE, COPE, and every major publisher have made clear that AI tools cannot satisfy the criteria for authorship because they cannot take responsibility for the work. Every prompt, every editorial decision, every acceptance or rejection of generated text is the author's responsibility.

3. **Reproducibility extends to the writing process itself.** If we expect scientific results to be reproducible, we should expect the same of the process that produced the manuscript. The protocol advocates sharing not only data and code but also the prompts, skills, and workflow configurations used during AI-assisted writing.

4. **LaTeX compilation is a solved problem if you let the machine iterate.** The compile-check-fix loop---a bounded iteration in which Claude Code compiles a document, parses the log for errors, applies a targeted fix, and recompiles---eliminates the frustration of debugging AI-generated LaTeX by hand.

### The Power Tool Analogy

Claude Code is a power tool for academic writing. A table saw does not replace the cabinetmaker's judgment about joinery, grain direction, or design---but it does let the cabinetmaker cut more wood, more precisely, and in less time. Claude Code amplifies the author's productivity, but it also amplifies the consequences of unchecked assumptions.

### Time Savings May Be Illusory

AI can compress seven hours of initial drafting into 20 minutes, but that initial draft represents only 2--5% of total effort on a writing project. Most effort goes to data analysis, reading, figure preparation, and rewriting. The net time savings from responsible AI use are on the order of 10%. The focus should be on producing higher-quality work, not on producing more papers faster.

### AI Disclosure Protocol

The protocol includes a structured AI disclosure section that tracks every AI interaction contributing to the manuscript: date and time, AI system (name and version), prompt provided, output received, how the output was used (verbatim, paraphrased, inspiration only, or discarded), and which manuscript section was affected. This log makes it straightforward to complete AI disclosure forms required by journals including Nature, Science, JAMA, PLOS, Elsevier, IEEE, and ACM.

### How to Use

1. Copy `writingLogAIprotocol.org` into your writing project directory.
2. Rename it to reflect your project (e.g., `logAI-myproject.org`).
3. Set up your AI environment following Phase 0 (Foundations).
4. Work through Phases 1--3 during project initiation and planning.
5. During daily writing sessions, use Phase 5 (Daily Log) with context management and the Hemingway bridge.
6. When drafting, follow Phase 6 with the prompt template library and grounding documents.
7. After drafting, run the Phase 7 (Verification) three-layer framework.
8. Revise using Phase 8 (three levels of editing, peer review simulation).
9. Finalize and submit using Phase 9 (compliance, formatting, preprint archiving).
10. For book projects, scale up with Phase 10 (chapter briefs, quality gates).
11. Before submission, complete the AI disclosure log and review Phase 12 (ethics and policy).
12. Consult Phase 13 (Guidelines) for the daily protocol, AI disclosure protocol, and Writer's Creed.

### Companion File: AIaid.org

The file `AIaid.org` contains three curated lists of 25 items each:

1. **Twenty-Five Ways AI Agents Can Assist with Research and Information Retrieval** --- From literature database searching and citation tracing to preprint monitoring and glossary compilation.
2. **Twenty-Five Ways AI Agents Can Assist with Draft Assembly** --- From outline generation and prose conversion to terminology harmonization and journal-requirement compliance.
3. **Twenty-Five Ways AI Agents Can Assist with Finalizing a Manuscript for Submission** --- From formatting checks and reference validation to ethical compliance verification and submission package assembly.

These lists provide a quick reference for AI capabilities at each stage. The `writingLogAIprotocol.org` file integrates these capabilities into the writing log structure and adds the critical do-nots and verification chores.

### Companion Book

This protocol is a companion to the book *Scientific Writing with Claude Cowork and Code: A Practitioner's Guide to AI-Aided Manuscript and Book Assembly* by Blaine Mooers (2026). The book's twelve chapters cover foundations, literature retrieval, document structure, compilation loops, figure generation, simulation, drafting, verification, revision, submission, book-length projects, and the future of AI-assisted scholarship. The protocol distills the book's practical workflows into an actionable writing log format.


### Introduction

The writing log is a document that is external to the manuscript.
It stores the plans and progress made on one manuscript.
It is a tool for enhancing your focus and sustaining forward momentum on the writing project.
It is also a tool that eases re-engagement in an interrupted writing project.
It is like a master thinking document or a second brain for a writing project.

Instructions for using the writing log are found in the annotations in the template.
You can delete these after they are no longer needed.

Version 0.8 of the writing log is divided into these sections:

- Project initiation
- Project data
- Plans to support the project
- Timely completion
- Daily entries
- Future additions and tangents
- Guidelines, checklists, protocols, and helpful tips

The subsections of these sections are shown below.


### Project initiation

- Rationale
- Audience
- Target journals
- Related projects
- Potential Introduction
- Potential Results
- Potential Discussion points
- Prior discussion points
- Potential titles
- Potential keywords
- Potential abstract
- Abbreviations
- Potential collaborators
- Potential competitors
- Potential reviewers
- Draft cover letter


### Project Data

- Inventory of data on hand
- Inventory of project's required external software
- Inventory of the project's software repositories
- Relevant videos
- Relevant blogs
- Relevant literature sources
- Relevant collections of PDFs
- Project's progress summary for the annual grant report
- Project's progress summary for the annual report to college


### Plans to support the project

- Budget
- Relation to specific aims of funded grants.
- Secure funding for the research and manuscript.
- Timeline to do the required experiments to test the hypothesis.
- Secure access to required national laboratory resources at experimental stations (i.e., general user proposal and beamtime requests).
- Secure access to computing resources.
- Gather the appropriate information from the literature.
- Recruit collaborators
- Recruit lab members to do the work.
- Individual career development for lab members, including yourself.
- Biosafety.
- Authentication of key biological and chemical resources.
- Rigorous statistical sampling and data analysis
- Data management, including backups and archives.
- Data sharing.
- The NIH PEDP.
- Advertising plan: posters, talks, seminars, YouTube videos, social media posts.


### Project management for timely completion

- Checklist for manuscript completion.
- Timeline and Milestones.
- Periodic assessments of the current state of the manuscript.


### Daily entries

Create the following yasnippet snippet with the tab trigger of `daily` to auto-generate a subsection heading, property box, and index key using today's date.
Save it to a file named daily-entry-for-writing-log inside `./snippets/org-mode`.

```elisp
# -*- coding: utf-8 -*-
# group: writing-log
# name: daily-entry-for-writing-log
# key: daily
# --
** `(format-time-string "%Y-%m-%d")`
:PROPERTIES:
:CUSTOM_ID: `(format-time-string "%Y-%m-%d")`
:END:
#+Latex:\index{`(format-time-string "%Y-%m-%d")`}
$0
```

Now type `entry` followed by `tab` to start a new subsection for the current day's entry.


- Daily Log
- Update writing progress notebook
- Update personal knowledge base
- Timeline or Benchmarks
- Next action
- To be done
- Word Count

### Future additions and tangents

- Ideas to consider adding to the manuscript
  + Introduction
  + Results
  + Discussion
- To be done someday
- Spin-off writing projects


### Guidelines, checklists, protocols, helpful hints

This part of the writing project log may require customization.
You may want to include project-specific protocols.
You may have already written down your own protocols that you want to include, or the space for such protocols may stimulate you to develop protocols for multi-step processes you must go through in your work.
Having those multi-step processes recorded in a protocol and readily accessible in this document increases the probability that the protocol will be followed and that you will save time by avoiding mistakes.

We have made a variant of this writing log where this section is modular.
The modularity eases the inclusion and exclusion of various protocols and guidelines so that you can customize this section of the writing log to be most relevant to the writing project at hand.
Seek repositories on this website with the words modular and writing log.

Below is a list of protocols you can delete, supplement,  or expand upon.

- Daily Protocol
- Tips for using Overleaf
- Protocol for running Grammarly in Overleaf
- Guidelines for debugging the annotated bibliography
- Graphical Abstract
- Guidelines for benchmarks
- Guidelines for using the Writing Progress Notebook
- Guidelines for using a personal knowledge base
- Protocol for wrapping up the project and archiving data.

#### Standard Protocols

We store files containing established protocols in the home directory.
These files can be included in all writing-project log files.
This enables updating one file and propagating these updates to all log files.
In an org file, you can use the org-mode `#+INCLUDE:` or the LaTeX `\include{}`.
These included files will only be injected into the log file upon export to PDF.

To inject the contents of the external file into an org-mode file so that you see the protocol in the org file, use the following function.
It includes the file path of the injected file and a timestamp of when the external file was injected.

```elisp
(defun org-insert-external-file (file-path)
  "Insert the contents of an external file into the current org-mode file.
Prompts for a file path via minibuffer and includes a timestamp in a comment."
  (interactive "fFile to be inserted: ")
  (let ((timestamp (format-time-string "%Y-%m-%d %H:%M:%S")))
    (insert (format "#+BEGIN_COMMENT\n# File %s inserted on %s\n#+END_COMMENT\n\n" file-path timestamp))
    (insert-file-contents file-path)
    (goto-char (point-max))))

(global-set-key (kbd "C-c S") 'org-insert-external-file)
```
Here is an example of the output.

```org-mode
** Protocol to generate a bib file with only cited references
#+BEGIN_COMMENT
# File ~/protocols-org/bibfileCitedOnly-writing-checklist.org inserted on 2024-12-06 04:16:21
#+END_COMMENT
- [ ] Run the following code to generate a bib file of the papers cited in a manuscript:
- [ ] bibtool --preserve.key.case=on -x main.aux > cited.bib
- [ ] main.tex is the manuscript file.
- [ ] Note that the *main.aux* file is hidden on Overleaf under the "Logs and outputs" pulldown menu.
- [ ] The first flag in the command will preserve the letter case in the cite key.
```

Here is a modified form of the above function that prepends the file path to the protocols directory:

```elisp
(defun org-insert-protocol-file (file-path)
  "Insert the contents of a protocol file from ~/protocols-org into the current org-mode file.
Prompts for a file path via minibuffer and includes a timestamp in a comment."
  (interactive (list (read-file-name "Directory `~/protocols-org/`: " "~/" "protocols-org/")))
  (let ((full-path (expand-file-name file-path))
        (timestamp (format-time-string "%Y-%m-%d %H:%M:%S")))
    (insert (format "#+BEGIN_COMMENT\n# File %s inserted on %s\n#+END_COMMENT\n\n" full-path timestamp))
    (insert-file-contents full-path)
    (goto-char (point-max))))

(global-set-key (kbd "C-c P") 'org-insert-protocol-file)
```

Disclosure: The last two functions were generated with Lama 3.1 70B via the Sider plugin for Google Chrome.
The functions were tested, and they worked as advertised.

## Usage

- `git clone https://github.com/MooersLab/writingLogTemplateInOrg` into the folder containing your current writing project.
- Start Emacs, perhaps using this [Emacs configuration](https://github.com/MooersLab/dsw-2024-org-mode-init).
- Load the writingLogTemplate.org file into Emacs via `C-x C-f`.

## Configure yasnippets

You may want to enable yasnippets to make available your latex-mode and org-mode snippets while editing the writinglog.org file in org-mode.

1. In your `~/.emacs.d/snippets/latex-mode`, create a file named `.yas-parents`.
2. Add the following to this file:

```elisp
latex-mode
org-mode
```
3. Under the Yasnippets pulldown, select `reload everything` or in the minibuffer, enter `M-x yas-reload-all`.


## Essential keybindings for editing this file in org-mode:
  + `C-g` to abort current command.
  + `C-x C-c` to quit Emacs
  + `C-x C-s` to save the current document.
  + `C-c C-e l o` to export to pdflatex and BibTeX and open the resulting PDF in the default PDF viewer.
  + `C-x u` to undo the last change.
  + `M-UP` or `M-DOWN` to shift lines up and down. UP and Down are the arrow keys.
  + `C-3 S-tab` to collapse the whole document while showing headlines down to the 3rd level. Change the number to collapse to a different level.
  + `C-x C-o` to show the outline view using consult. This is the same as `M-x consult-outline`. This consult command collapses the document into a more compact format than `C-s S-tab` command. As a result, it is easier to navigate. You have to install the consult package.

The [latex-emacs profile](https://github.com/MooersLab/latex-emacs) can access org-mode because it is built into Emacs.

## Using with org-pomodoro

The daily log section is the ideal place for running a Pomodoro timer.
The daily entries have a property drawer.
Place the cursor or point below the current day's heading and enter `C-c o` to start a Pomodoro with the start and end times logged in a logbook in the property drawer.


## Bash function for creating a writing log for a new project

At the start of a writing project, use this function to write a copy of the writing log template to a file with the project name.
Store this Dash function in the `.bashrc` or `.zshrc` file. Oh shoot too

```bash
function logorg {
echo "Copy template writing log in org with project number in title."
if [ $# -lt 1 ]; then
  echo 1>&2 "$0: not enough arguments"
  echo "Usage1: logorg projectID"
  return 2
elif [ $# -gt 1 ]; then
  echo 1>&2 "$0: too many arguments"
  echo "Usage1: logorg projectID"
  return 2
fi
projectID="$1"
echo "Write writing log to log$1.org file."
cp  ~/6112MooersLabGitHubLabRepos/writingLogTemplateInOrg/writingLogTemplateVer5.org log$1.org

}
```

## Some relevant functions in [Mooerslab/mooereslab-functions-el](https://github.com/MooersLab/mooerslab-functions-el)

This repository contains my collection of useful functions to ease the use of this writing log and org-mode in general.

- add-periods-to-list
- org-add-periods-to-list-items
- org-insert-protocol-file (I now store my protocols in ~/org-roam for fast discovery and recall)
- region-to-itemized-list-in-org
- region-to-todos-in-org
- region-to-itemized-in-latex
- latex-to-org-list-region
- region-csv-to-org-table
- create-org-table-with-caption
- count-non-blank-lines
- export-csv-to-sqlite-table (great for creating databases from csv files)
- export-csv-to-matched-sqlite-table (great for adding data in csv file to existing database)
- get-citekeys-from-bibtex-file
- wrap-citekey-and-create-tex-file
- insert-org-captioned-figure
- org-convert-checkboxes-to-todos
- org-move-to-tag
- append-todo-to-tagged-headline
- open-new-abibnote-on-citekey
- split-sentences-into-lines (very useful for splitting the long line of sentences returned from the whisper-file transcription)

## Directly related talks
- [DSW 60-minute talk about scientific writing workflow in Org Mode: November 22, 2024](https://mediasite.ouhsc.edu/Mediasite/Channel/python/watch/cd5641aea892468c894ae31cd151d4671d)
- [Slides from the above talk](https://github.com/MooersLab/DSW24-org-mode-slides)
- [Emacs configuration associated with the above talk](https://github.com/MooersLab/dsw-2024-org-mode-init)

- [EmacsConf24 20-minute talk: December 7, 2024](https://emacsconf.org/2024/talks/project/)

## Related projects of possible interest
- [Org-mode manuscript template](https://github.com/MooersLab/manuscriptInOrg)
- [LaTeX manuscript template](https://github.com/MooersLab/manuscriptInLaTeX)
- [Writing log template in LaTeX (compiles on Overleaf and in Emacs)](https://github.com/MooersLab/writingLogTemplate)
- [Writing log template in reStructuredText](https://github.com/MooersLab/writing-log-rst) reStructuredText is used by programmers for documentation.
- [Writing log template in Markdown](https://github.com/MooersLab/writing-log-md) Markdown variant. Read and rendered to PDF by most good text editors.
- [Writing log template in ODT](https://github.com/MooersLab/writing-log-odt) ODT can be read by Open Office, LibreOffice and MS Word.
- [Writing log template in DOCX for MS Word](https://github.com/MooersLab/writing-log-docx) MS Word variant. Probably the least suitable format for this task.
- [Programming log in Org](https://github.com/MooersLab/programmingLogInOrg)

- [Slideshow template in LaTeX](https://github.com/MooersLab/slideshowTemplateLaTeX)
- [Annotated bibliography Template in LaTeX](https://github.com/MooersLab/annotatedBibliography)
- [LaTeX manuscript template](https://github.com/MooersLab/manuscriptInLaTeX/edit/main/README.md)
- [Org-mode manuscript template](https://github.com/MooersLab/manuscriptInOrg/edit/main/README.md)
- [Slideshow template in LaTeX](https://github.com/MooersLab/slideshowTemplateLaTeX)
- [Annotated bibliography Template in LaTeX](https://github.com/MooersLab/annotatedBibliography)
- [Diary for 2024 in LaTeX](https://github.com/MooersLab/diary2024inLaTeX)- [latex-emacs profile](https://github.com/MooersLab/latex-emacs)
- [default Emacs profile](https://github.com/MooersLab/configorg)
- [snippets for latex-mode in Emacs](https://github.com/MooersLab/snippet-latex-mode)
- [Quizzes about Emacs to improve recall of keybindings](https://github.com/MooersLab/qemacs)
- [Slides from talk about GhostText, Data Science Workshop, July 2022](https://github.com/MooersLab/DSW22ghosttext)
- [Video link to talk about GhostText, Data Science Workshop, July 2022](https://mediasite.ouhsc.edu/Mediasite/Channel/python/watch/4da0872f028c4255ae12935655e911321d)
- [Slideshow about using LaTeX in Emacs, Berlin Emacs Meetup, 31 August 2022](https://github.com/MooersLab/BerlinEmacsAugust2022)
- [The writer's crede](https://github.com/MooersLab/thewriterslaw)


## Update history

|Version      | Changes                                                                                      | Date                 |
|:-----------|-----------------------------------------------------------------------------------------------|:--------------------|
|  0.1 | First working version.                                                                              | 2022 September 10    |
|  0.5 | Added five sections to catch up with the tex version.                                               | 2024 August 11      |
|  0.6 | Compiles now without init.el file. Moved `Daily protocol` to `Guidelines` section. Elevated  `Daily Log` to section level. | 2024 August 18      |
|  0.7 | Moved the comments or advice prose into a GUIDANCE drawer in each section outside of the Guidelines section. | 2024 August 21      |
|  0.7.1 | Added subheading with noexport tag above each GUIDANCE drawer to prevent the export of their contents to the PDF.  Added the urlx package to linewrap long URLs. | 2024 August 27      |
|  0.7.2 | Added STARTUP command to open file with the drawers closed. | 2024 September 13 |
|  0.7.3 | Explained introduction to distinguish this tool from writing accountability tools. | 2024 October 30 |
|  0.8.0 | Added :restart: tag to position the cursor at the end of the last daily entry in the Daily Log section upon opening the document in Emac. Made minor updates to the README.md file including link to talk about this document. | 2024 November 28 |
| 0.8.1 | Added function to insert contents of external files. This is very cool!                            | 2024 December 6 |
| 0.8.2 | Added :appendtodos: tag to headline above TODO list in middle of document to work with org-projects.el. Replaced Next Action with  Hemmingway Bridge.                           | 2025 March 21 |
| 0.8.3 | Added list of useful functions found in mooerslab-functions-el                         | 2025 March 27 |
| 0.8.4 | Added section at beginning for drafting alternate central hypotheses.  | 2026 January 5 |
| 0.8.5 | Added AIaid.org with 75 ways AI agents can assist across three manuscript phases.  | 2026 March 28 |
| 0.9.0 | Added `writingLogAIprotocol.org`: AI Agent-enhanced writing log protocol with AI dos, do-nots, and verification chores for every section of the writing log. Updated README with full documentation. | 2026 March 28 |
| 0.9.1 | Major expansion of `writingLogAIprotocol.org` from 9 to 14+ phases, integrating content from all 12 chapters of *Scientific Writing with Claude Cowork and Code*. Added: Phase 0 (Foundations with MCP servers), Phase 4 (Compilation loops), Phases 7-8 (Figures, Simulation), Phase 10 (Three-layer verification), Phase 11 (Three-level revision), Phase 13 (Book-length projects), Phase 14 (Ethics/policy). Expanded literature retrieval with MCP integration, added prompt templates, /rewritechapter skill, grounding documents, journal AI policies, collaborative patterns, and quality gates. Protocol grew from 1,339 to 4,442 lines. | 2026 March 28 |

## Sources of funding

- NIH: R01 CA242845
- NIH: R01 AI088011
- NIH: P30 CA225520 (PI: R. Mannel)
- NIH: P20 GM103640 and P30 GM145423 (PI: A. West)


<!-- Local Variables: -->
<!-- jinx-local-words: "BibTeX" -->
<!-- End: -->