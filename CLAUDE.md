# Forward Deployed — writing conventions

## Sourcing real-world claims

Every claim about the real world (history, statistics, companies, laws, regulations, published research) must carry a source with a link.

- Use a Markdown footnote at the end of the sentence: `...as reported by the FT.[^short-id]`
- Collect footnote definitions under a `## Sources` heading at the end of the file, after a `---` rule.
- Each source gives author or publisher, title in italics, date where known, and the URL in `<angle brackets>`.
- Prefer primary sources (the original report, filing, opinion or paper). If only secondary coverage is available, say so in the footnote.
- If a claim cannot be sourced, soften it or remove it. Never present an unsourced figure as fact.

Fictional elements of the Mehra & Cole case (people, firm, numbers) need no sources.

## Structure: build the mental model while reading

Readers should be able to skim a chapter and come away with its structure. Avoid walls of prose.

- **Open each chapter with its point and a structure map**: one to three sentences stating the main point, then a small tree (in a code block) showing the chapter's branches. Each section then fills in one branch.
- **Each section follows the same rhythm:**
  1. A short lead paragraph (one to three sentences) that states the section's point.
  2. Pointers: a bulleted or numbered list, each item starting with a **bold label** and kept to one or two lines.
  3. A short paragraph that explains the "so what": how the pointers connect, and how they tie back to the chapter's tree.
- Keep paragraphs to about four sentences at most. Prefer short sentences.
- Narrative scenes and dialogue can stay as prose, but break them up with headings, and follow each scene with pointers that pull out what it shows.
- End each chapter with a reference section (tables) a reader can come back to.

`book/02-prologue-what-a-forward-deployed-engineer-is.md` is the model to follow.
