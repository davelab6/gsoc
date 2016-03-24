# Summer Job Opportunity (US$5,500)

#### Application Deadline March 25 19:00 UTC

**Wanted: Undergraduate Students with Python software development skills and interest in fonts and constructivist learning**

Typeface design is a cornerstone of literate cultures, with subliminal power: Typefaces carry the emotions of texts, from formal designs that speak with authority to fun designs that are silly or military or ornate. They are both artistic and functional works, and our ability to share and modify them is important for the same reasons as for software programs. 

Sugar is a learning platform that reinvents how computers are used for education. Collaboration, reflection, and discovery are integrated directly into the user interface, and "studio thinking" and "reflective practice" are promoted through Sugar's clarity of design. Sugar was initially developed by Red Hat and Pentagram with One Laptop per Child and now has over 1M users, including every child in Uruguay.

Fonts are fun to make, and Sugar needs a font editor activity so learners can make and modify them for their own tastes and needs.

Each year Google offers paid summer jobs to University students around the world with the Google Summer of Code (GSoC) programme, and a slot is available this summer for a student to develop a Sugar font editor. Students are expected to spend about 40 hours a week working on the project during a 3 month coding period (so if you already have an internship, another summer job, or plan to be gone on vacation for more than a week during that time, GSoC is not the right program for you this year.) The stipend paid for successful completion is US $5,500. 

Lots of free software Python libraries already exist so this project offers the possibility to make real progress: Shipping a sugar activity to draw letters, export fonts, and then use them immediately in other activities like write or paint. Stretch goals could include color fonts, drawing letters with expanded strokes or Spiro splines or turtle-art, and inventing algorithms to automate the repetitive aspects of typeface design.

To learn more, send a short email to Dave Crossland (dcrossland@google.com) with subject "Sugar Fonts Proposal" and include your resume, github username, and tell Dave why you are interested in this opportunity. 

## Deadline: 25 March 19:00 UTC

## Requirements

- You must be interested in typeface design and font technologies
- You must be proficient with the Python programming language
- You must be at least 18 years of age
- You must be a full or part-time student at an accredited university (or have been accepted as of April 22, 2016)
- You must be eligible to work in the country you will reside in during the program
- You have not already participated as a Student in GSoC more than twice
- You must reside in a country that is not currently embargoed by the United States

## Further Reading

- https://www.designwithfontforge.com
- https://www.oert.org
- https://wiki.sugarlabs.org/go/Sugar_Labs/FAQ
- https://developers.google.com/open-source/gsoc/faq
- http://write.flossmanuals.net/gsocstudentguide/writing-a-proposal/
- https://summerofcode.withgoogle.com/student-signup/

## Suggestions From Dave

I don't have any preconceptions about what a Sugar Activity for drawing and editing fonts should be like. 
I described some of the Big Ideas ([0]) of font editors in the Glyphr Studio web based font editor ([1].)

For drawing, I think that a spiro ([2] [3] [4] [5]) + curve offsetting ([6]) approach as can be done with inkscape ([7] [8]) (and used in Metapolator, FontArk, and LetterInk as discussed recently on the #1 font design forum ([9])) could be interesting. 

But this would be a stretch goal; before getting to that point, you'd need to create the most basic font editor possible - drawing with regular PostScript bezier outlines - and get the whole editor working end to end. For that, TruFont ([10]) is a great model to follow in terms of functionality, and base font data libraries, but since it is PyQt5 based its UI can not be used directly. 

In fact, making a simple Font Manager activity so that users can select, share (upload + download), install, and use fonts would likely be a big milestone and form a base for a font editor activity to build upon ([11] [12] [13] [14].) There are already two similar activities ([15] [16].)

Other improvements to the font related parts of the Sugar Platform may also be needed ([18])

[0]: https://en.wikipedia.org/wiki/Big_Idea_(marketing)
[1]: https://github.com/mattlag/Glyphr-Studio/issues/94
[2]: http://raph.levien.com/spiro/ 
[3]: http://raph.levien.com/phd/phd.html 
[4]: https://www.youtube.com/watch?v=-ekZJ9h9PXU 
[5]: http://fontly.com/sandbox/spiro.html 
[6]: https://pomax.github.io/bezierinfo/#offsetting
[7]: https://www.youtube.com/watch?v=3OaLZuFZxdk 
[8]: https://www.youtube.com/watch?v=yy2fxxqEZ-A
[9]: http://typedrawers.com/discussion/1463/how-skeleton-based-type-design-could-shake-up-digital-type-design-workflows
[10]: https://github.com/trufont/
[11]: https://en.wikipedia.org/wiki/Font_management_software 
[12]: https://www.google.com/fonts
[13]: http://fontmatrix.be
[14]: https://fontmanager.github.io
[15]: https://activities.sugarlabs.org/en-US/sugar/addon/4669
[16]: https://github.com/godiard/favorite-fonts-activity
[17]: https://github.com/godiard/favorite-fonts-activity
[18]: https://wiki.sugarlabs.org/go/Features/Font_configuration
