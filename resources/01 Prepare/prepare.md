---
title: "Stage 1 - Prepare"
author: "Skills4EOSC T2.3"
tags: 
    - FAIR-by-Design Learning Materials
    - FAIR Learning Objects
    - FAIR Learning Unit Template
hide:
    - toc
    - navigation
---

# Stage 1 - Prepare

## Small cards example

<div class="grid cards" markdown>

- :fontawesome-brands-html5: __HTML__ for content and structure
- :fontawesome-brands-js: __JavaScript__ for interactivity
- :fontawesome-brands-css3: __CSS__ for text running out of boxes
- :fontawesome-brands-internet-explorer: __Internet Explorer__ ... huh?
- :fontawesome-solid-building-columns: **hello**

</div>

## Large cards example

<div class="grid cards" markdown>

-   :material-clock-fast:{ .lg .middle } __Set up in 5 minutes__

    ---

    Install [`mkdocs-material`](#) with [`pip`](#) and get up
    and running in minutes

    [:octicons-arrow-right-24: Getting started](https://google.com)

-   :fontawesome-brands-markdown:{ .lg .middle } __It's just Markdown__

    ---

    Focus on your content and generate a responsive and searchable static site

    [:octicons-arrow-right-24: Reference](https://google.com)

-   :material-format-font:{ .lg .middle } __Made to measure__

    ---

    Change the colors, fonts, language, icons, logo and more with a few lines

    [:octicons-arrow-right-24: Customization](https://google.com)

-   :material-scale-balance:{ .lg .middle } __Open Source, MIT__

    ---

    Material for MkDocs is licensed under MIT and available on [GitHub](https://github.com)

    !!! info "Lorem ipsum"

        Lorem ipsum dolor sit amet, consectetur
        dipiscing elit. Nulla et euismod nulla.
        Curabitur feugiat, tortor non consequat
        finibus, justo purus auctor massa, nec
        semper lorem quam in massa.

    [:octicons-arrow-right-24: License](https://google.com)

</div>

## Diagrams Example

``` mermaid
graph LR
  A[Start] --> B{Error?};
  B[example <a href='https://google.com'>link</a>] -->|Yes| C[Hmm...];
  C[<a href='https://google.com'>just a link</a>] --> D[Debug];
  D --> B;
  B ---->|<a href='https://google.com'>No</a>| E[Yay!];
```

## Admonitions Example

### With no custom title (default title)

!!! note

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

!!! abstract

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

!!! info

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

!!! tip

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

!!! success

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

!!! question

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

!!! warning

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

!!! failure

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

!!! danger

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

!!! bug

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

!!! example

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

!!! quote

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

### With a custom title

!!! note "My Title"

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

### With no title

!!! note ""

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

### Collapsible admonition, defaults to collapsed

??? note

    A collapsible admonition can be created in the same way as a regular one, with the only difference being that it should start with `???` instead of `!!!`.

### Collapsible admonition, defaults to expanded

???+ note

    Syntax: `???+`

## Content Tabs

### Text example

=== "Tab 1"

    Lorem ipsum dolor est... Content of tab 1

=== "Tab 2"

    Lorem ipsum dolor est... Content of tab 2

### Nested cards within tabs

=== "Tab 1"

    <div class="grid cards" markdown>

    -   :material-clock-fast:{ .lg .middle } __Set up in 5 minutes__

        ---

        Install [`mkdocs-material`](#) with [`pip`](#) and get up
        and running in minutes

        [:octicons-arrow-right-24: Getting started](https://google.com)

    -   :fontawesome-brands-markdown:{ .lg .middle } __It's just Markdown__

        ---

        Focus on your content and generate a responsive and searchable static site

        [:octicons-arrow-right-24: Reference](https://google.com)

    -   :material-format-font:{ .lg .middle } __Made to measure__

        ---

        Change the colors, fonts, language, icons, logo and more with a few lines

        [:octicons-arrow-right-24: Customization](https://google.com)

    </div>

=== "Tab 2"

    <div class="grid cards" markdown>

    -   :material-clock-fast:{ .lg .middle } __Install__

        ---

        Install [`mkdocs-material`](#) with [`pip`](#) and get up
        and running in minutes

        [:octicons-arrow-right-24: Getting started](https://google.com)

    -   :fontawesome-brands-markdown:{ .lg .middle } __Markdown__

        ---

        Focus on your content and generate a responsive and searchable static site

        [:octicons-arrow-right-24: Reference](https://google.com)

    -   :material-format-font:{ .lg .middle } __Measure__

        ---

        Change the colors, fonts, language, icons, logo and more with a few lines

        [:octicons-arrow-right-24: Customization](https://google.com)

    </div>

### Nested tabs within cards

<div class="grid cards" markdown>

-   :material-clock-fast:{ .lg .middle } __Install__

    ---

    Install [`mkdocs-material`](#) with [`pip`](#) and get up
    and running in minutes

    === "Tab 1"

        Lorem

    === "Tab 2"

        Ipsum

    [:octicons-arrow-right-24: Getting started](https://google.com)

-   :fontawesome-brands-markdown:{ .lg .middle } __Markdown__

    ---

    Focus on your content and generate a responsive and searchable static site

    === "Tab 1"

        Lorem

    === "Tab 2"

        Ipsum

    [:octicons-arrow-right-24: Reference](https://google.com)

-   :material-format-font:{ .lg .middle } __Measure__

    ---

    Change the colors, fonts, language, icons, logo and more with a few lines

    === "Tab 1"

        Lorem

    === "Tab 2"

        Ipsum


    [:octicons-arrow-right-24: Customization](https://google.com)

</div>