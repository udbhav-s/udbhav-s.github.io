# Udbhav Saxena

517-980-4943 | udbhavs03@gmail.com | [udbhav-s.github.io](https://udbhav-s.github.io) | [linkedin.com/in/udbhav-s](https://www.linkedin.com/in/udbhav-s/)

## Professional Summary
I am a developer with experience in full-stack software, security, and low-level development. My skills include software performance engineering, public key infrastructure and zero-trust, applied cryptography as well as multimedia. I value working on challenging problems and creating polished user experiences!

## Experience

### Research Assistant
**Michigan State University (Department of Computer Science)** | East Lansing, MI
*Advisor: Dr. Xuhao Chen* | *September 2025 – May 2026*
* Investigating performance engineering techniques for Zero-Knowledge Proof generation using C++.
* Studying curve and hash based proof schemes, MSM / NTT algorithms, numerical optimizations, and parallelization with GPUs.

### Full Stack Developer
**MSU Burgess Institute for Entrepreneurship and Innovation** | East Lansing, MI
*March 2023 – September 2025*
* Developed technical MVPs for 10+ student startups in the Launch program, including full-stack Next.js projects, apps in Flutter, Shopify storefronts, and computer vision prototypes with OpenCV.
* Developed a computer vision prototype with OpenCV and React frontend to stitch captures from a fisheye lens for scanning a whiteboard.
* Used Google Vision for OCR.
* Streamlined inventory management for a storefront with 50+ student sellers with Google Apps scripts to sync spreadsheets with the Squarespace API, automating hours of inventory updates to seconds.

### Research Assistant
**Michigan State University** | East Lansing, MI
*October 2022 – March 2023*
* Built an internal tool for inventory management using TypeScript to generate forms using JSON schemas and convert them to and from Excel spreadsheets that reduced previous form codebase size by 80%.
* Designed a dynamic listings view for USDA farmer's markets in a region with an interactive map.

### Full Stack Intern
**AiBorne Tech (now Amply)** | Delhi, India
*October 2021 – April 2022*
* Developed the web dashboard for an AI car damage inspection platform with Vue 3 and TypeScript.
* Created an interactive 3D car model using Three.js and WebGL to display damage for separate parts, with a gallery widget that updated the Three.js viewport based on the selected region.

## Education

### Michigan State University
**Bachelor of Science in Computer Science and Mathematics** | East Lansing, MI
*GPA: 3.98/4.0 | Honors College | Dean's List | Gillette Research Scholar* | *August 2022 – May 2026*
* **Relevant Coursework:** Data Structures and Algorithms, Operating Systems and Networking, Software Performance Engineering, Foundations of Computing, Computer Security, Accelerated Computing (CUDA)

## Projects

### Diagonalize (HackMIT 2025 – 1st place in EigenLayer Track)
*JavaScript, Solidity, Python, Docker*
* Implemented a private OAuth provider that ran an SMTP server and verified emails inside a TEE, deployed on EigenCloud.
* Used the WebAuthn API to bind email verifications to user-managed public keys (passkeys).
* Wrote a smart contract in Solidity that stored verified anonymous attestations on-chain with associated public keys.

### Fluxus (HackMIT 2023 – 1st place in Healthcare Track)
*Vue 3, TypeScript, SQL, Flask, IntegratedML*
* Developed the front end for an intuitive workspace for transforming and visualizing healthcare data frames.
* The web dashboard featured a graph network illustrating table relationships.
* Fine-tuned an LLM to comprehend medical record codes, generating SQL queries based on natural language prompts for dataset transformations.
* Analyzed generated SQL with node-sql-parser to deduce new table relationships and update the dashboard.

### Capstone Project – Advanced C++ Traffic Simulation
*Modern C++, Emscripten, WebAssembly*
* Developed modern C++ modules that allowed creating Web UIs in C++ using Emscripten and WebAssembly, with support for inline styles, flex layouts, and event handling.

### Secure Satellite TV Decoder (MITRE eCTF 2025)
*Team Lead | Rust, Python, Microcontrollers*
* Designed firmware in Rust to model a secure Satellite TV decoder, placing 21st out of 116 teams.
* Devised a hierarchical key management scheme using hash trees for zero-trust access to channels in subscription packages.
* Employed cryptographic primitives including Ed25519 signatures, ChaCha20 encryption, HKDF key derivation (with SHA-512).
* Wrote a Python script to perform padding oracle attack on insecure AES implementation on the microcontroller.

### Secure Medical System Firmware (MITRE eCTF 2024)
*Team Lead | C, Analog Devices Microcontrollers, TLS*
* Wrote firmware for embedded Analog Devices microcontrollers in C, simulating a medical device and components for a semester-long cybersecurity competition.
* Ranked 9th among 95 international teams.
* Implemented secure and authenticated communication between boards modeled after a TLS handshake, with certificate verification using public-key cryptography and ChaCha20-Poly1305 for encrypted messages.
* Used ChaCha20-Poly1305 for AEAD with a counter for secure post-boot communications to protect integrity and authenticity of exchanged messages.

### Secure Automotive Car-Key Fob Firmware (MITRE eCTF 2023)
*C, TI Tiva Microcontrollers, Python, Docker*
* Engineered firmware for embedded TI Tiva microcontrollers in C, simulating a car and key fob for a semester-long cybersecurity competition (MITRE eCTF).
* Ranked 7th among 80 international teams and 3rd in defensive points.
* Devised a secure protocol for car unlocking, employing public-key cryptography and a challenge-response mechanism.
* The car generated a random nonce, and the fob signed it using elliptic curve digital signatures.
* Developed firmware build tools in Python, executed in Docker containers, to generate header files containing seeded entropy for randomness in firmware.

### Proximity Cast (2022)
*C++, Flutter, GMP Library, Android NDK, WebRTC*
* Built an app in C++ and Flutter that used public-key encryption to privately detect if two parties are within proximity of each other to find and broadcast events.
* 1st place at MSU Code Green Hackathon 2022.
* Implemented a protocol from a research paper, converting location information into ciphertexts and combining them for a distance result revealing only whether participants were within a certain range.
* Wrote the core library in C++ using the GMP library, and integrated into a Flutter app using the Android NDK.
* Facilitated real-time peer-to-peer chat between connected parties with WebRTC.

### Web Multiplayer Card Game
*Vue 3, TypeScript, Nest.JS, Postgres, WebSockets, Nginx, SVG, Inkscape*
* Web-based card game made using Vue.js, the Web Animations API, and SVG art.
* Used JS Proxies on the backend to reactively track changes in the game state, generate JSON patches that were sent through WebSockets to the frontend and integrated with the reactive Vue state.
* Designed artwork for game cards using Inkscape.

### Interactive Gallery Installation for School Centenary Museum
*Vue 3, WebSockets, SVG*
* Worked on an interactive gallery installation for an alumni reunion at HPS Begumpet that presented a physical interface with two displays and dials for scrubbing through images throughout the school's history.
* Independently developed all the software and backend for the project within a span of a month, leading to a physical installation used by hundreds of people at the event.
* More details at: https://thearchivehps.netlify.app/

### Document Scanning Aid for Visually Impaired Users
*Vue 3, WebSockets, SVG, JavaScript, Google MediaPipe*
* Worked on software accompanying a hardware prototype that explored new UX paradigms for document scanning and OCR for use by visually impaired people.
* Developed demos using JavaScript and Google MediaPipe that enabled ways to center documents in frame using audio cues.
* Incorporated feedback from testing at school for visually impaired children.
* Project won Best Student Project award at IndiaHCI 2025 conference.

## University Leadership

### MSU Cybersecurity Club President
* Responsible for coordinating cybersecurity events for a club of 200+ students.
* Created workshops on the Linux shell, web hacking, forensics, cryptography and binary analysis.

### First-year Engineering CoRe Experience Peer Leader, App Lead
*January 2023 – April 2025*
* Worked on a team of residential students that helped freshmen engineers acclimate to college at MSU.
* Organized College of Engineering colloquium, lab tours, and weekly academic and professional events for residents.

### SpartaHack Annual Hackathon Core Organizing Team
*2025, 2026*
* Led the operations team in organizing the theme, tracks, activities and judging at the hackathon.

## Skills
* **Languages & Core Development:** Python, TypeScript, JavaScript, C/C++, Rust, Go, Dart, SQL, HTML/CSS, Liquid
* **Frameworks & Libraries:** Vue.js (Vue 3), Next.js, React.js, Node.js, Nest.JS, Flask, Flutter, Three.js, WebGL, OpenCV, Google Vision, Google MediaPipe, WebRTC, OpenCilk, GMP, Android NDK
* **Tools, Databases & Deployment:** Docker, CMake, Nginx, Firebase, Postgres, WebSockets, Git, Linux/Unix, Shopify, Squarespace API, Google Apps Script
* **Security & Cryptography:** Zero-Knowledge Proofs, Public Key Infrastructure (PKI), Identity and Authentication, Application Security, Web Hacking, Forensics, Binary Analysis, Cryptographic Primitives (ChaCha20-Poly1305, Ed25519, HKDF, AES)
* **Systems & High Performance Computing:** CUDA, Software Performance Engineering, Microcontrollers, Embedded Systems Security, Hardware/Firmware Tools
* **Design & Multimedia:** Figma, Adobe Photoshop, Adobe Illustrator, Adobe After Effects, Unity, Inkscape, SVG, Digital Design, Interactive User Experiences
* **Leadership & Operations:** Team Leadership, Event Coordination, Workshop Creation