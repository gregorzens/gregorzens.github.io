# gregorzens.github.io

Personal academic website built on the [Academic Pages](https://academicpages.github.io/)
Jekyll template (forked from [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/),
© Michael Rose, MIT License — see `LICENSE`).

## Structure

The site is four static pages in `_pages/`, all in the same style:

- `about.md`     → home page (`/`): intro, research focus, contact
- `research.md`  → `/research/`: preprints, publications, software, press, awards, visits
- `talks.md`     → `/talks/`: conference, seminar and workshop presentations
- `teaching.md`  → `/teaching/`: teaching and thesis supervision

Header navigation is defined in `_data/navigation.yml`. Site-wide settings
(name, author sidebar, social links, analytics) live in `_config.yml`.

## Editing content

Each page uses plain Markdown with a little inline HTML for the section
headers, e.g.:

    <p style = "margin-bottom:5px;"> <font size="5" > <br> Software </font></p>

To add a publication, talk, etc., copy an existing bullet and edit the text
and links. Files linked from a page (e.g. PDFs) go in `files/`; images go in
`images/`.

## Running locally

    bundle install        # delete Gemfile.lock first if you hit errors
    bundle exec jekyll serve

Then open http://localhost:4000.

## Deploying

Push to the `master` branch of the `gregorzens.github.io` repository; GitHub
Pages builds and serves it automatically.
