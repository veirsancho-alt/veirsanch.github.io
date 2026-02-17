<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nature Vision | Photography & Tips</title>
    <style>
        :root { --primary: #00d4ff; --bg: #0a0a0a; --text: #eee; }
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Segoe UI', sans-serif; background: var(--bg); color: var(--text); line-height: 1.8; }
        header { height: 60vh; background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://images.unsplash.com/photo-1472214103451-9374bd1c798e?auto=format&fit=crop&w=1200&q=80'); background-size: cover; background-position: center; display: flex; flex-direction: column; justify-content: center; align-items: center; text-align: center; }
        .content-section { max-width: 900px; margin: 40px auto; padding: 20px; }
        h2 { color: var(--primary); margin-bottom: 20px; text-transform: uppercase; border-bottom: 2px solid #333; display: inline-block; }
        .article { background: #111; padding: 20px; border-radius: 8px; margin-bottom: 30px; border-left: 4px solid var(--primary); }
        .article h3 { color: var(--primary); margin-bottom: 10px; }
        .gallery { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 15px; margin-top: 20px; }
        .gallery img { width: 100%; height: 200px; object-fit: cover; border-radius: 5px; }
        footer { text-align: center; padding: 40px; background: #000; font-size: 0.9rem; }
    </style>
</head>
<body>

    <header>
        <h1>Nature Vision</h1>
        <p>Expert Nature Photography & Visual Storytelling</p>
    </header>

    <div class="content-section">
        <h2>About The Project | حول المشروع</h2>
        <p>Welcome to Nature Vision. This platform is dedicated to exploring the hidden beauty of natural landscapes. Our mission is to provide high-quality visual content and share professional insights into the world of photography.</p>
    </div>

    <div class="content-section">
        <h2>Photography Tips (Blog)</h2>
        
        <div class="article">
            <h3>1. The Magic of Golden Hour</h3>
            <p>Golden hour is the period shortly after sunrise or before sunset. The light is redder and softer, making it perfect for landscape photography. To capture the best shots, always use a tripod and keep your ISO low for maximum clarity.</p>
        </div>

        <div class="article">
            <h3>2. Composition in Nature</h3>
            <p>Using the "Rule of Thirds" can transform your photos. Instead of placing your subject in the center, try placing it on the imaginary grid lines. This creates more balance and energy in your nature shots.</p>
        </div>
    </div>

    <div class="content-section">
        <h2>Visual Gallery</h2>
        <div class="gallery">
            <img src="https://images.unsplash.com/photo-1441974231531-c6227db76b6e?auto=format&fit=crop&w=500&q=60">
            <img src="https://images.unsplash.com/photo-1501854140801-50d01698950b?auto=format&fit=crop&w=500&q=60">
            <img src="https://images.unsplash.com/photo-1447752875215-b2761acb3c5d?auto=format&fit=crop&w=500&q=60">
        </div>
    </div>

    <footer>
        <p>&copy; 2026 Nature Vision Portfolio - Built for Professional Showcasing</p>
        <p>Privacy Policy | Terms of Service</p>
    </footer>

</body>
</html>
