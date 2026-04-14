<!DOCTYPE html>

<html class="light" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Skincare | Onvynix Labs</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif:ital,wght@0,400;0,700;1,400&amp;family=Manrope:wght@300;400;500;600&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "on-secondary-fixed": "#261900",
                        "inverse-primary": "#f7b6b6",
                        "secondary": "#775a19",
                        "on-primary-container": "#66393a",
                        "on-background": "#1a1c1d",
                        "on-primary-fixed-variant": "#673a3b",
                        "on-surface-variant": "#514343",
                        "on-secondary-container": "#785a1a",
                        "surface-dim": "#d9dadb",
                        "primary": "#835151",
                        "surface": "#f9f9fa",
                        "surface-bright": "#f9f9fa",
                        "on-primary": "#ffffff",
                        "on-primary-fixed": "#341012",
                        "on-tertiary": "#ffffff",
                        "on-secondary": "#ffffff",
                        "surface-container-low": "#f3f3f4",
                        "surface-container": "#eeeeef",
                        "on-error": "#ffffff",
                        "primary-container": "#e2a4a4",
                        "on-error-container": "#93000a",
                        "surface-container-highest": "#e2e2e3",
                        "primary-fixed": "#ffdad9",
                        "on-tertiary-container": "#444647",
                        "tertiary-container": "#b3b4b5",
                        "secondary-fixed-dim": "#e9c176",
                        "tertiary-fixed-dim": "#c6c6c7",
                        "on-tertiary-fixed": "#1a1c1d",
                        "tertiary-fixed": "#e2e2e3",
                        "surface-container-lowest": "#ffffff",
                        "outline": "#847373",
                        "error-container": "#ffdad6",
                        "outline-variant": "#d6c2c1",
                        "on-surface": "#1a1c1d",
                        "primary-fixed-dim": "#f7b6b6",
                        "secondary-container": "#fed488",
                        "background": "#f9f9fa",
                        "inverse-surface": "#2f3132",
                        "on-tertiary-fixed-variant": "#454748",
                        "tertiary": "#5d5f60",
                        "surface-container-high": "#e8e8e9",
                        "on-secondary-fixed-variant": "#5d4201",
                        "surface-variant": "#e2e2e3",
                        "surface-tint": "#835151",
                        "secondary-fixed": "#ffdea5",
                        "inverse-on-surface": "#f0f1f1",
                        "error": "#ba1a1a"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.125rem",
                        "lg": "0.25rem",
                        "xl": "0.5rem",
                        "full": "0.75rem"
                    },
                    "fontFamily": {
                        "headline": ["Noto Serif"],
                        "body": ["Manrope"],
                        "label": ["Manrope"]
                    }
                },
            },
        }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 300, 'GRAD' 0, 'opsz' 24;
        }
        body {
            font-family: 'Manrope', sans-serif;
            background-color: #f9f9fa;
            color: #1a1c1d;
        }
        .serif-headline {
            font-family: 'Noto Serif', serif;
        }
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
    </style>
</head>
<body class="bg-background text-on-surface">
<!-- TopAppBar Navigation Shell -->
<nav class="fixed top-0 w-full z-50 bg-[#f9f9fa]/80 dark:bg-slate-950/80 backdrop-blur-xl">
<div class="flex justify-between items-center px-8 h-20 w-full max-w-[1440px] mx-auto">
<div class="font-['Noto_Serif'] text-2xl font-bold tracking-tighter text-[#1a1c1d] dark:text-slate-100 cursor-pointer active:scale-95 transition-all">
                Onvynix Labs
            </div>
<div class="hidden md:flex items-center space-x-8 font-['Noto_Serif'] text-lg tracking-tight">
<a class="text-[#835151] dark:text-[#e2a4a4] border-b border-[#775a19] pb-1 cursor-pointer transition-all active:scale-95" href="#">Skincare</a>
<a class="text-[#1a1c1d] dark:text-slate-400 hover:text-[#835151] transition-colors cursor-pointer transition-all active:scale-95" href="#">Haircare</a>
<a class="text-[#1a1c1d] dark:text-slate-400 hover:text-[#835151] transition-colors cursor-pointer transition-all active:scale-95" href="#">Fragrance</a>
<a class="text-[#1a1c1d] dark:text-slate-400 hover:text-[#835151] transition-colors cursor-pointer transition-all active:scale-95" href="#">Curated</a>
<a class="text-[#1a1c1d] dark:text-slate-400 hover:text-[#835151] transition-colors cursor-pointer transition-all active:scale-95" href="#">About</a>
</div>
<div class="flex items-center space-x-6">
<button class="material-symbols-outlined text-[#1a1c1d] dark:text-slate-100 hover:opacity-70 transition-opacity duration-300 active:scale-95">shopping_bag</button>
<button class="material-symbols-outlined text-[#1a1c1d] dark:text-slate-100 hover:opacity-70 transition-opacity duration-300 active:scale-95">person</button>
</div>
</div>
</nav>
<main class="pt-32 pb-20 px-8 max-w-[1440px] mx-auto">
<!-- Editorial Header Section -->
<header class="mb-16 md:mb-24 flex flex-col md:flex-row items-end justify-between gap-8">
<div class="max-w-2xl">
<span class="text-secondary label-md tracking-[0.2em] uppercase font-semibold text-xs mb-4 block">The Curation</span>
<h1 class="serif-headline text-5xl md:text-7xl font-light text-on-surface leading-tight tracking-tighter">
                    Essential <br/> <span class="italic font-normal text-primary">Skincare</span>
</h1>
<p class="mt-8 text-on-surface-variant font-body text-lg leading-relaxed max-w-lg">
                    A meticulous selection of botanical alchemy and clinical precision. We believe in the vibration of raw ingredients and the clarity of modern science.
                </p>
</div>
<div class="w-full md:w-1/3 aspect-[4/3] bg-surface-container overflow-hidden rounded-xl">
<img class="w-full h-full object-cover grayscale-[20%] hover:scale-105 transition-transform duration-700" data-alt="Minimalist luxury skincare bottles on a stone surface with soft morning light and long shadows" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBGRk1gOECy5rllYBXmOsk8WgGBPibeB25lX6pDZLUw7pIcbyWTZKDHvbkLRL-JjW1ZA_WnUS_5lT9ewtSpMdQ68T9Kg0hq8j5_PSI1vzJwbrerdeGVjgiQ0919q9eqXicUSevBzKa23XVe9ORy61iSRtvJaq0J66-ziNF77tbotS6kwI3-su18q_HBaBA7XC5m4XISUtXVh0o2IxiXn63JB8bcDNKaL0oUcjWM8SrnkdRr_UgAoU3iM37W_rBzC9Zfh-3HpXEnFb9B"/>
</div>
</header>
<div class="flex flex-col md:flex-row gap-12">
<!-- Sidebar Filters -->
<aside class="w-full md:w-64 flex-shrink-0 space-y-12">
<div class="space-y-6">
<h3 class="font-headline text-xl text-on-surface border-b border-outline-variant pb-2 opacity-80">Skin Type</h3>
<ul class="space-y-4 font-body text-sm">
<li class="flex items-center justify-between group cursor-pointer text-on-surface-variant hover:text-primary transition-colors">
<span>Oily &amp; Combination</span>
<span class="text-[10px] opacity-40 group-hover:opacity-100 transition-opacity">12</span>
</li>
<li class="flex items-center justify-between group cursor-pointer text-primary transition-colors">
<span>Dry &amp; Dehydrated</span>
<span class="text-[10px] opacity-100">08</span>
</li>
<li class="flex items-center justify-between group cursor-pointer text-on-surface-variant hover:text-primary transition-colors">
<span>Sensitive</span>
<span class="text-[10px] opacity-40 group-hover:opacity-100 transition-opacity">15</span>
</li>
<li class="flex items-center justify-between group cursor-pointer text-on-surface-variant hover:text-primary transition-colors">
<span>Mature</span>
<span class="text-[10px] opacity-40 group-hover:opacity-100 transition-opacity">09</span>
</li>
</ul>
</div>
<div class="space-y-6">
<h3 class="font-headline text-xl text-on-surface border-b border-outline-variant pb-2 opacity-80">Brand</h3>
<ul class="space-y-4 font-body text-sm">
<li class="flex items-center space-x-3 cursor-pointer group">
<div class="w-3 h-3 border border-outline rounded-sm group-hover:border-primary transition-colors"></div>
<span class="text-on-surface-variant group-hover:text-primary transition-colors">Aurelia Probiotic</span>
</li>
<li class="flex items-center space-x-3 cursor-pointer group">
<div class="w-3 h-3 border border-primary bg-primary rounded-sm"></div>
<span class="text-primary">Onvynix Signature</span>
</li>
<li class="flex items-center space-x-3 cursor-pointer group">
<div class="w-3 h-3 border border-outline rounded-sm group-hover:border-primary transition-colors"></div>
<span class="text-on-surface-variant group-hover:text-primary transition-colors">Vintner's Daughter</span>
</li>
<li class="flex items-center space-x-3 cursor-pointer group">
<div class="w-3 h-3 border border-outline rounded-sm group-hover:border-primary transition-colors"></div>
<span class="text-on-surface-variant group-hover:text-primary transition-colors">Aesop Botanicals</span>
</li>
</ul>
</div>
<div class="space-y-6">
<h3 class="font-headline text-xl text-on-surface border-b border-outline-variant pb-2 opacity-80">Price Range</h3>
<div class="relative pt-4">
<div class="h-0.5 w-full bg-surface-container-highest rounded-full">
<div class="absolute h-0.5 bg-secondary-fixed-dim" style="left: 20%; right: 30%;"></div>
</div>
<div class="absolute top-3 left-[20%] w-3 h-3 bg-white border-2 border-secondary rounded-full shadow-sm"></div>
<div class="absolute top-3 right-[30%] w-3 h-3 bg-white border-2 border-secondary rounded-full shadow-sm"></div>
</div>
<div class="flex justify-between text-[10px] font-bold text-secondary uppercase tracking-widest pt-2">
<span>$45</span>
<span>$280</span>
</div>
</div>
</aside>
<!-- Product Grid -->
<section class="flex-1">
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-x-8 gap-y-16">
<!-- Card 1 -->
<div class="group flex flex-col">
<div class="relative aspect-[3/4] overflow-hidden mb-6 bg-surface-container-low rounded-xl">
<img class="w-full h-full object-cover transition-transform duration-1000 group-hover:scale-110" data-alt="Frosted glass bottle of facial serum with golden liquid inside, minimalist botanical background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCUxAllF12SQQwkyjZcVkVm5NDUGSLytDhg_b4AD8LvaVVc411uKeg5B2NlkJ8BKel_cJzTgccq0Prz0IZ_5LK0my0gY_byCdW8TipgQD-0wgKMIhuPk49vh65Yav2VVpqagqUA-e_GQ105PY7pZSnRVCfWUjzFVsv39dqP0uy2ZtbfqcXQl-JhfBZex1YcRiEBcdS780SvEjWV-zm_8ZWJNX8KSwrG160VUHQpHo_UI15xwJhXRc7C0Gda_5sVFjLYQ27kcHwtyHek"/>
<div class="absolute top-4 right-4">
<span class="bg-white/80 backdrop-blur-md px-3 py-1 text-[10px] uppercase tracking-widest font-bold text-secondary rounded-full">Bestseller</span>
</div>
</div>
<h3 class="font-headline text-2xl text-on-surface group-hover:text-primary transition-colors duration-300">Ethereal Glow Serum</h3>
<p class="mt-2 text-on-surface-variant text-sm font-body leading-relaxed line-clamp-2">
                            A concentrated fusion of peptide-rich botanicals and hyaluronic acid for transcendent radiance.
                        </p>
<div class="mt-4 flex items-baseline justify-between mb-6">
<span class="text-lg font-medium text-on-surface">$120</span>
<span class="text-[10px] uppercase tracking-widest text-secondary font-bold">In Stock</span>
</div>
<button class="w-full bg-primary text-on-primary py-4 text-xs uppercase tracking-[0.2em] font-semibold transition-all hover:bg-on-primary-container active:scale-95">
                            Buy at Official Store
                        </button>
</div>
<!-- Card 2 -->
<div class="group flex flex-col mt-8 md:mt-0">
<div class="relative aspect-[3/4] overflow-hidden mb-6 bg-surface-container-low rounded-xl">
<img class="w-full h-full object-cover transition-transform duration-1000 group-hover:scale-110" data-alt="Abstract composition of white skincare cream texture with artistic curves and soft lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCyMgYdCqCiA0B5y31Ls7MV6oSNkmAvgbnD0r2mYH54pEYHvs7dIv5o9Rp7g-U7t9KiKnFV8zNF-8m6xjcBaz-prKTSiZWpRr0LxyKTmxnqrlq9ynIoOCMVDvbhNDxp43Oznlyt7MICVGknsbu2MbLNilwTEMiDhadPuBcsopizTEqonENxLwXjfDISBeBijV_9PPvrzlb_GhlFq0Eg_qMT9Obl0XkN1wnDpgm0MFzef5GVA4u0bqbfM4XjCKnLOsnsKcXIpuSf0wfN"/>
</div>
<h3 class="font-headline text-2xl text-on-surface group-hover:text-primary transition-colors duration-300">Midnight Renewal Balm</h3>
<p class="mt-2 text-on-surface-variant text-sm font-body leading-relaxed line-clamp-2">
                            Restorative night treatment infused with blue tansy and rare orchid stem cells.
                        </p>
<div class="mt-4 flex items-baseline justify-between mb-6">
<span class="text-lg font-medium text-on-surface">$95</span>
</div>
<button class="w-full bg-primary text-on-primary py-4 text-xs uppercase tracking-[0.2em] font-semibold transition-all hover:bg-on-primary-container active:scale-95">
                            Buy at Official Store
                        </button>
</div>
<!-- Card 3 -->
<div class="group flex flex-col md:translate-y-12">
<div class="relative aspect-[3/4] overflow-hidden mb-6 bg-surface-container-low rounded-xl">
<img class="w-full h-full object-cover transition-transform duration-1000 group-hover:scale-110" data-alt="Close-up of luxury dark amber glass bottle with clinical dropper on a clean white surface" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDyEyBKcYL7INX7TRAk5AwJfiPA5yF5nSkPKRya9R68ADfa6Mnp-YbINXdKigXbyPkyMctxeNIZ9opBj2s9L0CB08HsBYnWlD2kMI8tU_ECJKprcRS2gV4oEItftynSq58Ew8SlPfpb0_GuwrWUJ4X-9zmajR0kI5VYKcGK9Zo2gCEFcnx4xahd9tfbj63QxeZahW2R81XJNqXNTedPmqrpkuOWn9pmgPXWh1nyldD5b2GNN1e7pnX7dsGCMfRm5Ng9mYSn0OW2PtM6"/>
<div class="absolute top-4 right-4">
<span class="bg-secondary-fixed/90 backdrop-blur-md px-3 py-1 text-[10px] uppercase tracking-widest font-bold text-on-secondary-fixed rounded-full">New Arrival</span>
</div>
</div>
<h3 class="font-headline text-2xl text-on-surface group-hover:text-primary transition-colors duration-300">Velvet Cleansing Oil</h3>
<p class="mt-2 text-on-surface-variant text-sm font-body leading-relaxed line-clamp-2">
                            Gentle transformation for the skin using fermented camellia oil and damask rose.
                        </p>
<div class="mt-4 flex items-baseline justify-between mb-6">
<span class="text-lg font-medium text-on-surface">$68</span>
</div>
<button class="w-full bg-primary text-on-primary py-4 text-xs uppercase tracking-[0.2em] font-semibold transition-all hover:bg-on-primary-container active:scale-95">
                            Buy at Official Store
                        </button>
</div>
<!-- Card 4 -->
<div class="group flex flex-col md:mt-24 lg:mt-0">
<div class="relative aspect-[3/4] overflow-hidden mb-6 bg-surface-container-low rounded-xl">
<img class="w-full h-full object-cover transition-transform duration-1000 group-hover:scale-110" data-alt="Luxury eye cream container on a reflective marble surface with soft golden light diffusion" src="https://lh3.googleusercontent.com/aida-public/AB6AXuC7ZjgsXrkGJSxaPEs9ZC7OVDiEUC2dYnIInn9AF7SIVJmft7n4AFusVNBeaA4KrxdtvBd58vvR57TZuNqrj8nxUGk2yxuWwEKj6inbr5tSFOagVSwWkaYtEmZ-qoT-yRPVwBBy7gz9C245J4oFdndw7UxvuNedvWCDivx_qa0yfcYyZiOUR-5kIYpzimlBmzH-ppUK4WSXnwx7Ahwm8meTlwpdZuERrVuu0q4OJnqmWl8iQ7jaUSvEq7LX1PykttaFaRtXgXI-_qKI"/>
</div>
<h3 class="font-headline text-2xl text-on-surface group-hover:text-primary transition-colors duration-300">Prism Eye Elixir</h3>
<p class="mt-2 text-on-surface-variant text-sm font-body leading-relaxed line-clamp-2">
                            Targeted luminosity for the delicate eye area with encapsulated vitamin C.
                        </p>
<div class="mt-4 flex items-baseline justify-between mb-6">
<span class="text-lg font-medium text-on-surface">$82</span>
</div>
<button class="w-full bg-primary text-on-primary py-4 text-xs uppercase tracking-[0.2em] font-semibold transition-all hover:bg-on-primary-container active:scale-95">
                            Buy at Official Store
                        </button>
</div>
<!-- Card 5 (Asymmetric placement focus) -->
<div class="group flex flex-col lg:translate-y-8">
<div class="relative aspect-[3/4] overflow-hidden mb-6 bg-surface-container-low rounded-xl">
<img class="w-full h-full object-cover transition-transform duration-1000 group-hover:scale-110" data-alt="Professional flat lay of various skincare products in neutral tones with organic shapes" src="https://lh3.googleusercontent.com/aida-public/AB6AXuB9VBwa8nBhqe3u4LCVpZmPmPAvRx917G1CiUinQikpXByiQSV1RU6RpXnkfpKn0b-FzB9L_p6P_OPURTZJapket-CgQ6eGDtolI0JbQqknGdDy_0e8Fjlg71MS22cxWr3LIdWPIGdDlAp4t2FqXvWshiE9w1wVMSmCxxGRixuCJHpi3ayvEAHXaPAMHmx0dWZwhK5so9pMSRVS97BQta54n1_ewneDXhBtYtS6wQIYQypjo89oyzM7qj76SdFzNOW0d4WLt3l0kXit"/>
</div>
<h3 class="font-headline text-2xl text-on-surface group-hover:text-primary transition-colors duration-300">Lunar Clay Mask</h3>
<p class="mt-2 text-on-surface-variant text-sm font-body leading-relaxed line-clamp-2">
                            Detoxifying kaolin clay blended with activated charcoal and essential minerals.
                        </p>
<div class="mt-4 flex items-baseline justify-between mb-6">
<span class="text-lg font-medium text-on-surface">$55</span>
</div>
<button class="w-full bg-primary text-on-primary py-4 text-xs uppercase tracking-[0.2em] font-semibold transition-all hover:bg-on-primary-container active:scale-95">
                            Buy at Official Store
                        </button>
</div>
<!-- Card 6 -->
<div class="group flex flex-col md:translate-y-12 lg:translate-y-24">
<div class="relative aspect-[3/4] overflow-hidden mb-6 bg-surface-container-low rounded-xl">
<img class="w-full h-full object-cover transition-transform duration-1000 group-hover:scale-110" data-alt="Sunlight hitting a glass water-based toner bottle creating beautiful light refractions" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCaL2HJrdh0XdxrZXPZimZL8Nm_qU_K6pw_D2i-WZ4sGElm4k0WrGSIQW-p1ryk4CRhAhqzo1Kszlq5L0pMkUa3kPFQkpTJHXg31YPcfmKEQOUTqCqbIQPcqpRgzzPtkPtctVfO4ge8YvjvtWieBTDhtw0AU1SxSUh2dz4MXdC2s7ZAmpikQWTQ8lOWYFc2ircM4OJSikEufCiCJzaIXikw_1Wv3kMX_TnwGE9LzHS54DKK_bUnkQFS5_Bs-iSDkR1tcljLPIQke5qN"/>
</div>
<h3 class="font-headline text-2xl text-on-surface group-hover:text-primary transition-colors duration-300">Pure Hydration Mist</h3>
<p class="mt-2 text-on-surface-variant text-sm font-body leading-relaxed line-clamp-2">
                            A refreshing cloud of glacial water and soothing cucumber extract for instant dewiness.
                        </p>
<div class="mt-4 flex items-baseline justify-between mb-6">
<span class="text-lg font-medium text-on-surface">$42</span>
</div>
<button class="w-full bg-primary text-on-primary py-4 text-xs uppercase tracking-[0.2em] font-semibold transition-all hover:bg-on-primary-container active:scale-95">
                            Buy at Official Store
                        </button>
</div>
</div>
</section>
</div>
</main>
<!-- Footer -->
<footer class="w-full pt-20 pb-10 bg-[#eeeeef] dark:bg-slate-900">
<div class="grid grid-cols-1 md:grid-cols-4 gap-12 px-12 max-w-7xl mx-auto">
<div class="col-span-1 md:col-span-1">
<div class="font-['Noto_Serif'] text-xl italic text-[#1a1c1d] dark:text-slate-200 mb-6">Onvynix Labs</div>
<p class="text-[#1a1c1d]/60 dark:text-slate-500 font-['Manrope'] text-sm leading-relaxed lowercase">
                    Curation of clinical performance and botanical luxury for the modern skin.
                </p>
</div>
<div class="space-y-4">
<h4 class="font-['Manrope'] text-sm tracking-wide uppercase text-[#835151] dark:text-[#e2a4a4]">Explore</h4>
<div class="flex flex-col space-y-2">
<a class="text-[#1a1c1d]/60 dark:text-slate-500 hover:text-[#835151] transition-colors font-['Manrope'] text-sm tracking-wide uppercase" href="#">New Arrivals</a>
<a class="text-[#1a1c1d]/60 dark:text-slate-500 hover:text-[#835151] transition-colors font-['Manrope'] text-sm tracking-wide uppercase" href="#">Limited Editions</a>
<a class="text-[#1a1c1d]/60 dark:text-slate-500 hover:text-[#835151] transition-colors font-['Manrope'] text-sm tracking-wide uppercase" href="#">Consultations</a>
</div>
</div>
<div class="space-y-4">
<h4 class="font-['Manrope'] text-sm tracking-wide uppercase text-[#835151] dark:text-[#e2a4a4]">Legal</h4>
<div class="flex flex-col space-y-2">
<a class="text-[#1a1c1d]/60 dark:text-slate-500 hover:text-[#835151] transition-colors font-['Manrope'] text-sm tracking-wide uppercase" href="#">Privacy Policy</a>
<a class="text-[#1a1c1d]/60 dark:text-slate-500 hover:text-[#835151] transition-colors font-['Manrope'] text-sm tracking-wide uppercase" href="#">Affiliate Disclosure</a>
<a class="text-[#1a1c1d]/60 dark:text-slate-500 hover:text-[#835151] transition-colors font-['Manrope'] text-sm tracking-wide uppercase" href="#">Terms of Service</a>
</div>
</div>
<div class="space-y-4">
<h4 class="font-['Manrope'] text-sm tracking-wide uppercase text-[#835151] dark:text-[#e2a4a4]">Connect</h4>
<div class="flex flex-col space-y-2">
<a class="text-[#1a1c1d]/60 dark:text-slate-500 hover:text-[#835151] transition-colors font-['Manrope'] text-sm tracking-wide uppercase" href="#">Contact Us</a>
<a class="text-[#1a1c1d]/60 dark:text-slate-500 hover:text-[#835151] transition-colors font-['Manrope'] text-sm tracking-wide uppercase" href="#">Instagram</a>
<a class="text-[#1a1c1d]/60 dark:text-slate-500 hover:text-[#835151] transition-colors font-['Manrope'] text-sm tracking-wide uppercase" href="#">Journal</a>
</div>
</div>
</div>
<div class="mt-16 px-12 max-w-7xl mx-auto border-t border-outline-variant/30 pt-8 flex flex-col md:flex-row justify-between items-center gap-4">
<div class="font-['Manrope'] text-xs tracking-wide uppercase text-[#1a1c1d]/40">© 2024 Onvynix Labs. The Ethereal Curator.</div>
<div class="flex space-x-6 text-[#1a1c1d]/40 text-[10px] tracking-[0.3em] uppercase font-bold">
<span>London</span>
<span>Paris</span>
<span>New York</span>
</div>
</div>
</footer>
</body></html>
