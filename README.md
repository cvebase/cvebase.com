<p align="center">
<img src="assets/cvebase-logo.png" alt="cvebase" title="cvebase" />
</p>

This is the official data repository for cvebase, open to all and can be edited by anyone to collectively improve the CVE & Researcher pages. Updates are immediately synced with the content at [cvebase.com](https://www.cvebase.com/).

### About cvebase
cvebase is a community-driven data platform for security vulnerabilities, developed for use by security researchers, penetration testers, and bug bounty hunters.

* Researcher profiles feature their published CVEs to date.
* Community commentary enhances and clarifies official CVE vendor advisories.
* References link to valid Proof-of-Concept Exploits and detailed technical writeups.

![](assets/cvebase_examples.png)

## About this repository
This repository contains the Markdown files for the two main components of cvebase.com:
* `cve`: CVE files are located in the `/cve/` directory, organized by year and sequence identifier following the naming scheme set by [`CVEProject/cvelist`](https://github.com/CVEProject/cvelist).
* `researcher`: Researcher profiles are in the `/researcher/` directory, named by researcher slug.

Inspired by static site generator [`gohugoio/hugo`](https://github.com/gohugoio/hugo), the Markdown files have YAML "front matter" to define metadata for both CVEs and Researchers.

See example files here:
* [/cve/2020/15xxx/CVE-2020-15505.md](https://raw.githubusercontent.com/cvebase/cvebase.com/main/cve/2020/15xxx/CVE-2020-15505.md)
* [/researcher/orange.md](https://raw.githubusercontent.com/cvebase/cvebase.com/main/researcher/orange.md)

## Status
The project is currently under active development. Please follow us on twitter [@cvebase](https://twitter.com/cvebase) and check back soon.

## Contributing
* Send pull requests
* [Create an issue](https://github.com/cvebase/cvebase.com/issues) in this repository

## License
Repository content licensed [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
