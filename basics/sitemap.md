# sitemap

I can convert that sitemap XML into GitBook-optimized Markdown, but I can't fetch external URLs directly. Please either:

* Paste the contents of https://fenomeral.gitbook.io/eidolon-guide/sitemap-pages.xml here, or
* Upload the file contents.

If you prefer to do the fetch yourself and paste the result, here are two quick ways to get the sitemap content:

* curl: curl "https://fenomeral.gitbook.io/eidolon-guide/sitemap-pages.xml"
* wget: wget -qO- "https://fenomeral.gitbook.io/eidolon-guide/sitemap-pages.xml"

Once you paste the XML, I will:

* Extract and preserve all page entries and their URLs.
* Remove navigation chrome or in-page table-of-contents that are not part of article content.
* Convert multi-step ordered lists into a GitBook stepper.
* Convert sequences of package-manager code snippets into a tabs block.
*   Convert FAQ Q/A pairs into GitBook expandables (

    ).
* Preserve and not alter any URLs or query parameters.
* Remove placeholder base64 markers if present, and leave any real base64 images unchanged.

If you’d like, I can also:

* Produce a single GitBook Markdown file listing all sitemap URLs, or
* Produce separate Markdown stubs for each URL in the sitemap (title + link + optional excerpt if available), or
* Convert actual page HTML (if you paste the page HTML instead of the sitemap) into cleaned GitBook-optimized Markdown.

Tell me which output format you want (single index file vs separate stubs) and paste the XML (or let me know you want me to proceed after you fetch it).
