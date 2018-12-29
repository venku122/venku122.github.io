# Introduction

My name is T.J. Tarazevits and I am a Full-Stack Engineer. I specialize in real-time data processing and visualization, creating user-facing tools that make others more effective.

## About Me
I graduated from Rochester Institute of Technology with a B.S in Game Design and Development. At school, I worked with a broad array of technologies including Object Oriented Programming in C# and C++, functional programming in JavaScript, and hardware programming using C.
## Projects
All projects listed below are hosted on Github and open source. Check them out!

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