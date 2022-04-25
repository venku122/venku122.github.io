# Introduction

My name is T.J. Tarazevits and I am a Full-Stack Engineer. I specialize in real-time data processing and visualization, creating user-facing tools that make others more effective.

## About Me
I graduated from Rochester Institute of Technology with a B.S in Game Design and Development. At school, I worked with a broad array of technologies including Object Oriented Programming in C# and C++, functional programming in JavaScript, and hardware programming using C.
## Projects
All projects listed below are hosted on Github and open source. Check them out!

Joined the engineering team as the 10th engineer post Series A</li>
<li>Updated internal interview processes and conducted dozens of interviews to grow the team to over 80 engineers</li>

## Sitemap Generator
<li>Implemented system to automatically update sitemap as new  talent joined the platform</li>

## Amplitude Integration

<li>Implemented 3rd party analytics client and developed procedures to track and analyze user behavior across the org.</li>

## OneSignal Integration
<li>Implemented OneSignal push notification system into our React Native application.</li>

## Datadog APM
<li>Set up Datadog APM for full monitoring of our production servers.</li>
<li>Implemented Datadog Real User Monitoring (RUM) to collect performance metrics and logs from real customer clients</li>

## Image Resizing Service
<li>Created an in-house image resizing service using Lambda@Edge and Sharp, speeding up asset delivery while reducing the cost of resizing images.</li>

## Cameo Coins and Cameo Credits
<li>Created a virtual currency system and In-App Purchase system to comply with iOS guidelines.</li>

## BrowseRow and Shelf CMS
<li>Implemented homepage marketing merchandising components for the in-house server-driven UI CMS.</li>
<li>Implemented real time deduplication of product listings on the homepage and categories to maximize available product display.</li>
<li>Implemented in-house CMS built on MongoDB to allow for server-driven UI of the homepage to address holiday scaling traffic.</li>
<li>Created Online Now merchandising row to showcase talent currently active on the site to potential customers.</li>

## HD Video Transcoding Pipeline
<li>Refactored video upload pipeline to use ElasticTranscoder to support multiple output formats includes HD videos and HLS streaming formats.</li>

## Server-Side Rendering (SSR) Streaming
<li>Refactored Server Side Rendering (SSR) implementation to use streaming mode to reduce Time-to-First-Byte (TTFB) by 40%</li>
https://medium.com/cameoeng/resizing-images-at-cameo-using-lambda-edge-2d84775f730e

## LazyImage optimizations 
<li>Implemented lazy image loading to improve homepage Time To Interactive (TTI)</li>

## Search Improvements

<li>Created the first Search Engine Results Page (SERP) on web to improve search conversion.</li>

<li>Created an Airflow data pipeline to generate CategoryScore, to sort and rank the most popular talent categories on the site.</li>

<li>Refactored app search experience to match best-in-class examples like Instagram including new search bar, recent and recommended searches, and an in-app SERP.</li>


## Content Feed 
<li>Led project team to implement TikTok-style Content Feed using Cameo videos in-app</li>

## FanScale Database Projects
<li>Led FanScale™ team to implement critical performance improvements to prevent site failure as we scaled our fan-facing products.</li>
<li>Split Fan Club specific collections into their own MongoDB cluster using Kafka and CDC for a zero-downtime migration.</li>

## Load Testing @ Cameo
<li>Implemented load testing framework and procedures to validate new scalability improvements.</li>

## ChannelPreview Service
<li>Created several Redis-backed services to provide high-throughput, low latency messaging features</li>
<li>Created ChannelPreview system to handle traffic spikes from talent-driven communication.</li>

## QAMEO
<li>Designed and implemented migration framework using SQS and Kubernetes workers to handle millions of record updates.</li>
<li>Refactored Redis caching layer to use static keys and TTLs, reducing CPU usage by 80%</li>

## MongoDB Performance Tuning
<li>Refactored MongoDB aggregations into individual lookups to improve query time and scalability on our ReplicaSet.</li>
<li>Upgraded Mongoose to v6 to improve Typescript support, support MongoDB 5.x.x and support multiple concurrent connection pools.</li>
<li>Optimized indexes to reduce query targeting and improve performance of the core Cameo MongoDB cluster.</li>

## CockroachDB Production Proof of Concept
<li>Implemented PoC of CockroachDB at Cameo to demonstrate Distributed SQL technology.</li>

## Session Cache
<li>Added Redis caching layer in front of MongoDB session collection to improve per-request latency and reduce database load.</li>


## Kafka Projects
<li>Implemented audience-based notification system backed by Kafka and CDC events, eliminating the need for database user lookups to send a push notification.</li>

<li>Early adopter of Nest.js and GraphQL to migrate Fan Club features to microservices.</li>

## Node 16 migration
<li>Upgraded server runtime and dependencies from Node 12 to Node 16 to support ESModules, M1 Macs, and the most up to date Node.js features.</li>

## In-house React Native Performance Profiler
<li>Conducted performance testing on React Native app to identify and resolve performance and memory issues.</li>

## Fan Club Previews on Web
<li>Implemented VirtualizedList components on web to support infinite loading content feeds.</li>

## Talent Create Tool
<li>Created new Talent Create Tool as a extendable, reusable media upload component for talent.</li>

### HABnet 
HABnet is a multi-user web application designed to facilitate the collection and visualization of embedded sensor data. There are two primary components included within this application. The backend server receives incoming JSON data from hardware sensors. This data is stored using InfluxDB, a time-series database, and then re-broadcast to data visualizers using a Publisher-Subscriber model.

The data visualizer is a React-Redux Single Page Application (SPA) hosted by an Express web server built into the HABnet backend. It uses Websockets to provide streaming data support without polling. Users can use the dashboard builder to create multiple data graphs to monitor incoming data from multiple data sources on a single screen, all updating in real time.

### SatTrack
SatTrack is an application that propagates orbital trajectories and visualizes satellite ground tracks, the path they make across the surface of the Earth, to help people understand the thousands of objects that fly over their head every day. SatTrack is a full-stack application, leveraging a Node.js/Express backend and a React/Redux front-end. The backend retrieves Two-Line Elements (TLEs) from Space-track.org to use as the data set for orbit propagation simulations. This data is stored in MongoDB to respect API rate limits, and speed up the user experience. When a user visits the site, they are presented with a list of satellites and objects in orbit around the Earth. Once selected, the backend propagates the orbit of the satellite into the future, generating a set of GPS coordinates over time as a result and sends that back to the frontend. Node.js streams are used to minimize the memory footprint of long-running simulations and to return results in-progress, minimizing network latency.

The UI uses HTML5 Canvas to render the ground track on a map of the Earth, showing the unique orbital motion of different satellites.

## Activities
In addition to programming, I love to learn and talk about space. I co-host a podcast called SPEXcast, and write about space engineering topics on blog.spexcast.com. In my free time, I love to cook, from weeknight pizzas and tacos, to beef wellington and prime rib.


## Contact Info

<a href = "mailto: tarazevits@gmail.com?subject=Website">Send me an email</a>
<br/>
<a href="https://www.linkedin.com/in/tjtarazevits/">Connect on LinkedIn</a>
<br/>
<a href="https://github.com/venku122">Checkout my Github profile</a>