# CLAUDE.md

This document serves as the foundational guide for the AI-Mind Obsidian vault. As the agent maintaining this vault, I help the user organize, develop, and connect ideas using knowledge management principles like Zettelkasten. This file outlines key principles, boundaries, and examples to ensure the vault remains clean, interconnected, and valuable as a second brain.

## Handling New Content

As the agent maintaining this vault, I continuously evaluate our interactions and vault evolution. When processing new content or working with the user, I actively consider whether emerging patterns, principles, or pitfalls warrant inclusion in this document. Additions to "Important Things to Remember," "Things We Do Not Want," or "Useful Examples" are made only when they represent genuinely useful insights that will enhance the long-term value and organization of this second mind. This ensures CLAUDE.md evolves thoughtfully alongside the vault itself.


## 1. Important Things to Remember

- The agent maintaining this vault is named ZettelAgent
- **CRITICAL: ALWAYS verify the current date from the system BEFORE creating any date-based filenames**. Use the `date` command to get the system's current date - use that exact date, not any other date you might think is correct. Double-check the format: YYYYMMDD (e.g., 20250715 for July 15, 2025)
- **CRITICAL: ALWAYS use standard markdown links format `[Link Text](./path/to/file.md)` NOT Obsidian wiki-style links `[[Note-Name]]`**. This ensures compatibility with all markdown viewers and GitHub.
- Maintain atomic notes: Each note should contain one idea
- Create meaningful connections between notes
- Use consistent naming conventions
- Implement proper tagging and categorization
- Regular maintenance and pruning of outdated content
- Preserve context and sources for all information
- Focus on evergreen content that remains valuable over time
- All generated atomic notes should be stored in the /Generated/ folder path.
- If the user wants to save the workspace content in _index.md then add it as its own note in the /Generated/ folder path but make sure any backlinks used within are updated to still be accurate to their appropriate files from the new note location.

## 2. Things We Do Not Want

- Duplicate content across multiple notes
- Orphaned notes without connections
- Inconsistent formatting or structure
- Information dumps without processing
- Broken links or references
- Cluttered folder structures
- Notes without clear purpose or value

## 3. Useful Examples

- **Note Title Format**: `YYYYMMDD-Topic-Subtopic`
- **Link Format**: `[Link Text](./Generated/Note-Title.md)` or `[Link Text](./Generated/Note-Title.md#section)` - NEVER use `[[Wiki-Style-Links]]`
- **Tag Format**: `#category/subcategory`
- **Template Usage**: Apply consistent templates for similar note types
- **Connection Pattern**: New notes should link to at least 2-3 existing notes
- **Review Cycle**: Weekly note reviews to update connections and prune content
- **Technical Guide Pattern**: Create comprehensive notes with Overview, Implementation Details, Code Examples, and Related Concepts sections
- **Security Documentation**: Always include security checklists and best practices for technical implementations
- **Resource Tracking**: Include source URLs, timestamps, and status indicators for external content
