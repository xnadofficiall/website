<!DOCTYPE html>
<html lang="id" class="dark">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>X-NadStore | Jual Script Bot</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      darkMode: 'class'
    }
  </script>
  <style>
    body { font-family: 'Poppins', sans-serif; }
    .card {
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .card:hover {
      transform: scale(1.04);
      box-shadow: 0 0 25px rgba(99, 102, 241, 0.35);
    }
    .btn {
      transition: all 0.25s ease-in-out;
    }
    .btn:hover {
      transform: scale(1.05);
    }
  </style>
</head>

<body class="relative text-black dark:text-white min-h-screen transition-colors duration-500 bg-gray-100 dark:bg-gray-900">

  <!-- Background Glowing -->
  <div class="absolute inset-0 -z-10 bg-gradient-to-tr from-indigo-400/10 via-purple-500/5 to-pink-500/10 dark:from-indigo-600/20 dark:via-purple-700/10 dark:to-pink-600/20 blur-2xl"></div>

  <!-- Toggle Mode -->
  <div class="fixed top-4 right-4 z-50">
    <button id="toggleMode" class="bg-indigo-600 text-white px-3 py-1.5 rounded-full text-sm hover:bg-indigo-700 btn">
      🌙 Dark Mode
    </button>
  </div>

  <!-- Header -->
  <header class="text-center py-14 px-4">
    <h1 class="text-5xl font-extrabold text-indigo-600 dark:text-indigo-400 drop-shadow-lg">🛍️Nad Store</h1>
    <p class="text-gray-700 dark:text-gray-300 mt-4 text-lg max-w-2xl mx-auto leading-relaxed">
      Tempat Jasbug/Jasabug
    </p>
    <div class="mt-6 flex justify-center gap-4">
      <a href="https://wa.me/6282120738778" target="_blank" class="bg-green-500 hover:bg-green-600 px-6 py-2 rounded-full font-semibold text-white shadow-lg btn">
        💬 Hubungi Admin
      </a>
    </div>
  </header>

  <!-- Produk -->
  <main class="max-w-7xl mx-auto px-6">
    <div class="grid sm:grid-cols-2 md:grid-cols-3 gap-8 mt-6">

      <!-- Produk 1 -->
      <div class="card bg-white dark:bg-white/5 p-6 rounded-2xl shadow-lg">
        <h2 class="text-xl font-bold text-indigo-600 dark:text-indigo-400 mb-2">JASBUG/JASABUG💣</h2>
         <p class="text-sm text-gray-700 dark:text-gray-300 mb-2"> DI JAMIN HAPUS APK
        <p class="text-sm text-gray-500 dark:text-gray-400 italic">1 nomor 5.000</p>
        <p class="text-sm text-gray-500 dark:text-gray-400 italic">2 nomor 10.000</p>
        <p class="text-sm text-gray-500 dark :text-gray-400 italic">3 nomor 12.000</p>
        <div class="mt-4 flex items-center justify-between">
          <span class="text-green-600 dark:text-green-400 font-bold text-lg">Rp 5.000 - 12.000</span>
          
          <a href="https://wa.me/6282120738778?text=Sewa%20Murbug%20atau%20Jasbug" target="_blank" class="bg-indigo-600 hover:bg-indigo-700 px-4 py-1.5 rounded-full text-sm font-medium text-white btn">Order</a>
          </div>
        </div>
        
      <!-- Produk 3 -->
      <div class="card bg-white dark:bg-white/5 p-6 rounded-2xl shadow-lg">
        <h2 class="text-xl font-bold text-indigo-600 dark:text-indigo-400 mb-2">EFECK BUG</h2>
         <p class="text-sm text-gray-700 dark:text-gray-300 mb-2">YG TERDAMPAK PADA TARGET TERSEBUT
        </p>• DI JAMIN MENTAL MENTAL WA NYA☑️
        </p>• FORCE CLOSE INVISIBLE☑️
        </P>• FORCE CLOSE INFINITY☑️
        </P>• DELAY HARD☑️
        </P>• CRASH ALL WHATSAPP☑️
        </p>• AUTO HAPUS APK☑️
        
        </div>
      </div>

    </div>
  </main>

  <!-- Footer -->
  <footer class="text-center text-sm text-gray-500 dark:text-gray-400 mt-16 pb-10 px-4">
    &copy; 2025 <span class="text-indigo-600 dark:text-indigo-400 font-medium">X-Nad Official</span> — Open Jasbug/Jasabug
  </footer>

  <!-- Toggle Dark Mode -->
  <script>
    const toggle = document.getElementById('toggleMode');
    toggle.addEventListener('click', () => {
      document.documentElement.classList.toggle('dark');
      toggle.textContent = document.documentElement.classList.contains('dark')
        ? '☀️ Light Mode'
        : '🌙 Dark Mode';
    });
  </script>

</body>
</html>
