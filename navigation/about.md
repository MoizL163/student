---
layout: post
title: About
permalink: /about/
comments: true
---

## As a conversation Starter

Here are some places I have lived.

<comment>
Flags are made using Wikipedia images
</comment>

<style>
    /* Style looks pretty compact, 
       - grid-container and grid-item are referenced the code 
    */
    .grid-container {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(150px, 1fr)); /* Dynamic columns */
        gap: 10px;
    }
    .grid-item {
        text-align: center;
    }
    .grid-item img {
        width: 100%;
        height: 100px; /* Fixed height for uniformity */
        object-fit: contain; /* Ensure the image fits within the fixed height */
    }
    .grid-item p {
        margin: 5px 0; /* Add some margin for spacing */
    }

    .image-gallery {
        display: flex;
        flex-wrap: nowrap;
        overflow-x: auto;
        gap: 10px;
        }

    .image-gallery img {
        max-height: 150px;
        object-fit: cover;
        border-radius: 5px;
    }
</style>

<!-- This grid_container class is used by CSS styling and the id is used by JavaScript connection -->
<div class="grid-container" id="grid_container">
    <!-- content will be added here by JavaScript -->
</div>

<script>
    // 1. Make a connection to the HTML container defined in the HTML div
    var container = document.getElementById("grid_container"); // This container connects to the HTML div

    // 2. Define a JavaScript object for our http source and our data rows for the Living in the World grid
    var http_source = "https://upload.wikimedia.org/wikipedia/commons/";
    var living_in_the_world = [
        {"flag": "0/01/Flag_of_California.svg", "greeting": "Hey", "description": "California - forever"},
    ];

    // 3a. Consider how to update style count for size of container
    // The grid-template-columns has been defined as dynamic with auto-fill and minmax

    // 3b. Build grid items inside of our container for each row of data
    for (const location of living_in_the_world) {
        // Create a "div" with "class grid-item" for each row
        var gridItem = document.createElement("div");
        gridItem.className = "grid-item";  // This class name connects the gridItem to the CSS style elements
        // Add "img" HTML tag for the flag
        var img = document.createElement("img");
        img.src = http_source + location.flag; // concatenate the source and flag
        img.alt = location.flag + " Flag"; // add alt text for accessibility

        // Add "p" HTML tag for the description
        var description = document.createElement("p");
        description.textContent = location.description; // extract the description

        // Add "p" HTML tag for the greeting
        var greeting = document.createElement("p");
        greeting.textContent = location.greeting;  // extract the greeting

        // Append img and p HTML tags to the grid item DIV
        gridItem.appendChild(img);
        gridItem.appendChild(description);
        gridItem.appendChild(greeting);

        // Append the grid item DIV to the container DIV
        container.appendChild(gridItem);
    }
</script>

### Journey through Life

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            max-width: 700px;
            margin: 0 auto;
            padding: 40px 20px;
            background-color: #fafbfc;
            color: #333;
            line-height: 1.6;
        }

        h1 {
            font-size: 28px;
            margin-bottom: 20px;
            color: #2c5aa0;
            border-bottom: 3px solid #e8f0fe;
            padding-bottom: 10px;
        }

        h2 {
            font-size: 18px;
            margin-top: 30px;
            margin-bottom: 10px;
            color: #1a73e8;
        }

        p {
            margin-bottom: 15px;
            font-size: 14px;
        }

        ul {
            margin-bottom: 15px;
            padding-left: 20px;
            background-color: white;
            padding: 15px 20px;
            border-radius: 8px;
            box-shadow: 0 1px 3px rgba(0,0,0,0.1);
        }

        li {
            margin-bottom: 8px;
            font-size: 14px;
        }

        .highlight {
            background-color: #fff3cd;
            padding: 15px;
            border-radius: 8px;
            border-left: 4px solid #ffc107;
            margin: 20px 0;
        }
    </style>
</head>
<body>
    <h1>About Me 👋</h1>
    
    <p>Hey! I'm passionate about cybersecurity and pretty much every sport that exists. I approach cyber defense like a defensive coordinator - always thinking three moves ahead and protecting what matters most.</p>
    
    <h2>🛡️ What I Do</h2>
    <p>I work in cybersecurity where I get to solve puzzles and build defenses against creative attacks. Every vulnerability is just another challenge, and honestly, I love the mental chess game of staying ahead of threats.</p>
    
    <h2>🏈 Sports Obsession</h2>
    <p>If there's a ball, puck, or any kind of competitive action involved, I'm probably watching it. Football, basketball, baseball, hockey, tennis - you name it, I follow it. I analyze sports stats with the same intensity I bring to threat analysis.</p>
    
    <h2>🎮 Downtime</h2>
    <p>When I'm not working, you'll find me:</p>
    <ul>
        <li>Deep in YouTube rabbit holes about random topics</li>
        <li>Gaming on my Xbox (my setup is my pride and joy)</li>
        <li>Catching highlights from whatever sport is in season</li>
        <li>Learning something new in cybersecurity</li>
    </ul>
    
    <h2>😊 Personality</h2>
    <p>I'm pretty outgoing and love diving into complex problems with people, but I also value those quiet moments to recharge and think things through. Some of my best problem-solving techniques actually come from gaming - patience, strategy, and trying different approaches until something works.</p>
    
    <h2>⚡ Fun Facts</h2>
    <ul>
        <li>My perfect evening involves sports highlights, YouTube, and some serious Xbox time</li>
        <li>I can get super energized talking cybersecurity, then go home and spend hours perfecting my gaming setup</li>
        <li>My friends joke that I study game film with the same focus I use for security analysis</li>
    </ul>
    
    <div class="highlight">
        <p><em>Life's too short for boring conversations and easy games! 🚀</em></p>
    </div>
</body>
</html>

### Culture, Family, and Fun

Everything for me, as for many others, revolves around family and faith.

- My mother told me that I was Danish, English. and Irish, here is my researched [family tree]({{site.baseurl}}/images/about/familytree.png)
- My family is pretty big as I have been married twice, my 1st wife passed away.  We have had 5 kids, 4 adopted by me, 1 biological.  Plus, there are three grandkids.  My name to my grandkids is Abuilito.
- The gallery of pics has some of my family, fun, culture and faith memories.

<comment>
Gallery of Pics, scroll to the right for more ...
</comment>
<div class="image-gallery">
  <img src="{{site.baseurl}}/images/about/missionary.jpg" alt="Image 1">
  <img src="{{site.baseurl}}/images/about/john_tamara.jpg" alt="Image 2">
  <img src="{{site.baseurl}}/images/about/tamara_fam.jpg" alt="Image 3">
  <img src="{{site.baseurl}}/images/about/surf.jpg" alt="Image 4">
  <img src="{{site.baseurl}}/images/about/john_lora.jpg" alt="Image 5">
  <img src="{{site.baseurl}}/images/about/lora_fam.jpg" alt="Image 6">
  <img src="{{site.baseurl}}/images/about/lora_fam2.jpg" alt="Image 7">
  <img src="{{site.baseurl}}/images/about/pj_party.jpg" alt="Image 8">
  <img src="{{site.baseurl}}/images/about/trent_family.png" alt="Image 9">
  <img src="{{site.baseurl}}/images/about/claire.jpg" alt="Image 10">
  <img src="{{site.baseurl}}/images/about/grandkids.jpg" alt="Image 11">
  <img src="{{site.baseurl}}/images/about/farm.jpg" alt="Image 12">
</div>
