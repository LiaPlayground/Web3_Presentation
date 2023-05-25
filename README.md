<!--
author: Sebastian Zug

version: 1.0.0

link:    https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css
-->

# How To apply Web 3.0 technologies to enable sustainable and community driven online-learning



## Browser-Quiz

__What do you think is a modern browser capable of?__

- [[X]] Generating text to speech output
- [[X]] Storing LARGE amounts of data
- [[X]] Cache websites and access them offline
- [[X]] Access your device sensory information (GPS/orientation/light/compass/...)
- [[X]] Connect to another browser directly to exchage audio/video/data
- [[X]] Be a peer in a peer to peer filesharing network
- [[X]] Virtual & Augmented Reality applications
- [[X]] Bluetooth connections
************************************************

                          {{|>}}
The answer is always yes, and most modern browsers have Text to Speech engine implemented too.

************************************************

## Who Am I

<iframe id="map" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d745.0172241379928!2d13.329770317829896!3d50.92568159562554!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47a7600bf919ad43%3A0x4dc2cb2137dcaed9!2sTechnische%20Uni%2FBergakademie%20Freibg.%20Geologisches%20Institut!5e1!3m2!1sde!2sde!4v1681986802498!5m2!1sde!2sde" style="width: 100%; height: 60vh; border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

## The Browser is the next Operating System

                      {{1-2}}
![Moodle Plattform](img/cloud0.png)<!-- class="animate__animated animate__zoomIn" -->

                      {{2-3}}
![LiaScript](img/cloud3.png)<!-- class="animate__animated animate__zoomIn" -->


### Progressive Web Apps


> A __progressive web application (PWA)__, or __progressive web app__, is a type of application software delivered through the web, built using common web technologies including HTML, CSS, JavaScript...
>
> It is intended to work on any platform with a standards-compliant browser, including desktop and mobile devices.
>
> -- Source: [Wikipedia](https://en.wikipedia.org/wiki/Progressive_web_app)

Requirements:

- `manifest.json`: Meta information, base settings
- `ServiceWorker.js`: Used caching strategies
- [[IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API?retiredLocale=de)]: Storing large amounts of data persistently

                   --{{1}}--
The current LiaScript Website is an example of a progressive web app.
All the website data is stored on your device, the loaded course is cached and the state of your quiz is stored within indexedDB.

<!-- style="background: #bdad298f" -->
                     {{1}}
> __Experiment:__ Turn on the flight mode and reload the page.


## Decentralized Storage & Dissemination

                      --{{0}}--
Wenn __eine__ Zelle stirbt, dann mit ihr gehen alle ihre Informationen verloren.
Kopiert man die Inhalte und speichert sie an unterschiedlichen Orten, dann bleiben die Informationen mit einer höheren Wahrscheinlichkeit erhalten.

<div style="width:100%;height:0;padding-bottom:80%;position:relative;"><iframe src="https://giphy.com/embed/3ogwFSxwLoc3eNSfyE" width="100%" height="100%" style="position:absolute" frameBorder="0" class="giphy-embed" allowFullScreen></iframe></div><p><a href="https://giphy.com/gifs/feistmusic-century-feist-3ogwFSxwLoc3eNSfyE">via GIPHY</a></p>


### Inter-Planetary File System

> __The web of tomorrow needs IPFS today__
>
> IPFS aims to complement HTTP in order to build a better web for all of us. 
>
> -- WebSite: https://ipfs.tech

                   {{1}}    
``` ascii

   (Client-Server Architektur)           (Peer-to-Peer (IPFS))
 ┌────────────────────────────┐     ┌────────────────────────────
▒│ 📱 -----.        .----- 💻 │    ▒│     📱---------💻 ┄ ┄ ┄ ┄
▒│          \      /          │    ▒│    / \          \
▒│           \    /           │    ▒│   /   \          \
▒│  💻 ------- 🖥 ------- 📱  │    ▒│ 💻-----💻---------📱 ┄ ┄
▒│           /    \           │    ▒│   \   /  \       /
▒│          /      \          │    ▒│    \ /    \            📱
▒│ 📱 -----'        '----- 💻 │    ▒│     📱-----💻 ┄ ┄ ┄ ┄
▒└────────────────────────────┘    ▒└────────────────────────────
▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒     ▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒
```

<!-- style="background: #bdad298f" -->
                        {{2}}
> __Experiment:__ Download the [Brave-Browser](https://brave.com) and try to share content via IPFS.
>
> !?[Brave Browser & IPFS](https://www.youtube.com/watch?v=hpwh_zLpnCE)


### Darknet: Tor & OnionShare

                {{0-1}}
![Censorship](img/censorship.png)

                {{1}}
> The Tor network is an anonymizing network that allows users to obscure their online activities and protect their identity by routing their traffic through a series of volunteer-run Tor servers, making it difficult to trace their actual IP address.
>
> Website: https://www.torproject.org



                 {{2}}
> __Privacy + Productivity__
> 
> 🧅 OnionShare is an open source tool that lets you securely and anonymously share files, host websites, and chat with friends using the Tor network.
>
> -- Website: https://onionshare.org

<!-- style="background: #bdad298f" -->
            {{3}}
> __Experiment:__ Download the Tor-Browser and OnionShare and try out disseminating.
> You can setup a private chat too.
>
> !?[OnionShare](https://www.youtube.com/watch?v=D2OLpNtbFD8)

## Serverless Communication

> __WebRTC (Web Real-Time Communication)__ is a free and open-source project providing web browsers and mobile applications with real-time communication (RTC) via application programming interfaces (APIs). It allows audio and video communication to work inside web pages by allowing direct peer-to-peer communication, eliminating the need to install plugins or download native apps
>
> Source: [Wikipedia](https://en.wikipedia.org/wiki/WebRTC)

Applications:

- [WebTorrent](https://webtorrent.io): Browser-based torrent capable of streaming videos.
- [Meet.Jit.Si](https://meet.jit.si): Platform for video-chat and online meetings.
- [Instant.io](https://instant.io): Share a file via the Browser.

<!-- style="background: #bdad298f" -->
            {{1}}
> __Experiment:__ Create a Classroom directly from our LiaScript PWA.
>
> !?[Classroom](https://www.youtube.com/watch?v=Kjk6OblugXI)

### Classroom

What do you think is the most relevant feature for sustainable education.

- [[PWA]] Progressive Web APP & Caching
- [[Decentralized Storage]] Decentralization
- [[Communication]] Browser-based Realtime Communication

## Contact

