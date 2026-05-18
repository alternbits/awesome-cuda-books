# Contributing to Awesome CUDA Books

Thanks for your interest in improving this list! Contributions of all sizes are welcome — adding a new book, fixing a broken link, correcting an author or year, or improving a description.

## What belongs on this list

A book is a good fit if it meets **all** of the following:

- **Substantial CUDA content.** General GPU or parallel-computing books only qualify if a significant portion is dedicated to CUDA specifically.
- **Code or worked examples.** Pure-theory titles with no kernels/examples are out of scope.
- **Credible publication.** Established publisher (NVIDIA, Addison-Wesley, Packt, Cambridge, Manning, O'Reilly, Wrox, Morgan Kaufmann, CRC, Springer, etc.) **or** a self-published title with verifiable positive reviews and a real author.
- **Still useful.** Prefer titles from **2018 or later**, or older classics that remain widely cited (e.g., *CUDA by Example*, *PMPP*).
- **In English** (for now — open an issue if you'd like to propose a non-English section).

Out of scope: blog posts, video courses, single-chapter mentions inside a broader book, AI-generated filler books with no real author, and duplicates of titles already listed.

## How to submit

1. **Fork** the repo and create a branch (`add-<short-book-name>`).
2. **Add the entry** to the most appropriate section, keeping alphabetical or chronological order consistent with neighbors.
3. **Open a pull request** with a short description of why the book belongs and, if possible, a link to a review, table of contents, or sample chapter.

For small fixes (typos, broken links, wrong year), a PR with no extra context is fine.

## Entry format

Each entry uses this exact shape:

```markdown
- **[Book Title](https://link-to-publisher-or-amazon)**
  *Author Name(s) (Year, Publisher)*
  One- or two-sentence description focused on what makes it useful and who it's for.
```

Guidelines:

- **Link target.** Prefer the publisher's page over Amazon when both exist. Avoid affiliate links and tracking parameters.
- **Authors.** List all authors as they appear on the cover, separated by `&` for two or by commas for three or more.
- **Year.** Use the original publication year; note a later edition in parentheses if you're linking to it (e.g., *3rd Edition, 2022*).
- **Description.** Plain, factual, ≤ 200 characters. No marketing language ("revolutionary", "must-read"). Mention the audience or distinguishing angle (e.g., "engineer-focused", "best for Python users", "deep-dive reference").

## Section placement

- **Beginner / Getting Started** — first CUDA book for someone new to GPU programming.
- **Core Architecture & Parallel Programming** — emphasis on GPU hardware model and parallel-thinking foundations.
- **Practical & Hands-on Guides** — real-world projects, scientific computing, multi-GPU, streams.
- **Advanced / Optimization / Reference** — deep API coverage, profiling, performance tuning.
- **Python & High-Level CUDA** — Numba, CuPy, PyCUDA, pybind11, RAPIDS.
- **Modern & Recent Releases (2022–2026)** — cross-listed pointer to newer entries already placed above.

If a book fits two sections, put the full entry in the more specific one and add a one-line pointer in the other.

## Style and quality checks

Before opening your PR, please verify:

- [ ] Link works and points to a canonical source.
- [ ] No duplicate entry (search the existing readme).
- [ ] Markdown renders correctly (use a previewer or GitHub's "preview changes" tab).
- [ ] No trailing whitespace and the file ends with a single newline.
- [ ] You've placed the entry in the right section and preserved ordering.

## Removing or updating entries

Spotted a book that no longer fits — for example, a dead link, withdrawn title, or a low-quality entry that slipped through? Open an issue or PR explaining the reason. Replacements of older editions with newer ones are welcome; keep the older edition only if it's substantially different (e.g., PMPP 3rd vs. 4th edition).

## Code of conduct

Be respectful in issues and reviews. Disagreements about whether a book belongs are normal — argue from the criteria above, not from authority or taste.

## Questions

Open an issue with the `question` label if you're unsure whether a book fits before doing the work of a full PR.
