# ClimateData.be
ClimateData.be presents data and optimization techniques to reduce #climate change
(mitigation) and the impact from it (adaptation).

The site is available at <a href="https://www.climatedata.be/">https://www.climatedata.be/</a>.

## Licenses
All source code is licensed under the <a href="https://opensource.org/licenses/BSD-3-Clause">BSD-3-Clause</a> license.

All data is licensed under the Creative Commons <a href="https://creativecommons.org/licenses/by/4.0/">Attribution 4.0 International (CC BY 4.0)</a> license.

## How-to contribute
The simplest technique may be to click the "edit" button (stylus) on
the Github page with the <a href="https://github.com/petervandenabeele/ClimateData.be/blob/gh-pages/index.markdown">source code of the home</a> and then make a PR as suggested in that work flow.

At this moment, this repository is a "Github Pages" _project page_.

Changing the content occurs by checking out the `gh-pages` branch and changing the
content there (in Jekyll context).

Pushing the result to the server is by adding, committing and pushing the updated
contents in the `gh-pages` branch (_not_ on this main branch). This will
trigger a rebuild on the server. Local testing is possible with
`bundle exec jekyll serve`.

If you want to contribute while not a member of this project (yet), you could fork
this code, make a change in the `gh-pages` branch and raise a PR for it.
