# Documentation Guide

## Structure

The [root README](../README.md) is the short project overview. [Wiki Home](wiki_snapshot/Home.md) provides a project dashboard and links to topic pages. The [sidebar](wiki_snapshot/_Sidebar.md) provides complete navigation.

## Editing guidance

- Keep one topic per page and update navigation when adding pages.
- Check claims against the original TrueMatch report and available artifacts.
- Distinguish personal work from team functionality.
- Distinguish historical reporting, current checks and planned verification.
- Keep repository-relative links valid.
- Preserve team attribution.

The pages were drafted with AI assistance, checked against the supplied resume and archived project materials, and remain subject to the owner's review.

## Native GitHub Wiki publication

The pages under `wiki_snapshot/` are versioned Wiki source and are already browsable in the repository. No publication to the separate Wiki tab is claimed.

The connector does not expose Wiki writes, and the separate Wiki Git repository could not be accessed in this session. To publish after review:

1. Open the repository's Wiki tab and create a Home page if needed.
2. Add the topic pages with the same file basenames as page titles.
3. Change links between Wiki pages from `Project-Overview.md` to `Project-Overview`, and similarly for other pages.
4. Replace repository-relative artifact and README links with full URLs on the published branch.
5. Use `_Sidebar.md` as the custom sidebar, with the same link conversions.
6. Verify navigation before linking the root README to the live Wiki.

Keep the live Wiki and repository snapshot synchronized after future changes.
