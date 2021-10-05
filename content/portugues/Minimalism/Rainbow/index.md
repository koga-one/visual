---
# Essential settings
title: "Rainbow"
type: "post"
date: 2021-10-05T14:04:25-03:00
translationKey: "Rainbow"

# Scheduling
draft: false

# Organization
weight:
categories: [""]
tags: []

# Prototyping
layout:

# Thumbnail / Featured
thumb: "images/rainbow.png"

# Meta
summary: 
---

<div id="rainbow">
    <p class="h1">arco-íris</p>
</div>

<style>
    #rainbow {
        position: relative;
        height: 100vh;
        animation: colors infinite 15s linear;
    }

    #rainbow p {
        position: absolute;
        color: white;
        text-align: center;
        right: 50%;
        bottom: 50%;
        transform: translate(50%, 50%);
    }

    @keyframes colors {
        0% {
            background-color: hsl(0, 100%, 50%);
        }
        10% {
            background-color: hsl(36, 100%, 50%);
        }
        20% {
            background-color: hsl(72, 100%, 50%);
        }
        30% {
            background-color: hsl(108, 100%, 50%);
        }
        40% {
            background-color: hsl(144, 100%, 50%);
        }
        50% {
            background-color: hsl(180, 100%, 50%);
        }
        60% {
            background-color: hsl(216, 100%, 50%);
        }
        70% {
            background-color: hsl(252, 100%, 50%);
        }
        80% {
            background-color: hsl(288, 100%, 50%);
        }
        90% {
            background-color: hsl(324, 100%, 50%);
        }
        100% {
            background-color: hsl(360, 100%, 50%);
        }
    }
</style>