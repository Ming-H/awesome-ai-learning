# Contributing

Contributions are welcome! This project aims to be a high-quality, curated collection of AI learning resources.

## How to Contribute

### Adding a New Resource

1. **Check existing resources** to avoid duplicates
2. **Verify the resource** is actively maintained and high-quality
3. **Add it to the appropriate section** in the relevant topic README
4. **Follow the format** exactly:

```markdown
- [Resource Name](URL) - Description ending with a period. `Type` `Language`
```

### Format Guidelines

- **Title**: Use the official name of the resource
- **URL**: Link to the primary page (not deep links)
- **Description**: One concise sentence, ending with a period
- **Tags**: Use backtick-wrapped tags for Type and Language
  - Type: `Free Course`, `Paid Course`, `Docs`, `Repo`, `Article`, `Video`, `Framework`, `Tool`, `Standard`, `Report`
  - Language: `EN`, `ZH`, `EN/ZH`
- **Sorting**: Add new entries at the end of the appropriate subsection
- **⭐ mark**: Only for Editor's Picks (top 2-3 per category, not for new additions without discussion)

### Example

```markdown
- [ChatGPT Prompt Engineering for Developers](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers) - Andrew Ng + OpenAI most recommended introductory course. `Free Course` `EN`
```

### Adding a New Topic

1. Create a new directory with numbered prefix (e.g., `11-new-topic/`)
2. Add a `README.md` following the existing structure (Courses, Repos, Docs, Learning Path)
3. Update the main `README.md` table of contents
4. Submit a PR with a clear description of why this topic is needed

### Pull Request Process

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-resource`)
3. Make your changes
4. Ensure no broken links
5. Submit a PR with:
   - Clear title describing the addition
   - Brief explanation of why this resource is valuable
   - Verification that the resource is actively maintained

### Quality Criteria

Resources should meet at least one of:
- Official documentation from a major AI company
- 1,000+ GitHub stars (for repositories)
- Published by a recognized expert or institution
- Actively maintained (updated within the last 6 months)
- Widely recommended by the community

## Code of Conduct

Please read the [Code of Conduct](./CODE_OF_CONDUCT.md) before contributing.
