# List of work items

## Bug fix

- [ ] invisible headers/footers though settings exist in styles.css and headers-footer.css;
- [x] possible word bleeding in tables/simpletables; 
- [x] sequence of toc: move the list of figures and list of tables to the end of toc;
- [x] abnormal hyphenation in tables

## features

- [ ] customized icons for:
  - [x] note and its variants by attribute value;
  - [x] hazardstatement and its variants by attribute value;
  - [x] relevant local paths in root folder:
   - C:\Program Files\Oxygen XML Editor 23\frameworks\dita\lw\css\img for LwDITA
   - C:\Program Files\Oxygen XML Editor 23\frameworks\dita\css\img for DITA, transformation scenario = HTML5 & CSS
   - p4v path: //Solutions/Documentation/Library/Templates/Art/Rebrand 

- [ ] NI-styled side bar for left and right pages
- [x] Customized Font. Relevant local path:
  - C:\Program Files\Oxygen XML Editor 23\frameworks\dita\css\fonts for DITA, transformation scenario = HTML5 & CSS
- [ ] Customized cc_config for LwDITA, relevant local path:
  - C:\Program Files\Oxygen XML Editor 23\frameworks\dita\lw\resources for LwDITA
  - C:\Program Files\Oxygen XML Editor 23\frameworks\dita\resources for DITA 1.3
- [x] ditaval settings for templates:
    + project
    + product
    + customer
    + year
    + module

## Sample Project

- A sample project created in oxygen;
- It should contain at least 2 conditional texts in current STS templates;
- The conditional texts should be converted to ditavals;
- Fill the metadata for maps, topics.
- Keydef and keyref should be used for certain frequently used phrases;
- Conref should be used for content including copyright, legal notice, compliance chapter;

Structure:

Bookmap
  - Frontmatter
  - Chapters
  - Glossary
  - Relation tables
