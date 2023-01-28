---
# try also 'default' to start simple
theme: unicorn
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
# use UnoCSS
css: windicss
layout: intro
introImage: /se-cover.png
---

# Orientation

## SE-1221

### Introduction to Engineering Design **(for SE)**

###### Richard Michael Coo

<logos-github-octocat /> [Repo][repo] <span class="ml-4">Slides: </span>
<twemoji-link /> [Online][online] <mdi-file-pdf class="text-red-500" /> [PDF][pdf]

[repo]: https://github.com/psse-cpu/se-1221-orientation-slides
[online]: https://psse-cpu.github.io/se-1221-orientation-slides
[pdf]: https://psse-cpu.github.io/se-1221-orientation-slides/slides-export.pdf

<style>
h1 {
  padding-bottom: 16px;
  @apply border-b-2 border-gray-300;
}

h6 {
  margin-bottom: 32px;
}

h3 {
  margin-bottom: 40px;
}

#logos img {
  display: inline;
  margin-top: 32px;
  width: 96px !important;
  height: 96px !important;
}

h3 {
  margin-top: 16px;
}
</style>

---
src: ./preface/intro.md
---
---
src: ./preface/what-is-it.md
---
---
src: ./preface/agenda.md
---
---
src: ./preface/last-ied.md
---
---
src: ./preface/legal.md
---
---
src: ./preface/expectations.md
---
---
src: ./preface/house-rules.md
---
---
src: ./preface/meet-and-greet.md
---

---
src: ./se/nature-of-se.md
---
---
src: ./se/se.md
---
---
src: ./se/engg-design.md
---
---
src: ./se/ideation.md
---
---
layout: center
---

# Credits

- [Berkeley Method of Entrepreneurship: Opportunity Identification _(Ikhlaq Sidhu)_][1]
- others: TODO

[1]: https://www.slideshare.net/ikhlaqsidhu/bmoe1-berkeley-method-opportunity-recognition