<p align="center">
<img src="assets/cvebase-logo.png" alt="cvebase" title="cvebase" />
</p>

This is the official data repository for cvebase. Updates to this repo are immediately synced with the [cvebase.com](https://www.cvebase.com/) web app. Pull requests for improving the content are open to all.

Follow us on twitter [@cvebase](https://twitter.com/cvebase) to stay up-to-date on project updates.

## About cvebase
cvebase is a community-driven vulnerability platform for security researchers, pentesters, and bug bounty hunters:

* Follow security researchers and their latest disclosures: [cvebase.com/researcher](https://www.cvebase.com/researcher)
* Browse trending vulnerabilities: [cvebase.com/cve](https://www.cvebase.com/cve)
* Discover PoC exploits: [cvebase.com/poc](https://www.cvebase.com/poc)
* Learn to reverse CVEs: [cvebase.com/lab](https://www.cvebase.com/lab)

![](assets/cvebase_examples.png)

## About this repository
This repository contains the Markdown files for the two main components of cvebase.com:
* `cve`: CVE files are located in the `/cve/` directory, organized by year and sequence identifier following the naming scheme set by [`CVEProject/cvelist`](https://github.com/CVEProject/cvelist).
* `researcher`: Researcher profiles are in the `/researcher/` directory, named by researcher slug.

Inspired by static site generator [`gohugoio/hugo`](https://github.com/gohugoio/hugo), the Markdown files have YAML "front matter" to define metadata for both CVEs and Researchers.

Reference these examples of CVE & Researcher files:
* [/cve/2020/15xxx/CVE-2020-15505.md](https://raw.githubusercontent.com/cvebase/cvebase.com/main/cve/2020/15xxx/CVE-2020-15505.md)
* [/researcher/orange.md](https://raw.githubusercontent.com/cvebase/cvebase.com/main/researcher/orange.md)

### How to add a Security Researcher profile
* Fork this repo `git clone https://github.com/cvebase/cvebase.com.git`
* Create a markdown (`.md`) file in the `/researcher` directory. Name the file using researcher's handle if available (e.g. `rgod.md`), and if not use a slugged version of their full name (e.g. `qixun-zhao.md`).
* Fill in the contents of the file -> front matter + bio:
* For the front matter containing Security Researcher metadata, which is in YAML format:
	* Section is identified by opening and closing three dashes (`---`)
	* Minimum required  YAML field values are `name`, `alias`, and a list of `cves`
	* Optional YAML field values are `nationality`, `website`, `twitter`, `github`, `linkedin`, `hackerone`, `bugcrowd`
* Git commit & submit pull request on GitHub

## Project Roadmap

View our roadmap and share your ideas:

* Browse this project's [issues](https://github.com/cvebase/cvebase.com/issues) to review existing suggestions and ideas.
* If you're interested an issue, give it a 👍 which will help us prioritize. We'll update progress on the issue and mention you when the feature is ready.
* If you don't see your idea, create a new issue.
* Labels show progress on issues:
  * [soon](https://github.com/cvebase/cvebase.com/issues?q=is%3Aopen+is%3Aissue+label%3A%22soon%22) - work will begin shortly.
  * [in progress](https://github.com/cvebase/cvebase.com/issues?q=is%3Aopen+is%3Aissue+label%3A%22in+progress%22) - we've started work.

## Contributing
* Fork this repository and send a pull request
* [Create an issue](https://github.com/cvebase/cvebase.com/issues) in this repository

## License
Repository content licensed [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
