# YUDL  Digitization and Metadata Manual
_Work - in - Progress_

Note : this is a draft manual of what will eventually be available through yorkulibraries' github and published in YUDL and/or on the YUL website.It is being written in Markdown. If you're interested in learning, see: http://programminghistorian.org/lessons/getting-started-with-markdown

|Date | Activity| Name |
| --------- | --------- | --------- |
| 2017-04-17 | Anna St.Onge | Initial Draft |
| 2017-05-25 | Anna St.Onge | Markup of draft in Markdown|
| 2017-06-13 | Anna St.Onge | Adding content to Telegram FAQ |
| 2017-06-18 | Anna St.Onge | Putting basic structure for digitization workflows and metadata policy |
| 2017-06-19 | Anna St.Onge and Julia Holland | reviewing and confirming policies for Telegram negs and prints (digitzation and metadata creation) |
| 2017-07-24 | Anna St.Onge | adding in scanning procedures for Tele negatives |
| 2017-09-21 | Anna St.Onge | trying to continue work of integrating new policies in forms and documentation |
| 2017-10-02 | Anna St.Onge | updating decisions made re. date fields and prompt text for Telegram prints |

<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

[YUDL  Digitization and Metadata Manual](#yudl-digitization-and-metadata-manual)
- [TELEGRAM NEGATIVES](#telegram-negatives)
	- [Digitization workflows](#digitization-workflows)
	- [Descriptive Metadata For Telegram Negatives](#descriptive-metadata-for-telegram-negatives)
			- [ASC Number](#asc-number)
			- [Location](#location)
			- [Identifier Other](#identifier-other)
		- [Titles](#titles)
			- [Proper Title](#proper-title)
			- [Proper Title sub-title](#proper-title-sub-title)
			- [Supplied Title](#supplied-title)
			- [Supplied Title sub-title](#supplied-title-sub-title)
			- [Alternative Title](#alternative-title)
			- [Alternative sub-title](#alternative-sub-title)
		- [Description (abstract)](#description-abstract)
		- [Names of photographers](#names-of-photographers)
		- [Dates](#dates)
			- [Date taken (ISO)](#date-taken-iso)
			- [Date Published (ISO)](#date-published-iso)
		- [Physical Description](#physical-description)
		- [Relation](#relation)
		- [Publications](#publications)
		- [Parent URI](#parent-uri)
		- [Relation](#relation)
			- [Title](#title)
			- [ASC Number](#asc-number)
	- [Subjects](#subjects)
		- [Subject](#subject)
		- [Topic](#topic)
		- [Geographic](#geographic)
		- [Cartographic](#cartographic)
	- [Rights and Use of object](#rights-and-use-of-object)
		- [Use and Reproduction](#use-and-reproduction)
		- [In Copyright](#in-copyright)
		- [Public Domain Status](#public-domain-status)
		- [Rights Statement](#rights-statement)
- [TELEGRAM PRINTS](#telegram-prints)
	- [Digitization Workflows](#digitization-workflows)
	- [Descriptive Metadata For prints](#descriptive-metadata-for-prints)
		- [ASC Number](#asc-number)
		- [Box and File Number](#box-and-file-number)
		- [Identifier Other](#identifier-other)
	- [Title](#title)
	- [Title Note](#title-note)
			- [Caption](#caption)
			- [Cutline](#cutline)
			- [Annotation](#annotation)
	- [Description (Abstract)](#description-abstract)
	- [Names](#names)
		- [Photographers](#photographers)
		- [Wire Services](#wire-services)
		- [Author of article](#author-of-article)
	- [Origin Information (Dates)](#origin-information-dates)
		- [Date taken (free text)](#date-taken-free-text)
		- [Date taken (ISO)](#date-taken-iso)
		- [Date published (ISO)](#date-published-iso)
	- [Physical description](#physical-description)
		- [Format](#format)
		- [Relation](#relation)
	- [Publications](#publications)
	- [Subjects](#subjects)
		- [Subjects](#subjects)
		- [Topic](#topic)
		- [Geographic](#geographic)
		- [Cartographic](#cartographic)
	- [Use and Reproduction](#use-and-reproduction)
		- [In Copyright](#in-copyright)
		- [Public Domain Status](#public-domain-status)
		- [Rights Statement](#rights-statement)
- [OBJECT MODS](#object-mods)
- [Digitization workflows](#digitization-workflows)
	- [Titles](#titles)
		- [Proper Title](#proper-title)
		- [Proper Title Sub Title](#proper-title-sub-title)
		- [Supplied Title](#supplied-title)
		- [Supplied Title Sub Title](#supplied-title-sub-title)
		- [Alternative Title](#alternative-title)
		- [Alternative Title Sub Title](#alternative-title-sub-title)
	- [Names](#names)
	- [Name type](#name-type)
	- [Authority](#authority)
		- [Authority URI](#authority-uri)
		- [Value of URI](#value-of-uri)
	- [Terms of Address](#terms-of-address)
	- [Date](#date)
	- [Affiliation](#affiliation)
	- [Role](#role)
	- [Type of Resource](#type-of-resource)
	- [Genre](#genre)
		- [Genre Authority](#genre-authority)
		- [Authority URI](#authority-uri)
		- [Value URI](#value-uri)
	- [Origin Info](#origin-info)
		- [Date (other) Free Text](#date-other-free-text)
		- [Date Issued](#date-issued)
		- [Publisher](#publisher)
		- [Place](#place)
	- [Language](#language)
		- [Language Authority "iso639-2b"](#language-authority-iso639-2b)
	- [Abstract](#abstract)
	- [Identifier](#identifier)
		- [Handle](#handle)
		- [Local Identifier](#local-identifier)
		- [Identifier Other](#identifier-other)
	- [Location](#location)
		- [Physical Location](#physical-location)
		- [Location Note](#location-note)
	- [Physical Description](#physical-description)
	- [Extent](#extent)
	- [Form](#form)
		- [Form Authority](#form-authority)
		- [Authority URI](#authority-uri)
		- [Value URI](#value-uri)
	- [Notes](#notes)
		- [General note](#general-note)
		- [Publication Note](#publication-note)
		- [Funding Note](#funding-note)
		- [Related item](#related-item)
		- [Title Info](#title-info)
		- [Location](#location)
		- [Finding Aid URI](#finding-aid-uri)
	- [Subject](#subject)
	- [Topic](#topic)
	- [Geographic](#geographic)
	- [Temporal](#temporal)
	- [Geographic](#geographic)
		- [Continent](#continent)
		- [country](#country)
		- [Province](#province)
		- [Region](#region)
		- [County](#county)
		- [City](#city)
		- [citySection](#citysection)
		- [cartographics](#cartographics)
	- [Use and Reproduction](#use-and-reproduction)
		- [In Copyright](#in-copyright)
		- [Public Domain Status](#public-domain-status)
		- [Rights Statement](#rights-statement)

<!-- /TOC -->

# TELEGRAM NEGATIVES
## Digitization workflows
Acknowlegments: These workflows are adapted from earlier iterations of scanning manuals created and implemented by Julia Holland, Andrea Kosavic, Anna St.Onge and others in consulation with digital scanning assistants Ahmed Alwan, Nick Benko, Marisa Chase, David Ding, Prathna Lor, and others.

### Preparation
* Take envelopes out of box in sequence, use a bookmark to hold the envelope's spot in the box.
* For each envelope, you will be creating metadata in two spreadsheets: one for the contact sheet PDF, the other for the remaining tiffs.
* Always wear white cotton gloves when handling negatives
* Put all TIFFS and PDFs into the directory relevant to the number range of ASC numbers you've been assigned through Redmine.
* If you have not received a ticket to scan these assignments, create a ticket for them and follow the relevant workflow policies
* You may need to sleeve negatives that are loose. This may require you cutting the top of the assignment envelope to create some room.

### Scan the assignment envelope and prepare contact sheets
1. You will be scanning everything as 300 dpi TIFF files and then combining them into one PDF file.
2. Scan both sides of envelope in 24 bit colour, 300 dpi TIFF (leave a small margin around envelopes)
3. Scan anything else included in envelope in colour, as a 300 dpi TIFF (leave a small margin around items)
4. Sort out negative strips in order, dull side up, and scan as grayscale 8-bit TIFFs (if colour negatives, then scan in colour)
 * Order is determined by neg.# or sequence of events, note slice angles as well (this takes time sorting on the light table but is well worth the effort & time; sometimes multiple rolls of film were shot there might be multiples of the same number. Sorting out multiple reels is important
 * Some images will not be in sequence, there might be negs missing from a roll (i.e. they were pulled for publication etc.).  Do your best  and keep in mind that the images will complement the negative numbers (i.e. the beginning of the event will be in negative 1 in most cases and end at around negative 24)
5. Only put three to four 35mm negative strips or two 4 x 5 inch negatives on each page of the contact sheet, more pages can be added to the PDF contact sheet if there are more scans in an image. Try to orient the strips so they will be easily read.
6. If more than one page is required to scan all negatives into the contact sheet, be sure to adust the description from “File consists of front and back of negative envelope, and one contact sheet. Assignment …” to “File consists of front and back of negative envelope , and ____ contact sheets. Assignment …”. Leave enough of a margin that you can type in the ASC numbers when you create your PDF file. Give each tiff file a temporary file name.
7. Combine the TIFF files into one PDF file in the following order: front of envelope, back of envelope, negatives, anything else in the envelope
8. Make sure your TIFF files are oriented in an easily legible way.
9. Assign an ASC# to the single combined PDF file. Fill out the metadata for your contact sheet in your PDF spreadsheet
10. Delete the TIFFs you had created for staging purposes, now that you have a PDF of everything in your envelope (*may revise-shoud we preserve tiffs as part of bundle in Islandora?*)


### Scan individual negatives
1. Some of the negatives may already be scanned and have unique identifiers attributed to them. There will be ASC numbers written on the mylar slip and there may be annotations on the envelope.
2. You may need to resleeve 
#### Scanning dimensions on flatbed scanner

| Size of original | DPI for Archival TIF | Resulting pixel size |
|------------------ | ------------------- | -------------------  |
| 35 mm negative or slide | 3200 dpi |	4800 pixels |
| 2 1/4 x 2 3/4 inch negatives (5.7 x 7 cm) | 1900 dpi | 4275 pixels |
| 2 3/8 x 2 3/4 inch negatives (6 x 7 cm) | 1600 dpi | 4400 pixels |
| 2 3/8 x 2 3/8 inch negatives (6 x 6 cm) | 1800 dpi | 4275 pixels |
| 2 3/8 x 1 3/4 inch negatives (6 x 4.5 cm) | 1800 dpi | 4275 pixels |
| 4 x 5 inch negative (10.6 x 12.7 cm) | 900 dpi | 4500 pixels |
| 5 x 7 inch negative (12.7 x 17.78 cm) | 700 dpi | 4200 pixels |
| 8 x 10 inch negative (20.3 x 25.4 cm) | 600 dpi | 6000 pixels |

## Descriptive Metadata For Telegram Negatives
#### ASC Number
#### Location
#### Identifier Other
Occasionally there will be multiple folders of the same topic. In this case, note which folder this is.
Example: Folder 2 of 2.
Occasionally there will be an old Y.U.A. negative # that is written in pencil on the back of a print. Note it in this field.
Example:OLD Y.U.A. neg # 1080 . See: https://digital.library.yorku.ca/yul-100873/munitions-workers-1939-1944
### Titles
#### Proper Title
#### Proper Title sub-title
#### Supplied Title
#### Supplied Title sub-title
#### Alternative Title
#### Alternative sub-title
### Description (abstract)
### Names of photographers
### Dates
#### Date taken (ISO)

Based on RAD Rule 1.4.B5. we follow the recoding conventions for probable and uncertain dates as follows: 

| Date | convention |
| --------- | --------- |
| [1867?] | probable date|
| [ca. 1867] | approximate date |
| [before 1867] | terminal date |
| [after 5 Jan. 1867]| terminal date |
| [1892 or 1893]| one year or the other |
| [between 1915 and 1918]| use only for dates fewer than 20 years apart |
| [197-] | decade certain |
| [186-?] | probable decade |
| [17–] | century certain |
| [17–?] | probable century |


#### Date Published (ISO)
### Physical Description
If there are negatives of different sizes in the envelope say 35mm, 120 film as well as some large 9 x 11 cm ones, scan in the order of most to least for the contact sheet. So ten 35mm negs first, then six 120’s then four 9 x 11 cm but your physical description for the PDF contact sheet should read as: 20 photographs : b&w negative ; 11.9 x 9.2 cm and smaller + 1 envelope : 11 x 14.2 cm 

### Relation
### Publications
    Need examples
### Parent URI
### Relation
#### Title
#### ASC Number
## Subjects
### Subject
### Topic
### Geographic
### Cartographic
## Rights and Use of object
### Use and Reproduction
### In Copyright
### Public Domain Status
### Rights Statement

# TELEGRAM PRINTS
## Digitization Workflows

## Descriptive Metadata For prints
### ASC Number
### Box and File Number
### Identifier Other
## Title
## Title Note

[image of Scan of verso of a print featuring all three types]
#### Caption
#### Cutline
#### Annotation

## Description (Abstract)

## Names
### Photographers
Tab 3 of spreadsheet
### Wire Services
Tab 4 of spreadsheet
### Author of article
Create a directory of known Toronto Telegram reporters, columnists
## Origin Information (Dates)
Determining the date of a Telegram print can be tricky.

### Date taken (free text)
Enter the earliest date stamped on verso of print. 
Enter date without punctuation in the following format (including full month): 18 January 1967.
Sometimes the information is incomplete, and sometimes there are multiple dates stamped on the verso of a print.
YUL policy is to document the date the print was first created in this field, not its previous form (photonegative) or future forms (reproduction in the Telegram or in other publications) in this field. Any subsequent reuses are documented in fields such as Date Published or Publications.

Based on RAD Rule 1.4.B5. we follow the recoding conventions for probable and uncertain dates as follows: 

| Date | convention |
| --------- | --------- |
| [1967?] | probable date|
| [ca. 1967] | approximate date |
| [before 1967] | terminal date |
| [after 5 Jan. 1967]| terminal date |
| [1930 or 1933]| one year or the other |
| [between 1915 and 1918]| use only for dates fewer than 20 years apart |
| [196-] | decade certain |
| [196-?] | probable decade |
| [19–] | century certain |
| [19–?] | probable century |
	
### Date taken (ISO)
This field is required.
Enter the earliest date stamped on the verso of the print in the following format YYYY-MM-DD.
If the information is incomplete, or an estimate, YUL policy is to follow ISO_8601 standards on documenting intervals extended date/time formats. For more information see: https://www.loc.gov/standards/datetime/

The character '?' (question mark) is used to mean "uncertain". The character '~'  (tilde) is used to mean "approximate".  The character  '%’  (percent)  is  used to  mean  “both  uncertain  and  approximate".  “Uncertain” and/or “approximate” may apply to full representations as well as representation with reduced precision.

| Date (RAD standard) | convention | [ISO 8601_2](https://www.iso.org/standard/70908.html) |
| --------- | --------- | --------|
| [1967?] | probable date| 1967? |
| [ca. 1967] | approximate date | 1967~ |
| [before 1967] | terminal date | ../1967-01-01 |
| [after 5 January 1967]| terminal date | 1967-01-05/.. |
| [1930 or 1933]| one year or the other | [1930,1933] |
| [between 1915 and 1918]| use only for dates fewer than 20 years apart | 1915-01-01~/1918-12-31 |
| [196-] | decade certain | 196 |
| [196-?] | probable decade | 196~ |
| [19–] | century certain | 19~ |
| [19–?] | probable century | 1900/1999 |

### Date published (ISO)
Only enter this field if you can confirm the date of publication in the Toronto Telegram. This can be from a dated news clipping or caption attached to print, or by evidence obtained by looking at the microfilm.

## Physical description
### Format
Describe the item using the following format: 1 photograph : b&amp;w print ; ##.# x ##.# cm
### Relation
Typically will always be 1 print scanned out of folder.
May also be a series of prints from the same roll of film that has been clipped together, in which case note, "1 of a set of x prints scanned out of folder..."
## Publications


## Subjects
### Subjects
### Topic
### Geographic
### Cartographic
## Use and Reproduction
### In Copyright
### Public Domain Status
### Rights Statement

# OBJECT MODS
#### This is a manual to assist people in entering descriptive metadata into YUDL using the generic Object MODS form.
## Digitization workflows
_point to seperate docs for sound recordings/video/slides/illustrations/maps??_
## Titles
### Proper Title
### Proper Title Sub Title
### Supplied Title
### Supplied Title Sub Title
### Alternative Title
### Alternative Title Sub Title

## Names
##  Name type
##  Authority
### Authority URI
### Value of URI
##  Terms of Address
##  Date
##  Affiliation

## Role
We use terms listed under the LOC MARC Relator Codes. See: http://id.loc.gov/vocabulary/relators.html. A quick alphabetical listing of these terms can be found here: https://www.loc.gov/marc/relators/relacode.html
Select the most approriate term, or leave this field empty.

##  Type of Resource

##  Genre
As part of a move towards more structured descripttion, we must attribute a genre term (preferably from an existing ontology listed [here](https://www.loc.gov/standards/sourcelist/genre-form.html) to every object we ingest. Below are some common genres based on our collection strengths.

| Term | Authority | Authority URI | Term URI |
| ----- | ---- | ---- | ---- |
| Personal correspondence | lcgft | http://id.loc.gov/authorities/genreForms | http://id.loc.gov/authorities/genreForms/gf2014026141.html |
| Modern dance | lcsh | http://id.loc.gov/authorities/subjects | http://id.loc.gov/authorities/subjects/sh85086440.html |
| Oral histories | lcgft | http://id.loc.gov/authorities/genreForms | http://id.loc.gov/authorities/genreForms/gf2011026431.html | Folk music | lcgft | http://id.loc.gov/authorities/genreForms | http://id.loc.gov/authorities/genreForms/gf2014026809.html |
| Interviews (Sound recordings) | lcgft | http://id.loc.gov/authorities/genreForms/ | http://id.loc.gov/authorities/genreForms/gf2015026013 |
| Speeches | lcgft |http://id.loc.gov/authorities/genreForms/ | http://id.loc.gov/authorities/genreForms/gf2011026363.html |

Note that there are nuanced differences between genre and form (also a required field listed below)

## Origin Info

### Date (other) Free Text
### Date Issued
### Publisher
### Place

## Language
### Language Authority "iso639-2b"
Prompt: No language? zxx

##  Abstract
_Examples needed_

## Identifier
### Handle
### Local Identifier
### Identifier Other

## Location
### Physical Location
### Location Note

##  Physical Description

##  Extent
Provide a descriptive statement regarding the physical extent of the object being described, following the conventions established in RAD 1.5B. Should be always listed by height/length then width, and default scale should be in cm.

Below are some of the more common formats and examples

* 1 photograph : b&amp;w negative; 5.3 x 3.6 cm

* 1 photograph : colour positive ; 35 mm

* Sound recording
* Video
* Film
* Illustration
* Painting

## Form
While there is overlap between the Genre and the Form fields, in Form your focus should be on the 'aboutness' of an object.
For example:
* In `Genre` you might use [Concert programs](http://id.loc.gov/authorities/genreForms/gf2014026065.html) but in the `Form` field you would provide terms like [Pamphlets](), [Leaflets](http://id.loc.gov/vocabulary/graphicMaterials/tgm005863.html) or [Fliers (Printed matter)](http://id.loc.gov/vocabulary/graphicMaterials/tgm004107.html), depending on the form said concert program takes. In the same manner, in `Genre` you might enter Folk music but in the `Form` fields you may provide terms like Audiocassettes, audiotape reels, or [LP recordings](http://id.loc.gov/vocabulary/ethnographicTerms/afset010822.html) .
Here are some common forms that are in use within YUDL:

| Term  | Authority | Authority URI | Value URI | 
| ---- | ---- | ---- | ----- |
| Correspondence | gmgpc | http://id.loc.gov/vocabulary/graphicMaterials | http://id.loc.gov/vocabulary/graphicMaterials/tgm002590.html |
| Pamphlets | gmgpc| http://id.loc.gov/vocabulary/graphicMaterials | http://id.loc.gov/vocabulary/graphicMaterials/tgm007415.html |
| Leaflets| gmgpc |http://id.loc.gov/vocabulary/graphicMaterials |http://id.loc.gov/vocabulary/graphicMaterials/tgm005863.html |
| Fliers (Printed matter) | gmgpc | http://id.loc.gov/vocabulary/graphicMaterials | http://id.loc.gov/vocabulary/graphicMaterials/tgm004107.html |
| Photographs | gmgpc | http://id.loc.gov/vocabulary/graphicMaterials/ | http://id.loc.gov/vocabulary/graphicMaterials/tgm007721.html |
| audiotape reels | afset | http://id.loc.gov/vocabulary/ethnographicTerms/ | http://id.loc.gov/vocabulary/ethnographicTerms/afset001070.html |
| Audiocassettes |gmgpc | http://id.loc.gov/vocabulary/graphicMaterials | http://id.loc.gov/vocabulary/graphicMaterials/tgm012458.html |
| LP recordings | afset | http://id.loc.gov/vocabulary/ethnographicTerms | http://id.loc.gov/vocabulary/ethnographicTerms/afset010822.html |
| videotapes | afset | http://id.loc.gov/vocabulary/ethnographicTerms | http://id.loc.gov/vocabulary/ethnographicTerms/afset019647.html |
| 16mm film | afset | http://id.loc.gov/vocabulary/ethnographicTerms | http://id.loc.gov/vocabulary/ethnographicTerms/afset000003.html |
| 8mm film | afset |http://id.loc.gov/vocabulary/ethnographicTerms | http://id.loc.gov/vocabulary/ethnographicTerms/afset000013 |
## Notes
### General note
### Publication Note
### Funding Note
### Related item
###  Title Info
### Location
### Finding Aid URI

## Subject
## Topic
## Geographic
## Temporal
## Geographic
### Continent
### country
### Province
### Region
### County
### City
### citySection
### cartographics

## Use and Reproduction
### In Copyright
Is your object in copyright? http://rightsstatements.org/vocab/InC/1.0/

### Public Domain Status
Is your object in the public domain? https://creativecommons.org/publicdomain/mark/1.0/

### Rights Statement
Does your object have additional rights, permissions and descriptions that users must adhere to?


### What to do when you encounter a negative that already has a ASC # when completing an assignment?
1. If you come across a negative that has already been assigned an ASC # that means the negative has already been scanned.
2. Look up the ASC# in the master image log folder.
3. Check if the negative has been scanned at the correct dpi. If not, rescan at correct dpi.
4.  If vinegar syndrome is actively present (neg appears crackly and brittle), do not overwrite the old scan until you have compared them, as the old scan may actually be better if the damage has accelerated since the last scan.
5. Check to see if the image is already online in YUDL. If it is, make sure to include a note about that in your ticket for this envelope - this means that the staff person will have to go into Islandora and:
- edit the MODS Datastream for that image with any new additional metadata (some older scans are a bit “light” on metadata and 
- if there is mo evidence of active vinegar syndrom,  “replace” the older, lower quality .tiff file in the record’s OBJ Datastream. 
6. Staff will remove the metatadata of TIFFs already scanned before doing a batch ingest.
7. Staff will move the higher quality scan into the appropriate .tiff folder
8. In your spreadsheet, use the old ASC # that has already been assigned to the neg and fill the field with the correct metadata.



