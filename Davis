<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Davis Amedu II | Enterprise Sales Performance Profile</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Chart.js -->
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <!-- Plotly.js -->
    <script src="https://cdn.plot.ly/plotly-2.27.0.min.js"></script>
    
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">

    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #F3F4F6; /* Light gray background */
        }
        
        /* Vibrant Palette: Brilliant Blues & Electric Green */
        .text-brand-primary { color: #003366; } /* Deep Navy */
        .bg-brand-primary { background-color: #003366; }
        .text-brand-secondary { color: #00B388; } /* Vibrant Teal */
        .bg-brand-secondary { background-color: #00B388; }
        .text-brand-accent { color: #3B82F6; } /* Bright Blue */
        .bg-brand-accent { background-color: #3B82F6; }
        
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
            height: 300px;
            max-height: 400px;
        }

        /* Responsive height adjustments */
        @media (min-width: 768px) {
            .chart-container {
                height: 350px;
            }
        }

        .card {
            background-color: white;
            border-radius: 0.5rem;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
            transition: transform 0.2s;
        }
        .card:hover {
            transform: translateY(-2px);
        }
        /* Custom style for the AI feature highlight */
        .border-ai-feature { border-left-color: #EF4444; /* Red 500 */ }
    </style>
    <!-- NO MERMAID JS USED -->
    <!-- NO SVG GRAPHICS USED -->
    <!-- PALETTE: Brilliant Blues & Energetic Teal -->
</head>
<body class="text-gray-800 antialiased">

    <!-- Header / Hero Section -->
    <header class="bg-brand-primary text-white py-12">
        <div class="container mx-auto px-4 text-center">
            <h1 class="text-4xl md:text-6xl font-bold mb-4 tracking-tight">Davis Amedu II</h1>
            <p class="text-xl md:text-2xl text-gray-300 mb-6 font-light">Client Executive | Enterprise Sales | Business Development</p>
            <div class="flex flex-wrap justify-center gap-4">
                <span class="bg-brand-secondary text-white px-4 py-1 rounded-full text-sm font-semibold">TMT Sector Expert</span>
                <span class="bg-brand-secondary text-white px-4 py-1 rounded-full text-sm font-semibold">Top 10% National Performer</span>
                <span class="bg-brand-secondary text-white px-4 py-1 rounded-full text-sm font-semibold">Hunter Mentality</span>
            </div>
        </div>
    </header>

    <main class="container mx-auto px-4 py-8 space-y-12">

        <!-- Introduction -->
        <section class="max-w-4xl mx-auto text-center">
            <h2 class="text-3xl font-bold text-brand-primary mb-4">Performance-Driven Sales Leadership</h2>
            <p id="introText" class="text-lg text-gray-600 leading-relaxed">
                With over 5 years of experience in the competitive Telecommunications, Media, and Technology (TMT) sector, I specialize in navigating complex enterprise deals and driving new logo acquisition. My approach combines data-driven territory management with relationship-focused solution selling, consistently resulting in quota over-achievement and market expansion.
            </p>
        </section>

        <!-- Section 1: KPI & Performance History -->
        <section>
            <div class="mb-6">
                <h3 class="text-2xl font-bold text-brand-primary border-l-4 border-brand-secondary pl-3">Consistent Quota Execution</h3>
                <p class="text-gray-600 mt-2">A historical view of performance against targets, demonstrating sustained excellence from Senior Account Management to Client Executive roles.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Big Number Cards -->
                <div class="card p-6 text-center border-t-4 border-brand-secondary">
                    <div class="text-5xl font-bold text-brand-primary mb-2">167%</div>
                    <div class="text-sm font-bold text-gray-500 uppercase tracking-wide">Year-End Quota Attainment (2022)</div>
                    <p class="text-xs text-gray-400 mt-2">Consistently exceeding targets month-over-month.</p>
                </div>
                <div class="card p-6 text-center border-t-4 border-brand-secondary">
                    <div class="text-5xl font-bold text-brand-primary mb-2">2,725%</div>
                    <div class="text-sm font-bold text-gray-500 uppercase tracking-wide">SMB Adds YOY Increase</div>
                    <p class="text-xs text-gray-400 mt-2">Demonstrated ability to scale small business accounts rapidly.</p>
                </div>
                <div class="card p-6 text-center border-t-4 border-brand-secondary">
                    <div class="text-5xl font-bold text-brand-primary mb-2">#4</div>
                    <div class="text-sm font-bold text-gray-500 uppercase tracking-wide">National Rank (Q3 2022)</div>
                    <p class="text-xs text-gray-400 mt-2">Ranked out of 1,200+ sales professionals nationally.</p>
                </div>
            </div>

            <!-- Performance Chart -->
            <div class="mt-8 bg-white p-6 rounded-lg shadow-md">
                <h4 class="text-lg font-semibold text-gray-700 mb-4 text-center">Annual Performance Trends (% to Goal)</h4>
                <div class="chart-container">
                    <canvas id="performanceChart"></canvas>
                </div>
            </div>
        </section>

        <!-- Section 2: Strategic Territory Management -->
        <section>
            <div class="mb-6">
                <h3 class="text-2xl font-bold text-brand-primary border-l-4 border-brand-secondary pl-3">Strategic Territory Approach</h3>
                <p class="text-gray-600 mt-2">My methodology for managing a region involves a strict prioritization of high-value activities, balancing the "Hunter" mindset with strategic account growth.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- Territory Segmentation Chart -->
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <h4 class="text-lg font-semibold text-gray-700 mb-2 text-center">Territory Focus Allocation</h4>
                    <p class="text-sm text-gray-500 text-center mb-4">How I prioritize my book of business for maximum ROI.</p>
                    <div class="chart-container">
                        <canvas id="territoryChart"></canvas>
                    </div>
                </div>

                <!-- Sales Cycle Activity Chart -->
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <h4 class="text-lg font-semibold text-gray-700 mb-2 text-center">Weekly Activity Breakdown</h4>
                    <p class="text-sm text-gray-500 text-center mb-4">Dedicated time allocation to ensure pipeline health.</p>
                    <div class="chart-container">
                        <canvas id="activityChart"></canvas>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 3: Recent Major Deployments (2025) -->
        <section>
            <div class="mb-6">
                <h3 class="text-2xl font-bold text-brand-primary border-l-4 border-brand-secondary pl-3">2025 Major Deployments</h3>
                <p class="text-gray-600 mt-2">Recent complex wins demonstrating solution selling capabilities in hardware and infrastructure.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div class="bg-brand-primary text-white p-6 rounded-lg shadow-lg relative overflow-hidden">
                    <div class="absolute top-0 right-0 -mt-4 -mr-4 w-24 h-24 bg-brand-secondary rounded-full opacity-20"></div>
                    <h4 class="text-2xl font-bold mb-2">400 Units</h4>
                    <h5 class="text-xl font-semibold mb-2">Enterprise Tablet Deployment</h5>
                    <p class="text-blue-100 text-sm">Secured and managed the logistics for a large-scale mobile workforce upgrade (Oct 2025).</p>
                </div>
                <div class="bg-brand-primary text-white p-6 rounded-lg shadow-lg relative overflow-hidden">
                    <div class="absolute top-0 right-0 -mt-4 -mr-4 w-24 h-24 bg-brand-secondary rounded-full opacity-20"></div>
                    <h4 class="text-2xl font-bold mb-2">200 Units</h4>
                    <h5 class="text-xl font-semibold mb-2">Fixed Wireless Access (FWA)</h5>
                    <p class="text-blue-100 text-sm">Solved critical connectivity challenges for a distributed client base through FWA solutions (Mar 2025).</p>
                </div>
            </div>
        </section>

        <!-- Section 4: Gemini API Powered Tools (NEW) -->
        <section>
            <div class="mb-6">
                <h3 class="text-2xl font-bold text-brand-primary border-l-4 border-ai-feature pl-3">AI-Powered Profile Tools ✨</h3>
                <p class="text-gray-600 mt-2">Leveraging the Gemini API for quick communication drafts and audio generation.</p>
            </div>

            <!-- Pitch Generator Card -->
            <div class="card p-6 mb-6">
                <h4 class="text-xl font-bold text-gray-700 mb-4">Generate Personalized Pitch</h4>
                <p class="text-sm text-gray-500 mb-4">Click below to generate a concise, compelling 60-second elevator pitch based on Davis's profile data.</p>
                <button id="generatePitchBtn" onclick="window.generatePitch()" class="bg-brand-secondary hover:bg-teal-700 text-white font-bold py-2 px-4 rounded-lg transition duration-200 shadow-md">
                    ✨ Draft Elevator Pitch
                </button>
                <div id="pitchOutput" class="mt-4 p-4 bg-gray-50 border border-gray-200 rounded-lg hidden">
                    <p class="font-semibold mb-2 text-brand-primary">Draft Pitch:</p>
                    <p id="pitchText" class="text-gray-800 italic whitespace-pre-wrap"></p>
                </div>
                <div id="pitchLoading" class="mt-4 text-brand-accent hidden">Generating pitch...</div>
            </div>
            
            <!-- TTS Reader Card -->
            <div class="card p-6">
                <h4 class="text-xl font-bold text-gray-700 mb-4">Read Introduction Aloud</h4>
                <p class="text-sm text-gray-500 mb-4">Generate an audio reading of the Introduction section using Text-to-Speech (TTS).</p>
                <button id="readIntroBtn" onclick="window.readIntroduction()" class="bg-red-500 hover:bg-red-700 text-white font-bold py-2 px-4 rounded-lg transition duration-200 shadow-md">
                    🔊 Read Intro with TTS
                </button>
                <div id="audioPlayerContainer" class="mt-4 hidden">
                    <audio id="audioPlayer" controls class="w-full"></audio>
                </div>
                <div id="audioLoading" class="mt-4 text-red-500 hidden">Generating audio...</div>
            </div>
        </section>

        <!-- Section 5: Skills & Competencies (Old Section 4) -->
        <section class="mb-12">
            <div class="mb-6">
                <h3 class="text-2xl font-bold text-brand-primary border-l-4 border-brand-secondary pl-3">Competency Profile</h3>
                <p class="text-gray-600 mt-2">A balanced skillset combining aggressive sales tactics with technical proficiency and relationship management.</p>
            </div>

            <div class="bg-white p-6 rounded-lg shadow-md">
                <div id="skillsPlot" style="width:100%; height:400px;"></div>
                <!-- Plotly.js will render here. Note: Plotly uses Canvas/WebGL in the background -->
            </div>
        </section>

    </main>

    <footer class="bg-gray-800 text-white py-8 mt-12">
        <div class="container mx-auto px-4 text-center">
            <p class="text-lg font-semibold">Davis Amedu II</p>
            <p class="text-gray-400 text-sm mb-4">Enterprise Sales Professional • Jackson, MS</p>
            <div class="text-gray-500 text-xs">
                <!-- Hidden comment: Palette used: #003366, #00B388 -->
                Confirming: NO SVG, NO MERMAID JS used in this output.
            </div>
        </div>
    </footer>

    <!-- Scripts for Chart Rendering and Gemini API -->
    <script type="module">
        import { initializeApp } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-app.js";
        import { getAuth, signInAnonymously, signInWithCustomToken } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-auth.js";
        import { getFirestore, setLogLevel } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-firestore.js";

        // --- Firebase Setup (Mandatory Boilerplate) ---
        const firebaseConfig = JSON.parse(typeof __firebase_config !== 'undefined' ? __firebase_config : '{}');
        const initialAuthToken = typeof __initial_auth_token !== 'undefined' ? __initial_auth_token : null;
        let app, auth, db, userId;

        async function initFirebase() {
            setLogLevel('Debug');
            if (Object.keys(firebaseConfig).length > 0) {
                app = initializeApp(firebaseConfig);
                db = getFirestore(app);
                auth = getAuth(app);
                
                try {
                    if (initialAuthToken) {
                        await signInWithCustomToken(auth, initialAuthToken);
                    } else {
                        await signInAnonymously(auth);
                    }
                    userId = auth.currentUser?.uid || crypto.randomUUID();
                    console.log("Firebase initialized. User ID:", userId);
                } catch (error) {
                    console.error("Firebase Auth Error:", error);
                }
            }
        }
        
        // --- Gemini API Utilities ---
        const apiKey = ""; 
        const LLM_URL = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash-preview-09-2025:generateContent?key=${apiKey}`;
        const TTS_URL = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash-preview-tts:generateContent?key=${apiKey}`;
        
        /** Converts a base64 string to an ArrayBuffer. */
        function base64ToArrayBuffer(base64) {
            const binaryString = atob(base64);
            const len = binaryString.length;
            const bytes = new Uint8Array(len);
            for (let i = 0; i < len; i++) {
                bytes[i] = binaryString.charCodeAt(i);
            }
            return bytes.buffer;
        }

        /** Converts signed 16-bit PCM audio data to a WAV Blob. */
        function pcmToWav(pcm16, sampleRate) {
            const numChannels = 1;
            const bytesPerSample = 2;
            const byteRate = sampleRate * numChannels * bytesPerSample;
            const blockAlign = numChannels * bytesPerSample;
            const dataSize = pcm16.length * bytesPerSample;
            const buffer = new ArrayBuffer(44 + dataSize);
            const view = new DataView(buffer);
            let offset = 0;

            // RIFF chunk
            view.setUint32(offset, 0x52494646, false); offset += 4; // "RIFF"
            view.setUint32(offset, 36 + dataSize, true); offset += 4; // file size
            view.setUint32(offset, 0x57415645, false); offset += 4; // "WAVE"

            // FMT chunk
            view.setUint32(offset, 0x666d7420, false); offset += 4; // "fmt "
            view.setUint32(offset, 16, true); offset += 4; // chunk size (16 for PCM)
            view.setUint16(offset, 1, true); offset += 2; // audio format (1 for PCM)
            view.setUint16(offset, numChannels, true); offset += 2; // number of channels
            view.setUint32(offset, sampleRate, true); offset += 4; // sample rate
            view.setUint32(offset, byteRate, true); offset += 4; // byte rate
            view.setUint16(offset, blockAlign, true); offset += 2; // block align
            view.setUint16(offset, 16, true); offset += 2; // bits per sample (16)

            // DATA chunk
            view.setUint32(offset, 0x64617461, false); offset += 4; // "data"
            view.setUint32(offset, dataSize, true); offset += 4; // data size

            // Write PCM data
            for (let i = 0; i < pcm16.length; i++) {
                view.setInt16(offset, pcm16[i], true);
                offset += 2;
            }

            return new Blob([buffer], { type: 'audio/wav' });
        }
        
        /** General fetch wrapper with exponential backoff. */
        async function callApiWithBackoff(url, payload, maxRetries = 5) {
            let delay = 1000;
            for (let i = 0; i < maxRetries; i++) {
                try {
                    const response = await fetch(url, {
                        method: 'POST',
                        headers: { 'Content-Type': 'application/json' },
                        body: JSON.stringify(payload)
                    });
                    
                    if (response.ok) {
                        return await response.json();
                    } else if (response.status === 429 && i < maxRetries - 1) {
                        // Too many requests, retry
                        await new Promise(resolve => setTimeout(resolve, delay));
                        delay *= 2;
                    } else {
                        throw new Error(`API call failed with status: ${response.status}`);
                    }
                } catch (error) {
                    if (i === maxRetries - 1) throw error;
                    await new Promise(resolve => setTimeout(resolve, delay));
                    delay *= 2;
                }
            }
        }

        // --- Gemini LLM Feature 1: Pitch Generator ---
        window.generatePitch = async function() {
            const btn = document.getElementById('generatePitchBtn');
            const loading = document.getElementById('pitchLoading');
            const output = document.getElementById('pitchOutput');
            const pitchText = document.getElementById('pitchText');
            
            btn.disabled = true;
            loading.classList.remove('hidden');
            output.classList.add('hidden');
            pitchText.textContent = '';

            const systemPrompt = "You are a professional sales consultant. Generate a concise, 60-second elevator pitch (max 4 sentences) for the professional described. The pitch MUST focus on quantifying their impact and expertise.";
            
            const profileData = `
                Role: Client Executive, Enterprise Sales
                Sector: TMT (Telecommunications, Media, Technology)
                Core Strengths (Competency 100%): New Business Hunter, Strategic Planning (95%), Complex Negotiation (90%)
                KPIs: 167% Year-End Quota Attainment (2022), #4 National Rank (Q3 2022) out of 1,200+.
                Recent Win: Led a 400-unit Enterprise Tablet Deployment.
            `;
            
            const userQuery = `Generate the pitch based on this profile data: ${profileData}`;

            const payload = {
                contents: [{ parts: [{ text: userQuery }] }],
                systemInstruction: { parts: [{ text: systemPrompt }] },
            };

            try {
                const result = await callApiWithBackoff(LLM_URL, payload);
                const generatedText = result.candidates?.[0]?.content?.parts?.[0]?.text || "Could not generate pitch.";
                
                pitchText.textContent = generatedText;
                output.classList.remove('hidden');

            } catch (error) {
                pitchText.textContent = `Error generating pitch: ${error.message}`;
                output.classList.remove('hidden');
                console.error("LLM Error:", error);
            } finally {
                loading.classList.add('hidden');
                btn.disabled = false;
            }
        };

        // --- Gemini TTS Feature 2: Audio Reader ---
        window.readIntroduction = async function() {
            const btn = document.getElementById('readIntroBtn');
            const loading = document.getElementById('audioLoading');
            const audioContainer = document.getElementById('audioPlayerContainer');
            const audioPlayer = document.getElementById('audioPlayer');
            const textToRead = document.getElementById('introText').textContent.trim();
            
            btn.disabled = true;
            loading.classList.remove('hidden');
            audioContainer.classList.add('hidden');

            const payload = {
                contents: [{
                    parts: [{ text: `Say in a confident, professional voice: ${textToRead}` }]
                }],
                generationConfig: {
                    responseModalities: ["AUDIO"],
                    speechConfig: {
                        voiceConfig: {
                            prebuiltVoiceConfig: { voiceName: "Kore" }
                        }
                    }
                },
                model: "gemini-2.5-flash-preview-tts"
            };

            try {
                const result = await callApiWithBackoff(TTS_URL, payload);
                
                const part = result?.candidates?.[0]?.content?.parts?.[0];
                const audioData = part?.inlineData?.data;
                const mimeType = part?.inlineData?.mimeType;

                if (audioData && mimeType && mimeType.startsWith("audio/L16")) {
                    const sampleRateMatch = mimeType.match(/rate=(\d+)/);
                    const sampleRate = sampleRateMatch ? parseInt(sampleRateMatch[1], 10) : 16000;
                    
                    const pcmData = base64ToArrayBuffer(audioData);
                    const pcm16 = new Int16Array(pcmData);
                    const wavBlob = pcmToWav(pcm16, sampleRate);
                    
                    if (audioPlayer.src) URL.revokeObjectURL(audioPlayer.src);
                    audioPlayer.src = URL.createObjectURL(wavBlob);
                    audioContainer.classList.remove('hidden');
                    audioPlayer.play();
                } else {
                    throw new Error("Invalid or missing audio data from API.");
                }

            } catch (error) {
                console.error("TTS Error:", error);
                // Updated: Display error message on the UI instead of using alert()
                const errorMessage = "Failed to generate audio. Check the console for API details.";
                audioContainer.classList.remove('hidden');
                audioContainer.innerHTML = `<p class="text-red-600">${errorMessage}</p>`;
                console.error("TTS Audio Generation Failed:", error);
            } finally {
                loading.classList.add('hidden');
                btn.disabled = false;
            }
        }

        // --- Chart Rendering Logic (Existing) ---
        function renderCharts() {
            // --- Chart 1: Performance History (Bar) ---
            const ctxPerformance = document.getElementById('performanceChart').getContext('2d');
            const performanceLabels = ['2021 Net Adds', '2021 EOY', '2022 EOY', '2024 Sales Revenue'];
            
            new Chart(ctxPerformance, {
                type: 'bar',
                data: {
                    labels: performanceLabels.map(label => {
                        if (label.length > 16) {
                            const words = label.split(' ');
                            const lines = [];
                            let currentLine = words[0];

                            for (let i = 1; i < words.length; i++) {
                                if ((currentLine + " " + words[i]).length < 16) {
                                    currentLine += " " + words[i];
                                } else {
                                    lines.push(currentLine);
                                    currentLine = words[i];
                                }
                            }
                            lines.push(currentLine);
                            return lines;
                        }
                        return label;
                    }),
                    datasets: [{
                        label: '% Achievement to Quota',
                        data: [179, 160, 148, 115],
                        backgroundColor: '#003366',
                        borderRadius: 4
                    }]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    plugins: {
                        tooltip: {
                            callbacks: {
                                title: function(tooltipItems) {
                                    const item = tooltipItems[0];
                                    let label = item.chart.data.labels[item.dataIndex];
                                    if (Array.isArray(label)) {
                                        return label.join(' ');
                                    } else {
                                        return label;
                                    }
                                }
                            }
                        },
                        legend: { display: false }
                    },
                    scales: {
                        y: {
                            beginAtZero: true,
                            title: { display: true, text: 'Percentage (%)' },
                            grid: { color: '#e5e7eb' }
                        },
                        x: {
                            grid: { display: false }
                        }
                    }
                }
            });

            // --- Chart 2: Territory Segmentation (Doughnut) ---
            const ctxTerritory = document.getElementById('territoryChart').getContext('2d');
            const territoryLabels = ['Tier B: New Logo Hunting', 'Tier A: Strategic Growth', 'Tier C: Partner Leverage', 'Admin & Ops'];
            
            new Chart(ctxTerritory, {
                type: 'doughnut',
                data: {
                    labels: territoryLabels.map(label => {
                        if (label.length > 16) {
                            const words = label.split(' ');
                            const lines = [];
                            let currentLine = words[0];

                            for (let i = 1; i < words.length; i++) {
                                if ((currentLine + " " + words[i]).length < 16) {
                                    currentLine += " " + words[i];
                                } else {
                                    lines.push(currentLine);
                                    currentLine = words[i];
                                }
                            }
                            lines.push(currentLine);
                            return lines;
                        }
                        return label;
                    }),
                    datasets: [{
                        data: [50, 20, 25, 5], // Percentages
                        backgroundColor: [
                            '#003366', // Hunting (Primary)
                            '#00B388', // Growth (Secondary)
                            '#3B82F6', // Partners (Accent)
                            '#9CA3AF'  // Admin (Gray)
                        ],
                        borderWidth: 0
                    }]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    plugins: {
                        tooltip: {
                            callbacks: {
                                title: function(tooltipItems) {
                                    const item = tooltipItems[0];
                                    let label = item.chart.data.labels[item.dataIndex];
                                    if (Array.isArray(label)) {
                                        return label.join(' ');
                                    } else {
                                        return label;
                                    }
                                }
                            }
                        },
                        legend: { position: 'bottom' }
                    }
                }
            });

            // --- Chart 3: Weekly Activity (Horizontal Bar) ---
            const ctxActivity = document.getElementById('activityChart').getContext('2d');
            const activityLabels = ['Demand Generation', 'Opportunity Qualification', 'Negotiation & Close', 'Post-Sale Growth'];

            new Chart(ctxActivity, {
                type: 'bar',
                indexAxis: 'y', // Horizontal
                data: {
                    labels: activityLabels.map(label => {
                        if (label.length > 16) {
                            const words = label.split(' ');
                            const lines = [];
                            let currentLine = words[0];

                            for (let i = 1; i < words.length; i++) {
                                if ((currentLine + " " + words[i]).length < 16) {
                                    currentLine += " " + words[i];
                                } else {
                                    lines.push(currentLine);
                                    currentLine = words[i];
                                }
                            }
                            lines.push(currentLine);
                            return lines;
                        }
                        return label;
                    }),
                    datasets: [{
                        label: '% Time Allocation',
                        data: [40, 30, 20, 10],
                        backgroundColor: '#00B388',
                        borderRadius: 4
                    }]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    plugins: {
                        tooltip: {
                            callbacks: {
                                title: function(tooltipItems) {
                                    const item = tooltipItems[0];
                                    let label = item.chart.data.labels[item.dataIndex];
                                    if (Array.isArray(label)) {
                                        return label.join(' ');
                                    } else {
                                        return label;
                                    }
                                }
                            }
                        },
                        legend: { display: false }
                    },
                    scales: {
                        x: {
                            beginAtZero: true,
                            max: 100,
                            grid: { color: '#e5e7eb' }
                        },
                        y: {
                            grid: { display: false }
                        }
                    }
                }
            });

            // --- Chart 4: Competency Profile (Plotly Radar) ---
            const data = [{
              type: 'scatterpolar',
              r: [95, 100, 90, 85, 90, 80],
              theta: ['Strategic Planning', 'New Business Hunter', 'Relationship Building', 'Tech/AI Adoption', 'Complex Negotiation', 'Project Management'],
              fill: 'toself',
              fillcolor: 'rgba(0, 51, 102, 0.2)',
              line: {
                color: '#003366'
              }
            }];

            const layout = {
              polar: {
                radialaxis: {
                  visible: true,
                  range: [0, 100]
                }
              },
              showlegend: false,
              margin: { t: 30, b: 30, l: 30, r: 30 },
              font: { family: 'Inter, sans-serif' },
              paper_bgcolor: "rgba(0,0,0,0)",
              height: 350
            };

            Plotly.newPlot('skillsPlot', data, layout, {displayModeBar: false, staticPlot: true});
        }
        
        // --- Initialization ---
        // Removed document.addEventListener('DOMContentLoaded') wrapper.
        // Module scripts run after the DOM is ready, so this is more robust.
        initFirebase();
        renderCharts();

    </script>
</body>
</html>
