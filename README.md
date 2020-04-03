

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

ALONE is a visual experiment that explores the relationship between lonelieness, technology, isolation, and the need for connection. While ALONE was originally thought up as a response to the intensity of being alone all day every day thanks to quarantine. In the process of its development Alone became an excercise in facing solitude and the stream of thoughts that come with it.   

---

**Features**

---
ALONE is simple yet powerful. It is a 3D representation of a stormy cloud, high up in the sky, thundering and pouring down rain on the viewer as he looks up at it. There are no features built into the web page. It is simply something to sit with and look at and respond to (or not).

![Alt text](app/assets/images/dash.png "Optional Title")

The crowning jewel of ALONE is the code used to create the rain simulation.  


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

---
**Todos**

Fix the background music. 

Add sound affects for the rain. 


