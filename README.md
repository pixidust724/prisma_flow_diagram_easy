# PRISMA 2026 Flow Diagram

I vibe coded this single-file, browser-based PRISMA 2026-style flow diagram generator for scoping reviews because I was looking for something similar to a PRISMA diagram but much more lightweight and easier to use. The flow diagram was inspired by https://rayyan.ai/, which a friend shared with me, and I noticed that it is a paid service. Apart from the other cool features they have for literature review, I only needed a scoping review diagram. Hence, this inspired the project. The project is completely vibe coded with claude-opus-4-6 with a few manual edits. You are free to use it for your academic or research purposes.


## Demo

Try it live: https://pixidust724.github.io/prisma_flow_diagram_easy/

## Usage

Open `index.html` in any modern browser. Fill in the form on the left and the flow diagram on the right updates live.

### Sections

| Section | What to enter |
|---|---|
| **Identification** | Database sources (one per line), removal reason and count |
| **Screening** | Records screened, exclusion reason and count |
| **Retrieval** | Reports sought, exclusion reason and count |
| **Eligibility** | Reports assessed, exclusion reasons (one per line) |
| **Included** | Final number of studies included |

### Export

Click **Export as PDF** to open the browser print dialog. Only the diagram is included in the PDF.

## Built with

Vibe coded with claude-opus-4-6
