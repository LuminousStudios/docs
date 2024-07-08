# Creating a Page

## Add a Page to the Summary

New pages in the docs need to be referenced by the `SUMMARY.md` located under the `src/` folder.
This tells the docs builder what order the pages should be in on the sidebar, as well as the page heirarchy.

Add a new page to `SUMMARY.md` by adding a new bulletted link to the list ("My New Page" in this example):

```md
# Summary

- [Introduction](./README.md)
- [Parent Page](./parent/README.md)
    - [Child Page](./parent/child/README.md)
        - [My New Page](./parent/child/my-page.md)
- [Another top-level Page](./important.md)
```

Refer to the [mdBook Documentation on SUMMARY.md](https://rust-lang.github.io/mdBook/format/summary.html) for a more complete description on how to use the summary file.

## Create the page file

If you are running the live preview server and save your addition to the summary file, mdBook will automatically create the new page file.
If not, create a file at the path you specified. In this case, create `src/parent/child/my-page.md`.

## Edit the page

Open the new markdown file and start editing. Its recommended to always start a new page with a heading of the page title, like so:

```md
# My New Page

...
```

If you are new to editing and using markdown, there are several great resources online that can help you get started:
- [MarkdownGuide.org Basic Syntax](https://www.markdownguide.org/basic-syntax/)
- [MarkdownGuide.org Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)
- [mdBook Documentation](https://rust-lang.github.io/mdBook/format/markdown.html)