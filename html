<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculus in Agro-Product Tech: Oil Palm Ripening</title>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
    <style>
        .gradient-bg {
            background: linear-gradient(135deg, #115e59 0%, #0f766e 100%);
        }
    </style>
</head>
<body class="bg-gray-50 font-sans min-h-screen pb-12">

    <header class="gradient-bg text-white py-8 px-6 shadow-md text-center">
        <h1 class="text-3xl font-bold tracking-wide">Derivatives in Malaysian Agro-Product Technology</h1>
        <p class="text-teal-100 mt-2 text-lg">Optimizing Oil Palm Fruit Harvest Windows via Rate of Change $f'(x)$</p>
    </header>

    <main class="max-w-5xl mx-auto px-4 mt-8 grid grid-cols-1 lg:grid-cols-3 gap-8">
        
        <div class="lg:col-span-1 space-y-6">
            <div class="bg-white p-6 rounded-xl shadow-sm border border-gray-100">
                <h2 class="text-xl font-bold text-teal-800 mb-3 border-b pb-2">The Bioscience Scenario</h2>
                <p class="text-gray-600 text-sm leading-relaxed mb-3">
                    In Malaysia's palm oil industry, harvesting Fresh Fruit Bunches (FFB) at peak oil content is vital. 
                    As the fruits ripen between weeks 12 to 22 post-anthesis, oil accumulation follows a <strong>sigmoidal (logistic) curve</strong>.
                </p>
                <p class="text-gray-600 text-sm leading-relaxed">
                    By analyzing the <strong>derivative $f'(x)$</strong>, food technologists can identify the precise day where the rate of oil synthesis peaks, ensuring maximum oil extraction efficiency before fruit abscission (dropping) occurs.
                </p>
            </div>

            <div class="bg-white p-6 rounded-xl shadow-sm border border-gray-100">
                <h2 class="text-xl font-bold text-teal-800 mb-3 border-b pb-2">Mathematical Modeling</h2>
                <div class="space-y-4 text-sm">
                    <div>
                        <span class="font-semibold text-gray-700 block mb-1">Oil Accumulation Function $f(x)$:</span>
                        <div class="bg-teal-50 p-3 rounded text-center font-mono overflow-x-auto text-teal-950">
                            $$f(x) = \frac{60}{1 + e^{-0.6(x - 17)}}$$
                        </div>
                        <p class="text-xs text-gray-500 mt-1">Yields total oil content percentage (%) at week $x$.</p>
                    </div>
                    <div>
                        <span class="font-semibold text-gray-700 block mb-1">Derivative $f'(x)$ (Rate of Accumulation):</span>
                        <div class="bg-amber-50 p-3 rounded text-center font-mono overflow-x-auto text-amber-950">
                            $$f'(x) = \frac{36 e^{-0.6(x - 17)}}{(1 + e^{-0.6(x - 17)})^2}$$
                        </div>
                        <p class="text-xs text-gray-500 mt-1">Yields the rate of oil production in <strong>% oil increase per week</strong>.</p>
                    </div>
                </div>
            </div>

            <div class="bg-white p-4 rounded-xl shadow-sm border border-gray-100 text-xs text-gray-500">
                <span class="font-semibold block text-gray-700 mb-1">Realistic Data Reference:</span>
                Based on baseline sigmoidal physiological profiles found in MPOB (Malaysian Palm Oil Board) research portals tracking mesocarp oil development timelines.
            </div>
        </div>

        <div class="lg:col-span-2 space-y-6">
            <div class="bg-white p-6 rounded-xl shadow-sm border border-gray-100">
                <div class="flex flex-col sm:flex-row sm:items-center justify-between mb-4">
                    <h2 class="text-xl font-bold text-gray-800">Visualizing Growth vs. Rate of Growth</h2>
                    <span class="text-xs font-semibold text-teal-600 bg-teal-50 px-2.5 py-1 rounded-full mt-2 sm:mt-0 animate-pulse">
                        💡 Click anywhere on the lines to inspect rates!
                    </span>
                </div>
                
                <div class="relative h-96 w-full">
                    <canvas id="ripeningChart"></canvas>
                </div>
            </div>

            <div id="inspector-card" class="bg-slate-900 text-white p-6 rounded-xl shadow-md border-l-4 border-amber-500 transition-all duration-300 transform">
                <h3 class="text-amber-400 font-bold tracking-wider text-sm uppercase mb-2">📋 Real-time Derivative Inspector</h3>
                <div id="inspector-placeholder" class="text-slate-400 text-sm italic">
                    Click a specific data point on either line above to calculate the instantaneous rate of change at that exact week of development.
                </div>
                <div id="inspector-content" class="hidden grid grid-cols-1 md:grid-cols-2 gap-4">
                    <div>
                        <p class="text-xs text-slate-400">Selected Maturity Stage</p>
                        <p class="text-lg font-semibold text-white" id="res-week">Week --</p>
                        
                        <div class="mt-2">
                            <p class="text-xs text-slate-400">Current Total Oil Content $f(x)$</p>
                            <p class="text-xl font-bold text-teal-400" id="res-f">-- %</p>
                        </div>
                    </div>
                    <div class="border-t md:border-t-0 md:border-l border-slate-700 pt-3 md:pt-0 md:pl-4">
                        <p class="text-xs text-slate-400">Instantaneous Rate of Accumulation $f'(x)$</p>
                        <p class="text-2xl font-black text-amber-400" id="res-df">-- % / week</p>
                        
                        <div class="mt-2 bg-slate-800 p-2.5 rounded border border-slate-700">
                            <p class="text-xs font-semibold text-amber-300">Layman Bioscience Insight:</p>
                            <p class="text-xs text-slate-300 mt-0.5 leading-normal" id="res-insight">Select a point to see analysis.</p>
                        </div>
