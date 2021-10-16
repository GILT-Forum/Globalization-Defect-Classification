# Globalization Defects 

## Document Revision History

| Version |  Revision Date     | Description|
|---------|--------------------|----------------------------------------------------------------------------------|
| v1.0    |  13 Oct 2021       | First Draft sent by the GILT Leaders’ Forum for Review by GILT community members |


## Globalization Defects Task Force Contributors

Satyendra Sheel – **Adobe** \
Lugarini, Enrico – **PTC** \
Lynn Ma – **VMWare** \
Arvind Pattabiraman – **Dell**

## Contact

**GILT Leaders’ Forum**: [https://github.com/GILT-Forum/Globalization-Defects](https://github.com/GILT-Forum/Globalization-Defects/issues)

## License

This resource is free for you to use and share as long as you adhere to the terms of the CC license.

![CC-BY-NC-SA](./media/image1.png)

Best Practices in Translation Memory Management is licensed under a [*Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License*](http://creativecommons.org/licenses/by-nc-sa/4.0/).

## Introduction

The GILT Leaders Forum is a self-organized group of seasoned globalization professionals representing various companies from the "buyer" side. The group chartered a Globalization Defects Management Task Force to research and produce standard set of categories to classify globalization defects. By globalization, we refer to internationalization, localization and linguistic issues.

The purpose of this work has been to gather knowledge from G11n Quality experts and transfer it to those responsible for managing quality/defects in their own organizations, or on behalf of others.


Upon completion of the first draft, we sought feedback from practitioners and experts in the wider GILT Community, including Language Service Providers and localization technology providers.


## Globalization defects category

### Internationalization defects 

| Keyword  (Level 1)             |  Keyword  (Level 1)     | Applicable to <br>(Software/<br>Documentation/<br>Both) |  Definition|
|--------------------------------|-------------------------|---------------|--------------------------------------------------------------------|
| INTL-Layout                    |                         | Both          | Any I18N layout/truncation issue observed in localized UI and doc. |
| INTL-Locale                    |                         | Software      | This covers issues related to locale related changes like Collation, Time, Date, Region, Numbers etc. |
| INTL-Localizability            |                         | Software      | All issues where string can't be localized due to wrong coding practices at core side. <br>When a build can’t be deployed in the selected locale. <br>The Languages supported by the product are not available in UI. |
|INTL-Multilingual-Text- Support |                         | Software      | Issues related to text support like Input, File operatoon, Display, Editing, Searching, Printing, GB18030          |
|INTL-Build-Testing-Environment  |                         | Software      | Issues related to product's build, environment set up. E.g.: <br> - Product's build process cannot be localized into multiple languages. <br>- Build directory structure's language-specific assets are not contained in language-specific folders or files.|
|INTL-TestAutomation             |                         | SOftware      |Test automation not according to I18n best practices- i.e. test data and resources are hardcoded in test scripts; no support to change the test language in script.|
|INTL-Other                      |                         | Both          |Any I18N issue that doesn't fall in any other category.|




### Localization defects
| Keyword                             | Applicable to <br>(Software/<br>Documentation/<br>Both) | Definition |
| ----------------------------------- | --------------------------------------------------------| ----------------|
| LOC-Functional                      | Software   | Features that do not function correctly in some languages but work in other languages. |
| LOC-Shortcut-Hotkeys                | Software   | This will cover bugs for shortcuts keys and hotkeys.  |
| LOC-URL                             | Both       | Covers any URL specific issues: 404 or 500 error |
| LOC-NotTranslated                   | Both       | When strings are externalized or segments are available for translation but appear in English in some languages but localized in other languages.  |
| LOC-Trans-Literal-Preferential      | Both       | Optional/preferential change. Where original translation is not wrong however the person performing linguistic testing/review prefers another translation over original one. Refers to subjective opinion.  |
| LOC-Trans-MisTranslation            | Both       | Translation is not correct in the context (i.e. the meaning is not correct); not from the grammar point of view.  |
| LOC-Trans-Grammar-Spelling          | Both       | Translation is correct in the context but has gramatical/spelling issues. This also covers any punctuation issue.   |
| LOC-Trans-Style-Inconsistency       | Both       | Inconsistent translation/style issue within/across application or with the source (e.g. same source translated in multiple ways, mix of personal and impersonal style, tailing spaces, new line, number of variables etc. |
| LOC-Trans-Terminology-Inconsistency | Both       | Incorrect terminology translation (non-compliance with product/company/3rd party terminiology) or<br>terminology is correct, but it is not used consistently.<br>Terms that should not be localized like product name, company name. |
| LOC-Trans-StyleGuide                | Both       | Non-compliance with company style guides and instructions. e.g awkward syntax, unidiomatic use of target language, tone and project specific instructions etc. |
| LOC-Other                           | Both       | Any localization issue that doesn't fall in any other category.  |
