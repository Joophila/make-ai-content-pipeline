Make AI Content & Publishing Pipeline

A multi-stage automation system built with Make.com that transforms external signals and structured inputs into published content assets.
- 1. Trending Topic → Blog Publishing

  - Trigger
    - Monitor trending topics via Inoreader

  - Process
    - Extract topic signal
    - Generate structured blog draft using GPT
    - Format and prepare publish-ready content

  - Output
    - Automated blog upload

  - Engineering Focus
    - Event-based triggering
    - Structured prompt design
    - Minimal manual intervention


- 2. Multi-language Quote Generator → Instagram Automation

  - Input
    - Quote theme or concept

  - Processing
    - GPT generation in 4 languages (English / Chinese / Korean / Japanese)

  - Media Enrichment
    - Retrieve related image via Unsplash
    - Overlay multilingual text onto image

  - Output
    - Auto-published Instagram content

  - Engineering Focus
    - Multilingual content normalization
    - Text-to-image compositing workflow
    - Automated social distribution


- 3. Structured Data → Product Detail Page Automation

  - Input
    - Google Sheets structured product dataset

  - Processing
    - Copy generation
    - Image asset generation
    - Status tracking & row-based iteration
    - Error logging & retry handling

  - Output
    - Figma template auto-populated
    - Production-ready product detail page

  - Engineering Focus
    - Data contract design
    - Idempotent row processing
    - Pipeline observability via status fields
    - Design automation integration
