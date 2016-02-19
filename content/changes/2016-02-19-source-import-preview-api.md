---
kind: change
title: GitHub Importer Preview API
created_at: 2016-02-19
author_name: spraints
---

We've added an API for source imports, which will let you start an import from a Git, Subversion, Mercurial, or Team Foundation Server source repository. This is the same functionality as [the GitHub Importer](https://import.github.com/).

To access [the Source Import API][docs] during the preview period, you must provide a custom [media type][media-type] in the `Accept` header:

    application/vnd.github.barred-rock-preview

If you have any questions or feedback, please [let us know][contact]!

[media-type]: /v3/media
[docs]: /v3/migration/source_imports/
[contact]: https://github.com/contact?form%5Bsubject%5D=Source+Import+API