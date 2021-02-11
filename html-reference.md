# HTML Reference

List of HTML elements and their status in this project, grouped by function

## Sectioning

These items require no custom CSS. They exist for semantic content sectioning only. I believe the only CSS that affects these elements are in the reset to make sure older browsers render them as block elements.

* article
* aside
* footer
* header
* section
* main
* nav
* div

## Block Content

The following html elements have recieved at least basic styling to support content flow.

[x] p
[x] address
[x] pre & pre code
[x] blockquote
[x] h1-h6

## Lists

List related elements have been styled up to 3 levels deep, and include a safety feature to eliminate specificity issues.

[x] ul
[x] ol
[x] li
[x] dl
[x] dt
[x] dd

## Tables

The following html table-related elements have recieved basic styling.

[x] table
[x] caption
[x] tr
[x] th
[x] td

These table-related elements have been skipped because they exist for semantic sectioning of table areas.

* thead
* tbody
* tfoot

## Media

The following media elements have recieved basic styles to allow for better content flow. I've also added several wrappers and utilities for dealing with aspect ratios.

[x] img
[x] video
[x] figure
[x] figcaption
[x] audio
[x] embed
[x] iframe
[x] object
[x] canvas

These elements remain unstyled because they are logic elements that do not display, similar to `<script>`.

* picture
* track
* area

These elements seem really obscure and would likely require a very specific use case, so I have not altered their styles.

* portal
* map

## Inline

All of the following elements have recieved CSS tweaks. Some are small quality of life changes and others are more extensive.

[x] a
[x] abbr
[x] cite
[x] em
[x] strong
[x] mark
[x] q
[x] s
[x] del
[x] ins
[x] small
[x] sub
[x] sup
[x] var
[x] code
[x] samp
[x] kbd

## Forms

The following html form elements have been styled for content flow consistencies

[x] legend
[x] fieldset
[x] label

These elements have been given simple input styles

[x] button
[x] input
[x] radio
[x] checkbox
[x] textarea
[x] select
NOTE [ ] optgroup
[X] progress

These elements have not been styled. Form is a sectioning element, and option is a logic element used with select.

* option
* form

These elements require more research

NOTE [ ] datalist
NOTE [ ] output

These elements are being skipped because they are incredibly difficult to style and out of the scope of this project. You would be better off with some custom JS solution for many of these.

* date
* color
* meter
* file

## Interactive

These elements have not been styled YET. I'm looking into the merits of styling them.

NOTE [ ] dialog
Not supported by Safari. Will not provide default styles, any required js, or suggested markup, but will be watching this space.
https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dialog

NOTE [ ] menu
Experimental. Not supported by most browsers.

[x] details / summary

https://codepen.io/johnbarnitz/pen/gOPbVer
https://freefrontend.com/html-details-summary-css/
https://jsbin.com/wogeyey/1/edit?html,css,js,output
https://justmarkup.com/articles/2020-09-22-styling-and-animation-details/
