---
layout: post
title: About
permalink: /about/
comments: true
---



<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            max-width: 900px;
            margin: 0 auto;
            padding: 40px 20px;
            background: linear-gradient(135deg, #8B5CF6 0%, #A855F7 50%, #9333EA 100%);
            min-height: 100vh;
            line-height: 1.7;
        }

        .container {
            background: #ffffff;
            border-radius: 20px;
            padding: 40px;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
            backdrop-filter: blur(10px);
        }

        h1 {
            font-size: 2.5em;
            margin-bottom: 30px;
            color: #000000 !important;
            text-align: center;
            font-weight: 800;
        }

        h2 {
            font-size: 1.4em;
            margin: 30px 0 15px 0;
            color: #000000 !important;
            display: flex;
            align-items: center;
            gap: 10px;
            font-weight: 700;
        }

        h3 {
            font-size: 1.8em;
            margin: 40px 0 20px 0;
            color: #000000 !important;
            border-bottom: 3px solid #A855F7;
            padding-bottom: 10px;
            font-weight: 800;
        }

        p {
            margin-bottom: 15px;
            font-size: 16px;
            color: #000000 !important;
            font-weight: 700;
        }

        ul {
            margin: 15px 0;
            padding: 20px 25px;
            background: #FFFFFF;
            border-radius: 12px;
            border-left: 4px solid #A855F7;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.15);
        }

        li {
            margin-bottom: 10px;
            font-size: 15px;
            color: #000000 !important;
            position: relative;
            padding-left: 10px;
            font-weight: 700;
        }

        li::before {
            content: "•";
            color: #A855F7;
            font-weight: bold;
            position: absolute;
            left: -10px;
        }

        .highlight {
            background: linear-gradient(135deg, #A855F7, #8B5CF6);
            padding: 25px;
            border-radius: 15px;
            margin: 30px 0;
            text-align: center;
            box-shadow: 0 10px 25px rgba(168, 85, 247, 0.3);
        }

        .highlight p {
            color: white;
            font-size: 18px;
            font-weight: 500;
            margin: 0;
        }

        /* Places I've Lived Section */
        .places-section {
            margin: 40px 0;
        }

        .grid-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }

        .grid-item {
            text-align: center;
            background: white;
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.08);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .grid-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
        }

        .grid-item img {
            width: 100%;
            height: 80px;
            object-fit: contain;
            margin-bottom: 15px;
            border-radius: 8px;
        }

        .grid-item p {
            margin: 8px 0;
            font-size: 14px;
        }

        .grid-item .description {
            font-weight: 800;
            color: #000000 !important;
        }

        .grid-item .greeting {
            color: #A855F7 !important;
            font-style: italic;
            font-weight: 700;
        }

        /* Image Gallery */
        .image-gallery {
            display: flex;
            gap: 15px;
            overflow-x: auto;
            padding: 20px 0;
            border-radius: 12px;
            background: rgba(255, 255, 255, 0.5);
            padding: 20px;
            margin: 20px 0;
        }

        .image-gallery::-webkit-scrollbar {
            height: 8px;
        }

        .image-gallery::-webkit-scrollbar-track {
            background: rgba(0, 0, 0, 0.1);
            border-radius: 10px;
        }

        .image-gallery::-webkit-scrollbar-thumb {
            background: #A855F7;
            border-radius: 10px;
        }

        .image-gallery img {
            min-width: 200px;
            height: 150px;
            object-fit: cover;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }

        .image-gallery img:hover {
            transform: scale(1.05);
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .container {
                padding: 20px;
            }
            
            h1 {
                font-size: 2em;
            }
            
            .grid-container {
                grid-template-columns: 1fr;
            }
            
            .image-gallery img {
                min-width: 150px;
                height: 120px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>About Me </h1>
        
        <p>Hey! I'm passionate about cybersecurity and pretty much every sport that exists. Welcome to my corner of the internet where I share a bit about who I am and what makes me tick.</p>
        
        <h3>🌍 Places I've Called Home</h3>
        <div class="places-section">
            <p>Here are some places that have shaped my journey:</p>
            <div class="grid-container" id="grid_container">
                <!-- Content will be added here by JavaScript -->
            </div>
        </div>

        <h3>My Journey Through Life</h3>
        
        <h2>What I Do</h2>
        <p>I work in cybersecurity where I get to solve puzzles and build defenses against creative attacks. Every vulnerability is just another challenge, and honestly, I love the mental chess game of staying ahead of threats. </p>
        
        <h2>Sports</h2>
        <p>If there's a ball, puck, or any kind of competitive action involved, I'm probably watching it. Football, basketball, baseball, hockey, tennis - you name it, I follow it. There's something about the strategy, the teamwork, and those clutch moments that just gets me every time.</p>
        
        <h2>Free Time</h2>
        <p>My downtime is sacred, and here's how I spend it:</p>
        <ul>
            <li>Deep diving into YouTube rabbit holes about random topics</li>
            <li>Gaming on my Xbox - my setup is my pride and joy and I'm always tweaking it to perfection</li>
            <li>Catching highlights from whatever sport is in season</li>
            <li>Learning something new in cybersecurity because the field never stops evolving</li>
            <li>Spending quality time with family, they keep me grounded</li>
        </ul>
        
        <h2>Who I Am</h2>
        <p>I'm pretty outgoing and love diving into complex problems with people, but I also value those quiet moments to recharge and think things through. Some of my best problem-solving techniques actually come from gaming - patience, strategy, and trying different approaches until something clicks.</p>
        
        <h2>Fun Facts About Me</h2>
        <ul>
            <li>My perfect evening involves sports highlights, YouTube deep dives, and some serious Xbox time</li>
            <li>I can get super energized talking cybersecurity, then go home and spend hours perfecting my gaming setup</li>
            <li>I believe the best solutions come from combining technical skills with creative thinking</li>
            
        </ul>
        
        <h3>👨‍👩‍👦‍👦 Family & Culture</h3>
        <p>Everything for me, as for many others, revolves around family and faith. My mom moved to India at a very young age from Dubai, and my dad was born and raised in India. I have a younger brother in 5th grade who's incredibly fun to be around.</p>
        
        <p>Our family story spans continents and cultures, and that diversity has given me a unique perspective on problem, solving and connecting with people from all walks of life.</p>

        <h3>📸 Memories & Moments</h3>
        <p>Here are some snapshots from my journey - scroll to see more!</p>
        <div class="image-gallery">
            <img src="images/about/IMG_0097.JPG" alt="Family moment 1" onerror="this.style.display='none'">
            <img src="images/about/IMG_0241.JPG" alt="Family moment 2" onerror="this.style.display='none'">
            <img src="images/about/IMG_0354.HEIC" alt="Family moment 3" onerror="this.style.display='none'">
            <img src="images/about/IMG_0940.HEIC" alt="Family moment 4" onerror="this.style.display='none'">
            <img src="images/about/ec8cd2b6-615b-47e1-91c5-0db3466e7a28.JPG" alt="Family moment 5" onerror="this.style.display='none'">
        </div>
        
        <div class="highlight">
            <p><em>Life's too short. Let's make it count. </em></p>
        </div>
    </div>

    <script>
        // Connect to the HTML container
        const container = document.getElementById("grid_container");
        
        // Define data for places lived
        const httpSource = "https://upload.wikimedia.org/wikipedia/commons/";
        const livingInTheWorld = [
            {
                "flag": "0/01/Flag_of_California.svg", 
                "greeting": "Hey there!", 
                "description": "California - Forever Home"
            },
            // Add more locations here as needed
        ];

        // Build grid items
        livingInTheWorld.forEach(location => {
            // Create grid item container
            const gridItem = document.createElement("div");
            gridItem.className = "grid-item";
            
            // Create and add flag image
            const img = document.createElement("img");
            img.src = httpSource + location.flag;
            img.alt = location.description + " Flag";
            img.onerror = function() { this.style.display = 'none'; };
            
            // Create and add description
            const description = document.createElement("p");
            description.className = "description";
            description.textContent = location.description;
            
            // Create and add greeting
            const greeting = document.createElement("p");
            greeting.className = "greeting";
            greeting.textContent = location.greeting;
            
            // Append all elements to grid item
            gridItem.appendChild(img);
            gridItem.appendChild(description);
            gridItem.appendChild(greeting);
            
            // Add grid item to container
            container.appendChild(gridItem);
        });
    </script>
</body>

</html>
