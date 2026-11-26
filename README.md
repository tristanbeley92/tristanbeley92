# Hey, I'm Tristan

**Builder · Software Engineering at Western University · Graduating in 2027**

I like taking an idea and turning it into something that works. That might be a web app, an AI experiment, a game, or a small tool that saves me time. Building gives me a reason to learn something new and a way to put it to use.

I'm studying Software Engineering at Western University and working part-time as a Junior Developer at ConvergentIS. My work there focuses on cloud infrastructure, DevOps, and production deployments. Between work, coursework, and personal projects, I enjoy getting involved across the stack, from the interface to the backend and the infrastructure that keeps it running.

Away from the keyboard, you'll usually find me working on cars or working out.

[Email](mailto:tristanbeley@gmail.com) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/tristanbeley/) &nbsp;·&nbsp; [GitHub](https://github.com/tristanbeley92)

---

## A few things I've built

<table>
<tr>
<td colspan="2" valign="top">

### 🐐 G.A.R.Y the Goat: Go Anywhere, Rediscover Yourself

A pocket mountain goat you wear, who only grows when you go outside. A camera on your cap looks where you look. Press the button on your strap and a Raspberry Pi 5 in your pack, running **QNX**, names what it sees right on the device: no cloud, and no photo stored or sent. Gary beeps, talks back through a speaker, logs the find, clears fog on the map and levels up. Built in 36 hours with a team of four at Hack Western 13, where we placed **4th of 36 teams in the QNX challenge**.

**The hardware**
- **Raspberry Pi 5 on QNX 8.0**, with Gary's vision written in C++ (OpenCV and TensorFlow Lite)
- **Two models on every frame**: an SSD for everyday things and people, and a YOLOv8s trained on Open Images for nature. 90 things, from squirrels and ducks to deer, at **3.5 fps, with a button press answered in about 170 ms**
- **Logitech C270 webcam** clipped to a cap brim. Its built-in mic lets you say "Go Gary, what am I looking at?"
- **Hand signals**: hold a thumbs up or an OK sign up to the camera, then lower your hand, and Gary sniffs. Two MediaPipe hand models and plain rules on 21 hand points, in both the C++ and Python versions
- **Grove button and buzzer** on a Base HAT (sockets D5 and D16), with good, bad and unsure beep patterns timed into Gary's voice
- **USB speaker and power bank** in a hip pack, with the phone hotspot carrying the Pi's finds to the server

**Behind it:** a TinyFish web agent reads live London park, trail and event pages each morning and turns real places into quests. Talking to Gary runs on Gemini and ElevenLabs. The backend is FastAPI on Vultr with Tiger Data (Postgres), and the front end is a React "Pocket Pixel" handheld.

**Tech:** QNX, C++, Python, OpenCV, TensorFlow Lite, FastAPI, React, TinyFish, Gemini, ElevenLabs, Tiger Data, Vultr

[Live](https://goatside.fit) · [Repo](https://github.com/anaybaid7/hackwestern13-gary) · [Devpost](https://devpost.com/software/gary-the-goat)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### NutriScan AI

A hackathon prototype exploring computer vision and AI for personalized, budget-friendly meal planning. Built in 36 hours with a team of four at HackWestern 12, where we won Sun Life's Best Health Hack and MLH's Best Use of DigitalOcean Gradient AI.

I wanted to see how far we could take an idea in a weekend and get a working demo into people's hands.

**Tech:** React, TypeScript, Google Gemini 2.5 Flash, DigitalOcean Gradient AI

[Repo](https://github.com/ZElnagar/HackWestern12) · [Live demo](https://zelnagar.github.io/HackWestern12/)

</td>
<td width="50%" valign="top">

### Escape from PolyLand

A 3D game built in Unity with a team of five for a game development course. We took it from a class assignment to a playable level with gameplay mechanics and physics.

A chance to build something outside the browser and bring a finished game together as a team.

**Tech:** Unity, C#

[Repo](https://github.com/AlexandraLHeureuxECE/final-project-thefellowship) · Team project

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Open-Cam Face Detection

A real-time face detection and emotion-recognition web app with webcam streaming, multiple-face tracking, and image uploads.

Originally a take-home challenge, it became an opportunity to work with live video and browser-based ML in a React app.

**Tech:** React, TypeScript, face-api.js, Redux Toolkit, Vite

[Repo](https://github.com/tristanbeley92/open-cam-lab)

</td>
<td width="50%" valign="top">

### PlaylistGenerator

A Python tool that creates Spotify playlists through the Spotify Web API.

I built it to cut down on adding tracks manually and get hands-on experience with REST APIs and OAuth.

**Tech:** Python, Spotify Web API

[Repo](https://github.com/tristanbeley92/PlaylistGenerator)

</td>
</tr>
</table>

---

## GitHub activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/metrics/metrics.dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/metrics/metrics.svg">
  <img src="assets/metrics/metrics.svg" alt="GitHub contribution and language activity for tristanbeley92" width="480">
</picture>

Updated daily from public GitHub activity. Some of my work lives in private repositories.

---

## Let's connect

Building something interesting, working on a similar problem, or just want to talk cars or code? Reach out at [tristanbeley@gmail.com](mailto:tristanbeley@gmail.com).
