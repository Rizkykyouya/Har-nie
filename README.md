<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Harunio VTuber Group</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f2f5;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            background: #6441a5;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        
        .logo {
            font-size: 32px;
            font-weight: bold;
        }
        
        nav {
            background-color: #8a5ac9;
            padding: 10px 0;
        }
        
        .menu {
            display: flex;
            justify-content: center;
            list-style-type: none;
            margin: 0;
            padding: 0;
        }
        
        .menu li {
            margin: 0 15px;
        }
        
        .menu a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            font-size: 18px;
        }
        
        .menu a:hover {
            text-decoration: underline;
        }
        
        .hero {
            background-color: #9146ff;
            color: white;
            text-align: center;
            padding: 50px 0;
            margin-bottom: 30px;
        }
        
        .hero h1 {
            font-size: 48px;
            margin-bottom: 20px;
        }
        
        .hero p {
            font-size: 20px;
            max-width: 800px;
            margin: 0 auto;
        }
        
        .section-title {
            text-align: center;
            font-size: 36px;
            margin-bottom: 30px;
            color: #6441a5;
        }
        
        .vtubers-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
        }
        
        .vtuber-card {
            background-color: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        
        .vtuber-card:hover {
            transform: translateY(-10px);
        }
        
        .vtuber-image {
            width: 100%;
            height: 250px;
            object-fit: cover;
        }
        
        .vtuber-info {
            padding: 20px;
        }
        
        .vtuber-name {
            font-size: 24px;
            margin-bottom: 10px;
            color: #6441a5;
        }
        
        .vtuber-role {
            font-size: 18px;
            color: #9146ff;
            margin-bottom: 15px;
        }
        
        .vtuber-description {
            color: #333;
            margin-bottom: 15px;
        }
        
        .social-links {
            display: flex;
            gap: 10px;
        }
        
        .social-button {
            background-color: #6441a5;
            color: white;
            border: none;
            padding: 8px 12px;
            border-radius: 5px;
            cursor: pointer;
            text-decoration: none;
            font-size: 14px;
        }
        
        .schedule {
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            margin-top: 40px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        
        .schedule-title {
            text-align: center;
            font-size: 28px;
            margin-bottom: 20px;
            color: #6441a5;
        }
        
        footer {
            background-color: #6441a5;
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
        }
        
        @media (max-width: 800px) {
            .vtubers-grid {
                grid-template-columns: repeat(2, 1fr);
            }
        }
        
        @media (max-width: 500px) {
            .vtubers-grid {
                grid-template-columns: 1fr;
            }
            
            .menu {
                flex-direction: column;
                align-items: center;
            }
            
            .menu li {
                margin: 5px 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">          
            <div class="logo">HARUNIE</div>
        </div>
    </header>
    
    <nav>
        <div class="container">
            <ul class="menu">
                <li><a href="#home">Home</a></li>
                <li><a href="#vtubers">VTubers</a></li>
                <li><a href="#schedule">Schedule</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>
    
    <section class="hero" id="home">
        <div class="container">
            <h1>Welcome to Harunie VTuber Group</h1>
            <p>Discover our amazing virtual talents bringing joy and entertainment to fans worldwide!</p>
        </div>
    </section>
    
    <main class="container">
        <section id="vtubers">
            <h2 class="section-title">Our VTubers</h2>
            
            <div class="vtubers-grid">
                <!-- VTuber 1 -->
                <div class="vtuber-card">
                    <img src="https://cdn.discordapp.com/attachments/1302256632163729408/1349406525860610138/IMG_1094.png?ex=67d2fc42&is=67d1aac2&hm=e5959ea30abfd1d6f5050233ffcbadedc2421a15212ea10343f0ca0239fb6b29&" alt="Ryuga Ranjaya" class="vtuber-image">
                    <div class="vtuber-info">
                        <h3 class="vtuber-name">Ryuga Ranjaya</h3>
                        <div class="vtuber-role">Gamer / Singer</div>
                        <p class="vtuber-description">Ryuga is an energetic fox spirit who loves action games and singing. His streams are always full of laughter and excitement!</p>
                        <div class="social-links">
                            <a href="https://youtube.com/@ryugaranjaya?si=P5IptDy9svmC4Gyx" class="social-button">YouTube</a>
                            <a href="https://twitter.com/RyugaRanjayaa?t=MiGvSFFbUYrJTBBUf4F5FQ&s=09" class="social-button">Twitter</a>
                            <a href="https://www.instagram.com/ryugaranjaya" class="social-button">Instagram</a>
                            <a href="https://www.tiktok.com/@ryugaranjaya" class="social-button">Tiktok</a>
                        </div>
                    </div>
                </div>
                
                <!-- VTuber 2 -->
                <div class="vtuber-card">
                    <img src="https://cdn.discordapp.com/attachments/1302256632163729408/1349405408380452985/Naana_milktea.png?ex=67d2fb38&is=67d1a9b8&hm=1d18b4a05eb3b67dc80a5e5a430092260ec9eece8aeff1cf02c5644c891f61e7&" alt="Nana" class="vtuber-image">
                    <div class="vtuber-info">
                        <h3 class="vtuber-name">Nana</h3>
                        <div class="vtuber-role">Gamer</div>
                        <p class="vtuber-description">Nana is a soft-spoken snow spirit who specializes in digital art and relaxing ASMR content. Join her chill streams to unwind!</p>
                        <div class="social-links">
                            <a href="https://www.youtube.com/channel/UC6kz3lJaZY4wV6olyeZ8nNA" class="social-button">YouTube</a>
                            <a href="https://x.com/naanakokona" class="social-button">Twitter</a>
                            <a href="#" class="social-button">Instagram</a>
                            <a href="https://www.tiktok.com/@kokowanaana" class="social-button">Tiktok</a>
                        </div>
                    </div>
                </div>
                
                <!-- VTuber 3 -->
                <div class="vtuber-card">
                    <img src="https://cdn.discordapp.com/attachments/1302256632163729408/1349404778903506984/2.png?ex=67d2faa2&is=67d1a922&hm=d62082d802f1bfeaf1247314d3dc4cc25987c41c4f1c3031ee69b4223f065fa9&" alt="Aru Masashi" class="vtuber-image">
                    <div class="vtuber-info">
                        <h3 class="vtuber-name">Aru Masashi</h3>
                        <div class="vtuber-role">Gamer</div>
                        <p class="vtuber-description">Aru is a dragon-human hybrid with a passion for RPGs and making people laugh. His commentary during gameplay is legendary!</p>
                        <div class="social-links">
                            <a href="https://www.youtube.com/@aru.masashi" class="social-button">YouTube</a>
                            <a href="https://twitter.com/aru_masashi" class="social-button">Twitter</a>
                            <a href="https://www.tiktok.com/@aru.masashii?enable_tiktok_webview=true" class="social-button">Tiktok</a>
                            <a href="https://www.instagram.com/aru.masashi/" class="social-button">Instagram</a>
                        </div>
                    </div>
                </div>
                
                <!-- VTuber 4 -->
                <div class="vtuber-card">
                    <img src="https://cdn.discordapp.com/attachments/1302256632163729408/1349404034200506368/IMG_20250226_035752_687.webp?ex=67d2f9f0&is=67d1a870&hm=103e26a1542e7625cb0d976ddba93c4233eab3945fafa946780da87ddf016549&" alt="Felix" class="vtuber-image">
                    <div class="vtuber-info">
                        <h3 class="vtuber-name">Felix</h3>
                        <div class="vtuber-role">Singer / Dancer</div>
                        <p class="vtuber-description">Felix is a light fairy who brings joy through his beautiful singing voice and dance performances. His karaoke streams are a must-watch!</p>
                        <div class="social-links">
                            <a href="https://youtube.com/@felix_kato?si=OKUX7_dnAsQjA93E" class="social-button">YouTube</a>
                            <a href="https://x.com/FelixKato_" class="social-button">Twitter</a>
                            <a href="https://www.instagram.com/felix_nyannn" class="social-button">Instagram</a>
                        </div>
                    </div>
                </div>
                
                <!-- VTuber 5 -->
                <div class="vtuber-card">
                    <img src="https://cdn.discordapp.com/attachments/1047949209925591070/1147079490678308885/new.png?ex=67d29186&is=67d14006&hm=358b47182fec64597a5be03a14fd2fcb430260b14cd942deca5ee685d530e129&" alt="Rizky" class="vtuber-image">
                    <div class="vtuber-info">
                        <h3 class="vtuber-name">Rizky</h3>
                        <div class="vtuber-role">Horror Gamer / Storyteller</div>
                        <p class="vtuber-description">Rizky is a friendly oni who loves horror games and telling spooky stories. Join him for a thrilling and chilling experience!</p>
                        <div class="social-links">
                            <a href="#" class="social-button">YouTube</a>
                            <a href="#" class="social-button">Twitter</a>
                            <a href="#" class="social-button">Instagram</a>
                        </div>
                    </div>
                </div>
                
                <!-- VTuber 6 -->
                <div class="vtuber-card">
                    <img src="https://cdn.discordapp.com/attachments/1302256632163729408/1349404636712276159/Aduh_gantengnyaaa....jpg?ex=67d2fa80&is=67d1a900&hm=6bf490f1ecd55b1a945e7db83d8e39c15b3dfd7de485bb0763bd67f359d7bb98&" alt="Coco" class="vtuber-image">
                    <div class="vtuber-info">
                        <h3 class="vtuber-name">Coco</h3>
                        <div class="vtuber-role">Variety / Cooking</div>
                        <p class="vtuber-description">Coco is a forest spirit who enjoys a variety of content, especially cooking streams. Her positive energy is contagious!</p>
                        <div class="social-links">
                            <a href="#" class="social-button">YouTube</a>
                            <a href="#" class="social-button">Twitter</a>
                            <a href="#" class="social-button">Instagram</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
        <section id="schedule" class="schedule">
            <h2 class="schedule-title">Streaming Schedule</h2>
            <p style="text-align: center; margin-bottom: 20px;">Check out when your favorite VTubers are going live!</p>
            
            <div style="overflow-x: auto;">
                <table style="width: 100%; border-collapse: collapse;">
                    <tr style="background-color: #6441a5; color: white;">
                        <th style="padding: 10px; border: 1px solid #ddd;">Nama</th>
                        <th style="padding: 10px; border: 1px solid #ddd;">Monday</th>
                        <th style="padding: 10px; border: 1px solid #ddd;">Tuesday</th>
                        <th style="padding: 10px; border: 1px solid #ddd;">Wednesday</th>
                        <th style="padding: 10px; border: 1px solid #ddd;">Thursday</th>
                        <th style="padding: 10px; border: 1px solid #ddd;">Friday</th>
                        <th style="padding: 10px; border: 1px solid #ddd;">Saturday</th>
                        <th style="padding: 10px; border: 1px solid #ddd;">Sunday</th>
                    </tr>
                    <tr>
                        <td style="padding: 10px; border: 1px solid #ddd; font-weight: bold;">Felix</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                    </tr>
                    <tr style="background-color: #f9f9f9;">
                        <td style="padding: 10px; border: 1px solid #ddd; font-weight: bold;">Coco</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                    </tr>
                    <tr>
                        <td style="padding: 10px; border: 1px solid #ddd; font-weight: bold;">Nana</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                    </tr>
                    <tr>
                        <td style="padding: 10px; border: 1px solid #ddd; font-weight: bold;">Rizky</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                    </tr>
                    <tr>
                        <td style="padding: 10px; border: 1px solid #ddd; font-weight: bold;">ryuga ranjaya</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">-</td>
                    </tr>
