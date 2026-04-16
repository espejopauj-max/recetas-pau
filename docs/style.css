/* ============================================================
   RecetasFáciles.com — style.css
   Diseño profesional para monetización AdSense + SEO
   ============================================================ */

/* === CSS VARIABLES === */
:root {
  --primary:    #e05c1a;
  --primary-dk: #b84910;
  --accent:     #f5a623;
  --dark:       #1a1208;
  --dark2:      #2d1f0a;
  --light:      #fffbf5;
  --light2:     #fdf3e7;
  --text:       #2d2010;
  --muted:      #7a6a55;
  --border:     #e8d5be;
  --card-shadow: 0 4px 24px rgba(0,0,0,0.09);
  --card-hover:  0 12px 40px rgba(224,92,26,0.18);
  --radius:     16px;
  --radius-sm:  10px;
  --font-display: 'Playfair Display', Georgia, serif;
  --font-body:    'DM Sans', system-ui, sans-serif;
  --transition:  0.3s cubic-bezier(0.4,0,0.2,1);
}

/* === RESET & BASE === */
*, *::before, *::after { box-sizing: border-box; }
html { scroll-behavior: smooth; }
body {
  font-family: var(--font-body);
  background: var(--light);
  color: var(--text);
  font-size: 1.05rem;
  line-height: 1.7;
}
img { max-width: 100%; }
a { text-decoration: none; color: inherit; }

/* Tipografía */
h1,h2,h3,h4,h5 { font-family: var(--font-display); }

/* === HIGHLIGHT === */
.highlight {
  color: var(--primary);
  position: relative;
}
.highlight::after {
  content: '';
  position: absolute;
  bottom: -2px; left: 0; right: 0;
  height: 3px;
  background: var(--accent);
  border-radius: 2px;
  opacity: .5;
}

/* ============================================================
   NAVBAR
   ============================================================ */
#mainNav {
  background: linear-gradient(135deg, var(--dark) 0%, var(--dark2) 100%);
  padding: 0.8rem 0;
  box-shadow: 0 2px 20px rgba(0,0,0,0.25);
  transition: var(--transition);
}
#mainNav.scrolled {
  padding: 0.5rem 0;
  background: rgba(26,18,8,0.97);
  backdrop-filter: blur(8px);
}
.navbar-brand {
  font-family: var(--font-display);
  font-size: 1.5rem;
  font-weight: 900;
  color: #fff !important;
  letter-spacing: -0.5px;
}
.navbar-brand i { color: var(--accent); }
.nav-link {
  font-weight: 500;
  color: rgba(255,255,255,0.85) !important;
  padding: 0.5rem 1rem !important;
  border-radius: 8px;
  transition: var(--transition);
}
.nav-link:hover, .nav-link.active {
  color: #fff !important;
  background: rgba(255,255,255,0.12);
}

/* ============================================================
   ADS (AdSense placeholders)
   ============================================================ */
.ad-banner { background: var(--light2); border-bottom: 1px solid var(--border); padding: 8px 0; }
.ad-top .ad-block { max-width: 728px; margin: 0 auto; }
.ad-block {
  background: linear-gradient(135deg, #fff8f0 0%, #fff3e5 100%);
  border: 1.5px dashed var(--accent);
  color: var(--muted);
  font-size: 0.82rem;
  font-weight: 600;
  letter-spacing: 0.03em;
  text-transform: uppercase;
  border-radius: var(--radius-sm);
  display: flex; align-items: center; justify-content: center;
  min-height: 90px;
  transition: var(--transition);
}
.ad-block:hover { border-color: var(--primary); color: var(--primary); }
.ad-horizontal { min-height: 90px; }
.ad-inline { min-height: 90px; margin: 0.5rem 0; }
.ad-inline-alt { min-height: 250px; max-width: 300px; margin: 0 auto; }
.ad-sidebar { min-height: 300px; border-radius: var(--radius); }
.ad-footer-wrap { background: var(--light2); border-top: 1px solid var(--border); padding: 12px 0; }
.ad-recipe { min-height: 90px; margin: 2rem 0; }
.ad-recipe-mid { min-height: 250px; max-width: 300px; margin: 2rem auto; }

/* ============================================================
   HERO
   ============================================================ */
.hero-section {
  position: relative;
  background: url('https://images.unsplash.com/photo-1543353071-087092ec393a?w=1400&q=80') center/cover no-repeat;
  min-height: 25vh;
  display: flex; align-items: center;
  overflow: hidden;
}
.hero-overlay {
  position: absolute; inset: 0;
  background: linear-gradient(135deg, rgba(26,18,8,0.88) 0%, rgba(60,30,10,0.70) 50%, rgba(224,92,26,0.30) 100%);
}
.min-vh-75 { min-height: 75vh; }
.hero-badge {
  display: inline-flex; align-items: center;
  background: rgba(245,166,35,0.18);
  color: var(--accent);
  border: 1px solid rgba(245,166,35,0.4);
  border-radius: 50px;
  padding: 6px 18px;
  font-size: 0.85rem;
  font-weight: 600;
  letter-spacing: 0.05em;
  text-transform: uppercase;
  margin-bottom: 1.2rem;
  backdrop-filter: blur(4px);
}
.hero-title {
  font-size: clamp(2rem, 5vw, 3.4rem);
  font-weight: 900;
  color: #fff;
  line-height: 1.15;
  margin-bottom: 1.2rem;
}
.hero-subtitle {
  font-size: 1.15rem;
  color: rgba(255,255,255,0.85);
  max-width: 560px;
  margin-bottom: 2rem;
}
.btn-hero {
  background: var(--primary);
  border-color: var(--primary);
  font-weight: 600;
  border-radius: 50px;
  padding: 14px 32px;
  box-shadow: 0 4px 20px rgba(224,92,26,0.4);
  transition: var(--transition);
}
.btn-hero:hover {
  background: var(--primary-dk);
  transform: translateY(-2px);
  box-shadow: 0 8px 30px rgba(224,92,26,0.5);
}
.hero-stats {
  display: flex; gap: 2rem;
}
.stat { display: flex; flex-direction: column; }
.stat-num {
  font-family: var(--font-display);
  font-size: 1.8rem;
  font-weight: 900;
  color: var(--accent);
  line-height: 1;
}
.stat-label { font-size: 0.8rem; color: rgba(255,255,255,0.6); text-transform: uppercase; letter-spacing: 0.05em; }

/* Hero image */
.hero-img-wrap {
  position: relative;
  display: inline-block;
}
.hero-img {
  width: 420px;
  height: 420px;
  object-fit: cover;
  border-radius: 30px 60px 30px 60px;
  box-shadow: 0 20px 60px rgba(0,0,0,0.4);
  border: 4px solid rgba(255,255,255,0.15);
}
.floating-badge {
  position: absolute;
  background: rgba(255,255,255,0.95);
  color: var(--text);
  font-size: 0.8rem;
  font-weight: 700;
  padding: 8px 16px;
  border-radius: 50px;
  box-shadow: 0 4px 16px rgba(0,0,0,0.15);
  animation: float 3s ease-in-out infinite;
}
.fb1 { top: 20px; left: -30px; animation-delay: 0s; }
.fb2 { bottom: 40px; right: -20px; animation-delay: 1.5s; }
@keyframes float {
  0%, 100% { transform: translateY(0); }
  50% { transform: translateY(-8px); }
}

/* ============================================================
   BREADCRUMB BAR
   ============================================================ */
.breadcrumb-bar {
  background: var(--light2);
  border-bottom: 1px solid var(--border);
  padding: 10px 0;
}
.breadcrumb { font-size: 0.85rem; }
.breadcrumb-item a { color: var(--primary); }
.breadcrumb-item.active { color: var(--muted); }
.breadcrumb-item+.breadcrumb-item::before { color: var(--muted); }

/* ============================================================
   CATEGORIES
   ============================================================ */
.categories-section { padding: 1.2rem 0; border-bottom: 1px solid var(--border); }
.categories-row { display: flex; gap: 0.6rem; flex-wrap: wrap; }
.cat-pill {
  display: inline-flex; align-items: center;
  padding: 8px 18px;
  border-radius: 50px;
  border: 1.5px solid var(--border);
  font-size: 0.85rem;
  font-weight: 500;
  color: var(--muted);
  background: #fff;
  transition: var(--transition);
  cursor: pointer;
}
.cat-pill:hover, .cat-pill.active {
  background: var(--primary);
  border-color: var(--primary);
  color: #fff;
  transform: translateY(-1px);
  box-shadow: 0 4px 12px rgba(224,92,26,0.25);
}

/* ============================================================
   SECTION HEADERS
   ============================================================ */
.section-tag {
  display: inline-block;
  background: rgba(224,92,26,0.10);
  color: var(--primary);
  padding: 5px 16px;
  border-radius: 50px;
  font-size: 0.8rem;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  margin-bottom: 0.8rem;
}
.section-title {
  font-size: clamp(1.6rem, 4vw, 2.4rem);
  font-weight: 900;
  margin-bottom: 0.5rem;
  line-height: 1.2;
}
.section-subtitle { color: var(--muted); font-size: 1.05rem; max-width: 600px; margin: 0 auto; }

/* ============================================================
   RECIPES SECTION
   ============================================================ */
.recipes-section { padding: 5rem 0; }

/* === RECIPE CARDS === */
.recipe-card {
  background: #fff;
  border-radius: var(--radius);
  overflow: hidden;
  box-shadow: var(--card-shadow);
  transition: var(--transition);
  display: flex; flex-direction: column;
  border: 1px solid var(--border);
}
.recipe-card:hover {
  transform: translateY(-6px);
  box-shadow: var(--card-hover);
  border-color: rgba(224,92,26,0.2);
}
.recipe-card-featured .recipe-img { height: 300px; }

.recipe-img-wrap { position: relative; overflow: hidden; }
.recipe-img {
  width: 100%; height: 220px;
  object-fit: contain;
  background: #fff8f5;
  transition: transform 0.5s ease;
  display: block;
}
.recipe-card:hover .recipe-img { transform: scale(1.05); }

/* Badges */
.recipe-badge {
  position: absolute; top: 12px; left: 12px;
  background: var(--primary);
  color: #fff;
  font-size: 0.72rem;
  font-weight: 700;
  padding: 5px 12px;
  border-radius: 50px;
  text-transform: uppercase;
  letter-spacing: 0.05em;
}
.badge-new { background: #2563eb; }
.badge-green { background: #16a34a; }
.badge-orange { background: #ea580c; }
.badge-pink { background: #db2777; }
.badge-gold { background: linear-gradient(135deg, #b45309, #d97706); }

.recipe-time {
  position: absolute; top: 12px; right: 12px;
  background: rgba(0,0,0,0.65);
  color: #fff;
  font-size: 0.75rem;
  font-weight: 600;
  padding: 5px 10px;
  border-radius: 50px;
  backdrop-filter: blur(4px);
}

/* Body */
.recipe-body {
  padding: 1.4rem;
  display: flex; flex-direction: column;
  flex: 1;
}
.recipe-meta { display: flex; gap: 0.5rem; margin-bottom: 0.8rem; }
.meta-tag {
  font-size: 0.75rem;
  background: var(--light2);
  color: var(--muted);
  padding: 3px 10px;
  border-radius: 50px;
  font-weight: 600;
  border: 1px solid var(--border);
}
.recipe-title {
  font-size: 1.1rem;
  font-weight: 700;
  margin-bottom: 0.6rem;
  line-height: 1.35;
  color: var(--text);
}
.recipe-desc {
  font-size: 0.9rem;
  color: var(--muted);
  line-height: 1.6;
  flex: 1;
  margin-bottom: 1.2rem;
}

/* === COMPACT RECIPE CARDS === */
.recipe-card-compact { background: #fff; border-radius: 12px; overflow: hidden; box-shadow: 0 2px 12px rgba(0,0,0,0.08); }
.recipe-card-compact:hover { transform: translateY(-4px); box-shadow: 0 8px 24px rgba(224,92,26,0.15); }
.recipe-card-compact .recipe-img { height: 160px; object-fit: contain; background: #fff8f5; }
.recipe-body-compact { padding: 1rem; }
.recipe-title-compact { font-size: 0.95rem; font-weight: 700; line-height: 1.3; margin-bottom: 0.6rem; color: var(--text); }
.recipe-ingredients-compact { display: flex; flex-wrap: wrap; gap: 0.4rem; margin-bottom: 0.8rem; }
.ingredient-tag {
  font-size: 0.7rem;
  background: var(--light2);
  color: var(--muted);
  padding: 3px 8px;
  border-radius: 20px;
  font-weight: 600;
  border: 1px solid var(--border);
}
.btn-recipe-compact { width: 100%; padding: 0.5rem; font-size: 0.85rem; }
}
.btn-recipe {
  background: linear-gradient(135deg, var(--primary) 0%, var(--primary-dk) 100%);
  color: #fff;
  border: none;
  border-radius: 50px;
  padding: 10px 22px;
  font-weight: 600;
  font-size: 0.9rem;
  transition: var(--transition);
  text-align: center;
  width: 100%;
}
.btn-recipe:hover {
  color: #fff;
  transform: translateY(-2px);
  box-shadow: 0 6px 20px rgba(224,92,26,0.35);
  background: linear-gradient(135deg, var(--primary-dk) 0%, var(--primary) 100%);
}

/* ============================================================
   POPULAR SECTION
   ============================================================ */
.popular-section { background: var(--light2); padding: 5rem 0; border-top: 1px solid var(--border); border-bottom: 1px solid var(--border); }
.popular-list { display: flex; flex-direction: column; gap: 0.6rem; }
.popular-item {
  display: flex; align-items: center;
  background: #fff;
  border-radius: var(--radius-sm);
  padding: 1rem 1.2rem;
  gap: 1rem;
  border: 1px solid var(--border);
  transition: var(--transition);
  color: var(--text);
}
.popular-item:hover {
  border-color: var(--primary);
  box-shadow: var(--card-shadow);
  transform: translateX(4px);
}
.pop-num {
  font-family: var(--font-display);
  font-size: 1.4rem;
  font-weight: 900;
  color: var(--border);
  min-width: 40px;
}
.popular-item:hover .pop-num { color: var(--primary); }
.popular-item img { width: 60px; height: 60px; object-fit: cover; border-radius: 10px; flex-shrink: 0; }
.pop-info { flex: 1; }
.pop-info strong { display: block; font-weight: 600; font-size: 0.95rem; }
.pop-info span { font-size: 0.8rem; color: var(--muted); }
.pop-arrow { color: var(--muted); transition: var(--transition); }
.popular-item:hover .pop-arrow { color: var(--primary); transform: translateX(3px); }

/* ============================================================
   NEWSLETTER
   ============================================================ */
.newsletter-section { padding: 5rem 0; }
.newsletter-box {
  background: linear-gradient(135deg, var(--dark) 0%, var(--dark2) 50%, #3d1f00 100%);
  border-radius: 24px;
  padding: 3rem;
  color: #fff;
}
.newsletter-title { font-size: clamp(1.4rem, 3vw, 2rem); font-weight: 900; }
.newsletter-box p { color: rgba(255,255,255,0.75); }
.newsletter-box .section-tag { background: rgba(245,166,35,0.2); color: var(--accent); border: 1px solid rgba(245,166,35,0.3); }
.newsletter-box .form-control {
  background: rgba(255,255,255,0.1);
  border-color: rgba(255,255,255,0.2);
  color: #fff;
}
.newsletter-box .form-control::placeholder { color: rgba(255,255,255,0.5); }
.newsletter-box .form-control:focus {
  background: rgba(255,255,255,0.15);
  border-color: var(--accent);
  box-shadow: none;
  color: #fff;
}

/* ============================================================
   FOOTER
   ============================================================ */
.site-footer { background: var(--dark); color: rgba(255,255,255,0.75); }
.footer-logo {
  font-family: var(--font-display);
  font-size: 1.4rem;
  font-weight: 900;
  color: #fff;
  display: block;
  margin-bottom: 1rem;
}
.footer-logo i { color: var(--accent); }
.footer-desc { font-size: 0.88rem; color: rgba(255,255,255,0.55); line-height: 1.6; }
.footer-title { font-family: var(--font-display); font-size: 1rem; font-weight: 700; color: #fff; margin-bottom: 1rem; }
.footer-links { list-style: none; padding: 0; margin: 0; }
.footer-links li { margin-bottom: 0.5rem; }
.footer-links a {
  color: rgba(255,255,255,0.55);
  font-size: 0.88rem;
  transition: var(--transition);
}
.footer-links a:hover { color: var(--accent); padding-left: 4px; }
.social-links { display: flex; gap: 0.6rem; margin-top: 1rem; }
.social-links a {
  width: 38px; height: 38px;
  display: flex; align-items: center; justify-content: center;
  background: rgba(255,255,255,0.08);
  border-radius: 50%;
  color: rgba(255,255,255,0.7);
  font-size: 1rem;
  transition: var(--transition);
}
.social-links a:hover { background: var(--primary); color: #fff; transform: translateY(-3px); }
.footer-hr { border-color: rgba(255,255,255,0.1); margin: 2rem 0 1rem; }
.footer-bottom { font-size: 0.8rem; color: rgba(255,255,255,0.35); text-align: center; }

/* ============================================================
   RECIPE PAGE STYLES
   ============================================================ */
.recipe-page-hero {
  height: 480px;
  background-size: cover;
  background-position: center;
  position: relative;
  display: flex; align-items: flex-end;
}
.recipe-page-hero::before {
  content: '';
  position: absolute; inset: 0;
  background: linear-gradient(0deg, rgba(26,18,8,0.95) 0%, rgba(26,18,8,0.3) 60%, transparent 100%);
}
.recipe-hero-content {
  position: relative; z-index: 1;
  color: #fff;
  padding-bottom: 2.5rem;
}
.recipe-hero-content h1 { font-size: clamp(1.8rem, 4vw, 2.8rem); font-weight: 900; line-height: 1.15; }
.recipe-quick-stats {
  display: flex; flex-wrap: wrap; gap: 1rem;
  margin-top: 1rem;
}
.qs { display: flex; align-items: center; gap: 0.4rem; font-size: 0.9rem; color: rgba(255,255,255,0.85); }
.qs i { color: var(--accent); }

/* Recipe body layout */
.recipe-page { padding: 3rem 0; }
.recipe-main { max-width: 760px; }
.recipe-sidebar { position: sticky; top: 80px; }

/* Intro text */
.recipe-intro { font-size: 1.08rem; line-height: 1.9; color: #3a2a15; margin-bottom: 2rem; }

/* Ingredients */
.ingredients-card {
  background: var(--light2);
  border-radius: var(--radius);
  padding: 1.8rem;
  margin-bottom: 2rem;
  border: 1px solid var(--border);
}
.ingredients-card h2 { font-size: 1.4rem; margin-bottom: 1rem; }
.ingredient-list { list-style: none; padding: 0; margin: 0; }
.ingredient-list li {
  display: flex; align-items: center;
  padding: 0.6rem 0;
  border-bottom: 1px solid var(--border);
  font-size: 0.95rem;
}
.ingredient-list li:last-child { border-bottom: none; }
.ingredient-list li::before {
  content: '✓';
  background: var(--primary);
  color: #fff;
  width: 22px; height: 22px;
  border-radius: 50%;
  display: flex; align-items: center; justify-content: center;
  font-size: 0.7rem;
  font-weight: 700;
  margin-right: 0.8rem;
  flex-shrink: 0;
}

/* Steps */
.steps-section h2 { font-size: 1.4rem; margin-bottom: 1.5rem; }
.step-item {
  display: flex; gap: 1.2rem;
  margin-bottom: 2rem;
  padding-bottom: 2rem;
  border-bottom: 1px solid var(--border);
}
.step-item:last-child { border-bottom: none; }
.step-num {
  background: var(--primary);
  color: #fff;
  font-family: var(--font-display);
  font-size: 1.2rem;
  font-weight: 900;
  width: 46px; height: 46px;
  border-radius: 50%;
  display: flex; align-items: center; justify-content: center;
  flex-shrink: 0;
  box-shadow: 0 4px 12px rgba(224,92,26,0.3);
}
.step-content h3 { font-size: 1.05rem; font-weight: 700; margin-bottom: 0.4rem; }
.step-content p { font-size: 0.95rem; color: var(--muted); line-height: 1.7; margin: 0; }

/* Tips */
.tips-card {
  background: linear-gradient(135deg, #fff7ed 0%, #fff3e0 100%);
  border-radius: var(--radius);
  padding: 2rem;
  border: 1px solid #fed7aa;
  margin-bottom: 2rem;
}
.tips-card h2 { font-size: 1.3rem; color: var(--primary-dk); margin-bottom: 1rem; }
.tips-list { list-style: none; padding: 0; margin: 0; }
.tips-list li { padding: 0.5rem 0 0.5rem 1.8rem; position: relative; font-size: 0.95rem; }
.tips-list li::before { content: '💡'; position: absolute; left: 0; }

/* FAQ */
.faq-section { margin-bottom: 2rem; }
.faq-section h2 { font-size: 1.4rem; margin-bottom: 1.2rem; }
.accordion-button:not(.collapsed) { background: var(--light2); color: var(--primary); box-shadow: none; }
.accordion-button:focus { box-shadow: none; }
.accordion-item { border-color: var(--border); margin-bottom: 0.5rem; border-radius: var(--radius-sm) !important; overflow: hidden; }
.accordion-button { font-weight: 600; font-size: 0.95rem; }

/* Related recipes */
.related-section { padding: 3rem 0; background: var(--light2); border-top: 1px solid var(--border); }
.related-section h2 { font-size: 1.6rem; margin-bottom: 2rem; }

/* Schema rating */
.recipe-rating { display: flex; align-items: center; gap: 0.5rem; margin-bottom: 0.5rem; }
.stars { color: #f59e0b; font-size: 1.1rem; }
.rating-count { color: rgba(255,255,255,0.6); font-size: 0.85rem; }

/* Print button */
.btn-print { border-color: var(--border); color: var(--muted); }
.btn-print:hover { border-color: var(--primary); color: var(--primary); }

/* Jump links */
.jump-links { background: var(--light2); border-radius: var(--radius); padding: 1.2rem 1.5rem; margin-bottom: 2rem; border: 1px solid var(--border); }
.jump-links h6 { font-size: 0.75rem; text-transform: uppercase; letter-spacing: 0.08em; color: var(--muted); margin-bottom: 0.6rem; }
.jump-links ul { list-style: none; padding: 0; margin: 0; display: flex; flex-wrap: wrap; gap: 0.4rem; }
.jump-links ul li a {
  display: inline-block;
  padding: 5px 14px;
  background: #fff;
  border: 1px solid var(--border);
  border-radius: 50px;
  font-size: 0.82rem;
  color: var(--text);
  transition: var(--transition);
}
.jump-links ul li a:hover { border-color: var(--primary); color: var(--primary); }

/* Sidebar card */
.sidebar-card {
  background: #fff;
  border-radius: var(--radius);
  padding: 1.5rem;
  border: 1px solid var(--border);
  margin-bottom: 1.5rem;
  box-shadow: var(--card-shadow);
}
.sidebar-card h5 { font-size: 1rem; font-weight: 700; margin-bottom: 1rem; padding-bottom: 0.6rem; border-bottom: 2px solid var(--primary); display: inline-block; }

/* ============================================================
   ANIMATIONS
   ============================================================ */
@keyframes fadeInUp {
  from { opacity: 0; transform: translateY(30px); }
  to   { opacity: 1; transform: translateY(0); }
}
[data-aos="fade-up"] {
  opacity: 0;
  animation: fadeInUp 0.6s ease forwards;
}
[data-aos-delay="50"]  { animation-delay: 0.05s; }
[data-aos-delay="100"] { animation-delay: 0.10s; }

/* ============================================================
   RESPONSIVE
   ============================================================ */
@media (max-width: 991px) {
  .hero-section { min-height: 70vh; }
  .hero-stats { gap: 1.2rem; }
}
@media (max-width: 767px) {
  .hero-title { font-size: 2rem; }
  .hero-stats { gap: 1rem; }
  .stat-num { font-size: 1.4rem; }
  .newsletter-box { padding: 2rem 1.2rem; }
  .recipe-page-hero { height: 320px; }
}
@media (max-width: 575px) {
  .recipes-section { padding: 3rem 0; }
  .popular-section { padding: 3rem 0; }
}
