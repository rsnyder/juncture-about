[![](https://v3.juncture-digital.org/badge.png)](https://v3.juncture-digital.org)

# About Juncture

**[Juncture](https://v3.juncture-digital.org)** is a set of services and web components designed to work with GitHub and Markdown to easily create interactive web pages/sites.  

GitHub is a free web service that provides file and web hosting, Markdown file editing, and powerful tools for collaboration and workflow management.  Markdown is a simple markup language commonly used for formatting plain text.

Juncture components can be easily added to any Markdown text to create interactive and engaging web pages.

##

`image wc:Incense_in_Vietnam.jpg right`

Commonly used Juncture components include an IIIF-enabled image viewer.

Juncture's IIIF ([International Image Interoperability Framework](https://iiif.io)) compatible image viewer supports panning and zooming of high resolution images.  Images may also be viewed in full screen mode.

Interactive features like [zoomto image region](zoomto/3312,261,1359,907) are provided for connecting the narrative with the viewer.  Image annotations are also supported.

Metadata is linked to the image provding owner attribution, licensing and reuse rights, descriptions, and other useful information.

Juncture supports the authoring and viewing of scholarly content with support for
- Footnotes
- Image attribution
- Image and essay annotation
- PDF generation

Juncture is based on open technologies and resources, including
- The IIIF (International Image Interoperability Framework) and OpenSeadragon for images
- Leaflet and GeoJSON for maps and map overlays
- Wikidata knowledge graph
- Wikimedia Commons

##
`.columns`

### Juncture components

- [Image](https://v3.juncture-digital.org/#/docs/components/image-viewer) and [map](https://v3.juncture-digital.org/#/docs/components/map-viewer) viewers
- [Audio](https://v3.juncture-digital.org/#/docs/components/audio-player) and [video](https://v3.juncture-digital.org/#/docs/components/video-player) players
- [Header](https://v3.juncture-digital.org/#/docs/components/header) and [footer](https://v3.juncture-digital.org/#/docs/components/footer) 
- An [IFrame viewer](https://v3.juncture-digital.org/#/docs/components/iframe-viewer) for embedding external resources
- Support for [Mermaid](https://v3.juncture-digital.org/#/docs/components/mermaid-diagram-viewer) and [Vis.js](https://v3.juncture-digital.org/#/docs/components/visjs-diagram-viewer) diagrams
- And much more…

### Juncture tools/ and services

- Web editor with preview and drag-drop support for images and multimedia
- IIIF image server with automatic IIIF image creation
- Juncture-enabled web server for exploration and sharing
- A [GitHub template](https://github.com/juncture-digital/template) for easily creating websites with support for custom domains
- A semantic search tool for locating images and documents for use in visual essay development

## Viewing a Juncture essay

Any Markdown file hosted in Github can be viewed as a Juncture visual essay.  All that is needed is to point the Juncture server to the Markdown file.

> [https://v3.juncture-digital.org](https://v3juncture-digital.org) + `Github username` + `Github repository name` + `Optional repository file path`

For example, 

- to render this file as a Juncture visual essay - [https://v3.juncture-digital.org/rsnyder/juncture-about](https://juncture-digital.org/rsnyder/juncture-about)
- to render an example file in this repository - [https://v3.juncture-digital.org/rsnyder/juncture-about/examples/monument-valley](https://v3.juncture-digital.org/rsnyder/juncture-about/examples/monument-valley)

## Creating a Juncture Website

The Juncture server provides a convenient way for exploring Juncture and sharing visual essays.  Using the Juncture server any Markdown file can be easily viewed as a Juncture essay.  For users that want to create a full-featured web site (with an optional custom domain) from Juncture-enabled Markdown files a GitHub template is provided to quickly get a site up and running.  The [GitHub Setup Guide](https://v3.juncture-digital.org/#/docs/getting-started?id=github-setup) on the Juncture site provides a simple 2-step process for activating a Juncture web site in less than 2 minutes.

## Juncture History

### Initial version

The [Plant Humanities Lab](https://lab.plant-humanities.org) is a web site hosting visual essays that "Explore the cultural histories of plants and their influence on human societies".  The Plant Humanities Lab was launched in 2021 as a key output of 2 Mellon funded projects jointly conducted by Dumbarton Oaks and JSTOR Labs.

The infrastructure for the Plant Humanities Lab enables non-programmers to generate a single visual essay or a rich web site consisting of multiple interactive visual essays.

A generalized version of the visual essay rendering code developed for the Plant Humanities Lab was released at the conclusion of the development projects as [Juncture](https://v3.juncture-digital.org)

#### Recent versions

Following the release of Juncture in Fall 2021, Juncture continued to evolve and addressed some of the lessons learned in developing and using the first version.

- Improved flexibility in page layouts, including better accessibnility and rendering on mobile devices
- Enhanced IIIF support, including new capabilities for creating and using self-hosted image collections in Github
- Authoring tools for easier editing
    - Preview from editor
    - Drag-and-drop for images and videos with automatic tag creation
- Improved on-line documentation with drag-and-drop and cut-paste code snippets
- Viewer components reimplemented as standard HTML5 Web Components enabling use outside of Juncture environments, including in vanilla HTML pages and Wordpress

The Juncture web site is located at https://juncture-digital.org.  A beta site for the 3rd generation of Juncture is located at https://v3.juncture-digital.org.  This version will be released before the end of 2024 and is generally recommended for use.

## Key technologies used in Juncture

A guiding principle in the development of the Plant Humanities Lab (and the subsequent evolution of Juncture) was use of free and/or open-source tools where possible in a minimal computing environment. 

### Github

[GitHub](https://www.github.com), Inc. is a platform and cloud-based service commonly used for software development and version control.  It provides distributed version control plus access control, bug tracking, software feature requests, task management, continuous integration, and project wikis.  Github has been a subsidiary of Microsoft since 2018.

As of 2023, GitHub reported having over 100 million developers and more than 372 million repositories, including at least 28 million public repositories. It is the world's largest source code host as of June 2023.

Github features incclude,

- File storage (Markdown, images, annotations, etc)
- A rich API for programmatic interaction with repository contents
- Version control
- Support for implementation of publishing workflows
- Web hosting, with custom domains
- Most features are free to use (including all features used by Juncture)

New Github users may find the first couple episodes in the [Github for Poets](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6ZF9C0YMKuns9sLDzK6zoiV) video series helpful as a gentle introduction to Github use and concepts.

### Markdown

[Markdown](https://www.markdownguide.org/) is a lightweight markup language for creating formatted text using a plain-text editor. Markdown was created in 2004 as a markup language that is easy to read in its source code form.  Markdown is widely used for blogging and instant messaging, and also used elsewhere in online forums, collaborative software, documentation pages, and readme files.

### Wikidata

[Wikidata](https://www.wikidata.org) is a collaboratively edited multilingual knowledge graph hosted by the Wikimedia Foundation.It is a common source of open data that Wikimedia projects such as Wikipedia, and anyone else, can use under the CC0 public domain license. Wikidata is a wiki powered by the software MediaWiki, including its extension for semi-structured data, the Wikibase.

### International Image Interoperability Framework (IIIF)

[The International Image Interoperability Framework](https://iiif.io) (IIIF, spoken as 'triple-I-eff') defines several application programming interfaces that provide a standardised method of describing and delivering images over the web, as well as "presentation based metadata" (that is, structural metadata) about structured sequences of images. If institutions holding artworks, books, newspapers, manuscripts, maps, scrolls, single sheet collections, and archival materials provide IIIF endpoints for their content, any IIIF-compliant viewer or application can consume and display both the images and their structural and presentation metadata.

### Leaflet

```
map Q201492,12 marker right
Q83813
```

[Leaflet](https://leafletjs.com/) is an open source JavaScript library used to build web mapping applications. First released in 2011, it supports most mobile and desktop platforms, supporting HTML5 and CSS3. Among its users are FourSquare, Pinterest and Flickr.

Leaflet allows developers without a GIS background to very easily display tiled web maps hosted on a public server, with optional tiled overlays. It can load feature data from GeoJSON files, style it and create interactive layers, such as markers with popups when clicked.

Like the Juncture image viewer, the map viewer also supports the use of text triggers for map animation.  The [flyto](/flyto/Q83813) interaction repositions a map using a Wikidata identifier or geographic coordinates.

### GeoJSON

[GeoJSON](https://geojson.org/) is an open standard format designed for representing simple geographical features, along with their non-spatial attributes. It is based on the JSON format.

The features include points (addresses and locations), line strings (streets, highways and boundaries), polygons (countries, provinces, tracts of land), and multi-part collections of these types.

# Examples

## Some sites currently using Juncture

- [Kent Maps Online](https://www.kent-maps.online)
- [Biodiversity Stories](https://www.juncture-digital.org/Digital-Scholarship-NUS-Libraries/biodiversitystories/) - Site developed by Katherine Enright, a participant in a Dumbarton Oaks summer program
- [Edison Papers Exhibit Site](https://www.juncture-digital.org/edisonpapers/Latimer)
- [DigitalPeni](https://digitalpeni.org/)
- [Print & Probability](http://bookhistory.rocks/)

## Demo essays

- [Monument Valley](https://juncture-digital.github.io/examples/monument-valley)
- [Amalfi Coast](https://juncture-digital.github.io/examples/amalfi-coast)

## FAQ

1. **How much does it cost to use Juncture?**

	Nothing for basic usage - GitHub accounts and hosting are free and Juncture is open source.
	A nominal cost may be incurred to add a custom domain.  These can often be obtained for around $20/year.

2. **What level of technical expertise is required to setup and run a Juncture site?**

	Some familiarity with GitHub and Markdown is needed to get started with a basic website.
	More elaborate websites with interactive maps, entity popovers, and such may require some additional familiarity with GeoJSON, Wikidata, and other technologies.

	*Programming skills are not needed to setup and maintain a Juncture site.*

# For more info...

Contact me via [email](mailto:ron@snyderjr.com)
