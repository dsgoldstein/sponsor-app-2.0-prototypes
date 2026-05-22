# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Purpose

This is a rapid UI prototyping workspace. The base is a static HTML page (`Section 2.html`) pulled from a Salesforce Experience Cloud application (OASIS ACF sponsor portal). The goal is to prototype new UI interactions and components on top of this existing form layout to showcase ideas to stakeholders.

## Structure

- `Section 2.html` — the main prototype page (originally a Salesforce OmniScript application view)
- `Section 2_files/` — static assets (CSS, JS, images) saved with the page

## Prototyping Approach

The page is fully static — no Salesforce backend connectivity. All prototyping is done by editing the HTML directly or adding new assets to the files directory.

Planned component additions:
- Audio player for form instructions
- Video player for guidance content
- Rich text components for detailed form instructions
- Modals with contextual help content

## Serving Locally

Open `Section 2.html` directly in a browser, or use any static file server:

```
python3 -m http.server 8000
```

## Key Context

- The original page uses Salesforce Lightning Design System (SLDS) classes and USWDS (U.S. Web Design System) styling
- OmniStudio/Vlocity components are present but non-functional in this static context
- The page includes multi-language support scaffolding (English, Spanish, etc.)
- Prototype changes should look visually consistent with existing USWDS and SLDS styling
