# Creating accessible office documents

## Table of contents

<!-- MarkdownTOC -->

- [Introduction](#introduction)
	- [Foreword](#foreword)
	- [The RGAA and Office Documents](#the-rgaa-and-office-documents)
	- [Presentation of guides](#presentation-of-guides)
	- [Who are these guides for?](#who-are-these-guides-for)
	- [Technical devices used to access content](#technical-devices-used-to-access-content)
- [How to structure a document](#how-to-structure-a-document)
	- [Introduction](#introduction-1)
	- [Headings](#headings)
	- [Paragraphs](#paragraphs)
	- [Lists](#lists)
	- [Footnotes](#footnotes)
	- [Page Numbers](#page-numbers)
	- [Columns](#columns)
	- [Floating Objects](#floating-objects)
	- [Reading order](#reading-order)
	- [Text areas](#text-areas)
	- [Slide Master](#slide-master)
	- [Headers and footers in slides](#headers-and-footers-in-slides)
- [Using an appropriate layout](#using-an-appropriate-layout)
	- [Introduction](#introduction-2)
	- [Colors](#colors)
	- [Fonts](#fonts)
	- [Styles](#styles)
	- [Themes](#themes)
	- [Template](#template)
- [Language](#language)
	- [Introduction](#introduction-3)
	- [Language of the document](#language-of-the-document)
	- [Abbreviations and acronyms](#abbreviations-and-acronyms)
	- [Unusual, idiomatic or specialized expressions](#unusual-idiomatic-or-specialized-expressions)
	- [Words or passages in a foreign language](#words-or-passages-in-a-foreign-language)
- [Giving an alternative to non-textual elements](#giving-an-alternative-to-non-textual-elements)
	- [Introduction](#introduction-4)
	- [Images](#images)
	- [Images of texts](#images-of-texts)
	- [Charts](#charts)
	- [Mathematical formulas](#mathematical-formulas)
	- [Multimedia files](#multimedia-files)
- [Creating accessible tables](#creating-accessible-tables)
	- [Introduction](#introduction-5)
	- [Layout tables](#layout-tables)
	- [Data Tables](#data-tables)
	- [Copying and pasting tables from spreadsheets](#copying-and-pasting-tables-from-spreadsheets)
- [Creating navigation aids](#creating-navigation-aids)
	- [Introduction](#introduction-6)
	- [Tables of contents, figures and tables](#tables-of-contents-figures-and-tables)
	- [Bookmarks](#bookmarks)
	- [Cross-reference](#cross-reference)
	- [Links](#links)
	- [Citations](#citations)
- [Creating accessible forms](#creating-accessible-forms)
- [Setting document properties](#setting-document-properties)
- [Making oral presentations accessible](#making-oral-presentations-accessible)
- [Checking accessibility](#checking-accessibility)
- [Publishing the document in other formats](#publishing-the-document-in-other-formats)
- [Licence](#licence)

<!-- /MarkdownTOC -->

## Introduction

### Foreword

French law n° 2005-102, of 11 February 2005, for equality of rights and opportunities, participation and citizenship of people with disabilities, makes accessibility a requirement for all public online communication services, for the State, local and regional authorities and the public institutions that depend on them.

The RGAA (General Accessibility Framework for Administrations) aims to promote accessibility of the contents available in digital form. In 2014, the RGAA was redesigned to be up-to-date and more operational. The French administrations currently ought to refer to the RGAA 3.

To meet the needs of diverse groups and contexts, three levels of compliance have been defined: A (lowest), AA and AAA. The level legally expected is level double-A (AA). Success criteria associated with the AAA level may be taken into account in certain contexts where possible and relevant.

### The RGAA and Office Documents

The RGAA applies to any document or application available online: websites, Intranet and web applications, but also the contents downloadable as separate files.

In the Consultation category of the RGAA, [criterion 13.7](https://disic.github.io/rgaa_referentiel_en/criteria.html#crit-13-7) (Level A) states that "each office document that can be downloaded [must] have an accessible version if necessary". Compliance with this criterion can be achieved in particular by providing an accessible HTML version or by making the document accessible in the format proposed for download.

### Presentation of guides

These companion guides present the considerations and principles for creating an accessible office document, with non-normative guidance and procedures for implementing them.

This document describes the general principles for the production of accessible office documents. These principles are detailed in the form of specific procedures, presented and illustrated in dedicated downloadable guides, for the following applications:

* [Microsoft Word 2016 (ODT - 6.7 MB](./ MicrosoftOfficeWord.odt)
* [Microsoft Excel 2016 (ODT - 2.4 MB](./ MicrosoftOfficeExcel.odt)
* [Microsoft PowerPoint 2016 (ODT - 3.2 MB](./ MicrosoftOfficePowerPoint.odt)
* [LibreOffice Writer 5.2 (ODT - 4.6 MB)](./LibreOfficeWriter.odt)
* [LibreOffice Calc 5.2 (ODT - 3.1 MB)](./ LibreOfficeCalc.odt)
* [LibreOffice Impress 5.2 (ODT - 2.6 MB)](./LibreOfficeImpress.odt)
*  [Adobe Acrobat Pro Document Cloud 2017 (ODT - 5.9 MB)](./ AdobeAcrobatPro.odt)


### Who are these guides for?

These guides are intended for all professionals in government departments, local authorities, agencies, public institutions, public enterprises or anyone wishing to:

* Produce accessible office documents;
* Improve the accessibility of existing office documents;
* Test the level of accessibility of office documents already created.


### Technical devices used to access content

A document is accessible if it can be accessed by any user, regardless of the computer tool being used. More and more users are using assistive technologies to overcome barriers to accessing office documents or web content. These technical solutions include

* Software assistive technologies (screen readers, voice recognition / dictation software, etc.);
* Hardware assistive technologies (adapted mice, trackballs, Braille displays, etc.).

Content and applications must be compatible with these various assistive technologies, their functionalities and uses.

## How to structure a document

### Introduction

The notion of structure is central to any document. In addition to facilitating reading, formatting (font, size, spacing, etc.) and the position of the elements convey to the reader a first glimpse of the hierarchy of the content.

When applied correctly, the use of styles - a set of formatting features - allows a structure to be quickly and easily attributed to the document, while ensuring that the structure is accessible and navigable by users of assistive technologies.

When composing the document, the use of layout features (layout of text in columns, anchoring of inserted objects) makes it possible to ensure that all the elements of the document follow a logical order, and that they are easily reachable via the keyboard and easily read with assistive technologies.

### Headings

The primary elements that allow to  structure text are headings and sub-headings.

To begin with, to any text of a new document is assigned a default style. Then different sets of quick styles are proposed. It is necessary to apply the appropriate styles to the headings, so that they are correctly identified by the assistive technologies.

It is also possible to create your own heading styles and save them.

Please note:

* The application of styles for headings must imperatively respect the contents hierarchy, without skipping levels;
* Heading styles should never be used for formatting purposes only;
* Generally, headings should not exceed one line;
* To facilitate browsing in longer documents, there should be at least one heading every two pages;
* It is possible to verify that the styles have been correctly applied by viewing the table of contents, using the plan view or the navigation pane, depending on the software used.


### Paragraphs

Any paragraph text must be identified as such.

Repeated line breaks inserted to space the text of a document are to be avoided, because a succession of empty paragraphs can be perceived by the user of a screen reader or a speech synthesis as indicating the end of the document. Blank spaces can be made by applying styles with larger or smaller margins and paddings as required.

Similarly, when you want to continue writing on a new page, you must insert a page break rather than a succession of line breaks.

### Lists

Lists created only by inserting dashes in the form of "-" characters, or other special characters will not be rendered correctly by certain assistive technologies, that will interpret them as a sequence of separate paragraphs. It is then imperative to create lists identified as such, using styles of bulleted lists or numbered lists.

### Footnotes

Footnotes and endnotes contain additional information. They are made up of two related parts, namely the footnote (or endnote) indicator and the text of the corresponding note.

The user can navigate between text and notes, provided they have been inserted correctly.

### Page Numbers

Page numbers provide important landmarks for any user, including users of assistive technology. The page number insertion feature should be used, instead of inserting manually a number at the top or bottom of the page.

### Columns

Mock-columns, created with the tab key or using a data table, can cause difficulties for assistive technology users. It is necessary to use the appropriate functionality to organize a part of the document into separate and easily navigable columns.

### Floating Objects

When images or objects are inserted into a document, they are positioned relatively to the page by default, and remain in the same position when the user browses the page. This behavior makes these "floating objects" difficult to select through a keyboard. It is important to ensure that the objects inserted in a document (images, shapes, etc.) remain associated with the text to which they refer, by defining an anchor point.

### Reading order

Assistive technologies scan the document in a linear fashion.

Some precautions need to be taken so that the reading order is consistent:

* Do not use data tables for layout of contents (text or images) in the document;
* Do not use tab keys to create columns
* Do not use editable text areas to highlight some given content, but use styles instead.

### Text areas

Text areas are often problematic because they can be ignored by some screen readers. For this reason, it is better to create a box by applying a style.

### Slide Master

When creating slides, it is useful to create a slide master, which represents the "template" slide that stores all page layout information, including the size and positioning of the content areas. The styles for each new slide are inherited from this master.

Any master created or used must meet the accessibility requirements outlined in this guide.

It is best to create a slide master before you start creating the presentation, so that any new slides are based on one or more accessible masters.

### Headers and footers in slides

Headers and footers are not read automatically by screen readers. For this reason, important information in these areas should be avoided.

## Using an appropriate layout

### Introduction

The visual complexity of a document (the quantity, density and variety of fonts, colors, texts, etc.) can play a decisive role in understanding its content. For users browsing with assistive technologies, a complex document often relies on a complex structure and may require more time to apprehend. If the understanding of certain content is conveyed only through color, shape, size or position, these readers may miss some information.

When composing the document, the use of standard styles and fonts improves its readability.

### Colors

If information is conveyed only through color, screen reader users (blind or visually impaired users, in general) and some color blind people will not be able to access it. Any information conveyed through color must therefore also be available via another means (for example, an appropriate style).

For information provided through color in text, the solution is to add an explanatory text. For example, in a procedure indicating that the items in red are mandatory, you will need to:

* Number the items
* Add a note like "Items numbered 2 to 4 (in red) are required".

The contrast between the background and text colors must also be sufficient to make the reading of the document comfortable. The RGAA states that the contrast ratio between a non-bold text and its background should be 4.5:1 up to 150% of the default font size, and 3:1 beyond. For bold text, a 4.5:1 contrast ratio is required up to 120% of the default font size, and 3:1 beyond. This applies to text, graphics and images.

A contrast checker is used to determine if colors have sufficient contrasts. The [Colour Contrast Analyser](https://www.paciellogroup.com/resources/contrastanalyser/), provided by the Paciello Group, can be downloaded free of charge. 

Among others, you may also use this [online checker proposed by Tanaguru](http://contrast-finder.tanaguru.com/?lang=en).


### Fonts

For the reasons given above, it is compulsory to use the styling features rather than the character formatting tools, to format any element with a semantic value (headings, list elements, notes, etc.).

Whenever possible, some formatting standards should be prioritized to facilitate reading, and make the documents legible in the main text editors.

* Standard fonts created for ease of reading: Arial, Calibri, Cambria, Constantia, Garamond, Georgia, Helvetica, Times New Roman, Trebuchet MS, and Verdana;
* Font sizes between 12 and 18 points for the body text;
* Normal or expanded character spacing, rather than condensed.

Avoid:

* Long chunks of text in uppercase, italic or underlined fonts
* Animated or scrolling text.

### Styles

Styles can be used to give a hierarchical structure to the document, but also to highlight certain types of content (quote, caption, etc.). In order to allow readers to understand the meaning of formatting, it is appropriate to use styles rather than directly using character formatting tools.

### Themes

A theme is a set of colors, fonts, and layout effects that can be applied to the document. The edition applications generally offer many predefined themes. It is also possible to customize it to meet the requirements of the RGAA in terms of colors and fonts.

### Template

A template serves as the basis for new documents and contains predefined formatting styles.

You can create your own accessible template from blank content, or edit and modify pre-existing templates to accommodate accessibility recommendations.

## Language 

### Introduction

When the contents of a document are well identified, organized according to a coherent logic, and well-spaced, they are easier to consult. Similarly, documents with clear headings, short paragraphs and concise, simple, jargon-free sentences will be accessible to as many people as possible.

When it is necessary to use technical terms, words in a foreign language or abbreviations, it is important to give the reader the information necessary for their proper understanding.

### Language of the document

The language selected for the document determines the dictionary used for spell checking, synonyms and hyphenation, as well as a number of formatting rules. For text-to-speech software, it also determines how content is spoken. It is therefore imperative to define a language for any document, and to ensure that any word or passage in another language is correctly identified.

### Abbreviations and acronyms

Often, there is no mechanism for identifying acronyms or abbreviations. It is however possible to facilitate understanding by following a few recommendations:

* The meaning of abbreviations and acronyms shall be indicated in clear text in their first occurrences, followed by the abbreviation or acronym between parentheses. For example: National Aeronautics and Space Administration (NASA);
* You can link an acronym or an abbreviation to a glossary via a bookmark or a hyperlink.


### Unusual, idiomatic or specialized expressions

When it is necessary to use unusual, idiomatic or specialized expressions, an accessible definition must be provided. These definitions can be proposed in the footnotes or endnotes, or grouped in a glossary and linked to the expressions through bookmarks.


### Words or passages in a foreign language

Words in a foreign language must be correctly marked so that the speech synthesizers pronounce them correctly.

It is important to ensure that the foreign language is selected as an editing language for the document, and then to indicate each language change. No visual changes will occur; only assistive technologies will have access to this information.

## Giving an alternative to non-textual elements

### Introduction

Non-textual elements are becoming increasingly important in office documents. Photos, maps, graphics and mathematical formulas enrich documents and convey information to readers.

For non-textual elements that convey information not presented as text in their proximity, this information must be described in a replacement text. Without proper description, these elements can't be perceived by assistive technologies, that will signal the presence of a graphic element without any other information.

It is possible to create a replacement text that will be returned to the reader by assistive technologies. The tools vary according to the nature of the non-textual content.

### Images

You should ask yourself 3 questions before choosing the text that will be rendered in place of the image:

* Is the image purely decorative, not conveying any information and having no function?
* Does the item convey information?
* Does the image have a function (for example, a picture serving as a link)?

If the image is purely decorative, it should not be assigned alternative text.

If the image conveys information, it must be associated with a replacement text. This alternative, which also serves as a title, must succinctly describe the information conveyed by the image and its meaning in the context.

For an image that serves as a hyperlink, the alternate text must be able to understand the function and the destination of the link. The conditions for returning this replacement text require that it be as short as possible (a maximum length of 80 characters is strongly recommended). If the information requires a longer alternative, a detailed description must be provided.

A replacement text should not:

* Duplicate information in the caption;
* Include copyright information (for example, for a photo, the name of the copyright holder and the date of the picture)
* Start with "picture of&hellip;" or "photo of&hellip;".

A detailed description is sometimes necessary when the information conveyed by the image is more complex. This requires an interpretation of the image.

### Images of texts

It is not recommended to use images of texts when it is possible to reproduce the same effects by defining styles for "actual" text.
If the text is part of a logo or an element associated with the graphic identity of an organization or a company, it is advisable to propose a textual alternative to the image, while following the recommendations above.

### Charts

The data shown in charts can range from very simple to very complex. First, a chart accessible to color-blind and partially sighted readers should be created. This involves to:

* Not use color alone to convey information (use of textures or shapes to differentiate the components of the graph for example);
* Emphasize the use of dashed line styles to improve readability;
* If necessary, replace predefined colors to meet the contrast requirements.

### Mathematical formulas

Depending on the software used, it may be possible to use the embedded equation editor, or necessary to install an additional  plug-in which will be able to convert mathematical formulas into a format that can be interpreted by assistive technologies (MathML). This is the case of the [MathType](http://www.dessci.com/en/products/mathtype/trial.asp) paid extension for Office, which allows you to edit and export equations.

### Multimedia files

A replacement text must accompany any video or audio sequence. It is also necessary to provide a transcription for any video or audio sequence, and to ensure that the videos have captions, either open or closed, for online videos, or embedded directly into the video file.

The role of transcription is to provide a relevant alternative to multimedia content. Readers must have access to all the information conveyed by the video or audio file, including the dialogues between the participating protagonists, the location, the main actions and the atmosphere.

It is also possible to propose an audiodescription, i.e. an additional soundtrack added to the video that describes the visual elements: actions, movements, expressions, sets, etc. in the blank spaces between the dialogues and the important sound elements.

The transcription can be proposed as an appendix or in a downloadable file stored on a server and accessible via a link located near the object (same for audio description). The link text must clearly identify the proposed audio description or transcription for the video, because it is not possible to establish a semantic relationship between the two.


## Creating accessible tables

### Introduction

Tables constitute a complex environment for users of assistive technologies because the organization of information and the relationships between them can't be perceived and scanned quickly. It is necessary to ensure that each data cell in the table can be correctly linked to the header cell(s) that make it meaningful.

### Layout tables

The use of tables for layout purposes is generally not a good practice: it is preferable to use the layout functions (columns, borders, etc.).
However, some assistive technologies make it possible to differentiate layout and data tables. For layout tables, it is imperative to present the information in a logical order (in Western languages, from left to right and from top to bottom) to make sure it makes sense and not to mislead the user.

### Data Tables

The use of the tab key and the space bar to simulate data  is to be avoided because assistive technologies are not able to interpret this type of formatting. To insert a data table, you need to go through the appropriate functionality offered by the application, while adhering to the following recommendations

#### Formatting

If a data table appears to be the best option for presenting information, formatting rules must be followed to ensure that the data is accessible and understandable to the largest number of users.

* Create a uniform table that facilitates the identification of each cell and its meaning in context;
* Prefer multiple simple tables to more complex tables;
* Avoid nesting tables in one another;
* As far as possible, avoid merging cells;
* Eliminate empty cells - if data is missing, replace it with an explicit mention;
* Make blank lines by using styles, and not by inserting empty rows;
* Avoid inserting images within the table.

#### Row and column headers

It is then necessary to identify the contents of the table by means of the headers, the caption, and the alternative text, and to define these properties in order to allow a better rendering by the screen readers.

The row and column headers give meaning to the relationship between the data presented.

Note: Header cells content should be clear and concise.


#### Caption and text alternatives

A table caption describes the function of the table and how it is organized. All abbreviations used within the table must be explained in the caption.

A text alternative is necessary to describe the function of a complex data table in the context in which it is located. Oftentimes, a detailed description of the most remarkable information, or a summary of the data presented in the table, is necessary.

### Copying and pasting tables from spreadsheets

When inserting a table into a document from another document, it is necessary to ensure that it is copied as an actual table, and not as an image, whose content eventually can't be accessed through assistive technologies.


## Creating navigation aids

### Introduction

A document is not necessarily read in a linear manner. Provided that the document is well structured, with proper application of headings, captions, footnotes, etc., a hypertext structure can be generated automatically, allowing users to move quickly within the document.

In addition to the structuring elements described in the previous sections, and tables of contents, of figures or of tables, that can be generated automatically, it is possible to enrich the document with navigation elements pointing to contents inside and outside the document.


### Tables of contents, figures and tables

The table of contents must not be generated manually: the features provided by the authoring tools must be used to do so.

### Bookmarks

A bookmark is used to identify a location or a selection of text that can be referenced elsewhere in the document. Rather than browsing through the document to retrieve the text, the user can easily access the text using tools that list bookmarks.

### Cross-reference

Cross-references allow users to directly access to passages of text or objects in a document. Cross-references consist of a target and a reference.

### Links

Links allow users to navigate within the document, and to external resources where appropriate. Explicit text should be used to make links understandable in context, i.e., the sentence or paragraph in which they are located.

### Citations

Whenever possible, it is recommended to associate citations with bibliographic references in a consistent way, that is also accessible to assistive technologies: this allows users to easily access the bibliographic references related to a passage of the text.

## Creating accessible forms

A form is an input space, which can have several "fields" where the user can enter text, check boxes, select from a list of predefined terms, press buttons, and so on.

Well-designed forms will be accessible to users of assistive technology, provided they follow a few simple rules:

* The focus path (tab order) must be logical and understandable;
* Each form field must be identified;
* Form fields must be editable;
* Information of the same nature should be grouped and labelled clearly;
* For complex forms, a short description, providing the number of questions or sections, and an estimate of the time required to complete the form, may be proposed.


## Setting document properties


Document properties, also known as metadata, are information about a file that describes or identifies it. They include information such as title, author's name, subject, and keywords identifying the topics or content of the document.

When opening a document, some assistive technologies refer to these properties to announce the title of the document and to summarize the content.

These properties are also preserved and used when the document is published in another format.

It is necessary to indicate at least the title of the document, and possibly the author, keywords and a statement about the document's accessibility where possible.

## Making oral presentations accessible

Slides (PowerPoint or Impress) can be used independently, but are often used to support an oral presentation with visual information.

To create presentations that are accessible to all, regardless of the capabilities of the audience, it is imperative that any visual information that makes sense for the oral presentation is described so that people who can't see the projection have access to the same information. In no case should the slide replace speech.

To make the presented information accessible and understandable to the largest audience:

* If possible, distribute a digital version of your slides in advance, so that the audience can see the information on the screen of their laptops. Some participants will also benefit from a printed version in enlarged text;
* Express yourself clearly and accurately, at a reasonable speech rate;
* Begin by introducing yourself and announcing the format of the presentation (the allotted time, the outline, when the audience can ask their questions, etc.). If you agree that audience will interrupt you to solicit an explanation in case of misunderstanding, let it be known;
* Make sure that any text on the screen is announced verbally. And do not forget to limit yourself to between 3 and 7 sentences per slide;
* Explain any graph or diagram by stating the information you want to convey by presenting it;
* Describe, instead of pointing the finger, where on the slide the information you are referring to is located;
* If someone asks a question, repeat the question before answering it.

## Checking accessibility

Some tools include an accessibility checker. The accessibility checker identifies content that can cause reading issues for people accessing the document with assistive technologies.

Checkers detect issues like the absence of alternatives to images or the inconsistency of document headings. However, it should be noted that the use of these checkers does not exempt manual control, as compliance with the accessibility criteria can only be verified automatically for a small proportion of the criteria.

## Publishing the document in other formats

If the techniques described in this guide are used during the creation of an electronic document, this document will not only be read by users of assistive technologies for the software used for creation, but its semantic composition will also allow for better conversion into other formats, although some adjustments may still be necessary depending on the chosen format.

In these guides, the publication process is described for the following formats:

* <abbr title="Hypertext Markup Language">HTML</abbr>;
* <abbr title="Portable Document Format">PDF</abbr>.

Conversion to these formats assumes that documents are properly structured upstream, by following the guidelines described in the previous chapters of this guide.

It is necessary to ensure that the elements related to the accessibility of the document are preserved when saving or exporting to other formats. This evaluation work and any corrections due to loss of information or conversion errors are discussed in detail in the Adobe Acrobat Pro DC guide. For HTML export, it is necessary to use verification techniques specific to this language that are not covered in these guides.

## Licence

This document is the property of the <span lang="fr">Secrétariat général à la modernisation de l'action publique</span> (SGMAP). It is placed under [Open Licence 1.0 or later (PDF, 541 kb)](http://ddata.over-blog.com/xxxyyy/4/37/99/26/licence/Licence-Ouverte-Open-Licence-ENG.pdf), equivalent to a Creative Commons BY licence. To indicate authorship, add a link to the original version of the document available on the [DINSIC's GitHub account](https://github.com/DISIC).