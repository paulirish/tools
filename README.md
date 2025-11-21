# tools.simonwillison.net but forked and maybe different.

Simon did ALLLLLLLLL of this and maybe i have small edits deployed here.

Miscellaneous HTML+JavaScript tools built mostly with the help of LLMs. See also [/python/](https://paulirish.github.io/tools/python/) for tools written using Python.

This collection is an experiment in prompt-driven development with very low stakes.

The [colophon](https://paulirish.github.io/tools/colophon) lists commit messages and transcripts for every tool.

The code lives in [simonw/tools](https://github.com/simonw/tools) and many tools used the Claude custom instructions [described here](https://simonwillison.net/2024/Dec/19/one-shot-python-tools/#custom-instructions).

<!-- recently starts -->
<!-- recently stops -->

## Image and media
- [Social media cropper](https://paulirish.github.io/tools/social-media-cropper) crop images to 2×1 for social sharing
- [Image resize and quality comparison](https://paulirish.github.io/tools/image-resize-quality) compare JPEG quality settings
- [Image to JPEG](https://paulirish.github.io/tools/image-to-jpeg) convert PNG or WebP files to JPEG
- [Image to SVG](https://paulirish.github.io/tools/image-to-svg) trace bitmap images to SVG paths
- [SVG to JPEG/PNG](https://paulirish.github.io/tools/svg-render) render an SVG to a raster image
- [SVG sandbox](https://paulirish.github.io/tools/svg-sandbox) display decoded SVG files safely
- [SVG progressive render](https://paulirish.github.io/tools/svg-progressive-render) watch an SVG draw itself
- [BBox cropper](https://paulirish.github.io/tools/bbox-cropper) draw bounding boxes and read the coordinates
- [Mask visualizer](https://paulirish.github.io/tools/mask-visualizer) inspect JSON masks with bounding boxes
- [FFmpeg crop helper](https://paulirish.github.io/tools/ffmpeg-crop) generate FFmpeg commands for cropped videos
- [TIFF orientation viewer](https://paulirish.github.io/tools/tiff-orientation) inspect EXIF orientation metadata
- [Avatar web component](https://paulirish.github.io/tools/avatar-web-component) upload and crop avatars in place
- [YouTube Thumbnails](https://paulirish.github.io/tools/youtube-thumbnails) list thumbnail URLs for a video

## Text and document
- [OCR](https://paulirish.github.io/tools/ocr) recognize text from images and PDFs in your browser
- [PDF OCR](https://paulirish.github.io/tools/pdf-ocr) run optical character recognition on uploaded PDFs
- [Compare PDFs](https://paulirish.github.io/tools/compare-pdfs) visualize differences between two PDFs
- [Render Markdown](https://paulirish.github.io/tools/render-markdown) convert Markdown to HTML using the GitHub API
- [HTML preview](https://paulirish.github.io/tools/html-preview) type HTML on the left and see it rendered on the right
- [RTF to HTML](https://paulirish.github.io/tools/rtf-to-html) inspect RTF clipboard data and convert it to HTML
- [Markdown math](https://paulirish.github.io/tools/markdown-math) live preview of Markdown with LaTeX equations
- [Footnotes experiment](https://paulirish.github.io/tools/footnotes-experiment) demo linking footnotes to popups
- [Reading time calculator](https://paulirish.github.io/tools/reading-time) estimate how long text will take to read
- [Word counter](https://paulirish.github.io/tools/word-counter) count words across multiple text blocks
- [Text wrap balance nav](https://paulirish.github.io/tools/text-wrap-balance-nav) explore the `text-wrap: balance` property
- [Navigation for headings](https://paulirish.github.io/tools/nav-for-headings) generate an ID-based table of contents
- [Paste rich text](https://paulirish.github.io/tools/paste-rich-text) inspect HTML and plain text on your clipboard
- [Paste HTML subset](https://paulirish.github.io/tools/paste-html-subset) see which tags survive HTML sanitization
- [Clipboard viewer](https://paulirish.github.io/tools/clipboard-viewer) debug everything stored in your clipboard
- [Extract URLs](https://paulirish.github.io/tools/extract-urls) pull a list of links from pasted HTML
- [JSON to Markdown transcript](https://paulirish.github.io/tools/json-to-markdown-transcript) convert transcript JSON to Markdown
- [JSON to YAML](https://paulirish.github.io/tools/json-to-yaml) convert between JSON and YAML formats
- [YAML Explorer](https://paulirish.github.io/tools/yaml-explorer) browse YAML documents in a collapsible tree
- [JSON schema builder](https://paulirish.github.io/tools/json-schema-builder) visually design a JSON schema
- [Incomplete JSON printer](https://paulirish.github.io/tools/incomplete-json-printer) pretty print partial JSON documents
- [PHP Deserializer](https://paulirish.github.io/tools/php-deserializer) turn serialized PHP into JSON
- [SQL Pretty Printer](https://paulirish.github.io/tools/sql-pretty-printer) reformat SQL queries for readability
- [Pipfile.lock parser](https://paulirish.github.io/tools/pipfile) extract dependency versions from `Pipfile.lock`

## Data and time utilities
- [Timestamp Converter](https://paulirish.github.io/tools/unix-timestamp) convert Unix timestamps to readable dates
- [Timezones](https://paulirish.github.io/tools/timezones) compare times across multiple time zones
- [Date calculator](https://paulirish.github.io/tools/date-calculator) count days between dates or only weekdays
- [Transfer time estimator](https://paulirish.github.io/tools/transfer-time) work out how long file transfers will take
- [Token usage calculator](https://paulirish.github.io/tools/token-usage) summarize LLM token logs by model
- [LLM prices redirect](https://paulirish.github.io/tools/llm-prices) quick link to the latest model pricing site
- [CSV marker map](https://paulirish.github.io/tools/csv-marker-map) plot markers on a map from a CSV file
- [Species observation map](https://paulirish.github.io/tools/species-observation-map) browse recent iNaturalist sightings

## GitHub and development
- [GitHub API write](https://paulirish.github.io/tools/github-api-write) upload text or images directly to a repo
- [GitHub issue viewer](https://paulirish.github.io/tools/github-issue) fetch GitHub issues and comments
- [GitHub issue to Markdown](https://paulirish.github.io/tools/github-issue-to-markdown) turn an issue thread into Markdown
- [Zip/Wheel explorer](https://paulirish.github.io/tools/zip-wheel-explorer) view the contents of Python wheels and zips
- [Ares phonetic alphabet](https://paulirish.github.io/tools/ares) convert text to the ARES emergency phonetic code
- [Code with Claude 2025](https://paulirish.github.io/tools/code-with-claude-2025) prototype workflow for Claude coding
- [Side panel dialog demo](https://paulirish.github.io/tools/side-panel-dialog) experiment with the HTML `dialog` element
- [Broadcast channel chat](https://paulirish.github.io/tools/broadcast-channel-chat) chat across tabs using BroadcastChannel

## Bluesky and social tools
- [Bluesky WebSocket Firehose](https://paulirish.github.io/tools/bluesky-firehose) watch real-time activity on Bluesky
- [Bluesky resolve DID](https://paulirish.github.io/tools/bluesky-resolve) convert a handle like `simonwillison.net` into a DID
- [Bluesky timeline](https://paulirish.github.io/tools/bluesky-timeline) view a user’s recent posts and replies
- [Bluesky thread export](https://paulirish.github.io/tools/bluesky-thread) save a Bluesky thread to Markdown
- [Event planner](https://paulirish.github.io/tools/event-planner) rough schedule planner stored in localStorage
- [Passkeys demo](https://paulirish.github.io/tools/passkeys) experiment with browser-based passkey authentication

## LLM playgrounds and debuggers
- [Haiku](https://paulirish.github.io/tools/haiku) generate haikus using Claude Haiku and your webcam
- [Chrome Prompt Playground](https://paulirish.github.io/tools/chrome-prompt-playground) run prompts on Chrome’s Gemini Nano
- [Gemini bounding box visualizer](https://paulirish.github.io/tools/gemini-bbox) visualize bounding boxes returned by Gemini
- [Gemini chat client](https://paulirish.github.io/tools/gemini-chat) simple chat UI for the Gemini API
- [Gemini mask visualizer](https://paulirish.github.io/tools/gemini-mask) overlay segmentation masks from Gemini
- [Gemini image JSON renderer](https://paulirish.github.io/tools/gemini-image-json) display images from Gemini JSON output
- [Claude Token Counter](https://paulirish.github.io/tools/claude-token-counter) count tokens for Claude prompts
- [OpenAI audio input](https://paulirish.github.io/tools/openai-audio) record and send audio to OpenAI models
- [OpenAI audio output](https://paulirish.github.io/tools/openai-audio-output) generate speech with OpenAI voices
- [OpenAI WebRTC demo](https://paulirish.github.io/tools/openai-webrtc) interact with OpenAI’s real-time audio API
- [GPT-4o Gist audio player](https://paulirish.github.io/tools/gpt-4o-audio-player) play audio responses stored on GitHub Gist
- [JSON schema builder](https://paulirish.github.io/tools/json-schema-builder) build JSON schemas with a visual editor

## Miscellaneous
- [Arena animated](https://paulirish.github.io/tools/arena-animated) animated chart of the LMSYS Chatbot Arena
- [California Clock Change](https://paulirish.github.io/tools/california-clock-change) see when daylight saving time changes
- [Open Sauce 2025 schedule](https://paulirish.github.io/tools/open-sauce-2025) browse the upcoming conference sessions
- [OpenFreeMap demo](https://paulirish.github.io/tools/openfreemap-demo) MapLibre demo with random points in San Francisco
- [Progress of the US presidency](https://paulirish.github.io/tools/progress) track days elapsed in the current term
- [User Agent display](https://paulirish.github.io/tools/user-agent) show your browser’s user agent string
- [Encrypt / decrypt message](https://paulirish.github.io/tools/encrypt) share short encrypted messages
- [ARIA live regions](https://paulirish.github.io/tools/aria-live-regions) demo of dynamic page announcements
- [Prompts.js](https://paulirish.github.io/tools/prompts-js) small library for nicer JavaScript prompts
- [APSW SQLite query explainer](https://paulirish.github.io/tools/apsw-query) explain SQLite queries using APSW

## On Observable

On [Observable](https://observablehq.com/):

- [Blog to newsletter](https://observablehq.com/@simonw/blog-to-newsletter) helps turn blog posts into a newsletter
- [Convert Claude JSON to Markdown](https://observablehq.com/@simonw/convert-claude-json-to-markdown) for sharing Claude transcripts
- [Hacker News homepage with links to comments ordered by most recent first](https://observablehq.com/@simonw/hacker-news-homepage)

<script type="module" src="homepage-search.js" data-tool-search></script>
