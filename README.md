# Girlfriend-day-website
 <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy National Girlfriend Day 2025</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Poppins:wght@300;400;600&display=swap');   
 :root {
        --primary-color: #EDE7F6; /* A soft, elegant lavender */
        --secondary-color: #B39DDB; /* A slightly deeper lavender */
        --accent-color: #FF4081; /* A vibrant pink for highlights */
        --background-color: #121212; /* A deep, rich black */
        --text-color: #FFFFFF;
    }

    body {
        font-family: 'Poppins', sans-serif;
        background-color: var(--background-color);
        color: var(--text-color);
        margin: 0;
        padding: 0;
        overflow-x: hidden;
    }

    .container {
        width: 90%;
        max-width: 1200px;
        margin: 0 auto;
        padding: 2rem 0;
        position: relative;
        z-index: 2;
    }

    .hero {
        height: 100vh;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        text-align: center;
        position: relative;
    }

    .hero h1 {
        font-family: 'Playfair Display', serif;
        font-size: 5rem;
        margin: 0;
        animation: fadeIn 2s ease-in-out;
        color: var(--primary-color);
    }

    .hero p {
        font-size: 1.5rem;
        margin-top: 1rem;
        animation: fadeIn 2s ease-in-out 0.5s;
        color: var(--secondary-color);
    }

    .scroll-down {
        position: absolute;
        bottom: 2rem;
        font-size: 1rem;
        animation: bounce 2s infinite;
    }

    .section {
        padding: 6rem 0;
        opacity: 0;
        transform: translateY(50px);
        transition: opacity 1s ease-out, transform 1s ease-out;
    }

    .section.visible {
        opacity: 1;
        transform: translateY(0);
    }

    .section h2 {
        font-family: 'Playfair Display', serif;
        font-size: 3rem;
        text-align: center;
        margin-bottom: 3rem;
        color: var(--primary-color);
    }

    .gallery-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 1.5rem;
    }

    .gallery-item {
        position: relative;
        overflow: hidden;
        border-radius: 10px;
        box-shadow: 0 10px 20px rgba(0,0,0,0.3);
    }

    .gallery-item img {
        width: 100%;
        height: 100%;
        object-fit: cover;
        transition: transform 0.5s ease;
    }

    .gallery-item:hover img {
        transform: scale(1.1);
    }

    .gallery-item .overlay {
        position: absolute;
        bottom: 0;
        left: 0;
        right: 0;
        background: linear-gradient(to top, rgba(0,0,0,0.8), transparent);
        color: var(--text-color);
        padding: 1.5rem;
        opacity: 0;
        transition: opacity 0.5s ease;
    }

    .gallery-item:hover .overlay {
        opacity: 1;
    }

    .timeline {
        position: relative;
        max-width: 800px;
        margin: 0 auto;
    }

    .timeline::after {
        content: '';
        position: absolute;
        width: 6px;
        background-color: var(--secondary-color);
        top: 0;
        bottom: 0;
        left: 50%;
        margin-left: -3px;
        animation: grow-line 2s ease-out forwards;
    }
    
    @keyframes grow-line {
        from { height: 0; }
        to { height: 100%; }
    }

    .timeline-item {
        padding: 10px 40px;
        position: relative;
        background-color: inherit;
        width: 50%;
    }

    .timeline-item.left {
        left: -50%;
    }

    .timeline-item.right {
        left: 50%;
    }

    .timeline-item::after {
        content: '';
        position: absolute;
        width: 25px;
        height: 25px;
        right: -17px;
        background-color: var(--accent-color);
        border: 4px solid var(--primary-color);
        top: 15px;
        border-radius: 50%;
        z-index: 1;
        transform: scale(0);
        animation: pop-in 0.5s ease-out forwards;
    }
    
    .timeline-item.left::after {
        right: -17px;
    }

    .timeline-item.right::after {
        left: -17px;
    }
    
    .timeline-item.visible .content {
        opacity: 1;
        transform: translateY(0);
    }
    
    .content {
        padding: 20px 30px;
        background-color: #1E1E1E;
        position: relative;
        border-radius: 6px;
        opacity: 0;
        transform: translateY(20px);
        transition: opacity 0.6s ease-out, transform 0.6s ease-out;
    }
    
    .final-message {
        text-align: center;
    }
    
    .final-message p {
        font-size: 1.2rem;
        line-height: 1.8;
        max-width: 700px;
        margin: 0 auto 2rem;
    }
    
    .heart {
        color: var(--accent-color);
        font-size: 3rem;
        animation: pulse 1.5s infinite;
    }

    @keyframes fadeIn {
        from { opacity: 0; }
        to { opacity: 1; }
    }

    @keyframes bounce {
        0%, 20%, 50%, 80%, 100% {
            transform: translateY(0);
        }
        40% {
            transform: translateY(-20px);
        }
        60% {
            transform: translateY(-10px);
        }
    }
    
    @keyframes pulse {
        0% { transform: scale(1); }
        50% { transform: scale(1.2); }
        100% { transform: scale(1); }
    }

    @keyframes pop-in {
        from { transform: scale(0); }
        to { transform: scale(1); }
    }
    
    /* Particle background */
    #particles-js {
        position: fixed;
        width: 100%;
        height: 100%;
        top: 0;
        left: 0;
        z-index: 1;
    }
</style>
</head>
<body>
<div id="particles-js"></div>

<header class="hero">
    <div class="container">
        <h1>Happy National Girlfriend Day</h1>
        <p>August 1, 2025</p>
    </div>
    <div class="scroll-down">Scroll to begin our journey</div>
</header>

    <section id="timeline-section" class="section">
        <div class="container">
            <h2>Our Story So Far</h2>
            <div class="timeline">
                <div class="timeline-item left">
                    <div class="content">
                        <h3>The Day We Met</h3>
                        <p>A little spark that started a beautiful fire. I'll never forget seeing you for the first time.</p>
                    </div>
                </div>
                <div class="timeline-item right">
                    <div class="content">
                        <h3>Our First "I Love You"</h3>
                        <p>On January 2023. A moment that changed everything and set us on this incredible path together.</p>
                    </div>
                </div>
                <div class="timeline-item left">
                    <div class="content">
                        <h3>Adventures and Milestones</h3>
                        <p>From texting to eventually go out on date together, every moment with you is a treasure in mylife.</p>
                    </div>
                </div>
                 <div class="timeline-item right">
                    <div class="content">
                        <h3>Here and Now</h3>
                        <p>Celebrating you today, my amazing girlfriend. Happy Girlfriend Day my only love!!!</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="final-message" class="section">
        <div class="container final-message">
            <h2>To My Everything</h2>
            <p>
               You are my best friend, my partner in crime, and the love of my life. Every day with you is a gift, and I cherish every memory we've made. Thank you for your endless love, support, and for just being you. There's many more adventures and a lifetime of happiness together. Love you always my cutie pie <3
            </p>
            <div class="heart">♥</div>
        </div>
    </section>
</main>

<script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
<script>
    document.addEventListener('DOMContentLoaded', function() {
        // Particle.js configuration
        particlesJS("particles-js", {
            "particles": {
                "number": {
                    "value": 80,
                    "density": {
                        "enable": true,
                        "value_area": 800
                    }
                },
                "color": {
                    "value": "#B39DDB" /* secondary-color */
                },
                "shape": {
                    "type": "circle",
                },
                "opacity": {
                    "value": 0.5,
                    "random": true,
                },
                "size": {
                    "value": 3,
                    "random": true,
                },
                "line_linked": {
                    "enable": true,
                    "distance": 150,
                    "color": "#B39DDB",
                    "opacity": 0.4,
                    "width": 1
                },
                "move": {
                    "enable": true,
                    "speed": 2,
                    "direction": "none",
                    "random": false,
                    "straight": false,
                    "out_mode": "out",
                    "bounce": false,
                }
            },
            "interactivity": {
                "detect_on": "canvas",
                "events": {
                    "onhover": {
                        "enable": true,
                        "mode": "grab"
                    },
                    "onclick": {
                        "enable": true,
                        "mode": "push"
                    },
                    "resize": true
                },
                 "modes": {
                    "grab": {
                      "distance": 140,
                      "line_linked": {
                        "opacity": 1
                      }
                    },
                    "push": {
                      "particles_nb": 4
                    }
                }
            },
            "retina_detect": true
        });
        
        // Intersection Observer for scroll animations
        const sections = document.querySelectorAll('.section');
        const timelineItems = document.querySelectorAll('.timeline-item');
        
        const observerOptions = {
            root: null,
            rootMargin: '0px',
            threshold: 0.1
        };

        const observer = new IntersectionObserver((entries, observer) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                    observer.unobserve(entry.target);
                }
            });
        }, observerOptions);

        sections.forEach(section => {
            observer.observe(section);
        });
        
        timelineItems.forEach(item => {
            observer.observe(item);
        });
    });
</script>
</body>
</html>
