# 🧔 Personal profile

I live in [Edinburgh, Scotland](https://www.google.com/maps/place/Edinburgh/@55.9412083,-3.2053387,12z/data=!3m1!4b1!4m6!3m5!1s0x4887b800a5982623:0x64f2147b7ce71727!8m2!3d55.953252!4d-3.188267!16zL20vMDJtNzc?entry=ttu&g_ep=EgoyMDI1MTExMi4wIKXMDSoASAFQAw%3D%3D) and work as an [Associate Technical Director](https://www.linkedin.com/in/iaincollins) at the game studio [Scopely](https://scopely.com).

Prior to joining Scopely, I was an Engineering Manager at [Unity](https://unity.com/) on Game Backend running services including authentication, player and game state storage, and socio-competitive services and SDKs, used by thousands of games across all mobile, console and desktop platforms.

Before joining Unity, I worked at various media and telecoms organisations - The Economist, BBC News, Sky and others - on a wide range of platforms (web, desktop, mobile, server and device software) and ran a small company, with work on games exclusively as a hobby - something I've been doing since the late 80s, first with BASIC for Intellivision, then Amstrad PCW and then Macintosh.

For over 25 years I've been creating, maintaining, and contributing to open-source software, ranging from hacks to small libraries, popular frameworks, desktop and server applications, and civic tech projects. Most of my personal projects on GitHub are small side projects I work on for fun or to inform my work.

<i>Some of the free open source software I've created has been used in products and services from organisations including IBM, ChatGPT, Unity as well as by organisations including Amnesty International, Friends of the Earth, the ISU (International Space University) and in thousands of open source projects.

The majority of my work on open source is non-commercial in nature but some of my work in the past was supported by funding from government departments and NGOs and others from larger grants from organisations like Google; all sponsored work should have acknowledgement in the relevant repository and/or attached to the relevant organisation.</i>

### Links

* Mastodon: <a rel="me" href="https://mastodon.social/@iaincollins">mastodon.social/@iaincollins</a>
* LinkedIn: [linkedin.com/in/iaincollins](https://www.linkedin.com/in/iaincollins/)
* Medium: [iaincollins.medium.com](https://iaincollins.medium.com/)

# ✍️ Side projects

Some of the projects I've worked on recently - many are video game and/or data centric.

## 🧊 [Web based isometric terrain engine](https://microstate.neocities.org)

<p align="center">
 <a href="https://microstate.neocities.org"><img src="https://github.com/user-attachments/assets/995edd3b-ff42-4ee1-a83f-275f51e29577" height="800"></a>
</p>

I've been developing a web-based isometric tile engine as a personal project to support a couple of hobby projects.

As well as simple flat and fixed-elevation terrain and dungeon maps built using pre-rendered tiles (either bitmaps and vector art), it supports complex maps with dynamic terrain and entirely procedurally generated worlds (terrain, buildings, roads, trees) - and allows tiles of arbitrary heights and transformations, with configurable degrees of quadrilateral shading.

The engine maximizes performance across mobile, tablet, and desktop devices by using a hardware-accelerated 2D Canvas and a combination of direct drawing and batch rendering. The use of procedurally generated art results in a compact payload of about 50 KB over the wire.

Dynamic generation allows for a high degree of variation in world objects and enables runtime blending of tile vertices and visual effects like corner rounding. This makes possible a range of rendering effects, including smooth transitions in height and/or color between adjacent tiles. It also supports dynamic zooming and tilting of the camera (dynamic dimetric projection) and can support rendering native resolution on any display - depending on the device hardware.

MicroState is implemented entirely in vanilla ECMAScript (JavaScript) with no build-time or runtime dependencies or transpilation, the engine uses a purely 2D Canvas to create the illusion of a 2.5D environment. While still an early stage tech demo and a work in progress, it is highly interactive and "playable." The entire project is self-contained within a single HTML file, including a compressed <script> payload.

## 🎮 [Procedurally generated scenes using WebGL](https://explore.iaincollins.com)

<p align="center">
 <a href="https://explore.iaincollins.com"><img src="https://github.com/user-attachments/assets/eedf01b2-29b1-4838-b6e5-fab1a40df106" width="800"></a>
</p>

This sample features three distinct environments at different times of day - a forest, a desert and a frozen landscape - that you can travel between and explore in a first-person view, with a new map generated at runtime using procedural generation. Built with Next.js, React, and React Three Fibre (a wrapper for Three.js, which abstracts WebGL). This unconventional stack serves as a simple demo with player movement and physics interaction. It was an exercise to explore the practical issues of implementing an interactive 3D environment using common web libraries and reusable components leveraging features like geometry instancing and GPU shaders.

## 📈 [Ardent Insight](https://ardent-insight.com)

<p align="center">
 <a href="https://ardent-insight.com"><img src="https://github.com/user-attachments/assets/971a4ced-5b4a-4fbd-86be-11f739422081" width="800"></a>
</p>

Ardent Insight is a live-updating database encompassing over 150 million star systems and millions of commodity buy/sell orders in a galactic trade database. It handles a stream of real time game data driving millions of updates per day. The data originates from players of the game Elite Dangerous, collected from game clients and submitted to the Elite Dangerous Data Network (EDDN), using a process approved by the game's developer (Frontier Developments). Both the frontend and backend are built in JavaScript, with SQLite as the database, with a socket interface and a RESTful API. Players can also sign in securely with their in-game account using OAuth.

Beyond being a functional tool for players and developers, who are able to use the API in their own third-party add ons for the game, the project is an example of how you can build scalable and reliable backend infrastructure, with support for large scale multiplayer games - with a single node supporting traffic from thousands of connected players - using simple open-source software running at very low cost.

## 🛰 [ICARUS Terminal](https://github.com/iaincollins/icarus)

<p align="center">
 <a href="https://github.com/iaincollins/icarus"><img src="https://github.com/user-attachments/assets/ed4fdef3-1a23-420f-91b6-aa7680aecff5" width="800"></a>
</p>

ICARUS Terminal is a companion app/second screen for Elite: Dangerous, the latest iteration of the 1984 classic space game, Elite. Designed for desktop/laptop computers and tablets/phones, the app integrates with the game to provide context-sensitive, real-time information. This information is event-driven and socket-based, combining data from the game's API with third-party APIs built by fans. It is built with Next.js, React, Node.js, Go, and C++.

## 🔑 [NextAuth.js](https://next-auth.js.org)

<p align="center">
 <a href="https://next-auth.js.org"><img src="https://user-images.githubusercontent.com/595695/151672056-ba14691b-b260-4010-8b2a-d7429c339319.png" width="800"></a>
</p>

I created NextAuth.js because there wasn't anything like it already and I wanted adding authentication to new projects to be easier. It now has millions of downloads a month and become one of top 1,000 open-source projects on GitHub and in thousands of projects and used by millions people every day. 

NextAuth.js is an open-source, community-supported project built around interoperability with open standards. It has expanded to support dozens of authentication providers and a wide range of SQL and NoSQL databases. Initially developed for React, and specifically Next.js (hence the name), it has been ported to other popular JS frameworks like Vue.js and Svelte, can be used with other non-JS systems, like Drupal.

I created the project in 2018 and led it for about 5 years. To ensure its continued open-source, collaborative, and independent nature, I spun the it off into a dedicated organization with its own core team and I am no longer actively involved.

## 🎬 Mercury

<p align="center">
 <img src="https://user-images.githubusercontent.com/595695/136658187-c3ef9888-e17f-4c50-aa2f-d54eec2a276b.png" width="600">
</p>

Mercury is a web based video and transcript editor and translation workflow tool that lets you drop-and-drag a video in one language in and then listen to it back in other languages, with an editable, timestamped transcript in each language, that can be used to edit the spoken audio and can be exported as subtitles or a text document.

Designed for news and media organisations, Mercury allows teams to upload, edit, transcode, transcribe and translate audio and video files in a wide range of formats, including large, unprocessed files - from anywhere in the world on any web enabled device, including a smartphone, and share them in a secure and searchable way.

Development of Mercury was funded by a grant I obtained form Google.

## 🛠 [Structured Data Testing Tool](https://github.com/glitchdigital/structured-data-testing-tool)

<p align="center">
 <img src="https://user-images.githubusercontent.com/595695/136657786-ec1f4db5-433b-41d0-b276-50469e3e9cb0.png" width="600">
</p>

This tool was designed to address a gap in existing tools like Google Lighthouse and Google's own Structured Data Testing Tool. It provides an extensible command-line tool and API with out-of-the-box support for checking both Schema.org entities and social media markup. While beneficial for any website, it is particularly useful for news and media organizations, as ensuring markup quality can significantly impact traffic from Google News and Google Discover, as well as organic search engine traffic.

## 🛠 [Table to JSON](https://www.npmjs.com/package/tabletojson)

A library useful for data scraping, originally created to support work on civic tech and data journalism. [Table to JSON is used by dozens of other packages](https://www.npmjs.com/browse/depended/tabletojson), in other higher level scraper libraries and in projects to track a wide range of things from COVID-19 data to TV shows, news and weather to class times for students. Table to JSON is now maintained by [@maugenst](https://github.com/maugenst).
