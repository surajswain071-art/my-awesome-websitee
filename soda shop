<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Cherish Boba</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    html { scroll-behavior: smooth; }
    body {
      background:
        radial-gradient(circle at top left, rgba(244,114,182,0.16), transparent 25%),
        radial-gradient(circle at top right, rgba(56,189,248,0.14), transparent 22%),
        radial-gradient(circle at bottom, rgba(168,85,247,0.12), transparent 28%),
        linear-gradient(180deg, #070816 0%, #0b1020 45%, #060712 100%);
    }
    .glass {
      background: rgba(255,255,255,0.08);
      backdrop-filter: blur(16px);
      -webkit-backdrop-filter: blur(16px);
      border: 1px solid rgba(255,255,255,0.12);
      box-shadow: 0 10px 30px rgba(0,0,0,0.25);
    }
    .glow {
      box-shadow: 0 0 30px rgba(236,72,153,0.22), 0 0 60px rgba(56,189,248,0.12);
    }
    .floaty { animation: floaty 6s ease-in-out infinite; }
    @keyframes floaty {
      0%,100% { transform: translateY(0px); }
      50% { transform: translateY(-10px); }
    }
    .pulse-soft { animation: pulseSoft 2.8s ease-in-out infinite; }
    @keyframes pulseSoft {
      0%,100% { transform: scale(1); opacity: 1; }
      50% { transform: scale(1.04); opacity: 0.9; }
    }
    .fade-up {
      opacity: 0;
      transform: translateY(22px);
      transition: opacity .8s ease, transform .8s ease;
    }
    .fade-up.show {
      opacity: 1;
      transform: translateY(0);
    }
    .sparkle {
      position: absolute;
      border-radius: 9999px;
      background: rgba(255,255,255,0.85);
      filter: blur(1px);
      animation: drift linear infinite;
    }
    @keyframes drift {
      from { transform: translateY(0) translateX(0) scale(1); opacity: 0; }
      10% { opacity: 1; }
      to { transform: translateY(-120vh) translateX(40px) scale(0.5); opacity: 0; }
    }
    .menu-card:hover { transform: translateY(-6px) scale(1.01); }
  </style>
</head>
<body class="text-white antialiased overflow-x-hidden">
  <div id="sparkles" class="fixed inset-0 pointer-events-none overflow-hidden"></div>

  <header class="sticky top-0 z-50 border-b border-white/10 bg-slate-950/70 backdrop-blur-xl">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex items-center justify-between h-16">
        <div class="flex items-center gap-3">
          <div class="w-11 h-11 rounded-2xl bg-gradient-to-br from-pink-400 via-fuchsia-500 to-cyan-400 flex items-center justify-center glow floaty">
            <span class="text-2xl">🧋</span>
          </div>
          <div>
            <p class="font-black text-lg leading-tight">Cherish Boba</p>
            <p class="text-xs text-white/60">Boba, tea, coffee & snacks</p>
          </div>
        </div>

        <nav class="hidden md:flex items-center gap-6 text-sm text-white/80">
          <button onclick="scrollToSection('home')" class="hover:text-white transition">Home</button>
          <button onclick="scrollToSection('menu')" class="hover:text-white transition">Menu</button>
          <button onclick="scrollToSection('location')" class="hover:text-white transition">Location</button>
          <button onclick="scrollToSection('contact')" class="hover:text-white transition">Contact</button>
        </nav>

        <button onclick="scrollToSection('menu')" class="px-4 py-2 rounded-xl bg-gradient-to-r from-pink-400 to-cyan-400 text-slate-950 font-bold hover:scale-105 transition transform">
          Order Now
        </button>
      </div>
    </div>
  </header>

  <main>
    <section id="home" class="relative">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-14 md:py-20">
        <div class="grid lg:grid-cols-2 gap-10 items-center">
          <div class="space-y-6 fade-up">
            <div class="inline-flex items-center gap-2 px-4 py-2 rounded-full glass text-sm text-white/80">
              <span class="w-2 h-2 rounded-full bg-emerald-400 animate-pulse"></span>
              Fresh drinks, sweet toppings, and tasty bites
            </div>
            <h1 class="text-4xl md:text-6xl font-black leading-tight">
              Welcome to
              <span class="bg-gradient-to-r from-pink-300 via-fuchsia-300 to-cyan-300 bg-clip-text text-transparent">Cherish Boba</span>
            </h1>
            <p class="text-white/75 text-lg max-w-xl">
              Discover our colorful menu of ice drinks, tea series, coffee series, boba favorites, toppings, and snacks — made to look lively, modern, and delicious.
            </p>
            <div class="flex flex-wrap gap-4">
              <button onclick="scrollToSection('menu')" class="px-6 py-3 rounded-2xl bg-gradient-to-r from-pink-400 to-fuchsia-500 text-white font-bold hover:scale-105 transition transform">
                Explore Menu
              </button>
              <button onclick="scrollToSection('location')" class="px-6 py-3 rounded-2xl glass font-semibold hover:bg-white/15 transition">
                Find Us
              </button>
            </div>

            <div class="grid grid-cols-3 gap-3 max-w-lg pt-4">
              <div class="glass rounded-2xl p-4 text-center">
                <div class="text-2xl font-black text-pink-300">24+</div>
                <div class="text-xs text-white/60">Menu Choices</div>
              </div>
              <div class="glass rounded-2xl p-4 text-center">
                <div class="text-2xl font-black text-cyan-300">Fresh</div>
                <div class="text-xs text-white/60">Made Daily</div>
              </div>
              <div class="glass rounded-2xl p-4 text-center">
                <div class="text-2xl font-black text-emerald-300">Best</div>
                <div class="text-xs text-white/60">For Sharing</div>
              </div>
            </div>
          </div>

          <div class="relative flex justify-center lg:justify-end fade-up">
            <div class="absolute inset-0 flex items-center justify-center">
              <div class="w-72 h-72 md:w-[30rem] md:h-[30rem] rounded-full bg-pink-500/10 blur-3xl pulse-soft"></div>
            </div>
            <div class="relative glass rounded-[2rem] p-5 md:p-8 w-full max-w-xl glow">
              <div class="grid grid-cols-2 gap-4">
                <div class="rounded-3xl overflow-hidden bg-gradient-to-b from-pink-300/20 to-cyan-300/10 p-4 border border-white/10">
                  <div class="text-sm text-white/70">Signature Vibe</div>
                  <div class="mt-2 text-2xl font-black">Cherish Boba</div>
                  <div class="mt-3 h-40 rounded-2xl bg-[radial-gradient(circle_at_30%_20%,rgba(255,255,255,0.55),transparent_20%),linear-gradient(180deg,#ff7ab8,#9f4cff)] relative overflow-hidden">
                    <div class="absolute inset-x-8 bottom-0 h-24 bg-slate-950/20 rounded-t-[3rem]"></div>
                    <div class="absolute left-1/2 top-8 -translate-x-1/2 text-6xl floaty">🧋</div>
                  </div>
                </div>
                <div class="space-y-4">
                  <div class="rounded-3xl bg-white/8 p-4 border border-white/10">
                    <div class="text-white/60 text-sm">Sweet & Cool</div>
                    <div class="mt-2 text-xl font-semibold">Milk Tea</div>
                    <div class="mt-3 flex gap-2 flex-wrap">
                      <span class="px-3 py-1 text-xs rounded-full bg-pink-400/20 text-pink-200">Boba</span>
                      <span class="px-3 py-1 text-xs rounded-full bg-cyan-400/20 text-cyan-200">Ice</span>
                      <span class="px-3 py-1 text-xs rounded-full bg-emerald-400/20 text-emerald-200">Fresh</span>
                    </div>
                  </div>
                  <div class="rounded-3xl bg-white/8 p-4 border border-white/10">
                    <div class="text-white/60 text-sm">Tasty Snacks</div>
                    <div class="mt-2 text-xl font-semibold">Fried Chicken & More</div>
                    <div class="mt-2 text-sm text-white/70">Perfect for a complete meal.</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="menu" class="py-10 md:py-16">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="flex flex-col md:flex-row md:items-end md:justify-between gap-4 mb-8 fade-up">
          <div>
            <h2 class="text-3xl md:text-4xl font-black">MENU</h2>
            <p class="text-white/65 mt-2">Cherish Boba menu list with animated, stylish presentation.</p>
          </div>
          <div class="flex gap-3 flex-wrap">
            <button onclick="scrollToSection('location')" class="px-4 py-2 rounded-xl glass hover:bg-white/15 transition">Available On</button>
            <button onclick="scrollToSection('contact')" class="px-4 py-2 rounded-xl glass hover:bg-white/15 transition">Contact</button>
          </div>
        </div>

        <div id="menuGrid" class="grid sm:grid-cols-2 lg:grid-cols-3 gap-5"></div>
      </div>
    </section>

    <section id="location" class="py-10 md:py-16">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="grid lg:grid-cols-2 gap-6 items-stretch fade-up">
          <div class="glass rounded-[2rem] p-8">
            <h2 class="text-3xl font-black">Available On</h2>
            <div class="mt-5 space-y-4 text-white/75">
              <div class="rounded-2xl bg-white/8 p-4">
                <div class="text-sm text-white/60">Address</div>
                <div class="mt-1 font-semibold">Kedundang Kec. Temon, Kulon Progo, D.I. Yogyakarta</div>
              </div>
              <div class="rounded-2xl bg-white/8 p-4">
                <div class="text-sm text-white/60">Instagram</div>
                <div class="mt-1 font-semibold">@cherishboba.id</div>
              </div>
              <div class="rounded-2xl bg-white/8 p-4">
                <div class="text-sm text-white/60">Delivery</div>
                <div class="mt-1 font-semibold">GrabFood & GoFood</div>
              </div>
            </div>
          </div>

          <div class="glass rounded-[2rem] p-8 overflow-hidden relative">
            <div class="absolute inset-0 bg-gradient-to-br from-pink-500/10 via-transparent to-cyan-500/10"></div>
            <div class="relative">
              <h2 class="text-3xl font-black">Mau Pesan Banyak Makanan?</h2>
              <p class="mt-4 text-white/75 leading-relaxed">
                BISA BANGET. Enjoy easy ordering with our full menu, perfect for sharing with friends, family, or office snacks.
              </p>
              <div class="mt-6 grid sm:grid-cols-2 gap-4">
                <div class="rounded-2xl bg-white/8 p-4">
                  <div class="text-2xl">🍔</div>
                  <div class="mt-2 font-semibold">Bites & Meals</div>
                  <div class="text-sm text-white/60">Chicken, burger, noodle, and more.</div>
                </div>
                <div class="rounded-2xl bg-white/8 p-4">
                  <div class="text-2xl">🧋</div>
                  <div class="mt-2 font-semibold">Drink Combos</div>
                  <div class="text-sm text-white/60">Pair drinks with tasty topping options.</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="contact" class="py-10 md:py-16 pb-20">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="glass rounded-[2rem] p-8 md:p-10 fade-up">
          <div class="grid lg:grid-cols-2 gap-8 items-center">
            <div>
              <h2 class="text-3xl md:text-4xl font-black">Cherish Boba</h2>
              <p class="mt-3 text-white/70 max-w-xl">
                A colorful, animated menu website for your boba shop with a modern layout and easy browsing experience.
              </p>
            </div>
            <div class="grid sm:grid-cols-2 gap-4">
              <div class="rounded-2xl bg-white/8 p-4">
                <div class="text-white/60 text-sm">Instagram</div>
                <div class="mt-1 text-lg font-semibold">@cherishboba.id</div>
              </div>
              <div class="rounded-2xl bg-white/8 p-4">
                <div class="text-white/60 text-sm">Delivery</div>
                <div class="mt-1 text-lg font-semibold">GrabFood / GoFood</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>

  <script>
    const menuData = [
      { title: 'ICE DRINK', items: [] },
      { title: 'THAI TEA', items: ['GREEN TEA 7K', 'CHOCOLATE 9K', 'LYCHEE TROPIC 8K', 'RED VELVET 9K', 'MILK BROWN SUGAR 8K'] },
      { title: 'CHERISH', items: ['PURE GREEN TEA 7K', 'PURE THAI TEA 5K', 'LEMON TEA 6K', 'LYCHEE TEA 7K', 'MILK TEA BS 8K'] },
      { title: 'COFFEE SERIES', items: ['MILO 8K', 'MILK MOCCA 10K', 'STRAWBERRY 9K', 'CAPPUCINO 8K'] },
      { title: 'CHERISH', items: ['TARO 8K', 'VANILLA 8K'] },
      { title: 'TOPPING', items: ['MANGGO TROPIC 8K', 'CHOCO CREAM +4K', 'CHOCO THAI TEA 10K', 'KOPAJA 10K', 'CHOCO GREEN TEA 12K', 'KOPI SUREN 10K', 'ICE CREAM VANILLA +4K'] },
      { title: 'CHERISH BOBA', items: ['BOBA +3K', 'CHOCO MILK MOCCA 12K', 'KOPI SUKLAT 12K', 'CHOCO VANILLA 12K', 'KOPSU MANTAN 12K', 'CHOCO MILK BS 12K', 'CHOCO TARO 12K', 'OREO +3K', 'REGAL +3K'] },
      { title: 'BOBA WAR', items: ['BOBA THAI TEA 10K', 'BOBA THAI TEA SMALL 6K', 'BOBA GREEN TEA 12K / 7K', 'BOBA GREEN TEA SMALL 6K', 'BOBA MILK TEA BS 12K / 6K', 'BOBA MILK TEA SMALL 6K'] },
      { title: 'CHERISH BOBA', items: ['BOBA TARO 10K', 'BOBA TARO SMALL 7K', 'BOBA STRAWBERRY 10K', 'BOBA MILK BS 10K', 'BOBA CHOCOLATE 12K', 'BOBA RED VELVET 12K'] },
      { title: 'LAIN-LAIN', items: ['BOBA MILK BS SMALL 7K', 'BOBA STRAWBERRY SMALL 7K', 'BOBA CHOCOLATE SMALL 7K', 'AIR MINERAL KECIL 2K', 'AIR MINERAL BESAR 3.5K', 'INDOMIE TANTE 8K', 'INDOMIE TELUR 10K', 'TEH MANIS 5K', 'TEH TAWAR 3K', 'KOPI HITAM 5K', 'INDOCAFE MIX 5K', 'POP MIE KECIL 5K', 'POP MIE BESAR 10K', 'BURGER 13K', 'FC ORIGINAL + NASI 13.5K', 'FC SAMBAL MATAH NASI 14.5K', 'FC SAOS KEJU NASI 13.5K', 'FC SAOS BLACKPAPPER NASI 14.5K', 'FC SAMBAL GEPREK NASI 14.5K', 'SUSU COKLAT 5K', 'SUSU PUTIH 5K', 'KEBAB 13K'] }
    ];

    const colors = [
      'border-pink-400/20',
      'border-cyan-400/20',
      'border-fuchsia-400/20',
      'border-emerald-400/20',
      'border-amber-400/20',
      'border-violet-400/20'
    ];

    const grid = document.getElementById('menuGrid');
    menuData.forEach((group, idx) => {
      const card = document.createElement('div');
      card.className = `menu-card glass rounded-3xl p-5 transition duration-300 ${colors[idx % colors.length]} fade-up`;
      card.innerHTML = `
        <div class="flex items-center justify-between gap-3">
          <h3 class="text-xl font-black">${group.title}</h3>
          <span class="text-2xl">${idx % 2 === 0 ? '🧋' : '✨'}</span>
        </div>
        <div class="mt-4 space-y-2">
          ${group.items.length ? group.items.map(item => `<div class="flex items-start justify-between gap-3 rounded-2xl bg-white/7 px-3 py-2">
              <span class="text-sm text-white/85 leading-5">${item}</span>
            </div>`).join('') : `<div class="rounded-2xl bg-white/7 px-3 py-3 text-sm text-white/70">Cold, refreshing drinks served ice-cold.</div>`}
        </div>
      `;
      grid.appendChild(card);
    });

    function scrollToSection(id) {
      document.getElementById(id).scrollIntoView({ behavior: 'smooth', block: 'start' });
    }

    const sparkles = document.getElementById('sparkles');
    for (let i = 0; i < 34; i++) {
      const s = document.createElement('div');
      s.className = 'sparkle';
      const size = 3 + Math.random() * 7;
      s.style.width = size + 'px';
      s.style.height = size + 'px';
      s.style.left = Math.random() * 100 + 'vw';
      s.style.bottom = -20 - Math.random() * 120 + 'px';
      s.style.opacity = 0;
      s.style.animationDuration = 6 + Math.random() * 10 + 's';
      s.style.animationDelay = Math.random() * 6 + 's';
      sparkles.appendChild(s);
    }

    const observer = new IntersectionObserver(entries => {
      entries.forEach(entry => {
        if (entry.isIntersecting) entry.target.classList.add('show');
      });
    }, { threshold: 0.12 });

    document.querySelectorAll('.fade-up').forEach(el => observer.observe(el));
  </script>
</body>
</html>
