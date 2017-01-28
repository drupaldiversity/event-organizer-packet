
## Initial Notes to Contribute

When adding documents, be sure to use [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/ "GitHub Flavored Markdown").

[Using GitBook | GitBook Toolchain Documentation](https://toolchain.gitbook.com/ "GitBook Toolchain Documentation")

### Contributors

#### Writers

- drnikki
- yesct
- cleverington
- bradleyfields

#### Editors

- cottser
- drnikki
- yesct
- cleverington
- sugaroverflow

### Editing

Editing current pages can be done using MarkDown via GitHub or Git by submitting Pull Requests.

![Contribution Edit Link](../../images/contribution-edit-link.png "Contribution Edit Link")

Authorized Contributors added into the @drupal-diversity Organization on GitBook can use the In-Browser editing feature for existing pages live here: [Drupal Developer Resources - In-Browser Editing](https://www.gitbook.com/book/drupal-diversity/drupal-organizer-resources/edit#/edit/master/README.md?_k=9owlcs "Drupal Developer Resources - In-Browser Editing")

### Copy-Edit Guidelines

The Drupal Documentation Team recently published the Drupal 8 User's Guide and the associated writing / editing documentation used.

See the definitions of Writer and Editor in the GLOSSARY.md.

#### This eBook will follow the Guidelines outlined in the Style Guid

- [Drupal.org/docs: User Guide Contributor Guidelines](https://www.drupal.org/docs/user_guide_guidelines/index.html "User Guide Contributor Guidelines")
- [Drupal.org/docs: User Guide Contributor Guidelines - Preface](https://www.drupal.org/docs/user_guide_guidelines/preface.html "User Guide Contributor Guidelines - Preface")
- [Drupal.org/docs: User Guide Contributor Guidelines - Chapter 1. Instructions for contributors](https://www.drupal.org/docs/user_guide_guidelines/instructions.html "User Guide Contributor Guidelines - Chapter 1. Instructions for contributors")
- [Drupal.org/docs: User Guide Contributor Guidelines - Chapter 2. Guidelines](https://www.drupal.org/docs/user_guide_guidelines/guidelines.html "User Guide Contributor Guidelines - Chapter 2. Guidelines")
- [Drupal.org/docs: User Guide Contributor Guidelines - Chapter 3. Instructions for project managers](https://www.drupal.org/docs/user_guide_guidelines/pm-section.html "User Guide Contributor Guidelines - Chapter 3. Instructions for project managers")

#### Example Pages

- [Drupal 8 User Guide - 2.1. Concept: Regions in a Theme](https://www.drupal.org/docs/user_guide/en/block-regions.html "Drupal 8 User Guide - 2.5. Planning your Content Structure")
- [Drupal 8 User Guide - 2.5. Planning your Content Structure](https://www.drupal.org/docs/user_guide/en/planning-structure.html "Drupal 8 User Guide - 2.5. Planning your Content Structure")

**Note** - Though following the Guidelines, we will be using GitHub Flavored Markdown (as noted above) instead of ASCII-DOC (as used by the Drupal Documentation Team).

The Style Guide created for the Drupal 8 User's Guide was loosely based on the *Drupal.org* Style Guide, available at https://www.drupal.org/drupalorg/style-guide/content.

### Including 'New' Pages

When adding new pages to the 'Book', they need to be updated in the [SUMMARY.md](SUMMARY.md "SUMMARY.md")
 file in order to be recognized by GitBook.

### Creating Links
```
[https://www.drupal.org/community](https://www.drupal.org/community "Title Text")
```

### Adding Images
```
![Druplicon](../images/druplicon-small.png "Druplicon")
```

If the images are in a directory, add the directory:

At times, the image may fail to load, even if deployed properly. Simply submit an issue requesting image correction and we can help link it.

```
![Druplicon](../images/random-directory/druplicon-small.png "Druplicon")
```

Be Accessible. Remember the Alt-Text!

### Adding YouTube Videos

```
take a look at this video:

{% youtube %}https://www.youtube.com/watch?v=oHg5SJYRHA0{% endyoutube %}
```
