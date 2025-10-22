<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="VsalesDigital — Dropshipping Mentor: Helping new dropshippers launch a successful dropshipping business." />
  <title>VsalesDigital — Dropshipping Mentor</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    /* Theme */
    :root{--bg:#ffffff;--fg:#000000;--muted:#6b7280;--card:#f7f7f7}
    body{background:var(--bg);color:var(--fg);font-family:Inter,ui-sans-serif,system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial;}

    /* Header */
    header{transition:all .28s ease;z-index:60}
    header.sticky{position:fixed;top:0;left:0;right:0;background:rgba(255,255,255,0.95);backdrop-filter:blur(6px);box-shadow:0 6px 20px rgba(0,0,0,0.06)}
    header.shrink .logo-mark{transform:scale(.86)}
    header .logo-mark{transition:transform .28s ease}

    /* Animations */
    .fade-in{opacity:0;transform:translateY(18px);animation:fadeInUp .9s ease .15s forwards}
    @keyframes fadeInUp{to{opacity:1;transform:none}}
    .hero-zoom{transform:scale(1.03);transition:transform 6s ease}
    .hero-zoom:hover{transform:scale(1.06)}

    /* Buttons */
    .btn-black{background:#000;color:#fff}
    .btn-black:hover{background:#111}

    /* Responsive container tweak */
    .container{max-width:1100px;margin-left:auto;margin-right:auto;padding-left:1rem;padding-right:1rem}

    /* Minor card style */
    .card{background:var(--card)}
  </style>
</head>
<body class="leading-relaxed">
  <!-- Header -->
  <header id="siteHeader" class="py-4">
    <div class="container flex items-center justify-between">
      <div class="flex items-center gap-3 logo-mark">
        <div class="w-12 h-12 bg-black text-white rounded-full flex items-center justify-center font-bold text-lg">VS</div>
        <div>
          <h1 class="text-lg font-bold">VsalesDigital</h1>
          <p class="text-xs text-gray-500">Dropshipping Mentor</p>
        </div>
      </div>
      <nav class="hidden md:flex items-center gap-6 text-sm text-gray-700">
        <a href="#about" class="hover:text-black">About</a>
        <a href="#services" class="hover:text-black">What I Teach</a>
        <a href="#proof" class="hover:text-black">Proof</a>
        <a href="#testimonials" class="hover:text-black">Testimonials</a>
        <a href="#contact" class="hover:text-black">Contact</a>
      </nav>
      <div class="md:hidden"></div>
    </div>
  </header>

  <!-- Hero -->
  <main>
    <section class="container grid md:grid-cols-2 gap-10 items-center pt-24 pb-14">
      <div class="fade-in">
        <p class="text-sm text-gray-600 font-medium">Trusted Dropshipping Mentor</p>
        <h2 class="text-4xl md:text-5xl font-extrabold mt-3">Helping new dropshippers launch a successful business</h2>
        <p class="mt-4 text-gray-700 max-w-xl">At VsalesDigital we turn curiosity into consistent sales. We teach practical product research, conversion-first store design, and ad strategies that scale — all backed by real student results and hands-on mentoring.</p>
        <div class="mt-6 flex gap-3">
          <a href="#contact" class="btn-black px-5 py-3 rounded-md font-semibold shadow">Work With Me</a>
          <a href="#proof" class="px-5 py-3 rounded-md border border-black font-semibold hover:bg-black hover:text-white transition">See Student Results</a>
        </div>
        <div class="mt-6 text-sm text-gray-600">Email: <a href="mailto:vsalesdigital2@gmail.com" class="text-black">vsalesdigital2@gmail.com</a></div>
      </div>

      <div class="overflow-hidden rounded-2xl shadow card hero-zoom">
        <img src="https://picsum.photos/900/600?seed=mentor-hero" alt="VsalesDigital mentor" class="w-full h-full object-cover object-center" />
      </div>
    </section>

    <!-- About -->
    <section id="about" class="container py-12">
      <div class="bg-white card rounded-2xl p-8 shadow">
        <h3 class="text-2xl font-bold">About VsalesDigital</h3>
        <div class="mt-4 grid md:grid-cols-2 gap-6">
          <div>
            <p class="text-gray-700">VsalesDigital started as a simple experiment — late nights, small ad budgets, and a stubborn refusal to accept mediocre results. Over time, the experiments turned into repeatable systems: product research that actually predicts demand, store setups that convert, and ad tests that reveal winners quickly.</p>
            <p class="mt-4 text-gray-700">Today, VsalesDigital helps beginners turn their first ideas into profitable Shopify stores. We focus on practical steps, mindset, and community support — the three ingredients that speed up success and reduce costly mistakes.</p>
          </div>
          <div>
            <h4 class="font-semibold">Our Approach</h4>
            <ul class="mt-3 text-gray-700 list-disc list-inside space-y-2">
              <li>Hands-on mentorship: real feedback during launches</li>
              <li>Data-first product research: minimize risk, maximize returns</li>
              <li>Conversion-led store design: pages that build trust</li>
              <li>Scaling with systems: profitable growth without burnout</li>
            </ul>
            <blockquote class="mt-6 p-4 border-l-4 border-black italic text-gray-700">"We believe success in dropshipping starts with belief, guidance, and consistent action."</blockquote>
          </div>
        </div>
      </div>
    </section>

    <!-- Services -->
    <section id="services" class="container py-12">
      <h3 class="text-2xl font-bold">What I Teach</h3>
      <p class="text-gray-700 mt-2">A practical curriculum built to get stores selling quickly and scaling sustainably.</p>
      <div class="mt-6 grid md:grid-cols-3 gap-6">
        <div class="p-6 card rounded-xl shadow">
          <h4 class="font-semibold text-lg">Winning Product Research</h4>
          <p class="mt-2 text-gray-700 text-sm">Data-backed product discovery and validation processes that reduce guesswork.</p>
        </div>
        <div class="p-6 card rounded-xl shadow">
          <h4 class="font-semibold text-lg">High-Converting Stores</h4>
          <p class="mt-2 text-gray-700 text-sm">Store layouts, copy, and trust elements optimized for conversion.</p>
        </div>
        <div class="p-6 card rounded-xl shadow">
          <h4 class="font-semibold text-lg">Ads & Creatives</h4>
          <p class="mt-2 text-gray-700 text-sm">Ad testing frameworks and creative templates for Facebook and TikTok.</p>
        </div>
      </div>

      <div class="mt-6 grid md:grid-cols-2 gap-6">
        <div class="p-6 card rounded-xl shadow">
          <h4 class="font-semibold text-lg">Analytics & Scaling</h4>
          <p class="mt-2 text-gray-700 text-sm">How to read performance data, optimize ROAS and scale sustainably.</p>
        </div>
        <div class="p-6 card rounded-xl shadow">
          <h4 class="font-semibold text-lg">Automation & Fulfillment</h4>
          <p class="mt-2 text-gray-700 text-sm">Supplier management, order automation and lean operations.</p>
        </div>
      </div>
    </section>

    <!-- Proof -->
    <section id="proof" class="container py-12 bg-gray-50 rounded-2xl">
      <h3 class="text-2xl font-bold">Student Results & Shopify Proof</h3>
      <p class="text-gray-700 mt-2">Below are placeholder screenshots representing typical Shopify dashboards and results my students have achieved. Replace with real screenshots for maximum credibility.</p>
      <div class="mt-6 grid md:grid-cols-3 gap-6">
        <div class="rounded-xl overflow-hidden shadow card">
          <img src="https://picsum.photos/600/360?seed=shop1" alt="Sales screenshot 1" class="w-full h-40 object-cover" />
          <div class="p-4">
            <h4 class="font-semibold">$12,450 Total Sales</h4>
            <p class="text-sm text-gray-600 mt-1">Sold in 14 days — multiple winning products. (Placeholder)</p>
          </div>
        </div>
        <div class="rounded-xl overflow-hidden shadow card">
          <img src="https://picsum.photos/600/360?seed=shop2" alt="Sales screenshot 2" class="w-full h-40 object-cover" />
          <div class="p-4">
            <h4 class="font-semibold">$8,320 First Week</h4>
            <p class="text-sm text-gray-600 mt-1">High-margin SKUs + scaled ads. (Placeholder)</p>
          </div>
        </div>
        <div class="rounded-xl overflow-hidden shadow card">
          <img src="https://picsum.photos/600/360?seed=shop3" alt="Sales screenshot 3" class="w-full h-40 object-cover" />
          <div class="p-4">
            <h4 class="font-semibold">$4,900 Profitable Month</h4>
            <p class="text-sm text-gray-600 mt-1">Sustainable ROAS after optimizations. (Placeholder)</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Testimonials -->
    <section id="testimonials" class="container py-12">
      <h3 class="text-2xl font-bold">Student Testimonials</h3>
      <div class="mt-6 grid md:grid-cols-3 gap-6">
        <div class="p-6 card rounded-xl shadow">
          <p class="text-gray-700">“VsalesDigital gave me a clear launch plan and the support I needed to hit my first profitable month. Highly recommend for beginners.”</p>
          <p class="mt-4 text-sm text-gray-500">— L. Student</p>
        </div>
        <div class="p-6 card rounded-xl shadow">
          <p class="text-gray-700">“Practical, honest, and results-focused mentorship. The ad testing system saved me weeks of mistakes.”</p>
          <p class="mt-4 text-sm text-gray-500">— M. Student</p>
        </div>
        <div class="p-6 card rounded-xl shadow">
          <p class="text-gray-700">“From product research to scaling, every step is actionable. The community support is the icing on the cake.”</p>
          <p class="mt-4 text-sm text-gray-500">— A. Student</p>
        </div>
      </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="container py-12 bg-white card rounded-2xl shadow">
      <div class="grid md:grid-cols-2 gap-6 items-center">
        <div>
          <h3 class="text-2xl font-bold">Work with VsalesDigital</h3>
          <p class="text-gray-700 mt-2">Ready to start your dropshipping journey? Book a free call and let's create a plan that gets you results.</p>
          <div class="mt-6">
            <a href="mailto:vsalesdigital@gmail.com" class="btn-black px-6 py-3 rounded-md font-semibold shadow">Email vsalesdigital@gmail.com</a>
          </div>
        </div>
        <div class="text-sm text-gray-700">
          <h4 class="font-semibold">Follow & Contact</h4>
          <ul class="mt-3 space-y-2">
            <li>Email: <a href="mailto:vsalesdigital@gmail.com" class="text-black">vsalesdigital@gmail.com</a></li>
            <li>Discord: share your invite link here</li>
            <li>Instagram: @henrymark6</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="container text-center py-8 text-gray-500 text-sm">
      <p>© <span id="year"></span> VsalesDigital — Dropshipping Mentor. All rights reserved.</p>
    </footer>
  </main>

  <script>
    // Fill year
    document.getElementById('year').textContent = new Date().getFullYear();

    // Sticky header with shrink
    const header = document.getElementById('siteHeader');
    const offset = 80;
    window.addEventListener('scroll', () => {
      if (window.scrollY > offset) {
        header.classList.add('sticky');
        header.classList.add('shrink');
      } else {
        header.classList.remove('sticky');
        header.classList.remove('shrink');
      }
    });

    // Simple fade-in for logo and nav links
    window.addEventListener('DOMContentLoaded', () => {
      document.querySelectorAll('.fade-in').forEach((el, i) => {
        el.style.animationDelay = (i * 120) + 'ms';
      });
    });
  </script>
</body>
</html>
