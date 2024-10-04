# Curriculum Vitae

`Curriculum Vitae` apparently means `course of life`.

Online research leads me to believe that a CV needs to include all academic
achievements.
As opposed to a resume, which is a concise version cut down to be relevant
to the applied job at hand.

# Credits

Using the [Modern Deedy](https://github.com/Aarif123456/modern-deedy) style.

# Usage

This repo is to hold the information; in multiple places.

The following is the proposed *file hierarchy*.

* Styling related things goes into `reference`
* Personal info is put in `info/batuhan.tex`, propagates to all files.
* If info about specific workplaces are needed, place them in `info/<place>.tex`.
* Text bodies should be put in `body/<place>.tex`.
* Once PDF's are produced, pull them into the appropriate folder in `production`.
* References are to be put in bibtex files in the `reference` folder.
* `archive` directory should contain tex files that are not actively worked on.

Usage guide is at follows;

* While working on a document to be compiled, it should be in the parent directory.
* The tex documents to be compiled should not contain the content, and should be just typesetting.
  This info should be pulled in from the `body` directory using `\input{body/<foobar>.tex}`.

## CV

