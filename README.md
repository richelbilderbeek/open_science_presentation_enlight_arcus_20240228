# open_science_presentation_enlight_20240228

My Open Science presentation of 2024-02-28

 * Formal event title: second ENLIGHT RISE and Arqus Alliance Open Science Ambassador Webinar on 28 February 2024 
 * [Event homepage](https://enlight-eu.org/index.php/university-about-us/news-events/158-news/1061-2nd-enlight-rise-and-arqus-alliance-open-science-ambassador-webinar-on-28-february-2024)
 * Duration of presentation (monologue): 30 minutes
 * Presentation as Quarto markdown: [presentation.qmd](presentation.qmd)
 * Presentation as PDF: [presentation.pdf](presentation.pdf). Latest version is also uploaded by the [build_pdfs](https://github.com/richelbilderbeek/open_science_presentation_enlight_arcus_20240228/actions/workflows/build_pdfs.yaml) continuous integration script
 * YouTube video: [here](https://youtu.be/zHpiz2P4h-U)

## Description

Richèl Bilderbeek will present on “The pros and cons of Open Science 
as discussed in the Uppsala local OS community.”

“Open Science is just science done right”. 
This is a slogan one sometimes hears 
at the local Open Science community in Uppsala, called OSU. 
Most OSU visitors do think Open Science leads to 
better-in-some-way science. 
And we know that it is hard to be critical on 
something most of us prefer so much. 
We do, however, try to remain critical and ask questions 
such as: ‘Is it worth it?’. 
In this webinar, Richèl Bilderbeek talks about some of 
the pros and cons of Open Science and the Uppsala community.

## Files used for continuous integration scripts

Filename                           |Descriptions
-----------------------------------|--------------------------------------------------------------------------------------------------------------------------------------
[mlc_config.json](mlc_config.json) |Configuration of the link checker, use `markdown-link-check --config mlc_config.json --quiet docs/**/*.md` to do link checking locally
[.spellcheck.yml](.spellcheck.yml) |Configuration of the spell checker, use `pyspelling -c .spellcheck.yml` to do spellcheck locally
[.wordlist.txt](.wordlist.txt)     |Whitelisted words for the spell checker, use `pyspelling -c .spellcheck.yml` to do spellcheck locally
