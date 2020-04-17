

**Live Website**

Click Here to experience [ALONE](https://ilyadubinski.github.io/ALONE/)

---

**ALONE**


---

**Table of Contents**

Introduction

Features

Technologies

Todos

---

**Introduction**

ALONE is a visual experiment that explores the relationship between lonelieness, technology, isolation, and the need for connection. During quarantine I felt myself going inward in a way that was both cathartic and terrifying. Like many people going through this moment in time I felt ambivalent about this new found time alone. However, as I continued inward I saw that the quarantine and the intrsopection that came with it had many faces. Out of this confusion, fear, and therapy came ALONE. What began as a one page web application and visualizer about lonelienss became a three paged visual journey through time, space, and the heart. ALONE utilizes poetry, audio, and visual design in a way that is both user-friendly and abstract. The fact that this is a very atypical web application is not unknown to me so consider this an excercise. This project has taught me a lot as a person and as an engineer. The more I let the creative part of me take over, the more I began to appreciate the structure of UI/UX design (something that is new to me). For example, a table can be beautiful or plain, it can have four legs or zero, however it must function as a table. In the end, ALONE turned into a sandbox for me to play around with art, design, poetry, and engineering. Thank you for taking the time to look at it. 

---

**Features**

---
ALONE is simple yet powerful. It contains three pages, each containing a 3D visualizer, a poem, and a song. Each page has a nav bar at the top of the page (for more seemless user interaction). The audio will mantain itself if the user chooses to open the poem (placed in a modal). 

![Alt text](app/assets/images/dash.png "Optional Title")

Here is a snippet of code where I create the rain simulation found within stormcloud.html.  


``` rainGeo = new THREE.Geometry();
    for (let i = 0; i < rainCount; i++) {
        rainDrop = new THREE.Vector3(
            Math.random() * 400 - 200,
            Math.random() * 500 - 250,
            Math.random() * 400 - 200
        );
        rainDrop.velocity = {};
        rainDrop.velocity = 1;
        rainGeo.vertices.push(rainDrop);
    }
    rainMaterial = new THREE.PointsMaterial({
        color: 0xaaaaaa,
        size: 0.3,
        transparent: true
    });
    rain = new THREE.Points(rainGeo, rainMaterial);
    scene.add(rain);
```





---
**Technologies**

ALONE is created with:

Javascript 

Three.js

WebGL

CSS

HTML 

---
**Todos**

Add a modal that opens on page load in index.html


