# lotuscode
Source code and sample data files for Lotus Chart 3D interactive data visualization

The Lotus Chart is a new type of experimental UI that combines parametric geometry with hyperlinks to render thousands of clickable Uniform Resource Identifiers (URIs) visible on a single computer screen at the same time, with visual cues providing metadata, context, and navigational hints. The result is an interactive 3D data map, accessible from any web browser. Lines on a Lotus Chart typically show trading symbols, media content, a web link, or rows within a database. This type of visualization requires no external software and is compatible with most REST API’s.

<a href ="https://web.lotus.fm/examples/">See examples here.</a>

Any type of search filter may be applied but the Lotus Chart structure is well suited for revealing machine learning insights and identifying growth trends across a data ecosystem. Applications include financial analysis, scientific literacy, epidemiology, real estate, e-commerce, marketing analytics, legal e-discovery, entertainment, and information security.

The Lotus Chart is compatible with the following data formats:

 - CSV
 - Excel spreadsheet
 - JSON REST API
 - Python SDK

It is built out using the <a href="https://threejs.org/">three.js</a> library, but could be 'ported for other 3D rendering environments (Unity, Web Assembly) or adapted for mobile devices, should the need or interest arise. The original source code (now deprecated) permitted about 500 links on-screen at one time; the optimizations completed in the summer of 2021 permit up to 2,000 chart lines (links) each representing a row with associated columns and/or metadata. The main advantage is being able to scan quickly through a large dataset using visual filters -- without having to submit a separate query and refresh your screen each time. It's also helpful when evaluating growth trends in the context of another quantitative index, since the significant of a percentage of growth varies greatly depending on the absolute numbers. (See our <a href="https://dev.lotus.fm/red/">global pandemic snapshot</a> for a real-world example.)

This repo contains a stripped-down version of the interactive <a href="https://dev.lotus.fm/retail/2k_view/index.html">Inventory Control and Management Demo</a>, based on CSV data rather than a SQL. Most of the recent work has happened in Python, and is still very much a work-in-progress! If you have questions about how to implement this type of visualization for your specific project, or if you're just curious to learn more, please don't hesitate to contact me.
