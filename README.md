<!DOCTYPE html>
<html lang="hi">
<head>
  <base target="_self">
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Uttarakhand Kala Sanskriti — Handicrafts, Handlooms & Pahadi Superfoods</title>
  <meta name="description" content="Authentic Uttarakhand handicrafts, handlooms & pahadi superfoods. Support local artisans & Himalayan heritage. Free shipping across India.">
  <link rel="canonical" href="https://uttarakhandkalasanskriti.com">

  <!-- Open Graph -->
  <meta property="og:title" content="Uttarakhand Kala Sanskriti">
  <meta property="og:description" content="Authentic Uttarakhand handicrafts & pahadi superfoods">
  <meta property="og:type" content="website">
  <meta property="og:image" content="https://picsum.photos/1200/630?random=777">

  <!-- Fonts & Icons -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Devanagari:wght@400;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">

  <!-- Tailwind -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            primary: "#4a6b3d",
            secondary: "#8b5a2b",
            accent: "#d97706",
            light: "#f5f5f5",
            dark: "#1e293b"
          },
          fontFamily: {
            sans: ['Poppins','sans-serif'],
            hindi: ['Noto Sans Devanagari','sans-serif']
          },
          boxShadow: {
            soft: '0 10px 30px rgba(0,0,0,0.08)'
          }
        }
      }
    }
  </script>

  <!-- Product Structured Data -->
  <script type="application/ld+json">
  {
    "@context":"https://schema.org",
    "@type":"Product",
    "name":"Kale Bhatt (Black Soybean) 350g",
    "image":["/images/kale-bhatt-350g.jpg"],
    "brand":{"@type":"Brand","name":"JATNOZ"},
    "description":"A Pahadi superfood from Uttarakhand. High protein, high fiber, zero cholesterol. Diabetic friendly.",
    "offers":{
      "@type":"Offer",
      "priceCurrency":"INR",
      "price":"199",
      "availability":"https://schema.org/InStock",
      "url":"https://uttarakhandkalasanskriti.com/#kale-bhatt"
    }
  }
  </script>

  <style>
    /* nice scroll for gallery lightbox lock */
    .noscroll { overflow: hidden; }
  </style>
</head>
<body class="font-sans bg-light text-dark antialiased">

  <!-- Header -->
  <header class="bg-white/90 backdrop-blur shadow-md sticky top-0 z-50">
    <div class="max-w-7xl mx-auto px-4 py-3 flex items-center justify-between">
      <div class="flex items-center">
        <img src="https://picsum.photos/80?random=101" alt="Logo" class="h-12 w-12 rounded-full ring-2 ring-primary/20">
        <div class="ml-3">
          <h1 class="text-xl md:text-2xl font-bold text-primary font-hindi">उत्तराखंड कला संस्कृति</h1>
          <p class="text-xs text-gray-500 -mt-1">The Taste & Art of Uttarakhand</p>
        </div>
      </div>
      <nav id="navDesktop" class="hidden md:flex items-center space-x-8">
        <a href="#home" class="hover:text-accent">Home</a>
        <a href="#kale-bhatt" class="hover:text-accent">Kale Bhatt</a>
        <a href="#shop" class="hover:text-accent">Shop</a>
        <a href="#gallery" class="hover:text-accent">Gallery</a>
        <a href="#blog" class="hover:text-accent">Blog</a>
        <a href="#contact" class="hover:text-accent">Contact</a>
      </nav>
      <div class="flex items-center space-x-3">
        <button id="searchBtn" class="p-2 rounded-full hover:bg-gray-100" aria-label="Search">
          <i class="fas fa-search"></i>
        </button>
        <button class="p-2 rounded-full hover:bg-gray-100 relative" aria-label="Cart">
          <i class="fas fa-shopping-cart"></i>
          <span id="cartCount" class="absolute -top-1 -right-1 bg-accent text-white text-xs rounded-full h-5 w-5 flex items-center justify-center">0</span>
        </button>
        <button id="menuBtn" class="md:hidden p-2 rounded-full hover:bg-gray-100" aria-label="Menu">
          <i class="fas fa-bars text-dark"></i>
        </button>
      </div>
    </div>

    <!-- Mobile Drawer -->
    <div id="mobileMenu" class="md:hidden hidden border-t bg-white">
      <div class="max-w-7xl mx-auto px-4 py-3 grid gap-2">
        <a href="#home" class="py-2">Home</a>
        <a href="#kale-bhatt" class="py-2">Kale Bhatt</a>
        <a href="#shop" class="py-2">Shop</a>
        <a href="#gallery" class="py-2">Gallery</a>
        <a href="#blog" class="py-2">Blog</a>
        <a href="#contact" class="py-2">Contact</a>
      </div>
    </div>
  </header>

  <!-- Hero -->
  <section id="home" class="relative h-[70vh] md:h-[78vh]">
    <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?q=80&w=2070&auto=format&fit=crop"
         alt="Himalayan landscape"
         class="absolute inset-0 w-full h-full object-cover">
    <div class="absolute inset-0 bg-black/45"></div>
    <div class="relative z-10 max-w-7xl mx-auto h-full px-6 flex flex-col justify-center text-white">
      <h2 class="text-4xl md:text-6xl font-bold leading-tight">Himalayan Craft & <span class="text-accent">Superfoods</span></h2>
      <p class="mt-3 md:text-xl text-gray-100 max-w-2xl">Local artisans & farmers से सीधे आपके घर तक। प्रामाणिक, टिकाऊ और स्वाद से भरपूर।</p>
      <div class="mt-6 space-x-3">
        <a href="#kale-bhatt" class="inline-block bg-accent px-6 py-3 rounded-xl font-semibold shadow-soft hover:bg-primary">Order Kale Bhatt 350g</a>
        <a href="#shop" class="inline-block bg-white/10 px-6 py-3 rounded-xl font-semibold ring-1 ring-white/40 hover:bg-white/20">Explore Shop</a>
      </div>
    </div>
  </section>

  <!-- USPs -->
  <section class="bg-white">
    <div class="max-w-7xl mx-auto px-6 py-8 grid grid-cols-2 md:grid-cols-6 gap-4 text-sm">
      <div class="flex items-center space-x-2"><i class="fas fa-seedling text-primary"></i><span>Plant Protein</span></div>
      <div class="flex items-center space-x-2"><i class="fas fa-heartbeat text-primary"></i><span>Zero Cholesterol</span></div>
      <div class="flex items-center space-x-2"><i class="fas fa-leaf text-primary"></i><span>High Fiber</span></div>
      <div class="flex items-center space-x-2"><i class="fas fa-check-circle text-primary"></i><span>Diabetic Friendly</span></div>
      <div class="flex items-center space-x-2"><i class="fas fa-mountain text-primary"></i><span>Pahadi Superfood</span></div>
      <div class="flex items-center space-x-2"><i class="fas fa-shipping-fast text-primary"></i><span>Free Shipping</span></div>
    </div>
  </section>

  <!-- Featured Product: Kale Bhatt -->
  <section id="kale-bhatt" class="bg-white">
    <div class="max-w-7xl mx-auto px-6 py-16 grid md:grid-cols-2 gap-10 items-center">
      <div class="bg-light rounded-3xl p-4 shadow-soft">
        <!-- Replace src with your real file/url -->
        <img src="images/kale-bhatt-350g.jpg" alt="JATNOZ Kale Bhatt (Black Soybean) 350g Pack"
             class="w-full h-auto rounded-2xl object-cover">
      </div>
      <div>
        <h3 class="text-3xl md:text-4xl font-bold mb-2">Kale Bhatt (Black Soybean) — 350g</h3>
        <p class="text-gray-700">Himalayas के दिल से सीधे—protein, fiber और micronutrients से भरपूर। पौष्टिक, स्वादिष्ट और पारम्परिक पका̄वन के लिए बेहतरीन।</p>

        <ul class="mt-4 grid grid-cols-2 gap-2 text-sm">
          <li class="flex items-center space-x-2"><i class="fas fa-check text-primary"></i><span>High Protein • High Fiber</span></li>
          <li class="flex items-center space-x-2"><i class="fas fa-check text-primary"></i><span>Zero Cholesterol</span></li>
          <li class="flex items-center space-x-2"><i class="fas fa-check text-primary"></i><span>Diabetic Friendly</span></li>
          <li class="flex items-center space-x-2"><i class="fas fa-check text-primary"></i><span>Made in Uttarakhand</span></li>
        </ul>

        <div class="mt-6 flex items-end justify-between">
          <div>
            <div class="text-2xl font-bold text-accent">₹199 <span class="text-gray-500 text-base font-normal">/ 350g</span></div>
            <div class="text-xs text-gray-500">Inclusive of all taxes • Free delivery</div>
          </div>
          <div class="flex items-center space-x-3">
            <div class="flex items-center border rounded-xl overflow-hidden">
              <button class="px-3 py-2" data-qty="minus" aria-label="Decrease">−</button>
              <input id="qtyKB" type="number" min="1" value="1" class="w-14 text-center outline-none py-2">
              <button class="px-3 py-2" data-qty="plus" aria-label="Increase">+</button>
            </div>
            <button id="addKB" class="bg-primary text-white px-5 py-3 rounded-xl font-semibold shadow-soft hover:bg-accent">
              <i class="fas fa-shopping-cart mr-2"></i>Add to Cart
            </button>
          </div>
        </div>

        <div class="mt-6 text-sm text-gray-600 leading-relaxed">
          <strong>How to use:</strong> रातभर भिगोकर प्रेशर कुकर में मसालों के साथ पकाएँ—भट्ट की दाल/चुडकानी, सलाद या सूप में।
        </div>
      </div>
    </div>
  </section>

  <!-- Shop Grid -->
  <section id="shop" class="bg-light">
    <div class="max-w-7xl mx-auto px-6 py-14">
      <div class="flex items-end justify-between mb-8">
        <h3 class="text-3xl font-bold">Shop More</h3>
        <a href="#" class="text-accent">View all →</a>
      </div>
      <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-8">
        <!-- Product Card 1: Kale Bhatt duplicate quick add -->
        <div class="bg-white rounded-2xl shadow-soft overflow-hidden hover:-translate-y-1 transition">
          <img src="images/kale-bhatt-350g.jpg" alt="Kale Bhatt 350g" class="w-full h-56 object-cover">
          <div class="p-5">
            <h4 class="font-semibold text-lg">Kale Bhatt (Black Soybean) 350g</h4>
            <p class="text-gray-600 text-sm">Pahadi superfood • High Protein</p>
            <div class="flex justify-between items-center mt-4">
              <span class="font-bold text-accent">₹199</span>
              <button data-add="KB" class="bg-primary text-white px-4 py-2 rounded-lg">Add</button>
            </div>
          </div>
        </div>
        <!-- Product Card 2 -->
        <div class="bg-white rounded-2xl shadow-soft overflow-hidden hover:-translate-y-1 transition">
          <img src="https://picsum.photos/600/400?random=302" alt="Woolen Shawl" class="w-full h-56 object-cover">
          <div class="p-5">
            <h4 class="font-semibold text-lg">Woolen Shawl</h4>
            <p class="text-gray-600 text-sm">Handwoven Kumaoni warmth</p>
            <div class="flex justify-between items-center mt-4">
              <span class="font-bold text-accent">₹1200</span>
              <button class="bg-primary text-white px-4 py-2 rounded-lg">Add</button>
            </div>
          </div>
        </div>
        <!-- Product Card 3 -->
        <div class="bg-white rounded-2xl shadow-soft overflow-hidden hover:-translate-y-1 transition">
          <img src="https://picsum.photos/600/400?random=303" alt="Wooden Carving" class="w-full h-56 object-cover">
          <div class="p-5">
            <h4 class="font-semibold text-lg">Wooden Carving</h4>
            <p class="text-gray-600 text-sm">Traditional Garhwali craft</p>
            <div class="flex justify-between items-center mt-4">
              <span class="font-bold text-accent">₹1500</span>
              <button class="bg-primary text-white px-4 py-2 rounded-lg">Add</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Gallery (engaging photos) -->
  <section id="gallery" class="bg-white">
    <div class="max-w-7xl mx-auto px-6 py-14">
      <h3 class="text-3xl font-bold mb-8">Photo Gallery</h3>
      <div class="columns-2 md:columns-3 gap-4 [column-fill:_balance]">
        <!-- Replace/add your real images as needed -->
        <img class="mb-4 rounded-2xl hover:scale-[1.01] transition origin-center cursor-pointer gallery-img" src="https://picsum.photos/600/800?random=410" alt="">
        <img class="mb-4 rounded-2xl hover:scale-[1.01] transition cursor-pointer gallery-img" src="https://picsum.photos/600/500?random=411" alt="">
        <img class="mb-4 rounded-2xl hover:scale-[1.01] transition cursor-pointer gallery-img" src="https://picsum.photos/600/700?random=412" alt="">
        <img class="mb-4 rounded-2xl hover:scale-[1.01] transition cursor-pointer gallery-img" src="https://picsum.photos/600/600?random=413" alt="">
        <img class="mb-4 rounded-2xl hover:scale-[1.01] transition cursor-pointer gallery-img" src="https://picsum.photos/600/750?random=414" alt="">
        <img class="mb-4 rounded-2xl hover:scale-[1.01] transition cursor-pointer gallery-img" src="https://picsum.photos/600/650?random=415" alt="">
      </div>
    </div>

    <!-- Lightbox -->
    <div id="lightbox" class="fixed inset-0 bg-black/80 hidden items-center justify-center p-4 z-[60]">
      <button id="lightboxClose" class="absolute top-5 right-5 text-white text-2xl" aria-label="Close"><i class="fas fa-times"></i></button>
      <img id="lightboxImg" src="" alt="" class="max-h-[85vh] max-w-full rounded-2xl shadow-soft">
    </div>
  </section>

  <!-- Blog -->
  <section id="blog" class="bg-light">
    <div class="max-w-7xl mx-auto px-6 py-14">
      <h3 class="text-3xl font-bold text-center mb-10">From Our Blog</h3>
      <div class="grid md:grid-cols-3 gap-8">
        <article class="bg-white rounded-2xl shadow-soft overflow-hidden">
          <img src="https://picsum.photos/600/360?random=501" class="w-full h-44 object-cover" alt="">
          <div class="p-5">
            <h4 class="font-semibold text-lg">The Art of Wool Weaving</h4>
            <p class="text-gray-600 text-sm mt-2">Kumaoni handloom की सदियों पुरानी परंपरा।</p>
            <a href="#" class="inline-block text-accent mt-3">Read More →</a>
          </div>
        </article>
        <article class="bg-white rounded-2xl shadow-soft overflow-hidden">
          <img src="https://picsum.photos/600/360?random=502" class="w-full h-44 object-cover" alt="">
          <div class="p-5">
            <h4 class="font-semibold text-lg">Woodwork of Garhwal</h4>
            <p class="text-gray-600 text-sm mt-2">देवभूमि की काष्ठ कला और intricate designs।</p>
            <a href="#" class="inline-block text-accent mt-3">Read More →</a>
          </div>
        </article>
        <article class="bg-white rounded-2xl shadow-soft overflow-hidden">
          <img src="https://picsum.photos/600/360?random=503" class="w-full h-44 object-cover" alt="">
          <div class="p-5">
            <h4 class="font-semibold text-lg">Pahadi Superfoods 101</h4>
            <p class="text-gray-600 text-sm mt-2">भट्ट, गहत, झंगोरा—स्वाद और सेहत का संगम।</p>
            <a href="#" class="inline-block text-accent mt-3">Read More →</a>
          </div>
        </article>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="bg-white">
    <div class="max-w-7xl mx-auto px-6 py-16 text-center">
      <h3 class="text-3xl font-bold mb-2">Contact Us</h3>
      <p class="text-gray-600 mb-8">Orders, bulk enquiries या collaborations—हमें लिखें।</p>
      <form class="max-w-xl mx-auto bg-light rounded-2xl p-6 shadow-soft">
        <div class="grid sm:grid-cols-2 gap-4">
          <input type="text" placeholder="Your Name" class="w-full border p-3 rounded-lg">
          <input type="email" placeholder="Email" class="w-full border p-3 rounded-lg">
        </div>
        <input type="text" placeholder="Phone (optional)" class="w-full border p-3 rounded-lg mt-4">
        <textarea placeholder="Your Message" rows="5" class="w-full border p-3 rounded-lg mt-4"></textarea>
        <button class="mt-4 bg-accent text-white px-6 py-3 rounded-lg w-full sm:w-auto">Send Message</button>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-dark text-light">
    <div class="max-w-7xl mx-auto px-6 py-10 grid md:grid-cols-4 gap-8">
      <div>
        <h4 class="font-bold text-white mb-3">About</h4>
        <p class="text-gray-300 text-sm">Uttarakhand Kala Sanskriti स्थानीय कारीगरों और किसानों के असली उत्पाद सीधे आप तक पहुँचाता है।</p>
      </div>
      <div>
        <h4 class="font-bold text-white mb-3">Quick Links</h4>
        <ul class="space-y-2 text-gray-300 text-sm">
          <li><a href="#kale-bhatt" class="hover:text-accent">Kale Bhatt</a></li>
          <li><a href="#shop" class="hover:text-accent">Shop</a></li>
          <li><a href="#gallery" class="hover:text-accent">Gallery</a></li>
          <li><a href="#blog" class="hover:text-accent">Blog</a></li>
        </ul>
      </div>
      <div>
        <h4 class="font-bold text-white mb-3">Contact</h4>
        <ul class="text-gray-300 text-sm space-y-1">
          <li><i class="fas fa-envelope mr-2"></i>support@uttarakhandkalasanskriti.com</li>
          <li><i class="fas fa-phone mr-2"></i>+91-98XXXXXXXX</li>
          <li><i class="fas fa-map-marker-alt mr-2"></i>Dehradun, Uttarakhand</li>
        </ul>
      </div>
      <div>
        <h4 class="font-bold text-white mb-3">Follow</h4>
        <div class="flex space-x-4 text-xl">
          <a href="#" aria-label="Facebook" class="hover:text-accent"><i class="fab fa-facebook-f"></i></a>
          <a href="#" aria-label="Instagram" class="hover:text-accent"><i class="fab fa-instagram"></i></a>
          <a href="#" aria-label="Twitter" class="hover:text-accent"><i class="fab fa-twitter"></i></a>
          <a href="#" aria-label="YouTube" class="hover:text-accent"><i class="fab fa-youtube"></i></a>
        </div>
      </div>
    </div>
    <div class="border-t border-white/10">
      <p class="text-center text-gray-400 text-sm py-4">© 2025 Uttarakhand Kala Sanskriti. All rights reserved.</p>
    </div>
  </footer>

  <!-- Minimal JS: cart + mobile + gallery -->
  <script>
    // Mobile menu
    const menuBtn = document.getElementById('menuBtn');
    const mobileMenu = document.getElementById('mobileMenu');
    menuBtn?.addEventListener('click', () => mobileMenu.classList.toggle('hidden'));

    // Cart state (localStorage)
    const CART_KEY = 'uks_cart';
    const cartCountEl = document.getElementById('cartCount');
    const readCart = () => JSON.parse(localStorage.getItem(CART_KEY) || '{"KB":0}');
    const writeCart = (c) => localStorage.setItem(CART_KEY, JSON.stringify(c));
    const refreshCount = () => {
      const c = readCart();
      const total = Object.values(c).reduce((a,b)=>a+Number(b||0),0);
      cartCountEl.textContent = total;
    };
    refreshCount();

    // Quantity controls
    const qtyInput = document.getElementById('qtyKB');
    document.querySelectorAll('[data-qty]').forEach(btn=>{
      btn.addEventListener('click',()=>{
        const type = btn.getAttribute('data-qty');
        let v = parseInt(qtyInput.value || '1',10);
        if(type==='minus') v = Math.max(1, v-1);
        if(type==='plus') v = v+1;
        qtyInput.value = v;
      });
    });

    // Add to cart (featured)
    document.getElementById('addKB')?.addEventListener('click',()=>{
      const qty = Math.max(1, parseInt(qtyInput.value||'1',10));
      const cart = readCart();
      cart.KB = (cart.KB||0) + qty;
      writeCart(cart);
      refreshCount();
      // small feedback
      const btn = document.getElementById('addKB');
      btn.disabled = true;
      const old = btn.innerHTML;
      btn.innerHTML = '<i class="fas fa-check mr-2"></i>Added';
      setTimeout(()=>{ btn.disabled=false; btn.innerHTML=old; }, 1200);
    });

    // Add to cart (quick add buttons)
    document.querySelectorAll('[data-add="KB"]').forEach(el=>{
      el.addEventListener('click',()=>{
