<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="An aesthetic guide to Search Engine Optimization (SEO) and its main types.">
    <title>Aesthetic Guide to SEO</title>
    
    <!-- Google Fonts for Aesthetic Typography -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,500;0,600;0,700;1,400&family=Plus+Jakarta+Sans:wght@300;400;500;600&display=swap" rel="stylesheet">

    <style>
        :root {
            --bg-canvas: #fff5f7;
            --card-bg: rgba(255, 255, 255, 0.85);
            --primary-pink: #f472b6;
            --accent-pink: #fb7185;
            --deep-berry: #4a1d2f;
            --text-muted: #7c5869;
            --border-pink: #fce7f3;
            --soft-glow: rgba(244, 114, 182, 0.15);
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            background-color: var(--bg-canvas);
            /* Soft ambient background gradient */
            background-image: 
                radial-gradient(circle at 10% 20%, #ffe4e6 0%, transparent 35%),
                radial-gradient(circle at 90% 80%, #fce7f3 0%, transparent 40%);
            color: var(--deep-berry);
            font-family: 'Plus Jakarta Sans', sans-serif;
            line-height: 1.7;
            min-height: 100vh;
        }

        /* Hero / Header Section */
        header {
            text-align: center;
            padding: 80px 20px 40px;
            max-width: 800px;
            margin: 0 auto;
        }

        .badge {
            display: inline-block;
            background: #ffffff;
            color: var(--accent-pink);
            font-size: 0.85rem;
            font-weight: 600;
            letter-spacing: 1px;
            text-transform: uppercase;
            padding: 6px 18px;
            border-radius: 50px;
            border: 1px solid var(--border-pink);
            margin-bottom: 20px;
            box-shadow: 0 4px 15px var(--soft-glow);
        }

        header h1 {
            font-family: 'Playfair Display', serif;
            font-size: 3rem;
            font-weight: 700;
            color: var(--deep-berry);
            line-height: 1.2;
            margin-bottom: 15px;
        }

        header h1 span {
            font-style: italic;
            color: var(--accent-pink);
        }

        header p {
            font-size: 1.1rem;
            color: var(--text-muted);
            font-weight: 400;
            max-width: 580px;
            margin: 0 auto;
        }

        /* Layout Container */
        main {
            max-width: 1050px;
            margin: 20px auto 60px;
            padding: 0 24px;
        }

        /* Overview Banner Card */
        .overview-card {
            background: var(--card-bg);
            backdrop-filter: blur(12px);
            border: 1px solid var(--border-pink);
            border-radius: 24px;
            padding: 40px;
            margin-bottom: 50px;
            box-shadow: 0 15px 35px var(--soft-glow);
            text-align: center;
        }

        .overview-card h2 {
            font-family: 'Playfair Display', serif;
            font-size: 1.85rem;
            margin-bottom: 15px;
            color: var(--deep-berry);
        }

        .overview-card p {
            font-size: 1.05rem;
            color: var(--text-muted);
            max-width: 800px;
            margin: 0 auto;
        }

        /* Section Title */
        .section-header {
            text-align: center;
            margin-bottom: 35px;
        }

        .section-header h2 {
            font-family: 'Playfair Display', serif;
            font-size: 2.1rem;
            color: var(--deep-berry);
        }

        /* SEO Types 4-Card Grid */
        .types-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(290px, 1fr));
            gap: 25px;
        }

        .type-card {
            background: var(--card-bg);
            backdrop-filter: blur(8px);
            border: 1px solid rgba(255, 255, 255, 0.8);
            border-radius: 20px;
            padding: 30px;
            box-shadow: 0 10px 25px rgba(244, 114, 182, 0.08);
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }

        .type-card:hover {
            transform: translateY(-6px);
            box-shadow: 0 20px 35px var(--soft-glow);
            border-color: var(--primary-pink);
        }

        .card-icon {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            width: 48px;
            height: 48px;
            background: #fff0f5;
            color: var(--accent-pink);
            font-size: 1.3rem;
            border-radius: 14px;
            margin-bottom: 20px;
            border: 1px solid var(--border-pink);
        }

        .type-card h3 {
            font-family: 'Playfair Display', serif;
            font-size: 1.45rem;
            margin-bottom: 12px;
            color: var(--deep-berry);
        }

        .type-card p {
            font-size: 0.95rem;
            color: var(--text-muted);
            margin-bottom: 20px;
        }

        /* Aesthetic Pill Tags */
        .tag-list {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            list-style: none;
        }

        .tag-list li {
            font-size: 0.8rem;
            font-weight: 500;
            background: #fff;
            color: var(--text-muted);
            border: 1px solid var(--border-pink);
            padding: 4px 12px;
            border-radius: 50px;
        }

        /* Subtle Footer */
        footer {
            text-align: center;
            padding: 40px 20px;
            font-size: 0.85rem;
            color: var(--text-muted);
            border-top: 1px solid var(--border-pink);
            letter-spacing: 0.5px;
        }

        /* Responsive Mobile Tweak */
        @media (max-width: 600px) {
            header h1 {
                font-size: 2.3rem;
            }
            .overview-card {
                padding: 25px;
            }
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <span class="badge">🌸 Digital Marketing 101</span>
        <h1>Search Engine <span>Optimization</span></h1>
        <p>A gentle, aesthetic introduction to mastering visibility, organic search growth, and the core pillars of modern SEO.</p>
    </header>

    <!-- Main Content -->
    <main>

        <!-- What is SEO Overview -->
        <section class="overview-card">
            <h2>What is SEO?</h2>
            <p>
                <strong>Search Engine Optimization (SEO)</strong> is the art and science of optimizing your digital presence to rank higher on organic search results (like Google and Bing). Rather than paying for ads, SEO naturally connects your content to the people actively searching for it.
            </p>
        </section>

        <!-- The 4 Main Types Grid -->
        <section>
            <div class="section-header">
                <h2>The 4 Pillars of SEO</h2>
            </div>

            <div class="types-grid">

                <!-- 1. On-Page SEO -->
                <article class="type-card">
                    <div class="card-icon">✦</div>
                    <h3>On-Page SEO</h3>
                    <p>Focuses on elements living directly on your site, tailoring every page for both human readers and search engine crawlers.</p>
                    <ul class="tag-list">
                        <li>Keyword Strategy</li>
                        <li>Engaging Copy</li>
                        <li>Meta Titles</li>
                        <li>Alt Text</li>
                    </ul>
                </article>

                <!-- 2. Off-Page SEO -->
                <article class="type-card">
                    <div class="card-icon">♡</div>
                    <h3>Off-Page SEO</h3>
                    <p>Activities outside your website that boost authority, trust, and digital reputation across the web.</p>
                    <ul class="tag-list">
                        <li>Quality Backlinks</li>
                        <li>Brand Mentions</li>
                        <li>Digital PR</li>
                        <li>Collaborations</li>
                    </ul>
                </article>

                <!-- 3. Technical SEO -->
                <article class="type-card">
                    <div class="card-icon">⚡</div>
                    <h3>Technical SEO</h3>
                    <p>Fine-tuning website architecture behind the scenes so search engines can crawl, index, and render pages effortlessly.</p>
                    <ul class="tag-list">
                        <li>Blazing Speed</li>
                        <li>Mobile-First</li>
                        <li>XML Sitemaps</li>
                        <li>SSL Encryption</li>
                    </ul>
                </article>

                <!-- 4. Local SEO -->
                <article class="type-card">
                    <div class="card-icon">📍</div>
                    <h3>Local SEO</h3>
                    <p>Optimizing your business to show up in neighborhood queries, regional searches, and interactive map packs.</p>
                    <ul class="tag-list">
                        <li>Google Business Profile</li>
                        <li>Customer Reviews</li>
                        <li>Local Citations</li>
                        <li>"Near Me" Queries</li>
                    </ul>
                </article>

            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer>
        <p>Crafted with elegance &bull; SEO Basics Guide &bull; 2026</p>
    </footer>

</body>
</html>
