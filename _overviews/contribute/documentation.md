---
title: Documentation Contributions
num: 5
---
## Contributing Documentation to the Scala project

There are several ways you can help out with the improvement of Scala documentation. These include:

* API Documentation in Scaladoc
* Guides, Overviews, Tutorials, Cheat Sheets and more on the [docs.scala-lang.org][home] site
* Updating [scala-lang.org](https://scala-lang.org)

Please read this page, and the pages linked from this one, fully before contributing documentation. Many frequently asked questions will be answered in these resources. If you have a question that isn't answered, feel free to ask on the [Scala Contributors](https://contributors.scala-lang.org/) forum and then, please, submit a pull request with updated documentation reflecting that answer.

**General requirements** for documentation submissions include spell-checking all written language, ensuring code samples compile and run correctly, correct grammar, and clean formatting/layout of the documentation.

Thanks

### API Documentation (Scaladoc)

The Scala API documentation lives with the scala project source code. There are many ways you can help with improving Scaladoc, including:

* [Log issues for missing scaladoc documentation][report-api-doc-bugs] -
Please *follow the issue submission process closely* to help prevent duplicate issues being created.
* [Claim Scaladoc Issues and Provide Documentation][scala-standard-library-api-documentation] - please claim issues prior to working on a specific scaladoc task to prevent duplication of effort. If you sit on an issue for too long without submitting a pull request, it will revert back to unassigned and you will need to re-claim it.
* You can also just
[submit new Scaladoc][scala-standard-library-api-documentation]
without creating an issue, but please look to see if there is an issue already submitted for your task and claim it if there is. If not, please post your intention to work on a specific scaladoc task on [Scala Contributors](https://contributors.scala-lang.org/) so that people know what you are doing.

### The Main Scala Documentation Site

[docs.scala-lang.org][home] houses the primary source of written, non-API documentation for Scala. It's a GitHub project that you can fork and submit pull requests from. It includes:

* Overviews
* Tutorials
* Conversion Guides from Other Languages
* Cheat Sheets
* A Glossary
* The Scala Style Guide
* The Scala Language Specification
* SIP (Scala Improvement Process) Proposals
and more

Please read [Add New Guides/Tutorials][add-guides] through before embarking on changes. The site uses
the [Jekyll](https://jekyllrb.com/) markdown engine so you will need to follow the instructions to get that running as well.

### Updating scala-lang.org

Additional high-level documentation (including documentation on contributing
to Scala and related projects) is provided on the main
[Scala Language site](https://scala-lang.org), and is also kept in the
[scala-lang GitHub project](https://github.com/scala/scala-lang) which may be forked to create pull requests.

Please read both the
[Add New Guides/Tutorials][add-guides] document and the [scala-lang.org GitHub README](https://github.com/scala/scala-lang#scala-langorg) before embarking on any changes to the Scala language site, as it uses the same Jekyll markdown tool and many of the same conventions as the Scala documentation site.

[report-api-doc-bugs]: {% link _overviews/contribute/scala-standard-library-api-documentation.md %}#contribute-api-documentation-bug-reports
[scala-standard-library-api-documentation]: {% link _overviews/contribute/scala-standard-library-api-documentation.md %}
[home]: {% link index.md %}
[add-guides]: {% link _overviews/contribute/add-guides.md %}
