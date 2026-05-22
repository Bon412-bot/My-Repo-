<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Educational Facts About Cats</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 900px;
            margin: 0 auto;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
            overflow: hidden;
        }
        
        header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 40px 20px;
            text-align: center;
        }
        
        header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }
        
        header p {
            font-size: 1.1em;
            opacity: 0.9;
        }
        
        .content {
            padding: 40px;
        }
        
        .facts-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
        }
        
        .fact-card {
            background: #f8f9fa;
            border-left: 5px solid #667eea;
            padding: 20px;
            border-radius: 8px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .fact-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 20px rgba(102, 126, 234, 0.2);
        }
        
        .fact-card h3 {
            color: #667eea;
            margin-bottom: 12px;
            font-size: 1.3em;
        }
        
        .fact-card p {
            color: #555;
            line-height: 1.6;
            font-size: 0.95em;
        }
        
        .fact-icon {
            font-size: 2em;
            margin-bottom: 10px;
        }
        
        footer {
            background-color: #f8f9fa;
            text-align: center;
            padding: 20px;
            color: #666;
            border-top: 1px solid #ddd;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>🐱 Fascinating Facts About Cats</h1>
            <p>Discover amazing information about our feline friends</p>
        </header>
        
        <div class="content">
            <div class="facts-grid">
                <div class="fact-card">
                    <div class="fact-icon">👁️</div>
                    <h3>Superior Night Vision</h3>
                    <p>Cats can see in light levels six times lower than humans. They have a reflective layer called the tapetum lucidum behind their retina, which amplifies light and makes their eyes glow in the dark.</p>
                </div>
                
                <div class="fact-card">
                    <div class="fact-icon">👂</div>
                    <h3>Incredible Hearing</h3>
                    <p>Cats can hear frequencies up to 64,000 Hz, compared to humans at 20,000 Hz. They can rotate their ears independently to locate sounds and detect ultrasonic calls from other animals.</p>
                </div>
                
                <div class="fact-card">
                    <div class="fact-icon">🧠</div>
                    <h3>Brain Power</h3>
                    <p>A cat's brain is biologically more similar to a human brain than a dog's brain. Cats have a neocortex with 32 neurons per milligram, compared to 16 in dogs and 16 in humans.</p>
                </div>
                
                <div class="fact-card">
                    <div class="fact-icon">🦴</div>
                    <h3>Flexible Spine</h3>
                    <p>Cats have 53 vertebrae in their spine, compared to 33 in humans. This gives them exceptional flexibility and allows them to land on their feet from nearly any angle.</p>
                </div>
                
                <div class="fact-card">
                    <div class="fact-icon">💤</div>
                    <h3>Sleep Schedule</h3>
                    <p>Cats spend about 70% of their lives sleeping or napping, totaling around 13 to 16 hours per day. This energy conservation helps them hunt efficiently.</p>
                </div>
                
                <div class="fact-card">
                    <div class="fact-icon">🎯</div>
                    <h3>Hunting Instincts</h3>
                    <p>Cats have exceptional hunting abilities. They can reach speeds of 30 mph and their eyes are positioned to give them a wide field of view, perfect for spotting prey.</p>
                </div>
                
                <div class="fact-card">
                    <div class="fact-icon">🔊</div>
                    <h3>Diverse Vocalizations</h3>
                    <p>Cats make over 100 vocal sounds, including purrs, meows, hisses, and chirps. Different meows can convey different messages to humans and other cats.</p>
                </div>
                
                <div class="fact-card">
                    <div class="fact-icon">👃</div>
                    <h3>Powerful Sense of Smell</h3>
                    <p>Cats have a sense of smell 14 times stronger than humans. They have specialized scent glands throughout their body to mark territory and communicate with other cats.</p>
                </div>
                
                <div class="fact-card">
                    <div class="fact-icon">⏱️</div>
                    <h3>Ancient History</h3>
                    <p>Domestic cats descended from African wildcats approximately 10,000 years ago. Ancient Egyptians revered cats and mummified them to accompany owners to the afterlife.</p>
                </div>
            </div>
        </div>
        
        <footer>
            <p>&copy; 2026 Educational Facts About Cats | Learn more about our feline friends</p>
        </footer>
    </div>
</body>
</html>
