# 🧔 About me

_I'm an [engineering lead with ~30 years experience](https://www.linkedin.com/in/iaincollins) developing cross platform software for the web, desktop, server, mobile and routers with open source projects going back over two decades. I've worked in startups, large enterprises, on non-profit/civic-tech and started two companies (and way too many side projects)._

* I live in Edinburgh, Scotland
* I work at [Unity](https://unity.com/) on game backend services for [Unity Gaming Services](https://unity.com/solutions/gaming-services)
* You can find me on mastodon.social as <a rel="me" href="https://mastodon.social/@iaincollins">@iaincollins</a>, sometimes I post on [Medium](https://iaincollins.medium.com/)
 
# ✍ Side Projects

_Most of my public work on GitHub is on personal side projects and spans different types of software. These are some of the smaller things I've worked on more recently. Most of the open source projects I've worked on over the last 20-30 years are lost to the wind (or maybe sitting around in an SVN or CVS repository, on sitting on a disk on a shelf somewhere)._

## 🎮 [First person procedurally generated scenes using WebGL](https://demo-scene.vercel.app)

<p align="center">
 <a href="https://demo-scene.vercel.app"><img src="https://github.com/iaincollins/iaincollins/assets/595695/f13caa8b-221a-451e-bbf1-c57c1d81b1a3" width="600"></a>
</p>

A small collection of scenes in a first person perspective. The terrain and objects in each scene (trees, rocks, clouds, etc) are both created and placed at runtime using procedural generation. Features multiple real time lights (no baked shadows), instanced gemoetry with thousands of objects on screen at the same time and physics modeling for hundreds of objects at a time. It uses flat / vertex shading and a low-poly style to optimize for performance on mid-tier systems (and to avoid the overhead of requiring downloading of textures). It also features material shaders and particle effects.

It is built with Next.js and with custom components created for React Three Fibre - a wrapper for Three.js, which is in turn an abstraction for WebGL. This an unconventional stack, and it's a very simple demo, but it was a fun exercise in seeing what's possible using those components and to better understand how RTF and Three.js work in practice.

## 💽 [Ardent Industry](https://ardent-industry.com)

<p align="center">
 <a href="[https://ardent-industry.com"><img src="https://github.com/iaincollins/iaincollins/assets/595695/92408024-b594-4bb7-9de6-15525885f084" width="600"></a>
</p>

A live-updating database of over 100,000,000 locations, tracking millions of commodity prices across galactic trade markets in the year 3038, using data from players of the game Elite Dangerous (collected from game clients using an API provided by the games developers). It's a low-fi tech solution built entirely in JavaScript and SQLite with a similarly low-fi asthetic.

## 🛰 [ICARUS Terminal](https://github.com/iaincollins/icarus)

<p align="center">
 <a href="https://github.com/iaincollins/icarus"><img src="https://user-images.githubusercontent.com/595695/192074952-3bfa22b1-2dd1-45f6-893e-0f56ae5b87c7.png" width="600"></a>
</p>

ICARUS Terminal is a companion app / second screen for the game Elite: Dangerous, the latest follow up to the 1984 classic space game Elite. Designed for both desktop/laptop computers and for tablets/phones, the app hooks into the game to provide context-sensitive real time information (event driven and socket based) by combining the game API with third party APIs. Built with Next.js, React, Node.js, Go and C++.

## 🔑 [NextAuth.js](https://next-auth.js.org)

<p align="center">
 <a href="https://next-auth.js.org"><img src="https://user-images.githubusercontent.com/595695/151672056-ba14691b-b260-4010-8b2a-d7429c339319.png" width="600"></a>
</p>

I created NextAuth.js a few years ago. It now has millions of downloads a month and is apparently of the top 1000 open source projects on GitHub (according to GitHub). It's an open source, community supported project based around interoperability with open standards. NextAuth.js has grown to support dozens of auth providers and a wide range of SQL and no-SQL databases. Originally developed for React - and specifically Next.js, hence the name - it has been ported to other popular frameworks, including Vue.js and Svelte and can be used with non-JavaScript frameworks, such as Drupal.

I've since moved on to other projects and am no longer actively involved, other than to look in and see how things are going now and then. To ensure it remains open source, collaborative and independent it has been spun off into a dedicated organization, with it's own core team.

## 🎬 Mercury

<p align="center">
 <img src="https://user-images.githubusercontent.com/595695/136658187-c3ef9888-e17f-4c50-aa2f-d54eec2a276b.png" width="600">
</p>

I developed Mercury with funding from Google DNI. Mercury is a web based video and transcript editor and translation workflow tool that lets you drop-and-drag a video in one language in and then watch it back in other languages, with an editable, timestamped transcript in each language, that can also be exported as subtitles or text.

Designed for news and media organisations, Mercury allows teams to upload, edit, transcode, transcribe and translate audio and video files (in a wide range of formats, including large, unprocessed files) from anywhere in the world on any web enabled device (including a smartphone) and share them in a secure and searchable way.

## 🛠 [Structured Data Testing Tool](https://github.com/glitchdigital/structured-data-testing-tool)

<p align="center">
 <img src="https://user-images.githubusercontent.com/595695/136657786-ec1f4db5-433b-41d0-b276-50469e3e9cb0.png" width="600">
</p>

Designed to fill a gap in tooling in Google Lighthouse and Google's own Structured Data Testing Tool, by providing an extendible command line tool and API that includes out of the box support for checking both Schema.org entities and social media markup.

While useful for any website but especially useful for news and media organizations as ensuring markup quality can have a significant impact on traffic coming from Google News and Google Discover, as well as organic traffic from search engines.

## 🛠 [Table to JSON](https://www.npmjs.com/package/tabletojson)

A library useful for data scraping, originally created to support work on civic tech and data journalism. [Table to JSON is used by dozens of other packages](https://www.npmjs.com/browse/depended/tabletojson), in other higher level scraper libraries and in projects to track a wide range of things from COVID-19 data to TV shows, news and weather to class times for students. Table to JSON is now maintained by [@maugenst](https://github.com/maugenst).
