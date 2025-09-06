# ℹ️ About me

My background is in software and systems engineering. I live in Edinburgh, Scotland; although I’ve spent most of my career - and almost half my life - living and working in London, England. I'm a [software engineering manager](https://www.linkedin.com/in/iaincollins) at [Unity](https://unity.com/) leading work on game backend systems like authentication, storage, and socio-competitive services and SDKs used by thousands of production games on all major platforms.

For over 25 years I've been creating, maintaining, and contributing to open-source software, ranging from small libraries to popular frameworks, desktop and server applications, and civic tech projects.

Some of the open source software I've created has been used in products and services by a wide range of organisations including IBM, ChatGPT, Unity as well as to support projects from Amnesty International, Friends of the Earth, the ISU (International Space University) and in thousands of open source projects.

Most of my open source work is non-commercial in nature but some of it has been supported by funding from government departments and NGOs and others from larger grants from organisations like Google - all sponsored work should be acknowledged in the relevant respository.

Most of my personal projects on GitHub are small side projects I work on for fun, and sometimes to inform my work.

You can find me on Mastodon as <a rel="me" href="https://mastodon.social/@iaincollins">@iaincollins</a>. I occasionally post on [Medium](https://iaincollins.medium.com/).

# ✍️ Side projects

These are some of the projects I've worked on recently; many of these are video game and/or data centric.

## 🎮 [Procedurally generated scenes using WebGL](https://explore.iaincollins.com)

<p align="center">
 <a href="https://explore.iaincollins.com"><img src="https://github.com/user-attachments/assets/eedf01b2-29b1-4838-b6e5-fab1a40df106" width="800"></a>
</p>

This sample features three distinct environments - a forest, a desert and a frozen landscape - that you can travel between and explore in a first-person view, with a new map generated at runtime using procedural generation. Built with Next.js, React, and React Three Fibre (a wrapper for Three.js, which abstracts WebGL), this unconventional stack serves as a simple demo with player movement and physics interaction. It was an exercise to explore the practical issues of implementing an interactive 3D environment using common web libraries and reusable components leveraging features like geometry instancing and GPU shaders.

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

I created NextAuth.js because there wasn't anything like it already and I wanted adding authentication to new projects to be easier. It now has millions of downloads a month and become one of top 1,000 open I created NextAuth.js to simplify adding authentication to new projects, as there wasn't a similar solution available. It now has millions of monthly downloads and has become one of the top 1,000 open-source projects on GitHub and in thousands of projects, and used by millions of end users. 

NextAuth.js is an open-source, community-supported project built around interoperability with open standards. It has expanded to support dozens of authentication providers and a wide range of SQL and NoSQL databases. Initially developed for React, and specifically Next.js (hence the name), it has been ported to other popular JS frameworks like Vue.js and Svelte, can be used with other non-JS systems, like Drupal.

I created the project in 2018 and led it for about 5 years. To ensure its continued open-source, collaborative, and independent nature, I spun the it off into a dedicated organization with its own core team and I am longer actively involved, as I couldn't provide the level of support needed while also meeting my full time responsibilities.

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
