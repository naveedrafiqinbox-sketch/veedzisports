<!DOCTYPE html>
<html lang="en" class="dark">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
  <!-- ================= SEO & TOP TRENDING KEYWORDS ================= -->
  <title>Veedzi Sports - Watch Free Live Sports Streaming HD, Cricket, Football & F1 Channels</title>
  <meta name="description" content="Veedzi Sports is your premier destination for free live sports streaming online. Watch ICC World Cup, IPL, PSL Cricket, Premier League Football, Champions League, Formula 1, Wimbledon Tennis, NBA, and 24/7 global sports TV channels in HD.">
  <meta name="keywords" content="Veedzi Sports, Veedzi Sports live, watch live sports free, live cricket stream hd, live football streaming, free ipl live stream, psl live streaming, epl stream live, formula 1 live stream free, red bull tv live, cbs sports stream, world sports channels online free, CricHD alternative, buffstreams alternative, sports live streaming server">
  <meta name="robots" content="index, follow">
  <meta name="author" content="Veedzi Sports Network">

  <!-- Open Graph / Facebook / WhatsApp SEO -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://veedzisports.com/">
  <meta property="og:title" content="Veedzi Sports - Live Cricket, Football & Sports Channels HD">
  <meta property="og:description" content="Watch high quality live streams of Cricket, Football, Motorsport, Tennis & 24/7 sports channels on Veedzi Sports.">
  <meta property="og:image" content="https://images.unsplash.com/photo-1508098682722-e99c43a406b2?auto=format&fit=crop&w=1200&q=80">

  <!-- Twitter Card SEO -->
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:title" content="Veedzi Sports - Free Live Sports Streaming HD">
  <meta name="twitter:description" content="Watch global live sports channels, cricket tournaments, and football matches free in HD.">

  <!-- Schema.org Structured Data for Sports Events & Live Broadcast -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "SportsEvent",
    "name": "Live Sports Streaming Network - Veedzi Sports",
    "description": "Watch live sports matches including Cricket, Football, Tennis and Motorsports on Veedzi Sports.",
    "url": "https://veedzisports.com",
    "organizer": {
      "@type": "Organization",
      "name": "Veedzi Sports",
      "url": "https://veedzisports.com"
    }
  }
  </script>

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- FontAwesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <!-- Google Font: Inter -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          colors: {
            brand: {
              red: '#E50914',
              green: '#10B981',
              dark: '#0F172A',
              card: '#1E293B',
              border: '#334155',
              accent: '#3B82F6'
            }
          },
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
          }
        }
      }
    }
  </script>

  <style>
    /* Custom Scrollbar */
    ::-webkit-scrollbar {
      width: 6px;
      height: 6px;
    }
    ::-webkit-scrollbar-track {
      background: #0F172A;
    }
    ::-webkit-scrollbar-thumb {
      background: #334155;
      border-radius: 4px;
    }
    ::-webkit-scrollbar-thumb:hover {
      background: #475569;
    }

    /* Pulse animation for live indicators */
    @keyframes pulse-fast {
      0%, 100% { opacity: 1; }
      50% { opacity: 0.3; }
    }
    .animate-live {
      animation: pulse-fast 1.5s cubic-bezier(0.4, 0, 0.6, 1) infinite;
    }

    /* Responsive Aspect Ratio for Iframe Player */
    .aspect-video-container {
      position: relative;
      padding-bottom: 56.25%; /* 16:9 ratio */
      height: 0;
      overflow: hidden;
    }
    .aspect-video-container iframe {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      border: 0;
    }

    /* Ticker smooth animation */
    .ticker-wrapper {
      white-space: nowrap;
      overflow: hidden;
    }
    .ticker-content {
      display: inline-block;
      animation: ticker 35s linear infinite;
    }
    .ticker-content:hover {
      animation-play-state: paused;
    }
    @keyframes ticker {
      0% { transform: translateX(100%); }
      100% { transform: translateX(-100%); }
    }
  </style>
</head>
<body class="bg-slate-950 text-slate-100 font-sans min-h-screen flex flex-col">

  <!-- ================= TOP AD BANNER SLOT (LEADERBOARD) ================= -->
  <div class="bg-slate-900 border-b border-slate-800 py-2 px-4 text-center text-xs">
    <div class="max-w-7xl mx-auto flex flex-col items-center justify-center">
      <div class="flex items-center justify-between w-full max-w-4xl text-slate-400 mb-1">
        <span class="text-[10px] uppercase tracking-wider font-semibold">Advertisement (Top Banner)</span>
        <span id="top-ad-timer" class="text-[10px] text-brand-accent">Rotates in: 15s</span>
      </div>
      <!-- Ad Container -->
      <div id="ad-slot-top" class="w-full max-w-[728px] h-[90px] bg-slate-800 border border-slate-700 rounded flex items-center justify-center overflow-hidden transition-all duration-500 shadow-md">
        <!-- Rendered dynamically via JS -->
      </div>
    </div>
  </div>

  <!-- ================= HEADER & NAVIGATION ================= -->
  <header class="bg-slate-900/90 backdrop-blur border-b border-slate-800 sticky top-0 z-40">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex items-center justify-between h-16">
        
        <!-- Logo -->
        <div class="flex items-center space-x-3">
          <a href="#" class="flex items-center space-x-2">
            <div class="w-10 h-10 bg-gradient-to-tr from-blue-600 to-emerald-400 rounded-lg flex items-center justify-center text-white font-extrabold text-xl shadow-lg shadow-blue-500/20">
              <i class="fa-solid font-bold fa-bolt"></i>
            </div>
            <div>
              <span class="text-xl font-black tracking-tight text-white">Veedzi<span class="text-emerald-400">Sports</span></span>
              <span class="text-[10px] block font-bold tracking-widest text-sky-400 uppercase -mt-1">Global Live Network</span>
            </div>
          </a>
        </div>

        <!-- Desktop Navigation -->
        <nav class="hidden md:flex space-x-1 lg:space-x-2 font-medium text-sm">
          <a href="#" onclick="filterMatches('all')" class="px-3 py-2 rounded-md bg-slate-800 text-white hover:bg-slate-700 transition">Home</a>
          <a href="#" onclick="filterMatches('Cricket')" class="px-3 py-2 rounded-md text-slate-300 hover:text-white hover:bg-slate-800 transition flex items-center gap-1.5"><i class="fa-solid fa-baseball-bat-ball text-emerald-400"></i> Cricket</a>
          <a href="#" onclick="filterMatches('Football')" class="px-3 py-2 rounded-md text-slate-300 hover:text-white hover:bg-slate-800 transition flex items-center gap-1.5"><i class="fa-solid fa-futbol text-sky-400"></i> Football</a>
          <a href="#" onclick="filterMatches('Tennis')" class="px-3 py-2 rounded-md text-slate-300 hover:text-white hover:bg-slate-800 transition flex items-center gap-1.5"><i class="fa-solid fa-table-tennis-paddle-ball text-amber-400"></i> Tennis</a>
          <a href="#" onclick="filterMatches('Formula 1')" class="px-3 py-2 rounded-md text-slate-300 hover:text-white hover:bg-slate-800 transition flex items-center gap-1.5"><i class="fa-solid fa-flag-checkered text-red-500"></i> F1</a>
          <a href="#channels-section" class="px-3 py-2 rounded-md text-slate-300 hover:text-white hover:bg-slate-800 transition">24/7 Channels</a>
        </nav>

        <!-- Right Side Action Buttons -->
        <div class="flex items-center space-x-3">
          <!-- Ad Config Manager Button -->
          <button onclick="openAdModal()" class="bg-amber-500/10 text-amber-400 hover:bg-amber-500/20 border border-amber-500/30 text-xs font-semibold px-3 py-2 rounded-lg flex items-center gap-2 transition">
            <i class="fa-solid fa-ad"></i>
            <span>Ad Manager</span>
          </button>
          
          <!-- Refresh Button -->
          <button onclick="location.reload()" class="p-2 text-slate-400 hover:text-white hover:bg-slate-800 rounded-lg transition" title="Refresh Streams">
            <i class="fa-solid fa-arrows-rotate"></i>
          </button>

          <!-- Mobile menu button -->
          <button onclick="toggleMobileMenu()" class="md:hidden p-2 text-slate-400 hover:text-white hover:bg-slate-800 rounded-lg">
            <i class="fa-solid fa-bars text-lg"></i>
          </button>
        </div>
      </div>
    </div>

    <!-- Mobile Nav Menu -->
    <div id="mobile-menu" class="hidden md:hidden bg-slate-900 border-b border-slate-800 px-4 pt-2 pb-4 space-y-1">
      <a href="#" onclick="filterMatches('all'); toggleMobileMenu();" class="block px-3 py-2 rounded-md bg-slate-800 text-white font-medium">Home</a>
      <a href="#" onclick="filterMatches('Cricket'); toggleMobileMenu();" class="block px-3 py-2 rounded-md text-slate-300 hover:bg-slate-800 font-medium">Cricket Live</a>
      <a href="#" onclick="filterMatches('Football'); toggleMobileMenu();" class="block px-3 py-2 rounded-md text-slate-300 hover:bg-slate-800 font-medium">Football Live</a>
      <a href="#" onclick="filterMatches('Tennis'); toggleMobileMenu();" class="block px-3 py-2 rounded-md text-slate-300 hover:bg-slate-800 font-medium">Tennis</a>
      <a href="#" onclick="filterMatches('Formula 1'); toggleMobileMenu();" class="block px-3 py-2 rounded-md text-slate-300 hover:bg-slate-800 font-medium">Formula 1</a>
      <a href="#channels-section" onclick="toggleMobileMenu()" class="block px-3 py-2 rounded-md text-slate-300 hover:bg-slate-800 font-medium">24/7 Channels</a>
    </div>

    <!-- LIVE TICKER BAR -->
    <div class="bg-slate-950 border-t border-b border-slate-800/80 py-1.5 px-4 flex items-center text-xs overflow-hidden">
      <div class="flex items-center gap-2 bg-red-600/20 text-red-400 border border-red-500/30 px-2 py-0.5 rounded font-bold uppercase tracking-wider shrink-0 mr-3">
        <span class="w-2 h-2 rounded-full bg-red-500 animate-live"></span>
        Live Ticker
      </div>
      <div class="ticker-wrapper flex-1 text-slate-300 font-medium">
        <div class="ticker-content space-x-8">
          <span>🏏 <strong class="text-white">IND vs AUS:</strong> Australia 245/4 (42.3 ov) - India won the toss & elected to bowl</span>
          <span>⚽ <strong class="text-white">Real Madrid vs Barcelona:</strong> 2 - 1 (78') El Clasico Stream Live</span>
          <span>🎾 <strong class="text-white">Wimbledon Final:</strong> Djokovic vs Alcaraz - Set 3 Tiebreak</span>
          <span>🏎️ <strong class="text-white">F1 Grand Prix:</strong> Monza Qualifying - Live Stream Server 1 Active</span>
        </div>
      </div>
    </div>
  </header>

  <!-- ================= MAIN CONTENT CONTAINER ================= -->
  <main class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-6 flex-1 w-full">
    
    <div class="grid grid-cols-1 lg:grid-cols-12 gap-6">
      
      <!-- LEFT / CENTER COLUMN (STREAM PLAYER + POPULAR MATCHES) - 8 COLS -->
      <div class="lg:col-span-8 space-y-6">
        
        <!-- PLAYER CONTAINER -->
        <div class="bg-slate-900 border border-slate-800 rounded-xl overflow-hidden shadow-2xl">
          
          <!-- Player Header -->
          <div class="bg-slate-950 px-4 py-3 border-b border-slate-800 flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-3">
              <span id="current-category" class="bg-emerald-500/10 text-emerald-400 border border-emerald-500/30 text-[10px] font-bold uppercase px-2 py-0.5 rounded">
                Cricket
              </span>
              <h2 id="current-stream-title" class="text-sm sm:text-base font-bold text-white truncate max-w-[280px] sm:max-w-md">
                India vs Australia - 3rd ODI Live Stream
              </h2>
            </div>
            
            <div class="flex items-center gap-1 text-xs">
              <span class="text-slate-400 mr-1 hidden sm:inline">Servers:</span>
              <button onclick="switchServer(1)" id="srv-1" class="px-2.5 py-1 rounded bg-emerald-600 text-white font-semibold shadow hover:bg-emerald-500 transition">S1</button>
              <button onclick="switchServer(2)" id="srv-2" class="px-2.5 py-1 rounded bg-slate-800 text-slate-300 font-semibold hover:bg-slate-700 transition">S2</button>
              <button onclick="switchServer(3)" id="srv-3" class="px-2.5 py-1 rounded bg-slate-800 text-slate-300 font-semibold hover:bg-slate-700 transition">S3</button>
              <button onclick="switchServer(4)" id="srv-4" class="px-2.5 py-1 rounded bg-slate-800 text-slate-300 font-semibold hover:bg-slate-700 transition">HD</button>
            </div>
          </div>

          <!-- Video Stream Area (Responsive 16:9 Container) -->
          <div class="bg-black aspect-video-container relative group">
            <iframe id="main-player" 
                    src="https://www.youtube.com/embed/live_stream?channel=UC4R8DWoMoI7CAwX8_LjQHig" 
                    allowfullscreen 
                    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture">
            </iframe>
            
            <!-- Stream Overlay Warning/Info badge -->
            <div class="absolute top-3 left-3 bg-black/70 backdrop-blur text-slate-300 text-[11px] px-2.5 py-1 rounded-md border border-white/10 pointer-events-none flex items-center gap-2">
              <span class="w-2 h-2 rounded-full bg-emerald-500 animate-pulse"></span>
              <span id="player-status-text">Signal HD Stable (Server 1)</span>
            </div>
          </div>

          <!-- Player Controls & Information Bar -->
          <div class="p-3 bg-slate-900 border-t border-slate-800/80 flex flex-wrap items-center justify-between text-xs text-slate-400 gap-2">
            <div class="flex items-center gap-3">
              <span><i class="fa-solid fa-users text-slate-500"></i> <strong class="text-slate-200">24.5k</strong> Watching</span>
              <span><i class="fa-solid fa-signal text-emerald-400"></i> 1080p @ 60fps</span>
            </div>
            <div class="flex items-center gap-2">
              <button onclick="reloadPlayer()" class="hover:text-white bg-slate-800 px-2.5 py-1 rounded border border-slate-700"><i class="fa-solid fa-rotate-right mr-1"></i> Reload Stream</button>
              <button onclick="toggleFullscreen()" class="hover:text-white bg-slate-800 px-2.5 py-1 rounded border border-slate-700"><i class="fa-solid fa-expand mr-1"></i> Fullscreen</button>
            </div>
          </div>
        </div>

        <!-- ================= BELOW PLAYER AD BANNER SLOT ================= -->
        <div class="bg-slate-900 border border-slate-800 rounded-xl p-3 text-center">
          <div class="flex items-center justify-between text-slate-400 text-[10px] uppercase font-semibold mb-2">
            <span>Advertisement (In-Content Banner)</span>
            <span id="player-ad-timer" class="text-brand-accent">Rotates in: 15s</span>
          </div>
          <div id="ad-slot-player" class="w-full h-[100px] sm:h-[120px] bg-slate-950 border border-slate-800 rounded-lg flex items-center justify-center overflow-hidden">
            <!-- Dynamic Ad Content -->
          </div>
        </div>

        <!-- LIVE MATCHES SCHEDULE / SWITCHER LIST -->
        <div class="bg-slate-900 border border-slate-800 rounded-xl p-4">
          <div class="flex items-center justify-between mb-4 border-b border-slate-800 pb-3">
            <h3 class="text-base font-bold text-white flex items-center gap-2">
              <i class="fa-solid fa-tower-broadcast text-red-500"></i>
              Live Sports Fixtures
            </h3>
            <span class="text-xs text-slate-400">Click any event to switch player stream</span>
          </div>

          <!-- Category Filter Tabs -->
          <div class="flex items-center gap-2 overflow-x-auto pb-2 mb-3 text-xs scrollbar-none">
            <button onclick="filterMatches('all')" class="px-3 py-1.5 rounded-lg bg-emerald-600 text-white font-semibold whitespace-nowrap">All Matches</button>
            <button onclick="filterMatches('Cricket')" class="px-3 py-1.5 rounded-lg bg-slate-800 hover:bg-slate-700 text-slate-300 font-semibold whitespace-nowrap">Cricket</button>
            <button onclick="filterMatches('Football')" class="px-3 py-1.5 rounded-lg bg-slate-800 hover:bg-slate-700 text-slate-300 font-semibold whitespace-nowrap">Football</button>
            <button onclick="filterMatches('Tennis')" class="px-3 py-1.5 rounded-lg bg-slate-800 hover:bg-slate-700 text-slate-300 font-semibold whitespace-nowrap">Tennis</button>
            <button onclick="filterMatches('Formula 1')" class="px-3 py-1.5 rounded-lg bg-slate-800 hover:bg-slate-700 text-slate-300 font-semibold whitespace-nowrap">Motorsport</button>
          </div>

          <!-- Match List Items -->
          <div id="matches-list" class="space-y-2.5">
            <!-- Dynamic JavaScript injection of matches -->
          </div>
        </div>

      </div>

      <!-- RIGHT COLUMN (SIDEBAR BANNER + 24/7 CHANNELS GRID) - 4 COLS -->
      <div class="lg:col-span-4 space-y-6">

        <!-- ================= SIDEBAR VERTICAL AD BANNER SLOT ================= -->
        <div class="bg-slate-900 border border-slate-800 rounded-xl p-3 text-center">
          <div class="flex items-center justify-between text-slate-400 text-[10px] uppercase font-semibold mb-2">
            <span>Sponsor Ad (Sidebar)</span>
            <span id="sidebar-ad-timer" class="text-brand-accent">Rotates in: 15s</span>
          </div>
          <div id="ad-slot-sidebar" class="w-full h-[250px] sm:h-[300px] bg-slate-950 border border-slate-800 rounded-lg flex items-center justify-center overflow-hidden">
            <!-- Dynamic Ad Content -->
          </div>
        </div>

        <!-- 24/7 SPORTS CHANNELS GRID -->
        <div id="channels-section" class="bg-slate-900 border border-slate-800 rounded-xl p-4">
          <div class="flex items-center justify-between mb-4 border-b border-slate-800 pb-3">
            <h3 class="text-base font-bold text-white flex items-center gap-2">
              <i class="fa-solid fa-tv text-emerald-400"></i>
              24/7 Sports TV Channels
            </h3>
          </div>

          <div class="grid grid-cols-2 gap-2.5" id="channels-grid">
            <!-- Dynamic Channels JS injection -->
          </div>
        </div>

        <!-- QUICK CHAT / ANNOUNCEMENT BOX -->
        <div class="bg-slate-900 border border-slate-800 rounded-xl p-4">
          <h4 class="text-sm font-bold text-slate-200 mb-2 flex items-center gap-2">
            <i class="fa-solid fa-bullhorn text-amber-400"></i>
            Stream Help & Info
          </h4>
          <p class="text-xs text-slate-400 leading-relaxed mb-3">
            If a stream buffers or shows a black screen, click on <span class="text-emerald-400 font-semibold">Server 2</span> or <span class="text-emerald-400 font-semibold">Server 3</span> buttons above the video player.
          </p>
          <div class="bg-slate-950 p-2.5 rounded-lg border border-slate-800 text-[11px] text-slate-400">
            <i class="fa-solid fa-shield-halved text-emerald-400 mr-1"></i> Ad-Blocker Detection: Disabling ad-blocker ensures stream stability.
          </div>
        </div>

      </div>

    </div>

    <!-- ================= FOOTER AD BANNER SLOT ================= -->
    <div class="mt-8 bg-slate-900 border border-slate-800 rounded-xl p-3 text-center">
      <div class="flex items-center justify-between text-slate-400 text-[10px] uppercase font-semibold mb-2 max-w-4xl mx-auto">
        <span>Advertisement (Footer Banner)</span>
        <span id="footer-ad-timer" class="text-brand-accent">Rotates in: 15s</span>
      </div>
      <div id="ad-slot-footer" class="w-full max-w-4xl mx-auto h-[90px] bg-slate-950 border border-slate-800 rounded-lg flex items-center justify-center overflow-hidden">
        <!-- Dynamic Ad Content -->
      </div>
    </div>

  </main>

  <!-- ================= FOOTER ================= -->
  <footer class="bg-slate-900 border-t border-slate-800 mt-12 py-8 text-xs text-slate-400">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col md:flex-row items-center justify-between gap-4">
      <div>
        <span class="text-base font-bold text-white">Veedzi<span class="text-emerald-400">Sports</span> Network</span>
        <p class="text-slate-500 mt-1">Free Live Sports Streaming, Cricket, Football & F1 Streams.</p>
      </div>
      <div class="flex items-center space-x-4 text-slate-400">
        <a href="#" class="hover:text-white transition">Privacy Policy</a>
        <a href="#" class="hover:text-white transition">DMCA Disclaimer</a>
        <a href="#" class="hover:text-white transition">Contact Us</a>
        <button onclick="openAdModal()" class="text-amber-400 hover:underline">Manage Ads</button>
      </div>
    </div>
  </footer>

  <!-- ================= AD MANAGEMENT MODAL ================= -->
  <div id="ad-modal" class="fixed inset-0 bg-black/80 backdrop-blur-sm z-50 hidden flex items-center justify-center p-4">
    <div class="bg-slate-900 border border-slate-700 w-full max-w-2xl rounded-xl shadow-2xl overflow-hidden flex flex-col max-h-[90vh]">
      
      <!-- Modal Header -->
      <div class="bg-slate-950 px-6 py-4 border-b border-slate-800 flex items-center justify-between">
        <div class="flex items-center gap-2">
          <i class="fa-solid fa-rectangle-ad text-amber-400 text-xl"></i>
          <h3 class="text-lg font-bold text-white">Dynamic Ad Banner Manager</h3>
        </div>
        <button onclick="closeAdModal()" class="text-slate-400 hover:text-white p-1 rounded-lg">
          <i class="fa-solid fa-xmark text-xl"></i>
        </button>
      </div>

      <!-- Modal Body -->
      <div class="p-6 overflow-y-auto space-y-6 text-xs text-slate-300">
        <p class="text-slate-400 leading-relaxed">
          Paste your banner image URLs or embedded iframe ad links here. Added banners will automatically rotate every <strong class="text-emerald-400">10-15 seconds</strong> across all ad slots on the website.
        </p>

        <!-- Add New Ad Form -->
        <form id="add-ad-form" onsubmit="handleAddNewAd(event)" class="bg-slate-950 p-4 rounded-lg border border-slate-800 space-y-3">
          <h4 class="font-bold text-slate-200 text-sm">Add New Banner Link</h4>
          
          <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
            <div>
              <label class="block text-[11px] font-semibold text-slate-400 mb-1">Banner Title/Name</label>
              <input type="text" id="ad-title" placeholder="e.g. Bet365 Bonus Banner" required class="w-full bg-slate-900 border border-slate-700 rounded px-3 py-2 text-white focus:outline-none focus:border-amber-500">
            </div>
            <div>
              <label class="block text-[11px] font-semibold text-slate-400 mb-1">Target Click URL (Optional)</label>
              <input type="url" id="ad-target-url" placeholder="https://example.com/affiliate" class="w-full bg-slate-900 border border-slate-700 rounded px-3 py-2 text-white focus:outline-none focus:border-amber-500">
            </div>
          </div>

          <div>
            <label class="block text-[11px] font-semibold text-slate-400 mb-1">Image URL or Embedded HTML Code</label>
            <textarea id="ad-content" rows="2" placeholder="Paste image URL (e.g. https://via.placeholder.com/728x90) or <iframe> ad snippet..." required class="w-full bg-slate-900 border border-slate-700 rounded px-3 py-2 text-white focus:outline-none focus:border-amber-500 font-mono text-[11px]"></textarea>
          </div>

          <div class="flex justify-end">
            <button type="submit" class="bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold px-4 py-2 rounded-lg transition flex items-center gap-2">
              <i class="fa-solid fa-plus"></i> Add to Rotation Pool
            </button>
          </div>
        </form>

        <!-- Existing Ads List -->
        <div>
          <h4 class="font-bold text-slate-200 text-sm mb-2">Active Ads in Rotation Pool (<span id="ad-count">0</span>)</h4>
          <div id="ad-list-container" class="space-y-2 max-h-48 overflow-y-auto pr-1">
            <!-- Dynamic Ad items rendered here -->
          </div>
        </div>
      </div>

      <!-- Modal Footer -->
      <div class="bg-slate-950 px-6 py-3 border-t border-slate-800 flex justify-between items-center">
        <button onclick="resetDefaultAds()" class="text-xs text-red-400 hover:underline">Reset to Default Ads</button>
        <button onclick="closeAdModal()" class="bg-slate-800 hover:bg-slate-700 text-white text-xs px-4 py-2 rounded-lg font-semibold">Close</button>
      </div>

    </div>
  </div>

  <!-- ================= JAVASCRIPT LOGIC ================= -->
  <script>
    /* ================= 1. SAMPLE MATCHES & PUBLIC EMBEDDABLE CHANNELS DATA ================= */
    const matchesData = [
      {
        id: 'm1',
        category: 'Cricket',
        league: 'ICC T20 World Cup',
        team1: 'India',
        flag1: '🇮🇳',
        team2: 'Australia',
        flag2: '🇦🇺',
        status: 'LIVE',
        time: '18.4 Ov - Aus 165/3',
        servers: [
          'https://www.youtube.com/embed/live_stream?channel=UC4R8DWoMoI7CAwX8_LjQHig',
          'https://www.youtube.com/embed/21X5lGlDOfg',
          'https://player.twitch.tv/?channel=esl_csgo&parent=' + window.location.hostname
        ]
      },
      {
        id: 'm2',
        category: 'Cricket',
        league: 'Pakistan Super League (PSL)',
        team1: 'Lahore Qalandars',
        flag1: '🏏',
        team2: 'Karachi Kings',
        flag2: '🏏',
        status: 'LIVE',
        time: 'Innings Break',
        servers: [
          'https://www.youtube.com/embed/fJ9rUzIMcZQ',
          'https://www.youtube.com/embed/21X5lGlDOfg'
        ]
      },
      {
        id: 'm3',
        category: 'Football',
        league: 'UEFA Champions League',
        team1: 'Real Madrid',
        flag1: '🇪🇸',
        team2: 'Barcelona',
        flag2: '🇪🇸',
        status: 'LIVE',
        time: "78' (2 - 1)",
        servers: [
          'https://www.youtube.com/embed/21X5lGlDOfg',
          'https://www.youtube.com/embed/live_stream?channel=UC4R8DWoMoI7CAwX8_LjQHig'
        ]
      },
      {
        id: 'm4',
        category: 'Motorsport',
        league: 'Red Bull Extreme Sports',
        team1: 'Red Bull TV Live',
        flag1: '🏎️',
        team2: 'World Championship',
        flag2: '🏁',
        status: 'LIVE',
        time: 'Live Stream',
        servers: [
          'https://www.redbull.com/embed/v3/tv/live/rrn:content:live-events:3a0f1fa8-1f14-411a-8e2b-231a48c6883e/en-INT',
          'https://www.youtube.com/embed/live_stream?channel=UC4R8DWoMoI7CAwX8_LjQHig'
        ]
      },
      {
        id: 'm5',
        category: 'Basketball',
        league: 'NBA Global Championship',
        team1: 'Lakers',
        flag1: '🇺🇸',
        team2: 'Celtics',
        flag2: '🇺🇸',
        status: 'LIVE',
        time: 'Q3 (84 - 82)',
        servers: [
          'https://www.youtube.com/embed/fJ9rUzIMcZQ'
        ]
      }
    ];

    const channelsData = [
      { name: 'Red Bull TV Sports', icon: 'fa-bolt', color: 'text-amber-400', stream: 'https://www.redbull.com/embed/v3/tv/live/rrn:content:live-events:3a0f1fa8-1f14-411a-8e2b-231a48c6883e/en-INT' },
      { name: 'CBS Sports HQ (YouTube)', icon: 'fa-tv', color: 'text-sky-400', stream: 'https://www.youtube.com/embed/live_stream?channel=UC4R8DWoMoI7CAwX8_LjQHig' },
      { name: 'Willow Cricket HD Feed', icon: 'fa-baseball-bat-ball', color: 'text-emerald-400', stream: 'https://www.youtube.com/embed/21X5lGlDOfg' },
      { name: 'Star Sports 1 HD Broadcast', icon: 'fa-star', color: 'text-yellow-400', stream: 'https://www.youtube.com/embed/fJ9rUzIMcZQ' },
      { name: 'PTV Sports Live Stream', icon: 'fa-globe', color: 'text-green-500', stream: 'https://www.youtube.com/embed/live_stream?channel=UC4R8DWoMoI7CAwX8_LjQHig' },
      { name: 'Twitch Sports Stream', icon: 'fa-brands fa-twitch', color: 'text-purple-400', stream: 'https://player.twitch.tv/?channel=rocketleague&parent=' + window.location.hostname }
    ];

    /* ================= 2. AD MANAGEMENT SYSTEM ================= */
    const initialAdPool = [
      {
        id: 'ad1',
        title: 'Veedzi Sports Sponsor - 100% Sports Bonus',
        targetUrl: 'https://example.com/register',
        content: 'https://placehold.co/728x90/1e293b/38bdf8?text=Veedzi+Sports+Exclusive+%7C+Get+100%25+Deposit+Bonus'
      },
      {
        id: 'ad2',
        title: 'Bet365 Live In-Play Odds',
        targetUrl: 'https://example.com/bet365',
        content: 'https://placehold.co/728x90/064e3b/34d399?text=Live+Cricket+%26+Football+Odds+%7C+Bet+Now'
      },
      {
        id: 'ad3',
        title: 'Parimatch High Cricket Odds',
        targetUrl: 'https://example.com/parimatch',
        content: 'https://placehold.co/728x90/78350f/fbbf24?text=PariMatch+Super+Odds+%7C+Live+Match+Streaming'
      }
    ];

    const channelsData = [
      { name: 'Sky Sports Main Event', icon: 'fa-tv', color: 'text-sky-400', stream: 'https://www.youtube.com/embed/live_stream?channel=UC4R8DWoMoI7CAwX8_LjQHig' },
      { name: 'Willow TV Cricket', icon: 'fa-baseball-bat-ball', color: 'text-emerald-400', stream: 'https://www.youtube.com/embed/21X5lGlDOfg' },
      { name: 'Star Sports 1 HD', icon: 'fa-star', color: 'text-amber-400', stream: 'https://www.youtube.com/embed/fJ9rUzIMcZQ' },
      { name: 'Sony Ten 1 HD', icon: 'fa-bolt', color: 'text-blue-400', stream: 'https://www.youtube.com/embed/21X5lGlDOfg' },
      { name: 'PTV Sports Live', icon: 'fa-globe', color: 'text-green-500', stream: 'https://www.youtube.com/embed/live_stream?channel=UC4R8DWoMoI7CAwX8_LjQHig' },
      { name: 'SuperSport Grandstand', icon: 'fa-trophy', color: 'text-purple-400', stream: 'https://www.youtube.com/embed/fJ9rUzIMcZQ' }
    ];

    /* ================= 2. AD MANAGEMENT SYSTEM ================= */
    // Default initial mock banner ads
    const initialAdPool = [
      {
        id: 'ad1',
        title: '1xBet - 100% Sports Bonus',
        targetUrl: 'https://example.com/register',
        content: 'https://placehold.co/728x90/1e293b/38bdf8?text=1xBet+Sportsbook+%7C+100%25+Welcome+Bonus+Now'
      },
      {
        id: 'ad2',
        title: 'Bet365 Live Streaming Ads',
        targetUrl: 'https://example.com/bet365',
        content: 'https://placehold.co/728x90/064e3b/34d399?text=Bet365+Live+In-Play+Odds+%7C+Claim+Offer'
      },
      {
        id: 'ad3',
        title: 'Parimatch High Odds',
        targetUrl: 'https://example.com/parimatch',
        content: 'https://placehold.co/728x90/78350f/fbbf24?text=PariMatch+Best+Cricket+Odds+%7C+Bet+Now'
      }
    ];

    let adPool = JSON.parse(localStorage.getItem('cric_ad_pool')) || initialAdPool;
    let currentAdIndex = 0;
    let rotationIntervalSeconds = 12; // Dynamic rotation every 12 seconds
    let adCountdown = rotationIntervalSeconds;

    function saveAdsToStorage() {
      localStorage.setItem('cric_ad_pool', JSON.stringify(adPool));
      renderAdManagerList();
    }

    function renderAdSlot(slotElementId, adItem) {
      const container = document.getElementById(slotElementId);
      if (!container || !adItem) return;

      // Check if content is full HTML snippet (iframe/script) or direct image URL
      if (adItem.content.trim().startsWith('<') || adItem.content.includes('iframe')) {
        container.innerHTML = adItem.content;
      } else {
        // Image banner fallback
        const linkWrapper = document.createElement('a');
        linkWrapper.href = adItem.targetUrl || '#';
        linkWrapper.target = '_blank';
        linkWrapper.className = 'w-full h-full block flex items-center justify-center';
        
        const img = document.createElement('img');
        img.src = adItem.content;
        img.alt = adItem.title;
        img.className = 'w-full h-full object-cover rounded hover:opacity-95 transition';
        img.onerror = () => {
          img.src = `https://placehold.co/728x90/0f172a/94a3b8?text=${encodeURIComponent(adItem.title)}`;
        };

        linkWrapper.appendChild(img);
        container.innerHTML = '';
        container.appendChild(linkWrapper);
      }
    }

    function rotateAllAds() {
      if (adPool.length === 0) return;

      // Pick current ad & shifted indices for variety
      const topAd = adPool[currentAdIndex % adPool.length];
      const playerAd = adPool[(currentAdIndex + 1) % adPool.length];
      const sidebarAd = adPool[(currentAdIndex + 2) % adPool.length];
      const footerAd = adPool[(currentAdIndex + 3) % adPool.length];

      renderAdSlot('ad-slot-top', topAd);
      renderAdSlot('ad-slot-player', playerAd);
      renderAdSlot('ad-slot-sidebar', sidebarAd);
      renderAdSlot('ad-slot-footer', footerAd);

      currentAdIndex = (currentAdIndex + 1) % adPool.length;
    }

    function startAdRotatorTimer() {
      setInterval(() => {
        adCountdown--;
        if (adCountdown <= 0) {
          rotateAllAds();
          adCountdown = rotationIntervalSeconds;
        }

        // Update timer labels UI
        const timerTexts = document.querySelectorAll('#top-ad-timer, #player-ad-timer, #sidebar-ad-timer, #footer-ad-timer');
        timerTexts.forEach(el => {
          if (el) el.textContent = `Rotates in: ${adCountdown}s`;
        });
      }, 1000);
    }

    /* ================= 3. STREAM & PLAYER CONTROLLER ================= */
    let currentActiveMatch = matchesData[0];

    function loadMatchStream(matchId) {
      const match = matchesData.find(m => m.id === matchId);
      if (!match) return;

      currentActiveMatch = match;
      document.getElementById('current-stream-title').textContent = `${match.team1} vs ${match.team2} - ${match.league}`;
      document.getElementById('current-category').textContent = match.category;
      
      // Load primary server stream URL
      const iframe = document.getElementById('main-player');
      iframe.src = match.servers[0];

      document.getElementById('player-status-text').textContent = 'Signal HD Stable (Server 1)';

      // Highlight active match card
      renderMatchesList(matchesData);
    }

    function switchServer(serverNum) {
      if (!currentActiveMatch || !currentActiveMatch.servers) return;
      const serverIdx = serverNum - 1;
      const url = currentActiveMatch.servers[serverIdx] || currentActiveMatch.servers[0];

      document.getElementById('main-player').src = url;
      document.getElementById('player-status-text').textContent = `Signal HD Connected (Server ${serverNum})`;

      // Update button highlights
      for (let i = 1; i <= 4; i++) {
        const btn = document.getElementById(`srv-${i}`);
        if (btn) {
          if (i === serverNum) {
            btn.className = 'px-2.5 py-1 rounded bg-emerald-600 text-white font-semibold shadow hover:bg-emerald-500 transition';
          } else {
            btn.className = 'px-2.5 py-1 rounded bg-slate-800 text-slate-300 font-semibold hover:bg-slate-700 transition';
          }
        }
      }
    }

    function reloadPlayer() {
      const iframe = document.getElementById('main-player');
      const currentSrc = iframe.src;
      iframe.src = '';
      setTimeout(() => { iframe.src = currentSrc; }, 300);
    }

    function toggleFullscreen() {
      const iframe = document.getElementById('main-player');
      if (iframe.requestFullscreen) {
        iframe.requestFullscreen();
      } else if (iframe.webkitRequestFullscreen) {
        iframe.webkitRequestFullscreen();
      }
    }

    /* ================= 4. UI RENDERING & FILTERS ================= */
    function renderMatchesList(data) {
      const listContainer = document.getElementById('matches-list');
      if (!listContainer) return;

      listContainer.innerHTML = '';

      if (data.length === 0) {
        listContainer.innerHTML = `<div class="text-center py-6 text-slate-500 text-xs">No active matches in this category right now.</div>`;
        return;
      }

      data.forEach(m => {
        const isActive = currentActiveMatch && currentActiveMatch.id === m.id;
        const item = document.createElement('div');
        item.onclick = () => loadMatchStream(m.id);
        
        item.className = `p-3 rounded-lg border transition cursor-pointer flex items-center justify-between gap-3 ${
          isActive 
            ? 'bg-slate-800/90 border-emerald-500/50 shadow-md ring-1 ring-emerald-500/30' 
            : 'bg-slate-950/60 border-slate-800/80 hover:bg-slate-800/50'
        }`;

    /* ================= FOOTER ================= */
    <footer class="bg-slate-900 border-t border-slate-800 mt-12 py-8 text-xs text-slate-400">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col md:flex-row items-center justify-between gap-4">
        <div>
          <span class="text-base font-bold text-white">Veezi<span class="text-emerald-400">Sports</span> Network</span>
          <p class="text-slate-500 mt-1">Free Live Sports Streaming, Cricket, Football & F1 Streams.</p>
        </div>
            
            <div class="border-l border-slate-800 pl-3">
              <div class="text-[11px] text-emerald-400 font-semibold uppercase tracking-wider">${m.league}</div>
              <div class="text-xs font-bold text-white flex items-center gap-2 mt-0.5">
                <span>${m.flag1} ${m.team1}</span>
                <span class="text-slate-500 font-normal">vs</span>
                <span>${m.flag2} ${m.team2}</span>
              </div>
            </div>
          </div>

          <div class="shrink-0 flex items-center gap-2">
            ${m.status === 'LIVE' 
              ? '<span class="px-2 py-1 bg-red-600/20 text-red-400 border border-red-500/30 rounded text-[10px] font-bold flex items-center gap-1"><span class="w-1.5 h-1.5 rounded-full bg-red-500 animate-pulse"></span> WATCH</span>'
              : '<span class="px-2 py-1 bg-slate-800 text-slate-400 rounded text-[10px]">UPCOMING</span>'
            }
          </div>
        `;
        listContainer.appendChild(item);
      });
    }

    function renderChannelsGrid() {
      const grid = document.getElementById('channels-grid');
      if (!grid) return;

      grid.innerHTML = '';
      channelsData.forEach(ch => {
        const card = document.createElement('button');
        card.onclick = () => {
          document.getElementById('main-player').src = ch.stream;
          document.getElementById('current-stream-title').textContent = `${ch.name} 24/7 Stream`;
          document.getElementById('current-category').textContent = '24/7 TV';
        };
        card.className = 'p-2.5 bg-slate-950/80 border border-slate-800/80 rounded-lg hover:border-slate-700 hover:bg-slate-800/60 transition flex items-center gap-2.5 text-left group';

        card.innerHTML = `
          <div class="w-8 h-8 rounded bg-slate-900 border border-slate-800 flex items-center justify-center shrink-0 group-hover:scale-105 transition">
            <i class="fa-solid ${ch.icon} ${ch.color} text-sm"></i>
          </div>
          <div class="truncate">
            <span class="text-xs font-semibold text-slate-200 block truncate group-hover:text-emerald-400 transition">${ch.name}</span>
            <span class="text-[10px] text-slate-500 block">24/7 Live Stream</span>
          </div>
        `;
        grid.appendChild(card);
      });
    }

    function filterMatches(category) {
      if (category === 'all') {
        renderMatchesList(matchesData);
      } else {
        const filtered = matchesData.filter(m => m.category.toLowerCase() === category.toLowerCase());
        renderMatchesList(filtered);
      }
    }

    function toggleMobileMenu() {
      const menu = document.getElementById('mobile-menu');
      menu.classList.toggle('hidden');
    }

    /* ================= 5. MODAL & AD FORM HANDLERS ================= */
    function openAdModal() {
      document.getElementById('ad-modal').classList.remove('hidden');
      renderAdManagerList();
    }

    function closeAdModal() {
      document.getElementById('ad-modal').classList.add('hidden');
    }

    function renderAdManagerList() {
      const container = document.getElementById('ad-list-container');
      document.getElementById('ad-count').textContent = adPool.length;

      if (!container) return;
      container.innerHTML = '';

      adPool.forEach((ad, index) => {
        const item = document.createElement('div');
        item.className = 'p-2.5 bg-slate-950 border border-slate-800 rounded flex items-center justify-between text-xs gap-2';
        item.innerHTML = `
          <div class="truncate">
            <strong class="text-slate-200 block truncate">${ad.title}</strong>
            <span class="text-[10px] text-slate-500 truncate block font-mono">${ad.content}</span>
          </div>
          <button onclick="deleteAd(${index})" class="text-red-400 hover:text-red-300 p-1 bg-slate-900 rounded border border-slate-800">
            <i class="fa-solid fa-trash-can"></i>
          </button>
        `;
        container.appendChild(item);
      });
    }

    function handleAddNewAd(e) {
      e.preventDefault();
      const title = document.getElementById('ad-title').value;
      const targetUrl = document.getElementById('ad-target-url').value;
      const content = document.getElementById('ad-content').value;

      const newAd = {
        id: 'ad_' + Date.now(),
        title,
        targetUrl,
        content
      };

      adPool.push(newAd);
      saveAdsToStorage();
      rotateAllAds(); // Instantly apply

      // Clear Form
      document.getElementById('add-ad-form').reset();
    }

    function deleteAd(index) {
      adPool.splice(index, 1);
      saveAdsToStorage();
      rotateAllAds();
    }

    function resetDefaultAds() {
      if (confirm('Are you sure you want to reset ads back to defaults?')) {
        adPool = [...initialAdPool];
        saveAdsToStorage();
        rotateAllAds();
      }
    }

    /* ================= 6. INIT ON LOAD ================= */
    window.onload = function() {
      renderMatchesList(matchesData);
      renderChannelsGrid();
      rotateAllAds();
      startAdRotatorTimer();
    };
  </script>
</body>
</html>
