# NHS.UK Design System snippets for Nunjucks

This Atom package includes snippets to help build the UK's NHS digital services.

## Installation
Go to `Atom > Preferences > Install` and then search for `nhsuk design system snippets` under `Packages`.

After installing the package, you will need to restart Atom.

## Available snippets

### Styles

#### Layout

|Name|Shortcut|Notes|
|-------------------------|-------------------------|---|
|Form group|`nhsuk-form-group`||
|Form section|`nhsuk-form-section`||
|[Grid column full](https://service-manual.nhs.uk/design-system/styles/layout)|`nhsuk-grid-column-full`||
|[Grid column one-half](https://service-manual.nhs.uk/design-system/styles/layout)|`nhsuk-grid-column-one-half`||
|[Grid column one-quarter](https://service-manual.nhs.uk/design-system/styles/layout)|`nhsuk-grid-column-one-quarter`||
|[Grid column one-third](https://service-manual.nhs.uk/design-system/styles/layout)|`nhsuk-grid-column-one-third`||
|[Grid column two-thirds](https://service-manual.nhs.uk/design-system/styles/layout)|`nhsuk-grid-column-two-thirds`||
|[Grid column](https://service-manual.nhs.uk/design-system/styles/layout)|`nhsuk-grid-column`||
|[Grid row](https://service-manual.nhs.uk/design-system/styles/layout)|`nhsuk-grid-row`||
|[Layout one-third / two-thirds](https://service-manual.nhs.uk/design-system/styles/layout)|`nhsuk-layout-one-third-two-thirds`||
|[Layout two-thirds / one-third](https://service-manual.nhs.uk/design-system/styles/layout)|`nhsuk-layout-two-thirds-one-third`||

#### Typography

|Name|Shortcut|Notes|
|-------------------------|-------------------------|---|
|Caption|`nhsuk-caption`||
|[Font size override](https://service-manual.nhs.uk/design-system/styles/typography#font-size)|`nhsuk-font-size`||
|[Font weight override](https://service-manual.nhs.uk/design-system/styles/typography#font-weight)|`nhsuk-font-weight`||
|[Heading](https://service-manual.nhs.uk/design-system/styles/typography#headings)|`nhsuk-heading`||
|[Links](https://service-manual.nhs.uk/design-system/styles/typography#links)|`nhsuk-link`||
|[Lists](https://service-manual.nhs.uk/design-system/styles/typography#lists)|`nhsuk-list`||
|[Lists – Bulleted](https://service-manual.nhs.uk/design-system/styles/typography#bulleted-lists)|`nhsuk-list-bulleted`||
|[Lists – Numbered](https://service-manual.nhs.uk/design-system/styles/typography#numbered-lists)|`nhsuk-list-numbered`||
|[Paragraph body text](https://service-manual.nhs.uk/design-system/styles/typography#body)|`nhsuk-paragraph-body`||
|[Paragraph body text large](https://service-manual.nhs.uk/design-system/styles/typography#lead-paragraph)|`nhsuk-paragraph-body-lead`||
|[Paragraph body text small](https://service-manual.nhs.uk/design-system/styles/typography#body-small)|`nhsuk-paragraph-body-small`||
|[Section break](https://service-manual.nhs.uk/design-system/styles/typography#section-break)|`nhsuk-section-break`||
|Visually hidden|`nhsuk-visually-hidden`|Creates a visually hidden `span`|

### Components

#### Form elements

|Name|Shortcut|Notes|
|-------------------------|-------------------------|---|
|Addresses|`nhsuk-address`||
|[Button](https://service-manual.nhs.uk/design-system/components/button)|`nhsuk-button`||
|[Checkboxes](https://service-manual.nhs.uk/design-system/components/checkboxes)|`nhsuk-checkboxes`||
|Checkbox or radio option|`nhsuk-option`|Use in conjunction with the `nhsuk-checkboxes` and `nhsuk-radios` Nunjucks snippets.|
|[Date input](https://service-manual.nhs.uk/design-system/components/date-input)|`nhsuk-date`||
|[Error summary](https://service-manual.nhs.uk/design-system/components/error-summary)|`nhsuk-error-summary`||
|[Fieldset](https://service-manual.nhs.uk/design-system/components/fieldset)|`nhsuk-fieldset`||
|[Radios](https://service-manual.nhs.uk/design-system/components/radios)|`nhsuk-radios`||
|[Select](https://service-manual.nhs.uk/design-system/components/select)|`nhsuk-select`||
|Select option|`nhsuk-select-option`|Use in conjunction with the `nhsuk-select` Nunjucks snippet.|
|[Text input](https://service-manual.nhs.uk/design-system/components/text-input)|`nhsuk-input`||
|[Textarea](https://service-manual.nhs.uk/design-system/components/textarea)|`nhsuk-textarea`||

#### Content presentation

|Name|Shortcut|Notes|
|-------------------------|-------------------------|---|
|[Details](https://service-manual.nhs.uk/design-system/components/details)|`nhsuk-details`||
|[Inset text](https://service-manual.nhs.uk/design-system/components/inset-text)|`nhsuk-inset-text`||
|[Tables](https://service-manual.nhs.uk/design-system/components/table)|`nhsuk-table`||
|[Warning callout](https://service-manual.nhs.uk/design-system/components/warning-text)|`nhsuk-warning-callout`||

#### Navigation

|Name|Shortcut|Notes|
|-------------------------|-------------------------|---|
|[Back link](https://service-manual.nhs.uk/design-system/components/back-link)|`nhsuk-back-link`||
|[Breadcrumbs](https://service-manual.nhs.uk/design-system/components/breadcrumbs)|`nhsuk-breadcrumbs`||
|[Footer](https://service-manual.nhs.uk/design-system/components/footer)|`nhsuk-footer`||
|[Header](https://service-manual.nhs.uk/design-system/components/header)|`nhsuk-header`||
|[Skip link](https://service-manual.nhs.uk/design-system/components/skip-link)|`nhsuk-skip-link`||

## Dependencies
Using this package depends on the installation of the [NHS.UK Frontend](https://www.npmjs.com/package/nhsuk-frontend) and [Nunjucks](https://www.npmjs.com/package/nunjucks) into your project.

## Support
This repository is maintained by Simon Whatley. If you’ve got a question or need support you can:

* Email support@humanedesign.co putting the repository name in the subject line.
* [View known issues on GitHub](https://github.com/simonwhatley/nhsuk-design-system-snippets-atom-package/issues).

## Contributing
If you’ve got an idea or suggestion you can:

* Email contribute@humanedesign.co putting the repository name in the subject line.
* [Create a GitHub issue](https://github.com/simonwhatley/nhsuk-design-system-snippets-atom-package/issues).

## Licence
Unless otherwise stated, this codebase is released under the [MIT License](https://github.com/simonwhatley/nhsuk-design-system-snippets-atom-package/blob/master/LICENSE). This covers both the codebase and any sample code in the documentation.
