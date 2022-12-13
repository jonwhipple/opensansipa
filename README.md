# Open Sans IPA
2022-12-12

This is an [Open Sans](https://github.com/googlefonts/opensans) variant that contains the *International Phonetic Alphabet* Extensions Unicode block.

It may be simplest (for the near term) to simply download the files here as a `.zip` because this isn't tracking the main Google effort, nor am I actively drawing or doing development work beyond ensuring these files exist, provide coverage, and don't break. You are welcome to fork this, but who knows what the future holds?

- [First Peoples Languages in British Columbia](#first-peoples-languages-in-british-columbia)
- [Language Coverage](#language-coverage)
- [Font Weights and Styles](#font-weights-and-styles)
- [Directory Structure](#directory-structure)
- [Technical Notes](#technical-notes)
- [TMI](#tmi)
- [Where This Is Going](#where-this-is-going)

## First Peoples Languages in British Columbia
This is an Open Sans variant to add coverage for many of the orthographies of the languages of the First Peoples of British Columbia.

British Columbia is unique within Canada when it comes to Indigenous language diversity. In the context of Canada, B.C.’s languages make up more than 50% of the approximately 61 languages indigenous to this country.
- There are 34 First Nations languages within 7 distinct unrelated language families.
- There are 3 languages once spoken that are now sleeping.
- Languages Indigenous to other parts of Canada are now spoken in B.C. because of migration.
- Source: *[Report on the Status of B.C. First Nations Languages 2018, Third Edition, Fact Sheet](https://fpcc.ca/wp-content/uploads/2020/05/FPCC-Fact-Sheet-Language-Report-2018.pdf)*
- Many of these languages use the *International Phonetic Alphabet* for their written representation.

## Language Coverage
These fonts provide coverage for B.C. First Nations languages that use Latin and/or International Phonetic Alphabet for their writing systems.
- International Phonetic Alphabet Extensions, **Unicode Range** `0250—02AF`
- Spacing Modifiers, **Unicode Range** `02B0—02FF`
- Combining Diacritical Marks, **Unicode Range** `0300—036F`

These fonts **_do not_** contain 
- Unified Canadian Aboriginal Syllabics, **Unicode Range** `1400—167F` (Dene & Cree)
- Unified Canadian Aboriginal Syllabics Extended, **Unicode Range** `18B0—18FF` (Dene & Cree)

## Font Weights and Styles
## Normal Width
- Thin `OpenSansIPA-Thin`
- Thin Italic `OpenSansIPA-ThinItalic`
- Light `OpenSansIPA-Light`
- Light Italic `OpenSansIPA-LightItalic`
- Regular `OpenSansIPA-Regular`
- Italic `OpenSansIPA-Italic`
- ~~Semibold~~
- ~~Semibold-Italic~~
- Bold `OpenSansIPA-Bold`
- Bold Italic `OpenSansIPA-BoldItalic`
- Extra Bold `OpenSansIPA-ExtraBold`
- Extra Bold Italic `OpenSansIPA-ExtraBold`

## Condensed Width
- Thin `OpenSansIPA-CondensedThin`
- Thin Italic `OpenSansIPA-CondensedThinItalic`
- Light `OpenSansIPA-CondensedLight`
- Light Italic `OpenSansIPA-CondensedLightItalic`
- Regular `OpenSansIPA-CondensedRegular`
- Italic `OpenSansIPA-CondensedItalic`
- ~~Semibold~~
- ~~Semibold-Italic~~
- Bold `OpenSansIPA-CondensedBold`
- Bold Italic `OpenSansIPA-CondensedBoldItalic`
- Extra Bold `OpenSansIPA-CondensedExtraBold`
- Extra Bold Italic `OpenSansIPA-CondensedExtraBoldItalic`

## Directory Structure

`dist` contains compressed (`.zip`) archives of compiled binaries in 3 flavours:
- TrueType Font (`.ttf`)
- Web Open Font Format File (`.woff`)
- Web Open Font Format 2.0 File (`.woff2`)

`fonts` contains compiled binary font files as a reference

`sources` contains source `.ufo` files.

## Technical Notes
These fonts are based on Open Sans available via Google Fonts. This project isn't forked and it doesn't track the original project.

These fonts are generated from the original projects sources `.ufo` files as at 2022-12-12. Subsequently they have all the IPA and and diacritics. They also have _a lot_ of kerning pairs and other things that maybe make them a bit large or exhibit momentary delays when displaying for the first time on a device.

These were made to solve some particular problems with previous versions from previous projects. Don't use those. Use these.

### TMI
In 2015–2016 I extended [Open Sans](https://github.com/googlefonts/opensans) with characters in the IPA unicode range, in order to both learn how to handle type and type design. This had the additional benefit of providing a useful font for Vancouver Public Library's new website which had the dual requirements of attempting to adhere to brand guidelines of the time, and establishing typographic support for Indigenous languages of the three First Nations, the territories of which is where Vancouver now exists.

In order to do this work, I established a project separate from the Google Open Sans effort. This was a deliberate choice because I knew I would not be able to actively maintain my fork as Open Sans evolved. Instead I maintained separate files and updated only a couple of times as the local languages and VPL's needs changed.

In 2017 I returned to the work in earnest, with the intent of expanding coverage for all available weights and styles at the time. This became [Open Sans FPBC](https://github.com/jonwhipple/opensansfpbc).

Then because of mental health and a worldwide pandemic, the project lay fallow.

In 2022, VPL required even more coverage, which I was happy to add. I became excited about the project again too. I added the required characters but sadly I introduced a scaling flaw by specifying the wrong units per em in various files with predictably bad results.

And that brings us to now.

**STILL NOT A FORK** because I think of this as an interim solution to getting IPA (and eventually, Canadian Syllabics) into Open Sans.

**NO SEMIBOLD** because there are no `.ufo`s of semibold.

I have used the `.ufo` files because they are character complete in the Unicode Ranges mentioned above. The shipping `.ttf` files contain only a subset of the IPA and other unicode ranges needed.

## Where This Is Going
The First Peoples of British Columbians deserve typeface options, far beyond this modest effort.

Ideally some kind of coalition of First Nations could
- Encourage Google to ensure its [Noto Project](https://fonts.google.com/noto) covers IPA and orthographies such as Unified Canadian Aboriginal Syllabics, Cherokee, Deseret, Osage and others
- Encourage Google and participating type designers to expand their fonts to include these ranges for all the typefaces available via Google Fonts
- A wider general appeal to type designers and foundries to expand their current libraries with these characters, and to include them by default in their new  typefaces
- Perhaps provide some kind of foundation to establish a design team to identify and extend typefaces in this manner

You and I can become advocates for this effort too. Try to find opportunities and ways to elevate this issue and address it in whatever way possible. Whether modest or bold.

Feel free to talk to me about any of this. Reach out via email and be sure to use words like _Open Sans_, _IPA_, _Indigenous_, _First Nations_ in the subject line.
