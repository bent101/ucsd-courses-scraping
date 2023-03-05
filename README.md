# Scraping the UCSD course catalog

The UCSD course catalog is littered with inconsistency under the hood. This notebook scrapes all 6,888 courses across 82 pages, cleans the data, and puts it in a JSON file for manual fixing. It then parses the data, indexes the courses, and finally "compiles" the data to 82 Svelte files. It replaces mentions of courses with components that I can add custom styles/functionality to. For example, all mentions of CSE 100 become `<CourseLink id={1837} href="/CSE#100">CSE 100</CourseLink>`. There's probably a better way to do this, but I don't know it.
