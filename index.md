<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Catcher Salazar | Curator of Interests</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/masonry/4.2.2/masonry.pkgd.min.js"></script>
    <style>
        :root {
            --primary-color: #2d3436;
            --secondary-color: #636e72;
            --accent-color: #00b894;
            --background-color: #f5f6fa;
            --card-color: #ffffff;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            background-color: var(--background-color);
            color: var(--primary-color);
            line-height: 1.6;
        }

        header {
            text-align: center;
            padding: 4rem 2rem;
            background-color: var(--card-color);
            margin-bottom: 2rem;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-bottom: 1rem;
            object-fit: cover;
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
            color: var(--primary-color);
        }

        .subtitle {
            color: var(--secondary-color);
            font-size: 1.2rem;
            margin-bottom: 1.5rem;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 2rem;
        }

        .grid {
            margin: 2rem 0;
        }

        .card {
            background: var(--card-color);
            border-radius: 10px;
            overflow: hidden;
            margin-bottom: 2rem;
            break-inside: avoid;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .card-content {
            padding: 1.5rem;
        }

        .card-title {
            font-size: 1.2rem;
            margin-bottom: 0.5rem;
            color: var(--primary-color);
        }

        .card-category {
            font-size: 0.9rem;
            color: var(--accent-color);
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 0.5rem;
        }

        .card-description {
            color: var(--secondary-color);
            font-size: 0.95rem;
            margin-bottom: 1rem;
        }

        .masonry-grid {
            display: flex;
            margin-left: -30px;
            width: auto;
        }

        .masonry-grid-column {
            padding-left: 30px;
            background-clip: padding-box;
        }

        @media (max-width: 768px) {
            .container {
                padding: 0 1rem;
            }
            
            .card {
                margin-bottom: 1rem;
            }
        }

        .navigation {
            display: flex;
            justify-content: center;
            gap: 2rem;
            margin-bottom: 2rem;
        }

        .nav-link {
            color: var(--secondary-color);
            text-decoration: none;
            font-weight: 500;
            padding: 0.5rem 1rem;
            border-radius: 20px;
            transition: all 0.3s ease;
        }

        .nav-link:hover {
            color: var(--accent-color);
            background-color: rgba(0,184,148,0.1);
        }
    </style>
</head>
<body>
    <header>
        <img src="/api/placeholder/150/150" alt="Catcher Salazar" class="profile-img">
        <h1>Catcher Salazar</h1>
        <p class="subtitle">Curator of Ideas & Inspiration</p>
        <nav class="navigation">
            <a href="#science" class="nav-link">Science</a>
            <a href="#literature" class="nav-link">Literature</a>
            <a href="#art" class="nav-link">Art</a>
            <a href="#poetry" class="nav-link">Poetry</a>
            <a href="#music" class="nav-link">Music</a>
        </nav>
    </header>

    <div class="container">
        <div class="grid">
            <!-- Science Cards -->
            <div class="card">
                <img src="/api/placeholder/400/200" alt="Neuroscience Research">
                <div class="card-content">
                    <div class="card-category">Science</div>
                    <h3 class="card-title">Neural Networks and Consciousness</h3>
                    <p class="card-description">Recent developments in understanding consciousness through the lens of computational neuroscience.</p>
                </div>
            </div>

            <div class="card">
                <img src="/api/placeholder/400/200" alt="Physics Discovery">
                <div class="card-content">
                    <div class="card-category">Science</div>
                    <h3 class="card-title">Dark Matter Detection</h3>
                    <p class="card-description">Latest experimental results from underground particle detectors searching for dark matter interactions.</p>
                </div>
            </div>
            <!-- Literature Card -->
            <div class="card">
                <img src="/api/placeholder/400/200" alt="Recent Scientific Literature">
                <div class="card-content">
                    <div class="card-category">Scientific Literature</div>
                    <h3 class="card-title">Quantum Computing Breakthrough</h3>
                    <p class="card-description">A fascinating paper on quantum supremacy and its implications for future computing paradigms.</p>
                </div>
            </div>

            <!-- Art Card -->
            <div class="card">
                <img src="/api/placeholder/400/200" alt="Museum Exhibition">
                <div class="card-content">
                    <div class="card-category">Art</div>
                    <h3 class="card-title">Modern Art at MoMA</h3>
                    <p class="card-description">Exploring the intersection of technology and traditional artistic expression in contemporary works.</p>
                </div>
            </div>

            <!-- Poetry Card -->
            <div class="card">
                <img src="/api/placeholder/400/200" alt="Poetry Collection">
                <div class="card-content">
                    <div class="card-category">Poetry</div>
                    <h3 class="card-title">Ocean Vuong's Time is a Mother</h3>
                    <p class="card-description">A powerful collection that explores loss, memory, and the immigrant experience.</p>
                </div>
            </div>

            <!-- Music Card -->
            <div class="card">
                <img src="/api/placeholder/400/200" alt="Music Album">
                <div class="card-content">
                    <div class="card-category">Music</div>
                    <h3 class="card-title">Contemporary Classical</h3>
                    <p class="card-description">Discovering the evolution of classical music in the modern era through innovative compositions.</p>
                </div>
            </div>
        </div>
    </div>

    <script>
        var grid = document.querySelector('.grid');
        var masonry = new Masonry(grid, {
            itemSelector: '.card',
            columnWidth: '.card',
            percentPosition: true
        });
    </script>
</body>
</html>
