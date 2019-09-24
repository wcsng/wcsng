# Allan Lab Website

<!--This is the website of our academic research group at Leiden University.

This website is powered by Jekyll and some Bootstrap, Bootwatch. We tried to make it simple yet adaptable, so that it is easy for you to use it as a template. Plese feel free to copy and modify for your own purposes.  You don't have to link to us or mention us (but of course we appreciate it).

Go to *aboutwebsite.md*  to learn how to copy and modidy this page for your purpose. -->


Copyright Allan Lab. Code released under the MIT License.

Note: one time change in `_config.yml`, when you want to host the webpage at `wcsng.github.io/wcsng`.
```
baseurl: "/wcsng"
```

Clone the repository. Install Jekyll. Run webpage on local server.
```
bundle exec jekyll serve
```

This command builds the webpage in the `_site` folder with all the html, CSS, and files. Just add, commit, and push the content to Github OR copy it to your webserver.


How to edit the contents:

Directory `_Data` 
* `publist.yml` to add new paper index (title, abstract, authors, link).
* `research_list` six research categories details
* `students.yml` for masters students, `colaborations` and `alumni`
* `team_member.yml` for PhDs
* `news.yml`
* `pictures` add all jpg image list

Directory `_pages`:
A standard template for all pages
```
title: "WCSNG Lab - Research"
layout: gridlay
excerpt: "WCSNG Lab -- Research"
sitemap: false
permalink: /research/
```
* Dir `Research`: One page each for each research topics (6 of them)
* `team.md`: ALumni and interns
* `home`: Logo and first page items

Directory `_includes`: to updata html files for header ("WCSNG @ UC San Diego"), footer, analytics, and news

Directory `_layouts`: `homelay.html` has "Welcome to WCSNG" message. Other files not useful.
