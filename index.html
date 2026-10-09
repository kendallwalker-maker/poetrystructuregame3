<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Poetry Quest: Rhyme Scheme & Stanza Master</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
  <link href="https://fonts.googleapis.com/css2?family=Fredoka:wght@400;500;600;700&family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet" />
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            fredoka: ['Fredoka', 'sans-serif'],
            sans: ['Inter', 'sans-serif'],
          },
          colors: {
            brand: {
              purple: '#7C3AED',
              blue: '#2563EB',
              teal: '#0D9488',
              amber: '#D97706',
              rose: '#E11D48',
              green: '#16A34A',
            }
          }
        }
      }
    }
  </script>
  <style>
    body {
      font-family: 'Inter', sans-serif;
      background-color: #F3F4F6;
    }
    .font-heading {
      font-family: 'Fredoka', sans-serif;
    }
    /* Custom animations */
    @keyframes bounce-short {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-6px); }
    }
    .animate-bounce-short {
      animation: bounce-short 0.5s ease-in-out infinite;
    }
    @keyframes pop-in {
      0% { transform: scale(0.8); opacity: 0; }
      100% { transform: scale(1); opacity: 1; }
    }
    .animate-pop-in {
      animation: pop-in 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275) forwards;
    }
    /* End word color coding tags */
    .rhyme-a { background-color: #DBEAFE; color: #1E40AF; border: 2px solid #93C5FD; font-weight: 700; padding: 0.1rem 0.4rem; border-radius: 0.375rem; }
    .rhyme-b { background-color: #FCE7F3; color: #9D174D; border: 2px solid #FBCFE8; font-weight: 700; padding: 0.1rem 0.4rem; border-radius: 0.375rem; }
    .rhyme-c { background-color: #FEF3C7; color: #92400E; border: 2px solid #FDE68A; font-weight: 700; padding: 0.1rem 0.4rem; border-radius: 0.375rem; }
    .rhyme-d { background-color: #D1FAE5; color: #065F46; border: 2px solid #A7F3D0; font-weight: 700; padding: 0.1rem 0.4rem; border-radius: 0.375rem; }
  </style>
</head>
<body class="min-h-screen text-slate-800 pb-12 flex flex-col">

  <!-- Top Navigation Header -->
  <header class="bg-white border-b border-slate-200 sticky top-0 z-30 shadow-sm">
    <div class="max-w-5xl mx-auto px-4 py-3 flex flex-wrap justify-between items-center gap-3">
      <div class="flex items-center space-x-3">
        <div class="w-10 h-10 rounded-2xl bg-gradient-to-tr from-brand-purple to-brand-blue flex items-center justify-center text-white text-xl shadow-md">
          <i class="fa-solid fa-feather-pointed"></i>
        </div>
        <div>
          <h1 class="font-heading font-bold text-xl md:text-2xl text-slate-800 leading-tight">Poetry Quest</h1>
          <p class="text-xs text-slate-500 font-medium">7th Grade Rhyme & Stanza Practice</p>
        </div>
      </div>

      <!-- Stat Counters -->
      <div class="flex items-center space-x-3 sm:space-x-6">
        <!-- Spanish Cognate Toggle -->
        <button id="spanish-toggle-btn" onclick="toggleSpanishSupport()" class="flex items-center space-x-1.5 px-3 py-1.5 rounded-full border border-slate-300 bg-slate-50 hover:bg-slate-100 text-xs sm:text-sm font-semibold text-slate-700 transition">
          <i class="fa-solid fa-language text-brand-purple text-base"></i>
          <span id="spanish-toggle-text">Spanish Support: OFF</span>
        </button>

        <!-- Points -->
        <div class="flex items-center space-x-1.5 bg-amber-50 border border-amber-200 px-3 py-1.5 rounded-full">
          <i class="fa-solid fa-star text-amber-500 text-sm"></i>
          <span id="score-display" class="font-heading font-bold text-amber-700 text-sm sm:text-base">0</span>
          <span class="text-xs text-amber-600 font-semibold hidden sm:inline">pts</span>
        </div>

        <!-- Streak -->
        <div class="flex items-center space-x-1.5 bg-rose-50 border border-rose-200 px-3 py-1.5 rounded-full">
          <i class="fa-solid fa-fire text-rose-500 text-sm"></i>
          <span id="streak-display" class="font-heading font-bold text-rose-700 text-sm sm:text-base">0</span>
        </div>
      </div>
    </div>
  </header>

  <!-- Level Indicator Banner -->
  <div class="bg-slate-800 text-white py-2.5 px-4 shadow-inner">
    <div class="max-w-5xl mx-auto flex flex-col sm:flex-row justify-between items-center gap-2">
      <div class="flex items-center space-x-2">
        <span id="level-badge-pill" class="bg-brand-purple text-white text-xs font-bold px-2.5 py-1 rounded-full uppercase tracking-wider">Level 1</span>
        <span id="level-title-text" class="font-heading text-sm md:text-base font-semibold">Poetry Scout</span>
      </div>
      <!-- Progress Bar -->
      <div class="w-full sm:w-64 bg-slate-700 rounded-full h-3 overflow-hidden border border-slate-600">
        <div id="level-progress-bar" class="bg-gradient-to-r from-brand-blue to-brand-purple h-full w-0 transition-all duration-500"></div>
      </div>
      <div class="text-xs text-slate-300 font-medium">
        Question <span id="current-q-num">1</span> of <span id="total-q-num">11</span>
      </div>
    </div>
  </div>

  <!-- Main Game Container -->
  <main class="max-w-4xl mx-auto px-4 py-6 flex-1 w-full">

    <!-- Spanish Cognate Helper Banner (Hidden by default) -->
    <div id="spanish-cognate-box" class="hidden mb-6 bg-purple-50 border-2 border-purple-200 rounded-2xl p-4 shadow-sm animate-pop-in">
      <div class="flex items-start space-x-3">
        <div class="text-purple-600 text-xl mt-0.5"><i class="fa-solid fa-book-bookmark"></i></div>
        <div>
          <h2 class="font-heading font-bold text-purple-900 text-sm uppercase tracking-wide">Spanish Cognates & Help / Ayuda de Vocabulario</h2>
          <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-4 gap-2 mt-2 text-xs font-medium text-purple-800">
            <div class="bg-white p-2 rounded-lg border border-purple-100 shadow-2xs">
              <span class="font-bold text-purple-900">Stanza:</span> Estanza / Párrafo poético
            </div>
            <div class="bg-white p-2 rounded-lg border border-purple-100 shadow-2xs">
              <span class="font-bold text-purple-900">Verse / Line:</span> Verso / Línea
            </div>
            <div class="bg-white p-2 rounded-lg border border-purple-100 shadow-2xs">
              <span class="font-bold text-purple-900">Rhyme Scheme:</span> Esquema de rima
            </div>
            <div class="bg-white p-2 rounded-lg border border-purple-100 shadow-2xs">
              <span class="font-bold text-purple-900">Near Rhyme:</span> Rima asonante / cercana
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Main Question Card -->
    <div class="bg-white rounded-3xl border border-slate-200 p-5 sm:p-8 shadow-sm relative">

      <!-- Question Header & Speech Button -->
      <div class="flex justify-between items-start gap-4 mb-4">
        <div>
          <span id="question-category" class="inline-block text-xs font-bold text-brand-blue uppercase tracking-wider bg-blue-50 px-2.5 py-1 rounded-md border border-blue-100 mb-2">
            Mechanics & Definitions
          </span>
          <h2 id="question-stem" class="text-lg sm:text-xl font-bold text-slate-800 leading-snug">
            Question text loading...
          </h2>
        </div>
        <!-- Read Aloud Button -->
        <button id="tts-btn" onclick="speakCurrentQuestion()" class="shrink-0 flex items-center justify-center w-11 h-11 rounded-2xl bg-indigo-50 border border-indigo-200 text-indigo-600 hover:bg-indigo-600 hover:text-white transition shadow-2xs group" title="Read Aloud / Leer en voz alta">
          <i class="fa-solid fa-volume-high text-lg group-hover:scale-110 transition-transform"></i>
        </button>
      </div>

      <!-- Poem Box (Visible when question contains poem snippet) -->
      <div id="poem-container" class="my-5 p-5 bg-slate-50 border-2 border-slate-200 rounded-2xl font-serif text-base sm:text-lg text-slate-800 leading-relaxed relative">
        <!-- Visual line labels or poem text injects here -->
        <div id="poem-lines" class="space-y-2"></div>
      </div>

      <!-- Answer Choices -->
      <div id="options-container" class="space-y-3 mt-6">
        <!-- Options injected dynamically -->
      </div>

      <!-- Feedback Box (Hidden initially) -->
      <div id="feedback-box" class="hidden mt-6 p-4 rounded-2xl border transition-all animate-pop-in">
        <div class="flex items-start space-x-3">
          <div id="feedback-icon" class="text-2xl mt-0.5"></div>
          <div class="flex-1">
            <h3 id="feedback-title" class="font-heading font-bold text-base"></h3>
            <p id="feedback-message" class="text-sm mt-1 leading-relaxed"></p>
          </div>
        </div>
      </div>

      <!-- Next Button Bar -->
      <div class="mt-6 pt-4 border-t border-slate-100 flex justify-end">
        <button id="next-btn" onclick="nextQuestion()" class="hidden bg-brand-purple hover:bg-purple-700 text-white font-heading font-bold px-6 py-3 rounded-2xl shadow-md transition transform active:scale-95 flex items-center space-x-2">
          <span>Next Question</span>
          <i class="fa-solid fa-arrow-right"></i>
        </button>
      </div>

    </div>

    <!-- Badges Showcase Section -->
    <div class="mt-8 bg-white border border-slate-200 rounded-3xl p-5 shadow-2xs">
      <h2 class="font-heading font-bold text-slate-700 text-base mb-3 flex items-center space-x-2">
        <i class="fa-solid fa-award text-amber-500"></i>
        <span>Your Earned Badges</span>
      </h2>
      <div class="grid grid-cols-1 sm:grid-cols-3 gap-3">
        <!-- Badge 1 -->
        <div id="badge-scout" class="flex items-center space-x-3 p-3 rounded-2xl border border-slate-200 bg-slate-50 opacity-50 grayscale transition-all">
          <div class="w-10 h-10 rounded-xl bg-blue-500 text-white flex items-center justify-center text-lg shrink-0 shadow-xs">
            <i class="fa-solid fa-magnifying-glass"></i>
          </div>
          <div>
            <div class="font-heading font-bold text-sm text-slate-800">Line Counter</div>
            <div class="text-xs text-slate-500">Complete Level 1</div>
          </div>
        </div>
        <!-- Badge 2 -->
        <div id="badge-detective" class="flex items-center space-x-3 p-3 rounded-2xl border border-slate-200 bg-slate-50 opacity-50 grayscale transition-all">
          <div class="w-10 h-10 rounded-xl bg-purple-500 text-white flex items-center justify-center text-lg shrink-0 shadow-xs">
            <i class="fa-solid fa-user-secret"></i>
          </div>
          <div>
            <div class="font-heading font-bold text-sm text-slate-800">Pattern Decoder</div>
            <div class="text-xs text-slate-500">Complete Level 2</div>
          </div>
        </div>
        <!-- Badge 3 -->
        <div id="badge-master" class="flex items-center space-x-3 p-3 rounded-2xl border border-slate-200 bg-slate-50 opacity-50 grayscale transition-all">
          <div class="w-10 h-10 rounded-xl bg-amber-500 text-white flex items-center justify-center text-lg shrink-0 shadow-xs">
            <i class="fa-solid fa-crown"></i>
          </div>
          <div>
            <div class="font-heading font-bold text-sm text-slate-800">Rhyme Master</div>
            <div class="text-xs text-slate-500">Complete Level 3</div>
          </div>
        </div>
      </div>
    </div>

  </main>

  <!-- Badge Modal Celebration Overlay -->
  <div id="badge-modal" class="fixed inset-0 bg-slate-900/60 backdrop-blur-xs z-50 flex items-center justify-center p-4 hidden">
    <div class="bg-white rounded-3xl p-6 sm:p-8 max-w-sm w-full text-center shadow-2xl border border-slate-100 transform animate-pop-in">
      <div id="modal-badge-icon" class="w-20 h-20 rounded-3xl bg-gradient-to-tr from-amber-400 to-amber-500 text-white flex items-center justify-center text-4xl mx-auto shadow-lg mb-4 animate-bounce-short">
        <i class="fa-solid fa-trophy"></i>
      </div>
      <h2 class="font-heading font-bold text-2xl text-slate-800">Badge Unlocked!</h2>
      <h3 id="modal-badge-title" class="font-heading text-lg text-brand-purple font-semibold mt-1">Line Counter</h3>
      <p id="modal-badge-desc" class="text-sm text-slate-600 mt-2">You mastered stanza and line counting basics!</p>
      <button onclick="closeBadgeModal()" class="mt-6 w-full bg-slate-800 hover:bg-slate-900 text-white font-heading font-bold py-3 rounded-2xl shadow-md transition">
        Awesome! Continue Quest
      </button>
    </div>
  </div>

  <script>
    // Game Data & Question Bank
    const questions = [
      // LEVEL 1: POETRY SCOUT
      {
        id: 1,
        level: 1,
        category: "Mechanics & Definitions",
        stem: "In a poem, what is a stanza?",
        stemES: "En un poema, ¿qué es una estanza (estrofa)?",
        poem: null,
        options: [
          "A single row of words across the page",
          "A group of lines grouped together (like a poem's paragraph)",
          "Words that sound the same at the end"
        ],
        correct: 1,
        explanation: "A stanza is a group of lines grouped together, separated by a blank space. It works just like a paragraph in a story!",
        points: 10
      },
      {
        id: 2,
        level: 1,
        category: "Stanza & Line Counting",
        stem: "Look at this poem snippet. How many verses (lines) are in this snippet?",
        stemES: "Mira este poema. ¿Cuántos versos (líneas) hay en este segmento?",
        poem: [
          { text: "The sun begins to rise so bright,", rhyme: null },
          { text: "It wakes the sleeping birds from sleep.", rhyme: null },
          { text: "They sing their songs into the light,", rhyme: null },
          { text: "A secret promise they will keep.", rhyme: null }
        ],
        options: [
          "1 stanza, 4 lines",
          "4 stanzas, 1 line",
          "2 stanzas, 2 lines"
        ],
        correct: 0,
        explanation: "There is 1 stanza (group of lines) containing 4 individual lines/verses.",
        points: 10
      },
      {
        id: 3,
        level: 1,
        category: "Spotting Exact Rhymes",
        stem: "Which pair of words has an exact (perfect) rhyme?",
        stemES: "¿Qué par de palabras tiene una rima exacta (perfecta)?",
        poem: null,
        options: [
          "Cat / Dog",
          "Night / Bright",
          "Moon / Boat"
        ],
        correct: 1,
        explanation: "Night and Bright end with the exact same 'ite' sound!",
        points: 10
      },
      {
        id: 4,
        level: 1,
        category: "Spotting Exact Rhymes",
        stem: "Which word rhymes perfectly with 'Rain'?",
        stemES: "¿Qué palabra rima perfectamente con 'Rain' (lluvia)?",
        poem: null,
        options: [
          "Train",
          "Cold",
          "See"
        ],
        correct: 0,
        explanation: "Rain and Train share the exact same 'ain' ending sound.",
        points: 10
      },

      // LEVEL 2: SCHEME DETECTIVE
      {
        id: 5,
        level: 2,
        category: "Near Rhymes (Slant Rhymes)",
        stem: "What is a near rhyme (slant rhyme)?",
        stemES: "¿Qué es una rima cercana o asonante (near rhyme)?",
        poem: null,
        options: [
          "Words that spell the exact same way",
          "Words that sound almost the same, but not perfectly (e.g., shape / late)",
          "Words that have no matching sounds at all"
        ],
        correct: 1,
        explanation: "Near rhymes (or slant rhymes) share similar vowel or consonant sounds, but don't match 100% perfectly.",
        points: 20
      },
      {
        id: 6,
        level: 2,
        category: "Near Rhymes (Slant Rhymes)",
        stem: "Which pair of words is a near rhyme?",
        stemES: "¿Qué par de palabras es una rima cercana (near rhyme)?",
        poem: null,
        options: [
          "Blue / Shoe",
          "Hope / Coat",
          "Sun / Fun"
        ],
        correct: 1,
        explanation: "'Hope' and 'Coat' share the same 'o' vowel sound, but end in different consonant sounds (p vs t) - making them a near rhyme!",
        points: 20
      },
      {
        id: 7,
        level: 2,
        category: "Rhyme Scheme Labeling",
        stem: "Read the stanza and find the rhyme scheme pattern:",
        stemES: "Lee la estrofa y encuentra el esquema de rima (rhyme scheme):",
        poem: [
          { text: "I walked into the dark green woods,", rhyme: "A" },
          { text: "I wore my warm red winter coat.", rhyme: "B" },
          { text: "I looked for berries where I could,", rhyme: "A" },
          { text: "And watched the wooden river boat.", rhyme: "B" }
        ],
        options: [
          "AABB",
          "ABAB",
          "ABCB"
        ],
        correct: 1,
        explanation: "Woods (A) and Could (A) rhyme. Coat (B) and Boat (B) rhyme. The pattern alternates: ABAB.",
        points: 20
      },
      {
        id: 8,
        level: 2,
        category: "Rhyme Scheme Labeling",
        stem: "Label this stanza's rhyme scheme pattern:",
        stemES: "Etiqueta el esquema de rima de esta estrofa:",
        poem: [
          { text: "The little puppy liked to play,", rhyme: "A" },
          { text: "He ran around the yard all day.", rhyme: "A" },
          { text: "He chased a big red bouncing ball,", rhyme: "B" },
          { text: "And never seemed to tire at all.", rhyme: "B" }
        ],
        options: [
          "AABB",
          "ABAB",
          "ABCA"
        ],
        correct: 0,
        explanation: "Play/day rhyme (AABB). Ball/all rhyme (BB). The pattern is AABB!",
        points: 20
      },

      // LEVEL 3: RHYME MASTER
      {
        id: 9,
        level: 3,
        category: "Full Analysis Challenge",
        stem: "How many total stanzas and lines are in this entire poem?",
        stemES: "¿Cuántas estrofas y líneas hay en total en este poema?",
        poem: [
          { text: "Stanza 1:", isHeader: true },
          { text: "The wind begins to softly blow,", rhyme: "A" },
          { text: "The yellow leaves drop to the ground.", rhyme: "B" },
          { text: "The chilly winter starts to show,", rhyme: "A" },
          { text: "Without making a single sound.", rhyme: "B" },
          { text: "Stanza 2:", isHeader: true },
          { text: "I put my boots upon my feet,", rhyme: "C" },
          { text: "And zip my jacket to my chin.", rhyme: "D" },
          { text: "I walk along the quiet street,", rhyme: "C" },
          { text: "And feel the frosty morning spin.", rhyme: "D" }
        ],
        options: [
          "2 stanzas, 8 lines",
          "1 stanza, 10 lines",
          "8 stanzas, 2 lines"
        ],
        correct: 0,
        explanation: "There are 2 distinct stanzas (blocks) and 8 total numbered poem verses/lines.",
        points: 30
      },
      {
        id: 10,
        level: 3,
        category: "Near Rhyme Detective",
        stem: "Look at this stanza. Is there a near rhyme present?",
        stemES: "Mira esta estrofa. ¿Hay alguna rima cercana (near rhyme)?",
        poem: [
          { text: "The clouds assemble in the sky,", rhyme: "A" },
          { text: "A storm is coming very fast.", rhyme: "B" },
          { text: "I hold my yellow umbrella high,", rhyme: "A" },
          { text: "And wait until the rain has passed.", rhyme: "B" }
        ],
        options: [
          "Yes, 'sky' and 'high' are near rhymes.",
          "No, all rhymes are perfect (sky/high, fast/passed).",
          "Yes, 'fast' and 'passed' are near rhymes."
        ],
        correct: 1,
        explanation: "Trick question check! 'Sky/high' and 'fast/passed' are both exact 100% perfect rhymes!",
        points: 30
      },
      {
        id: 11,
        level: 3,
        category: "Near Rhyme Challenge",
        stem: "Identify the near rhyme pair in this stanza:",
        stemES: "Identifica la rima cercana en esta estrofa:",
        poem: [
          { text: "The winter air is cold and chill,", rhyme: "A" },
          { text: "I climb up high upon the hill.", rhyme: "A" },
          { text: "I hold a warm cup in my hand,", rhyme: "B" },
          { text: "And watch the quiet frozen land.", rhyme: "B" }
        ],
        options: [
          "chill / hill",
          "hand / land",
          "Neither, both pairs are exact rhymes."
        ],
        correct: 2,
        explanation: "Both chill/hill and hand/land are exact rhymes. Always listen carefully to the ending sounds!",
        points: 30
      }
    ];

    // State Variables
    let currentIdx = 0;
    let score = 0;
    let streak = 0;
    let spanishMode = false;
    let answered = false;
    let audioSynth = window.speechSynthesis;
    let unlockedBadges = { scout: false, detective: false, master: false };

    // Web Audio API Synthesizer for Sound FX
    function playAudioTone(type) {
      try {
        const ctx = new (window.AudioContext || window.webkitAudioContext)();
        const osc = ctx.createOscillator();
        const gain = ctx.createGain();
        osc.connect(gain);
        gain.connect(ctx.destination);

        if (type === 'correct') {
          osc.type = 'triangle';
          osc.frequency.setValueAtTime(523.25, ctx.currentTime); // C5
          osc.frequency.exponentialRampToValueAtTime(659.25, ctx.currentTime + 0.15); // E5
          gain.gain.setValueAtTime(0.3, ctx.currentTime);
          gain.gain.exponentialRampToValueAtTime(0.01, ctx.currentTime + 0.3);
          osc.start();
          osc.stop(ctx.currentTime + 0.3);
        } else if (type === 'badge') {
          osc.type = 'sine';
          osc.frequency.setValueAtTime(440, ctx.currentTime);
          osc.frequency.setValueAtTime(554.37, ctx.currentTime + 0.1);
          osc.frequency.setValueAtTime(659.25, ctx.currentTime + 0.2);
          osc.frequency.setValueAtTime(880, ctx.currentTime + 0.3);
          gain.gain.setValueAtTime(0.4, ctx.currentTime);
          gain.gain.exponentialRampToValueAtTime(0.01, ctx.currentTime + 0.6);
          osc.start();
          osc.stop(ctx.currentTime + 0.6);
        } else {
          osc.type = 'sawtooth';
          osc.frequency.setValueAtTime(220, ctx.currentTime);
          osc.frequency.exponentialRampToValueAtTime(130.81, ctx.currentTime + 0.2);
          gain.gain.setValueAtTime(0.2, ctx.currentTime);
          gain.gain.exponentialRampToValueAtTime(0.01, ctx.currentTime + 0.25);
          osc.start();
          osc.stop(ctx.currentTime + 0.25);
        }
      } catch(e) {
        // Audio fallback
      }
    }

    // Initialize App
    window.onload = function() {
      renderQuestion();
    };

    function toggleSpanishSupport() {
      spanishMode = !spanishMode;
      const toggleText = document.getElementById('spanish-toggle-text');
      const box = document.getElementById('spanish-cognate-box');
      
      if (spanishMode) {
        toggleText.textContent = "Spanish Support: ON";
        box.classList.remove('hidden');
      } else {
        toggleText.textContent = "Spanish Support: OFF";
        box.classList.add('hidden');
      }
      renderQuestion();
    }

    function renderQuestion() {
      answered = false;
      const q = questions[currentIdx];

      // Update level pill and progress
      const pill = document.getElementById('level-badge-pill');
      const title = document.getElementById('level-title-text');
      if (q.level === 1) {
        pill.textContent = "Level 1";
        pill.className = "bg-brand-blue text-white text-xs font-bold px-2.5 py-1 rounded-full uppercase tracking-wider";
        title.textContent = "Poetry Scout";
      } else if (q.level === 2) {
        pill.textContent = "Level 2";
        pill.className = "bg-brand-purple text-white text-xs font-bold px-2.5 py-1 rounded-full uppercase tracking-wider";
        title.textContent = "Scheme Detective";
      } else {
        pill.textContent = "Level 3";
        pill.className = "bg-brand-amber text-white text-xs font-bold px-2.5 py-1 rounded-full uppercase tracking-wider";
        title.textContent = "Rhyme Master";
      }

      // Update counters
      document.getElementById('current-q-num').textContent = currentIdx + 1;
      document.getElementById('total-q-num').textContent = questions.length;
      document.getElementById('level-progress-bar').style.width = `${((currentIdx + 1) / questions.length) * 100}%`;

      // Set category & stem
      document.getElementById('question-category').textContent = q.category;
      document.getElementById('question-stem').textContent = spanishMode ? `${q.stem} (${q.stemES})` : q.stem;

      // Render Poem if present
      const poemContainer = document.getElementById('poem-container');
      const poemLines = document.getElementById('poem-lines');
      poemLines.innerHTML = '';

      if (q.poem) {
        poemContainer.classList.remove('hidden');
        q.poem.forEach((line) => {
          if (line.isHeader) {
            const h = document.createElement('div');
            h.className = "font-heading font-bold text-xs uppercase tracking-wider text-slate-400 mt-3 first:mt-0";
            h.textContent = line.text;
            poemLines.appendChild(h);
          } else {
            const l = document.createElement('div');
            l.className = "flex justify-between items-center bg-white px-3 py-2 rounded-xl border border-slate-200/80 shadow-2xs";

            // Process text & highlight end words if rhyme scheme present
            let lineHTML = line.text;
            if (line.rhyme) {
              const words = line.text.trim().split(' ');
              const lastWord = words.pop().replace(/[.,!]/g, '');
              const restText = words.join(' ');
              const rhymeClass = `rhyme-${line.rhyme.toLowerCase()}`;
              lineHTML = `${restText} <span class="${rhymeClass}">${lastWord}</span>`;
            }

            l.innerHTML = `
              <span>${lineHTML}</span>
              ${line.rhyme ? `<span class="text-xs font-bold px-2 py-0.5 rounded bg-slate-100 border text-slate-600 font-mono">${line.rhyme}</span>` : ''}
            `;
            poemLines.appendChild(l);
          }
        });
      } else {
        poemContainer.classList.add('hidden');
      }

      // Render Options
      const optionsContainer = document.getElementById('options-container');
      optionsContainer.innerHTML = '';

      q.options.forEach((opt, idx) => {
        const btn = document.createElement('button');
        btn.className = "w-full text-left p-4 rounded-2xl border-2 border-slate-200 hover:border-brand-purple hover:bg-purple-50/50 transition-all font-semibold text-slate-700 flex items-center justify-between group";
        btn.onclick = () => checkAnswer(idx);
        btn.innerHTML = `
          <div class="flex items-center space-x-3">
            <span class="w-8 h-8 rounded-xl bg-slate-100 text-slate-600 font-heading font-bold flex items-center justify-center group-hover:bg-brand-purple group-hover:text-white transition">
              ${String.fromCharCode(65 + idx)}
            </span>
            <span class="text-sm sm:text-base">${opt}</span>
          </div>
          <i class="fa-regular fa-circle text-slate-300 text-lg group-hover:text-brand-purple"></i>
        `;
        optionsContainer.appendChild(btn);
      });

      // Reset Feedback
      document.getElementById('feedback-box').classList.add('hidden');
      document.getElementById('next-btn').classList.add('hidden');
    }

    function checkAnswer(selectedIdx) {
      if (answered) return;
      answered = true;

      const q = questions[currentIdx];
      const feedbackBox = document.getElementById('feedback-box');
      const feedbackIcon = document.getElementById('feedback-icon');
      const feedbackTitle = document.getElementById('feedback-title');
      const feedbackMsg = document.getElementById('feedback-message');
      const optionButtons = document.getElementById('options-container').children;

      if (selectedIdx === q.correct) {
        playAudioTone('correct');
        score += q.points;
        streak += 1;

        optionButtons[selectedIdx].className = "w-full text-left p-4 rounded-2xl border-2 border-green-500 bg-green-50 font-semibold text-green-900 flex items-center justify-between";
        optionButtons[selectedIdx].querySelector('i').className = "fa-solid fa-circle-check text-green-600 text-lg";

        feedbackBox.className = "mt-6 p-4 rounded-2xl border-2 border-green-200 bg-green-50 animate-pop-in";
        feedbackIcon.className = "text-green-600 text-2xl mt-0.5";
        feedbackIcon.innerHTML = `<i class="fa-solid fa-circle-check"></i>`;
        feedbackTitle.className = "font-heading font-bold text-base text-green-900";
        feedbackTitle.textContent = "Correct! Excelente!";
        feedbackMsg.className = "text-sm mt-1 leading-relaxed text-green-800";
        feedbackMsg.textContent = `${q.explanation} (+${q.points} pts)`;

      } else {
        playAudioTone('wrong');
        streak = 0;

        optionButtons[selectedIdx].className = "w-full text-left p-4 rounded-2xl border-2 border-rose-400 bg-rose-50 font-semibold text-rose-900 flex items-center justify-between";
        optionButtons[selectedIdx].querySelector('i').className = "fa-solid fa-circle-xmark text-rose-500 text-lg";

        // Highlight correct option
        optionButtons[q.correct].className = "w-full text-left p-4 rounded-2xl border-2 border-green-400 bg-green-50 font-semibold text-green-900 flex items-center justify-between";

        feedbackBox.className = "mt-6 p-4 rounded-2xl border-2 border-rose-200 bg-rose-50 animate-pop-in";
        feedbackIcon.className = "text-rose-500 text-2xl mt-0.5";
        feedbackIcon.innerHTML = `<i class="fa-solid fa-lightbulb"></i>`;
        feedbackTitle.className = "font-heading font-bold text-base text-rose-900";
        feedbackTitle.textContent = "Good try! / ¡Buen intento!";
        feedbackMsg.className = "text-sm mt-1 leading-relaxed text-rose-800";
        feedbackMsg.textContent = q.explanation;
      }

      // Update UI Header Stats
      document.getElementById('score-display').textContent = score;
      document.getElementById('streak-display').textContent = streak;

      feedbackBox.classList.remove('hidden');
      document.getElementById('next-btn').classList.remove('hidden');

      // Check Badges Trigger
      checkBadges();
    }

    function checkBadges() {
      // Badge 1: Complete Level 1 (Question 4)
      if (currentIdx >= 3 && !unlockedBadges.scout) {
        unlockedBadges.scout = true;
        unlockBadgeUI('badge-scout', 'Line Counter', 'You mastered stanza and line counting basics!', 'fa-magnifying-glass', 'bg-blue-500');
      }
      // Badge 2: Complete Level 2 (Question 8)
      if (currentIdx >= 7 && !unlockedBadges.detective) {
        unlockedBadges.detective = true;
        unlockBadgeUI('badge-detective', 'Pattern Decoder', 'You solved ABAB / AABB rhyme schemes and near rhymes!', 'fa-user-secret', 'bg-purple-500');
      }
      // Badge 3: Complete Level 3 (Question 11)
      if (currentIdx >= 10 && !unlockedBadges.master) {
        unlockedBadges.master = true;
        unlockBadgeUI('badge-master', 'Rhyme Master', 'You are an official 7th Grade Rhyme Master!', 'fa-crown', 'bg-amber-500');
      }
    }

    function unlockBadgeUI(elementId, title, desc, iconClass, bgClass) {
      const el = document.getElementById(elementId);
      el.classList.remove('opacity-50', 'grayscale');
      el.classList.add('border-amber-300', 'bg-amber-50/50');

      // Show Modal Celebration
      document.getElementById('modal-badge-title').textContent = title;
      document.getElementById('modal-badge-desc').textContent = desc;
      const modalIcon = document.getElementById('modal-badge-icon');
      modalIcon.className = `w-20 h-20 rounded-3xl ${bgClass} text-white flex items-center justify-center text-4xl mx-auto shadow-lg mb-4 animate-bounce-short`;
      modalIcon.innerHTML = `<i class="fa-solid ${iconClass}"></i>`;

      document.getElementById('badge-modal').classList.remove('hidden');
      playAudioTone('badge');
    }

    function closeBadgeModal() {
      document.getElementById('badge-modal').classList.add('hidden');
    }

    function nextQuestion() {
      if (currentIdx < questions.length - 1) {
        currentIdx++;
        renderQuestion();
      } else {
        // Quest Completed Screen
        showCompletionScreen();
      }
    }

    function showCompletionScreen() {
      const card = document.querySelector('main');
      card.innerHTML = `
        <div class="bg-white rounded-3xl border border-slate-200 p-8 text-center shadow-lg animate-pop-in">
          <div class="w-20 h-20 rounded-full bg-amber-100 text-amber-500 flex items-center justify-center text-4xl mx-auto mb-4">
            <i class="fa-solid fa-trophy"></i>
          </div>
          <h2 class="font-heading font-bold text-3xl text-slate-800">Quest Complete!</h2>
          <p class="text-slate-600 mt-2">You finished all rhyme scheme challenges!</p>
          
          <div class="my-6 p-6 bg-slate-50 rounded-2xl border border-slate-200 inline-block text-left w-full max-w-sm">
            <div class="flex justify-between py-2 border-b">
              <span class="text-slate-600 font-medium">Final Score:</span>
              <span class="font-bold text-amber-600">${score} pts</span>
            </div>
            <div class="flex justify-between py-2 border-b">
              <span class="text-slate-600 font-medium">Badges Unlocked:</span>
              <span class="font-bold text-purple-600">${Object.values(unlockedBadges).filter(Boolean).length} / 3</span>
            </div>
          </div>

          <button onclick="location.reload()" class="bg-brand-purple hover:bg-purple-700 text-white font-heading font-bold px-8 py-3 rounded-2xl shadow-md transition">
            Play Again / Jugar de Nuevo
          </button>
        </div>
      `;
    }

    function speakCurrentQuestion() {
      if (!audioSynth) return;
      if (audioSynth.speaking) {
        audioSynth.cancel();
        return;
      }

      const q = questions[currentIdx];
      let speakText = q.stem + ". ";

      if (q.poem) {
        speakText += " Here is the poem snippet: ";
        q.poem.forEach(l => {
          if (!l.isHeader) speakText += l.text + ". ";
        });
      }

      speakText += " Options: ";
      q.options.forEach((opt, i) => {
        speakText += `Option ${String.fromCharCode(65 + i)}: ${opt}. `;
      });

      const utterance = new SpeechSynthesisUtterance(speakText);
      utterance.rate = 0.9; // Slightly slower for ELL clarity
      audioSynth.speak(utterance);
    }
  </script>
</body>
</html>