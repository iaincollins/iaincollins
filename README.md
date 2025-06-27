# ℹ️ About me

Professionally, [I'm a software and systems engineering lead](https://www.linkedin.com/in/iaincollins) with 30 years experience in software development and systems engineering.

I live in Edinburgh, Scotland and work at [Unity](https://unity.com/) with a fantastic team on Game Backend systems supporting millions of players.

You can find me on Mastodon as <a rel="me" href="https://mastodon.social/@iaincollins">@iaincollins</a>, sometimes I post on [Medium](https://iaincollins.medium.com/).

# ✍️ Side projects

I've been contributing to and release open source software for 25 years, from small libraries to frameworks to desktop and server applications, and a few bits of civic tech, but most of my projects these days are things I build for fun.

## 🎮 [Procedurally generated scenes using WebGL](https://explore.iaincollins.com)

<p align="center">
 <a href="https://explore.iaincollins.com"><img src="https://github.com/user-attachments/assets/ef59f45d-9c56-41cb-b15e-2b90031e6c08" width="600"></a>
</p>

This sample includes 3 different environments which can be explored in a first person view. The environments are generated at runtime using procedural generation. It's built with Next.js and React and React Three Fibre, a wrapper for Three.js, which is in turn an abstraction for WebGL.

This an unconventional stack and it's a simple demo with player movement and physics interaction as an exercise in seeing what's possible using those components and has helped me better understand what it's like to use React Three Fibre and Three.js in practice.

## 📈 [Ardent Industry](https://ardent-industry.com)

<p align="center">
 <a href="https://ardent-industry.com"><img src="https://github.com/user-attachments/assets/12f9f8f4-c5ea-44e3-a415-2575d0168b8f" width="600"></a>
</p>

Ardent Insight is a live-updating database of over 150 million star systems, with millions of commodity buy/sell orders in a galactic trade database and handles a stream that drives millions of updates a day.

The data comes from players of the game Elite Dangerous, collected from game clients and submitted to the Elite Dangerous Data Network (EDDN), using a process approved by the developer of the game (Frontier Developments).

The frontend and backend are both built in JavaScript with SQLite as the database, with public REST API.

As well as a functional tool for players and developers - who use the API in their own third party apps - it's an example of how developers can build scalable and reliable backend infrastructure for multiplayer environments using open source software at very low cost ($25 / month).

## 🛰 [ICARUS Terminal](https://github.com/iaincollins/icarus)

<p align="center">
 <a href="https://github.com/iaincollins/icarus"><img src="https://github.com/user-attachments/assets/ed4fdef3-1a23-420f-91b6-aa7680aecff5" width="800"></a>
</p>

ICARUS Terminal is a companion app / second screen for the game Elite: Dangerous, the latest follow up to the 1984 classic space game Elite.

Designed for both desktop/laptop computers and for tablets/phones, the app hooks into the game to provide context-sensitive real time information, that is event driven and socket based, by combining data from the games API with third party APIs built by fans of the game.

Built with Next.js, React, Node.js, Go and C++.

## 🔑 [NextAuth.js](https://next-auth.js.org)

<p align="center">
 <a href="https://next-auth.js.org"><img src="https://user-images.githubusercontent.com/595695/151672056-ba14691b-b260-4010-8b2a-d7429c339319.png" width="600"></a>
</p>

I created NextAuth.js because there wasn't anything like it already and I wanted adding authentication to new projects to be easier. It now has millions of downloads a month and become one of top 1,000 open source projects on GitHub and is used in thousands of projects.

NextAuth.js is an open source, community supported project based around interoperability with open standards. It has grown to support dozens of auth providers and a wide range of SQL and no-SQL databases. Originally developed for React - and specifically Next.js, hence the name - it has been ported to other popular frameworks, including Vue.js and Svelte and can be used with non-JavaScript frameworks, such as Drupal.

To ensure it remains open source, collaborative and independent it has been spun off into a dedicated organization and has it's own core team. I've since moved on to other projects and am no longer actively involved.

## 🎬 Mercury

<p align="center">
 <img src="https://user-images.githubusercontent.com/595695/136658187-c3ef9888-e17f-4c50-aa2f-d54eec2a276b.png" width="600">
</p>

Mercury is a web based video and transcript editor and translation workflow tool that lets you drop-and-drag a video in one language in and then watch it back in other languages, with an editable, timestamped transcript in each language, that can also be exported as subtitles or text.

Designed for news and media organisations, Mercury allows teams to upload, edit, transcode, transcribe and translate audio and video files in a wide range of formats, including large, unprocessed files - from anywhere in the world on any web enabled device, including a smartphone, and share them in a secure and searchable way.

I got a grant to build Mercury from Google, through Google DNI. 

## 🛠 [Structured Data Testing Tool](https://github.com/glitchdigital/structured-data-testing-tool)

<p align="center">
 <img src="https://user-images.githubusercontent.com/595695/136657786-ec1f4db5-433b-41d0-b276-50469e3e9cb0.png" width="600">
</p>

Designed to fill a gap in tooling in Google Lighthouse and Google's own Structured Data Testing Tool, by providing an extendible command line tool and API that includes out of the box support for checking both Schema.org entities and social media markup.

While useful for any website but especially useful for news and media organizations as ensuring markup quality can have a significant impact on traffic coming from Google News and Google Discover, as well as organic traffic from search engines.

## 🛠 [Table to JSON](https://www.npmjs.com/package/tabletojson)

A library useful for data scraping, originally created to support work on civic tech and data journalism. [Table to JSON is used by dozens of other packages](https://www.npmjs.com/browse/depended/tabletojson), in other higher level scraper libraries and in projects to track a wide range of things from COVID-19 data to TV shows, news and weather to class times for students. Table to JSON is now maintained by [@maugenst](https://github.com/maugenst).
