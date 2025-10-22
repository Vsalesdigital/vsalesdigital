
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="VsalesDigital — Dropshipping Mentor: Helping new dropshippers launch a successful dropshipping business." />
  <title>VsalesDigital — Dropshipping Mentor</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    :root{--bg:#000;--fg:#fff;--muted:#9ca3af;--card:#0b0b0b}
    html,body{height:100%}
    body{background:var(--bg);color:var(--fg);font-family:Inter,ui-sans-serif,system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial;margin:0}
    .container{max-width:1100px;margin:0 auto;padding:0 1rem}

    /* Header */
    header{transition:all .28s ease;z-index:60}
    header.sticky{position:fixed;top:0;left:0;right:0;background:rgba(0,0,0,0.92);backdrop-filter:blur(6px);box-shadow:0 6px 20px rgba(0,0,0,0.6)}
    header.shrink .logo-mark{transform:scale(.86)}
    header .logo-mark{transition:transform .28s ease}

    /* Animations */
    .fade-in{opacity:0;transform:translateY(18px);animation:fadeInUp .9s ease .15s forwards}
    @keyframes fadeInUp{to{opacity:1;transform:none}}
    .hero-zoom{transform:scale(1.02);transition:transform 6s ease}
    .hero-zoom:hover{transform:scale(1.06)}

    /* Hero agency background (use exact file: assets/Capture.JPG) */
    .hero-hero{background:linear-gradient(180deg,rgba(0,0,0,0.65),rgba(0,0,0,0.35)),url('assets/Capture.JPG') center/cover no-repeat;color:#fff;padding:6rem 0}

    /* Buttons */
    .btn-white{background:#fff;color:#000;font-weight:600;border-radius:8px;padding:.6rem 1rem;display:inline-block}
    .btn-white:hover{opacity:.95}

    /* Service cards with image overlay */
    .service-card{position:relative;height:260px;border-radius:14px;overflow:hidden;display:flex;align-items:flex-end}
    .service-card .overlay{position:absolute;inset:0;background:linear-gradient(180deg,rgba(0,0,0,0.12),rgba(0,0,0,0.6));}
    .service-card .content{position:relative;z-index:2;padding:1.25rem}

    /* Modal */
    .modal-backdrop{position:fixed;inset:0;background:rgba(0,0,0,0.75);display:none;align-items:center;justify-content:center;z-index:90}
    .modal{background:var(--card);color:var(--fg);max-width:760px;width:95%;border-radius:12px;padding:1.25rem}

    /* Signup popup */
    .signup-badge{position:fixed;right:20px;bottom:20px;background:#0f0f0f;border:1px solid #222;padding:10px 14px;border-radius:10px;box-shadow:0 8px 30px rgba(0,0,0,0.6);z-index:80}

    /* Packages */
    .price-card{background:linear-gradient(180deg,rgba(255,255,255,0.03),rgba(255,255,255,0.01));border:1px solid rgba(255,255,255,0.04);padding:1.25rem;border-radius:12px}
    .price-card .price{font-size:1.6rem;font-weight:700}

    @media (max-width:768px){.service-card{height:200px}}
  </style>
</head>
<body class="leading-relaxed">
  <!-- Header -->
  <header id="siteHeader" class="py-4">
    <div class="container flex items-center justify-between">
      <div class="flex items-center gap-3 logo-mark">
        <!-- Inline SVG logo (no external file needed) -->
        <div aria-hidden="true" style="width:56px;height:56px;border-radius:12px;background:linear-gradient(135deg,#111,#222);display:flex;align-items:center;justify-content:center;box-shadow:0 6px 20px rgba(0,0,0,0.6)">
          <svg width="36" height="36" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="VsalesDigital logo">
            <rect width="100" height="100" rx="18" fill="#fff" fill-opacity="0" />
            <path d="M18 78 L36 22 L54 78 Z" fill="#fff" opacity="0.95" />
            <text x="60" y="72" fill="#fff" font-family="Verdana" font-size="18" font-weight="700">VS</text>
          </svg>
        </div>
        <div>
          <h1 class="text-lg font-bold">VsalesDigital</h1>
          <p class="text-xs text-gray-400">Dropshipping Mentor</p>
        </div>
      </div>
      <nav class="hidden md:flex items-center gap-6 text-sm text-gray-300">
        <a href="#about" class="hover:text-white">About</a>
        <a href="#services" class="hover:text-white">What I Teach</a>
        <a href="#packages" class="hover:text-white">Packages</a>
        <a href="#proof" class="hover:text-white">Proof</a>
        <a href="#contact" class="hover:text-white">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <main>
    <section class="hero-hero">
      <div class="container grid md:grid-cols-2 gap-10 items-center">
        <div class="fade-in">
          <p class="text-sm text-green-300 font-medium">Trusted Dropshipping Mentor</p>
          <h2 class="text-4xl md:text-5xl font-extrabold mt-3">Helping new dropshippers launch a successful business</h2>
          <p class="mt-4 max-w-xl text-gray-200">VsalesDigital combines hands-on mentorship with data-driven systems to help students find winning products, build conversion-first stores, and scale ads sustainably. Real results. Real speed. Real mentorship.</p>
          <div class="mt-6 flex gap-3">
            <a href="#contact" class="btn-white">Work With Me</a>
            <button onclick="openModal('signupModal')" class="btn-white">Get Free Mentorship</button>
          </div>
          <div class="mt-6 text-sm text-gray-300">Email: <a href="mailto:vsalesdigital@gmail.com" class="text-white underline">vsalesdigital@gmail.com</a> • Instagram: <a href="https://instagram.com/henrymak6" target="_blank" class="text-white underline">@henrymak6</a></div>
        </div>

        <div class="overflow-hidden rounded-2xl shadow card hero-zoom">
          <img src="assets/image%20(1).webp" alt="VsalesDigital mentor" class="w-full h-full object-cover object-center" />
        </div>
      </div>
    </section>

    <!-- About -->
    <section id="about" class="container py-12">
      <div class="bg-transparent rounded-2xl p-0">
        <h3 class="text-2xl font-bold text-white">About VsalesDigital</h3>
        <div class="mt-4 grid md:grid-cols-2 gap-6">
          <div>
            <p class="text-gray-300">VsalesDigital began as late-night experiments and small launches. Over time, those experiments formed a repeatable system used to find winners, optimize stores, and scale ads. We teach practical steps — not theory — and guide students through every step of their first profitable launches.</p>
            <p class="mt-4 text-gray-300">Our mentorship focuses on hands-on support, clear checklists, and fast feedback loops so students avoid common mistakes and reach results faster.</p>
          </div>
          <div>
            <h4 class="font-semibold text-white">Our Approach</h4>
            <ul class="mt-3 text-gray-300 list-disc list-inside space-y-2">
              <li>Hands-on mentoring during launch and scaling</li>
              <li>Data-led product validation to reduce risk</li>
              <li>Conversion-first store design and copy</li>
              <li>Automation & fulfillment for lean ops</li>
            </ul>
            <blockquote class="mt-6 p-4 border-l-4 border-white italic text-gray-300">We believe success comes from clear systems, real support, and consistent execution.</blockquote>
          </div>
        </div>
      </div>
    </section>

    <!-- Services -->
    <section id="services" class="container py-12">
      <h3 class="text-2xl font-bold text-white">What I Teach</h3>
      <p class="text-gray-300 mt-2">Practical modules focused on launches and scaling. Click "Learn More" on any card to read full details.</p>

      <div class="mt-6 grid md:grid-cols-2 gap-6">
        <div class="service-card" style="background:url('assets/IMG-20251019-WA0062.webp') center/cover no-repeat">
          <div class="overlay"></div>
          <div class="content text-white">
            <h4 class="text-xl font-semibold">Product Research</h4>
            <p class="text-sm mt-2">Find high-demand products using tools and frameworks that predict winners.</p>
            <div class="mt-4">
              <button class="btn-white" onclick="openModal('service1')">Learn More</button>
            </div>
          </div>
        </div>

        <div class="service-card" style="background:url('assets/IMG-20251019-WA0068.webp') center/cover no-repeat">
          <div class="overlay"></div>
          <div class="content text-white">
            <h4 class="text-xl font-semibold">Store Setup</h4>
            <p class="text-sm mt-2">Conversion-first store builds, optimized product pages and trust signals.</p>
            <div class="mt-4">
              <button class="btn-white" onclick="openModal('service2')">Learn More</button>
            </div>
          </div>
        </div>

        <div class="service-card" style="background:url('assets/140.webp') center/cover no-repeat">
          <div class="overlay"></div>
          <div class="content text-white">
            <h4 class="text-xl font-semibold">Marketing & Ads</h4>
            <p class="text-sm mt-2">Ad frameworks and creative testing for Facebook & TikTok that find winners fast.</p>
            <div class="mt-4">
              <button class="btn-white" onclick="openModal('service3')">Learn More</button>
            </div>
          </div>
        </div>

        <div class="service-card" style="background:url('assets/image.webp') center/cover no-repeat">
          <div class="overlay"></div>
          <div class="content text-white">
            <h4 class="text-xl font-semibold">Automation & Fulfillment</h4>
            <p class="text-sm mt-2">Supplier setup, order flows and automation to keep your store lean.</p>
            <div class="mt-4">
              <button class="btn-white" onclick="openModal('service4')">Learn More</button>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Packages -->
    <section id="packages" class="container py-12">
      <h3 class="text-2xl font-bold text-white">Mentorship Packages</h3>
      <p class="text-gray-300 mt-2">Straightforward packages for beginners through to advanced sellers.</p>

      <div class="mt-6 grid md:grid-cols-3 gap-6">
        <div class="price-card text-center">
          <h4 class="font-semibold">Starter</h4>
          <div class="price mt-3">$50</div>
          <p class="text-gray-300 mt-2">Perfect for beginners — product research and store setup guidance to get your first sales.</p>
          <div class="mt-4"><button class="btn-white" onclick="openModal('package1')">Get Started</button></div>
        </div>

        <div class="price-card text-center" style="transform:scale(1.03);box-shadow:0 10px 40px rgba(255,255,255,0.03)">
          <h4 class="font-semibold">Growth</h4>
          <div class="price mt-3">$150</div>
          <p class="text-gray-300 mt-2">For stores ready to scale — ad strategy, creatives, and conversion optimization.</p>
          <div class="mt-4"><button class="btn-white" onclick="openModal('package2')">Apply Now</button></div>
        </div>

        <div class="price-card text-center">
          <h4 class="font-semibold">Premium</h4>
          <div class="price mt-3">$500</div>
          <p class="text-gray-300 mt-2">Full automation, supplier integration, and advanced scaling systems for high-growth stores.</p>
          <div class="mt-4"><button class="btn-white" onclick="openModal('package3')">Join Coaching</button></div>
        </div>
      </div>
    </section>

    <!-- Proof (case studies using uploaded images) -->
    <section id="proof" class="container py-12">
      <h3 class="text-2xl font-bold text-white">Real Results & Student Proof</h3>
      <p class="text-gray-300 mt-2">Actual screenshots from live student stores and launch tests you provided.</p>

      <div class="mt-6 grid md:grid-cols-3 gap-6">
        <div class="rounded-xl overflow-hidden shadow card">
          <img src="assets/image.webp" alt="Sales screenshot 1" class="w-full h-48 object-cover" />
          <div class="p-4 bg-black">
            <h4 class="font-semibold">Small Launch — Quick Win</h4>
            <p class="text-sm text-gray-300 mt-1">Total sales snapshot from a launch day.</p>
          </div>
        </div>

        <div class="rounded-xl overflow-hidden shadow card">
          <img src="assets/image%20(1).webp" alt="Sales screenshot 2" class="w-full h-48 object-cover" />
          <div class="p-4 bg-black">
            <h4 class="font-semibold">Momentum Week</h4>
            <p class="text-sm text-gray-300 mt-1">First week results and orders captured from tests.</p>
          </div>
        </div>

        <div class="rounded-xl overflow-hidden shadow card">
          <img src="assets/image%20(2).webp" alt="Sales screenshot 3" class="w-full h-48 object-cover" />
          <div class="p-4 bg-black">
            <h4 class="font-semibold">Scaling Snapshot</h4>
            <p class="text-sm text-gray-300 mt-1">Aggregated sales proof and growth trends.</p>
          </div>
        </div>
      </div>

    </section>

    <!-- Testimonials -->
    <section id="testimonials" class="container py-12">
      <h3 class="text-2xl font-bold text-white">Student Testimonials</h3>
      <div class="mt-6 grid md:grid-cols-3 gap-6">
        <div class="p-6 card rounded-xl shadow bg-black">
          <p class="text-gray-300">“VsalesDigital gave me a clear launch plan and the support I needed to hit my first profitable month. The step-by-step approach is priceless.”</p>
          <p class="mt-4 text-sm text-gray-500">— Lisa, First-time store owner</p>
        </div>
        <div class="p-6 card rounded-xl shadow bg-black">
          <p class="text-gray-300">“Practical, honest, and results-focused mentorship. I scaled to multiple profitable campaigns after implementing the ad testing system.”</p>
          <p class="mt-4 text-sm text-gray-500">— Mark, Scaled store owner</p>
        </div>
        <div class="p-6 card rounded-xl shadow bg-black">
          <p class="text-gray-300">“The product research framework saved me weeks of guessing and helped me launch a winning SKU.”</p>
          <p class="mt-4 text-sm text-gray-500">— Ana, Mentor student</p>
        </div>
      </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="container py-12 bg-transparent">
      <div class="grid md:grid-cols-2 gap-6 items-center">
        <div>
          <h3 class="text-2xl font-bold text-white">Work with VsalesDigital</h3>
          <p class="text-gray-300 mt-2">Book a free strategy call and we'll review your store, find quick wins, and map a growth path you can follow.</p>
          <div class="mt-6">
            <a href="mailto:vsalesdigital@gmail.com" class="btn-white">Email vsalesdigital@gmail.com</a>
          </div>
        </div>
        <div class="text-sm text-gray-300">
          <h4 class="font-semibold text-white">Follow & Contact</h4>
          <ul class="mt-3 space-y-2">
            <li>Email: <a href="mailto:vsalesdigital@gmail.com" class="text-white underline">vsalesdigital@gmail.com</a></li>
            <li>Discord: share your invite link here</li>
            <li>Instagram: <a href="https://instagram.com/henrymak6" target="_blank" class="text-white underline">@henrymak6</a></li>
          </ul>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="container text-center py-8 text-gray-500 text-sm">
      <p class="text-gray-400">© <span id="year"></span> VsalesDigital — Dropshipping Mentor. All rights reserved.</p>
    </footer>
  </main>

  <!-- Modals -->
  <div id="modalBackdrop" class="modal-backdrop" onclick="closeModal()">
    <div class="modal" onclick="event.stopPropagation()">
      <div id="modalContent"> <!-- injected content --> </div>
      <div class="mt-4 text-right">
        <button class="btn-white" onclick="closeModal()">Close</button>
      </div>
    </div>
  </div>

  <!-- Signup Badge (small) -->
  <div id="signupBadge" class="signup-badge" style="display:none">
    <div style="display:flex;align-items:center;gap:10px">
      <div style="flex:1">
        <strong>Free Mentorship</strong>
        <div style="font-size:12px;color:#9ca3af">Get a free strategy call</div>
      </div>
      <div>
        <button class="btn-white" onclick="openModal('signupModal')">Sign Up</button>
      </div>
    </div>
  </div>

  <!-- Signup Modal (hidden content) -->
  <div id="signupModalContent" style="display:none">
    <h3 class="text-xl font-bold">Sign Up for Free Mentorship</h3>
    <p class="text-gray-300 mt-2">Enter your details and I’ll personally review your store and suggest quick wins.</p>
    <form id="signupForm" class="mt-4">
      <div style="display:flex;gap:10px;flex-wrap:wrap">
        <input name="name" placeholder="Your name" required style="flex:1;padding:.6rem;border-radius:8px;border:1px solid #222;background:#050505;color:#fff" />
        <input name="email" type="email" placeholder="Your email" required style="flex:1;padding:.6rem;border-radius:8px;border:1px solid #222;background:#050505;color:#fff" />
      </div>
      <textarea name="message" placeholder="A short note about your store (optional)" style="width:100%;margin-top:10px;padding:.6rem;border-radius:8px;border:1px solid #222;background:#050505;color:#fff"></textarea>
      <div class="mt-4 text-right"><button type="submit" class="btn-white">Request Free Mentorship</button></div>
      <p class="text-xs text-gray-400 mt-2">By submitting you agree to receive emails about your mentorship.</p>
    </form>
  </div>

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

    // Modal functions
    const modalBackdrop = document.getElementById('modalBackdrop');
    const modalContent = document.getElementById('modalContent');
    function openModal(id){
      // populate content
      if(id === 'service1'){
        modalContent.innerHTML = `<h3 class=\"text-xl font-bold\">Product Research</h3><p class=\"mt-2 text-gray-300\">Deep-dive product research: trends, demand signals, and practical validation tests you can run in hours. We'll provide tools, checklists and hands-on feedback during research.</p><ul class='mt-3 text-gray-300 list-disc list-inside'><li>Market scanning</li><li>Creative ideation</li><li>Scale-ready validation</li></ul>`;
      } else if(id === 'service2'){
        modalContent.innerHTML = `<h3 class=\"text-xl font-bold\">Store Setup</h3><p class=\"mt-2 text-gray-300\">Conversion-first store builds: product pages, trust & refund policies, upsells and checkout optimization. We review and edit your store live on calls.</p>`;
      } else if(id === 'service3'){
        modalContent.innerHTML = `<h3 class=\"text-xl font-bold\">Marketing & Ads</h3><p class=\"mt-2 text-gray-300\">Ad frameworks for Facebook & TikTok: quick test setups, creative templates, and scaling rules to move from test to reliable ROAS.</p>`;
      } else if(id === 'service4'){
        modalContent.innerHTML = `<h3 class=\"text-xl font-bold\">Automation & Fulfillment</h3><p class=\"mt-2 text-gray-300\">Supplier setup, order automation and fulfillment routing to ensure timely delivery and simple operations.</p>`;
      } else if(id === 'package1'){
        modalContent.innerHTML = `<h3 class=\"text-xl font-bold\">Starter Package — $50</h3><p class=\"mt-2 text-gray-300\">Includes product research checklist, basic store setup guide and 1 review session. Perfect for beginners.</p><div class=\"mt-4 text-right\"><button class=\"btn-white\" onclick=\"openModal('signupModal')\">Request Starter</button></div>`;
      } else if(id === 'package2'){
        modalContent.innerHTML = `<h3 class=\"text-xl font-bold\">Growth Package — $150</h3><p class=\"mt-2 text-gray-300\">Includes ad strategy, creative testing templates, and 3 review sessions for scaling your store.</p><div class=\"mt-4 text-right\"><button class=\"btn-white\" onclick=\"openModal('signupModal')\">Apply for Growth</button></div>`;
      } else if(id === 'package3'){
        modalContent.innerHTML = `<h3 class=\"text-xl font-bold\">Premium Package — $500</h3><p class=\"mt-2 text-gray-300\">Full onboarding, automation & supplier integration, and hands-on scaling support across 6 sessions.</p><div class=\"mt-4 text-right\"><button class=\"btn-white\" onclick=\"openModal('signupModal')\">Join Premium</button></div>`;
      } else if(id === 'signupModal'){
        modalContent.innerHTML = document.getElementById('signupModalContent').innerHTML;
        // attach form handler
        const form = document.getElementById('signupForm');
        form && form.addEventListener('submit', handleSignup);
      }
      modalBackdrop.style.display = 'flex';
    }
    function closeModal(){
      modalBackdrop.style.display = 'none';
      modalContent.innerHTML = '';
    }

    // Signup badge show after 10 seconds and auto-open signup modal after 10s
    window.addEventListener('load', ()=>{
      setTimeout(()=>{
        document.getElementById('signupBadge').style.display = 'block';
        openModal('signupModal');
      }, 10000);
    });

    // Handle signup form: use mailto fallback
    function handleSignup(e){
      e.preventDefault();
      const form = e.target;
      const data = new FormData(form);
      const name = data.get('name') || '';
      const email = data.get('email') || '';
      const message = data.get('message') || '';
      const subject = encodeURIComponent('Free Mentorship Request - ' + name);
      const body = encodeURIComponent(`Name: ${name}\nEmail: ${email}\n\nMessage:\n${message}`);
      // open mail client as fallback
      window.location.href = `mailto:vsalesdigital@gmail.com?subject=${subject}&body=${body}`;
      // close modal
      closeModal();
    }

    // Close modal on ESC
    window.addEventListener('keydown', (e)=>{ if(e.key === 'Escape') closeModal(); });
  </script>
</body>
</html>
