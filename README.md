<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>لوحة القيادة الاستراتيجية 2026 | جامعة الملك عبدالعزيز</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;500;600;700;800;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
    <style>
        body { font-family: 'Cairo', sans-serif; }
        .glass { background: rgba(255,255,255,0.05); backdrop-filter: blur(20px); border: 1px solid rgba(255,255,255,0.1); }
        .glow { box-shadow: 0 0 50px -15px rgb(59 130 246 / 0.5); }
        .hero { background: linear-gradient(135deg, #0a1729 0%, #1e3a8a 50%, #164e63 100%); }
        .stat { font-variant-numeric: tabular-nums; transition: all 1.5s ease; }
        .section-title::after { content:''; position:absolute; bottom:-10px; right:0; width:80px; height:4px; background:linear-gradient(to left,#3b82f6,#10b981); border-radius:9999px; }
        .logo-img { filter: drop-shadow(0 10px 20px rgba(0,0,0,0.3)); }
    </style>
</head>
<body class="bg-zinc-950 text-slate-200 min-h-screen">

<!-- Navbar مع الشعار الرسمي -->
<nav class="fixed top-0 z-50 w-full bg-black/90 backdrop-blur-2xl border-b border-white/10">
    <div class="max-w-screen-2xl mx-auto px-8 py-6 flex justify-between items-center">
        <div class="flex items-center gap-4">
            <!-- الشعار الرسمي هنا -->
            <img src="https://upload.wikimedia.org/wikipedia/ar/4/4a/%D8%B4%D8%B9%D8%A7%D8%B1_%D8%AC%D8%A7%D9%85%D8%B9%D8%A9_%D8%A7%D9%84%D9%85%D9%84%D9%83_%D8%B9%D8%A8%D8%AF_%D8%A7%D9%84%D8%B9%D8%B2%D9%8A%D8%B2.svg" 
                 alt="شعار جامعة الملك عبدالعزيز" 
                 class="logo-img h-14 w-auto">
            <div>
                <h1 class="text-2xl font-black tracking-tighter">جامعة الملك عبدالعزيز</h1>
                <p class="text-xs text-blue-400">نائب رئيس الجامعة للدراسات العليا والبحث العلمي</p>
            </div>
        </div>
        <div class="flex gap-4">
            <button onclick="window.print()" class="px-7 py-3 rounded-2xl bg-white/10 hover:bg-white/20 flex items-center gap-3 transition-all">
                <i class="fas fa-print"></i> طباعة
            </button>
            <button onclick="downloadPDF()" class="px-8 py-3 bg-gradient-to-r from-blue-600 to-emerald-600 rounded-2xl font-bold flex items-center gap-3 hover:scale-105 transition-all">
                <i class="fas fa-download"></i> تحميل PDF
            </button>
        </div>
    </div>
</nav>

<!-- Hero مع الشعار أيضاً -->
<header class="hero min-h-screen flex items-center pt-24">
    <div class="max-w-screen-2xl mx-auto px-8 grid grid-cols-12 gap-12 items-center">
        <div class="col-span-12 lg:col-span-7">
            <div class="inline-flex bg-emerald-500/10 text-emerald-400 px-6 py-2 rounded-3xl text-sm font-medium mb-8">
                <i class="fas fa-star mr-2"></i> إصدار 2026 – نسخة محدثة وفق تصنيف 2024
            </div>
            <h1 class="text-7xl lg:text-[5.5rem] font-black leading-none tracking-tighter">لوحة القيادة<br>الاستراتيجية</h1>
            <p class="mt-6 text-3xl text-slate-400">الموقف الاستراتيجي لقطاع النشر العلمي</p>
            
            <div class="mt-16 grid grid-cols-2 md:grid-cols-4 gap-6">
                <div class="glass p-8 rounded-3xl glow text-center">
                    <div id="stat1" class="stat text-6xl font-bold text-emerald-400">36</div>
                    <div class="text-slate-400 mt-2 text-lg">مجلة علمية</div>
                </div>
                <div class="glass p-8 rounded-3xl glow text-center">
                    <div id="stat2" class="stat text-6xl font-bold text-blue-400">3</div>
                    <div class="text-slate-400 mt-2 text-lg">مجلات Q1</div>
                </div>
                <div class="glass p-8 rounded-3xl glow text-center">
                    <div id="stat3" class="stat text-6xl font-bold text-amber-400">11.7</div>
                    <div class="text-slate-400 mt-2 text-lg">أعلى CiteScore</div>
                </div>
                <div class="glass p-8 rounded-3xl glow text-center">
                    <div class="text-rose-400 text-6xl font-bold">سري</div>
                    <div class="text-slate-400 mt-2 text-lg">للاستخدام الداخلي</div>
                </div>
            </div>
        </div>
        
        <div class="col-span-12 lg:col-span-5">
            <div class="glass p-12 rounded-3xl glow text-center">
                <img src="https://upload.wikimedia.org/wikipedia/ar/4/4a/%D8%B4%D8%B9%D8%A7%D8%B1_%D8%AC%D8%A7%D9%85%D8%B9%D8%A9_%D8%A7%D9%84%D9%85%D9%84%D9%83_%D8%B9%D8%A8%D8%AF_%D8%A7%D9%84%D8%B9%D8%B2%D9%8A%D8%B2.svg" 
                     alt="شعار جامعة الملك عبدالعزيز" 
                     class="mx-auto logo-img h-32 w-auto mb-8">
                <h2 class="text-4xl font-bold leading-tight">من مرحلة بناء التميز<br>إلى مرحلة إدارة التميز</h2>
            </div>
        </div>
    </div>
</header>

<!-- باقي المحتوى (الـ Info Header + Sidebar + الأقسام 1-21 + الخلاصة) -->
<!-- للاختصار هنا، انسخ باقي الكود من النسخة السابقة التي أرسلتها لك (من "Info Header" إلى النهاية) وألصقه بعد </header> مباشرة -->

<!-- Script (نفس السابق مع الـ counters والـ ScrollSpy) -->
<script>
    function animateValue(id, start, end, duration) {
        let startTimestamp = null;
        const step = (timestamp) => {
            if (!startTimestamp) startTimestamp = timestamp;
            const progress = Math.min((timestamp - startTimestamp) / duration, 1);
            const value = Math.floor(progress * (end - start) + start);
            document.getElementById(id).innerHTML = value + (id === "stat3" ? ".7" : "");
            if (progress < 1) window.requestAnimationFrame(step);
        };
        window.requestAnimationFrame(step);
    }
    window.onload = () => {
        animateValue("stat1", 0, 36, 2000);
        animateValue("stat2", 0, 3, 1500);
        animateValue("stat3", 0, 11, 2500);
    };

    function downloadPDF() {
        alert("جاري تحميل النسخة PDF...\n(اضغط Ctrl+P → Save as PDF لأفضل جودة)");
    }
</script>
</body>
</html>
