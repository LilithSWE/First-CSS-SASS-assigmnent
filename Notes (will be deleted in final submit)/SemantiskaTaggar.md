Kom ihåg lapp för semantiska taggar, enligt W3 school:

<article> - Defines independent, self-contained content 
  Krav: An article should make sense on its own and it should be possible to distribute it independently 
        from the rest of the site.
  Används för: Forum posts, Blog posts, News stories. 

<aside> - Defines content aside from the page content
  Krav: The aside content should be indirectly related to the surrounding content.
  Tips: The <aside> content is often placed as a sidebar in a document.


<details> - Defines additional details that the user can view or hide/ can open and close on demand.
  Krav: Any sort of content can be put inside the <details> tag. 
  Tips: The <details> tag is often used to create an interactive widget that the user can open and close. 
        By default, the widget is closed. When open, it expands, and displays the content within.


<figcaption> - Defines a caption for a <figure> element
  Krav: The <figcaption> element can be placed as the first or last child of the <figure> element.

<figure> - Specifies self-contained content, like illustrations, diagrams, photos, code listings, etc.
  Krav: While the content of the <figure> element is related to the main flow, 
        its position is independent of the main flow, and if removed it should not affect the flow of the document.
  Tips: The <figcaption> element is used to add a caption for the <figure> element.

<footer> - Defines a footer for a document or section
  Krav: Should be placed at the bottom of the page or section. 
  Används till: Authorship information, copyright information, contact information, sitemap,
                back to top links, related documents.
  Tips: Contact information inside a <footer> element should go inside an <address> tag.

<header> - Specifies a header for a document or section. 
 Krav: The <header> element represents a container for introductory content or a set of navigational links.
       Should be placed at the top of the page or section. You can have several <header> elements in one HTML document. 
       However, <header> cannot be placed within a <footer>, <address> or another <header> element.
  Används till: one or more heading elements (<h1> - <h6>), logo or icon, authorship information.

<main> - Specifies the main content of a document
Krav: The content inside the <main> element should be unique to the document. 
      It should not contain any content that is repeated across documents such as sidebars, navigation links, copyright information, site logos, and search forms.

      There must not be more than one <main> element in a document. The <main> element must NOT be a descendant of an <article>, <aside>, <footer>, <header>, or <nav> element.

<mark> - Defines marked/highlighted text

<nav> - Defines navigation links
  Krav: Notice that NOT all links of a document should be inside a <nav> element. 
        The <nav> element is intended only for major blocks of navigation links.

        Browsers, such as screen readers for disabled users, can use this element to determine whether to omit the initial rendering of this content

<section> - Defines a section in a document

<summary> - Defines a visible heading for a <details> element. The heading can be clicked to view/hide the details.
  Krav: The <summary> element should be the first child element of the <details> element.

<time> - Defines a date/time
  Krav: The datetime attribute of this element is used translate the time into a machine-readable format
        so that browsers can offer to add date reminders through the user's calendar, and search engines can produce smarter search results.