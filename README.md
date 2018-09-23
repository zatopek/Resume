Deedy-Resume
=========================

A **one-page**, **two asymmetric column** resume template in **XeTeX** that caters particularly to an **undergraduate Computer Science** student.
As of **v1.2**, a single template is offered:

1. **OpenFonts** - uses free, open-source fonts that resemble the above - *Lato* (and its various variants) and *Raleway*.

It is licensed under the Apache License 2.0.

*For a version using fonts typically available only on Mac, please refer to the original [repository](https://github.com/Deedy/Deedy-Resume) by Deedy.

## Motivation

Common LaTeX resume-builders such as [**moderncv**](http://www.latextemplates.com/template/moderncv-cv-and-cover-letter)  and the [**friggeri-cv**](https://github.com/afriggeri/cv) look great if you're looking for a multi-page resume with numerous citations, but usually imperfect for making a thorough, single-page one. A lot of companies today search resumes based on [keywords](http://www.businessinsider.com/most-big-companies-have-a-tracking-system-that-scans-your-resume-for-keywords-2012-1) but at the same time require/prefer a one-page resume, especially for undergraduates.

This template attempts to **look clean**, highlight **details**, be a **single page**, and allow useful **LaTeX templating**.

## Preview

### OpenFonts
![alt tag](https://raw.githubusercontent.com/ZDTaylor/Deedy-Resume/master/OpenFonts/sample-image.png)

## Dependencies

1. Compiles only with **XeTeX** and required **BibTex** for compiling publications and the .bib filetype.

## Availability

1. OpenFonts version - [as a direct download](https://github.com/ZDTaylor/Deedy-Resume/raw/master/OpenFonts/deedy_resume-openfont.pdf)
2. **Overleaf**.com (formerly **WriteLatex**.com) (v1 fonts/colors changed) - [compilable online](https://www.writelatex.com/templates/deedy-resume/sqdbztjjghvz#.U2H9Kq1dV18)
3. **ShareLatex**.com (v1 fonts changes) - [compilable online](https://www.sharelatex.com/templates/cv-or-resume/deedy-resume)

## Changelog
### v1.3
 1. Removed MacFonts version as I have no desire to maintain it nor access to macOS
 2. Switched column ordering
 3. Changed font styles/colors for easier human readability
 4. Added, removed, and rearranged sections to reflect my own experience
 5. Hid last updated

### v1.2
 1. Added publications in place of societies.
 2. Collapsed a portion of education.
 3. Fixed a bug with alignment of overflowing long last updated dates on the top right.

### v1.1
 1. Fixed several compilation bugs with \renewcommand
 2. Got Open-source fonts (Windows/Linux support)
 3. Added Last Updated
 4. Moved Title styling into .sty
 5. Commented .sty file.

## TODO
1. Add various styling and section options and allow for multiple pages smoothly.

## Known Issues:
1. Overflows onto second page if any column's contents are more than the vertical limit
2. Hacky space on the first bullet point on the second column.

## License
    Original Work Copyright 2014 Debarghya Das
    Modified Work Copyright 2018 Zachary Taylor

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
