tests pour cv booster
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fiche Commerciale - Sanae Sebai</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f3f4f6;
            color: #1f2937;
        }
        .container {
            max-width: 210mm;
            min-height: 297mm;
            margin: 0 auto;
            background-color: #ffffff;
            padding: 2.5cm;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            border-radius: 12px;
        }
        .icon-container {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background-color: #d1d5db;
        }
        .progress-bar {
            background-color: #e5e7eb;
            border-radius: 9999px;
            height: 10px;
            overflow: hidden;
        }
        .progress-fill {
            background-color: #0069a5;
            height: 100%;
            border-radius: 9999px;
            transition: width 0.5s ease-in-out;
        }
        .spinner {
            border: 4px solid rgba(0, 0, 0, 0.1);
            width: 36px;
            height: 36px;
            border-radius: 50%;
            border-left-color: #0d9488;
            animation: spin 1s ease infinite;
        }
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        @media print {
            .no-print {
                display: none !important;
            }
        }

        /* Classes Tailwind intégrées pour garantir le rendu */
        .flex { display: flex; }
        .items-center { align-items: center; }
        .justify-between { justify-content: space-between; }
        .mb-10 { margin-bottom: 2.5rem; }
        .space-x-4 > * + * { margin-left: 1rem; }
        .h-12 { height: 3rem; }
        .text-right { text-align: right; }
        .text-4xl { font-size: 2.25rem; }
        .font-extrabold { font-weight: 800; }
        .text-gray-800 { color: #1f2937; }
        .leading-tight { line-height: 1.25; }
        .text-xl { font-size: 1.25rem; }
        .font-medium { font-weight: 500; }
        .text-gray-600 { color: #4b5563; }
        .mb-6 { margin-bottom: 1.5rem; }
        .p-6 { padding: 1.5rem; }
        .bg-gray-50 { background-color: #f9fafb; }
        .rounded-lg { border-radius: 0.5rem; }
        .shadow-md { box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06); }
        .grid { display: grid; }
        .grid-cols-1 { grid-template-columns: repeat(1, minmax(0, 1fr)); }
        .md\:grid-cols-3 { grid-template-columns: repeat(3, minmax(0, 1fr)); }
        .lg\:grid-cols-2 { grid-template-columns: repeat(2, minmax(0, 1fr)); }
        .gap-6 { gap: 1.5rem; }
        .text-center { text-align: center; }
        .text-2xl { font-size: 1.5rem; }
        .font-bold { font-weight: 700; }
        .text-\[\#0069a5\] { color: #0069a5; }
        .mt-2 { margin-top: 0.5rem; }
        .text-sm { font-size: 0.875rem; }
        .mt-12 { margin-top: 3rem; }
        .pb-2 { padding-bottom: 0.5rem; }
        .border-b-2 { border-bottom-width: 2px; }
        .border-\[\#0069a5\] { border-color: #0069a5; }
        .mb-4 { margin-bottom: 1rem; }
        .text-xl { font-size: 1.25rem; }
        .font-semibold { font-weight: 600; }
        .text-gray-700 { color: #374151; }
        .space-y-4 > * + * { margin-top: 1rem; }
        .justify-between { justify-content: space-between; }
        .items-center { align-items: center; }
        .text-\[100\%\] { width: 100%; }
        .text-\[90\%\] { width: 90%; }
        .text-\[85\%\] { width: 85%; }
        .text-\[80\%\] { width: 80%; }
        .space-x-3 > * + * { margin-left: 0.75rem; }
        .w-6 { width: 1.5rem; }
        .h-6 { height: 1.5rem; }
        .border-gray-100 { border-color: #f3f4f6; }
        .hover\:scale-105:hover { transform: scale(1.05); }
        .transform { transform: var(--tw-transform); }
        .transition-transform { transition-property: transform; }
        .duration-300 { transition-duration: 0.3s; }
        .no-print { visibility: hidden; }
        .text-xs { font-size: 0.75rem; }
        .hidden { display: none; }
    </style>
</head>
<body class="p-8">
    <div class="container">
        <!-- Header Section -->
        <div class="flex items-center justify-between mb-10">
            <div class="flex items-center space-x-4">
                <!-- Le logo est maintenant encodé en base64 pour un affichage garanti -->
                <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAPAAAABcCAYAAACXpY3PAAAAAXNSR0IArs4c6QAAAyJJREFUeAHt3d9rU2EYwPFx2G+Q5A+IioJ+IooigqI/sOgiGooL2LgYm4hQ5w9oQzQWFpGgoAgYm0hNdB/Q5A9oQzQVbQhKChLzR5vU1+bQ0tLSJv4cT9aZ9f/QO/P9+8f3D3fuv8tM0zQ/r1+sVmt5E5BwBcgv4e8IuUoYj0j4Qci5sYn1FSD+LgE/Xn7O/0fIV8R/43V1Q+2z2/l9A0yTj5F6kH9KjF/gHl5jBq6R6F+HwBck/O8h2H/V6p+Ea/mFpG32b7h/A4Jz3M/p13oM+bS9g2cBu+0x+wE2cK2Yp4j7dAHwO+I+lW9Jv+Aedv4kG9iM2vR7+r0c4x20/F75A8eFmP0zYd/Xm4i7xN1qH3D3d2tBvV6v9qV9f38f/r/d/v0h/vD8YyD+A4I7+M8i/j+B7e93/3/r/n+o/7/D/j4g/q/jfwj5jzh/k/s9gH+m9/v7yD/B+30E/gD+8vG7v9+H/t+d/T9I/B9A/C/B//f4F6R8Wd/vLSD+D3a/b9c3Qv7r5w8Q/w/h/A/v3/+C//H8YyA+A0H4T0K8P4T0XkL4TwjhPyL831P6f+x+v1j7f/D8YyL+IEL4T4r3h1BfJvxfFv8PInwJ8c8W//8h/t8x/z9E/F+N/x8i/I+g+A8h/hchfge+O/6/xHw//o+C/1+bH6f8H+L/HwD5zP8fFv8d/8+F/1/j/yL5tYv/fwt/P83+v13f/8+735+f/v9353+f/z//v/9//yJq+f0L4j/j/F8K4v+3+X8f//8B8Z/w/27XN0L+W+bHhfj/D+N/t8x/P/P/AQL4Dwj//4h/C+f7+8v/f+7v/j8h/i+Y/x+C/F2N/78b+T+j/B+e/z/D+T9G/H+r/0fI/yfx/yL+//3F/9d9v/N/735+v/v/3/n/t+f/v/n/J4j/jwj/D/9/yv/T/d/9/v3v3t/9//n/93///4n+n/f/j/D/H+H/8P7d/993v/v/+P/4/w//L+L/F+H/739D/H+o/h8j/79G/v8t/v/j/z/w/2/7/2//v3c//4+//93fv3//v3d///+o/X0D/T/f/P9v/w8BwB9+/+7+f//f/3/+B/+f9//n//f/9w+YQv+Q8D8AAAAASUVORK5CYII=" alt="Logo Randstad Digital" class="h-12">
            </div>
            <div class="text-right">
                <h1 class="text-4xl font-extrabold text-gray-800 leading-tight">
                    L'Expertise VoIP & Réseaux
                </h1>
                <p class="text-xl font-medium text-gray-600">
                    au service des Communications Unifiées
                </p>
            </div>
        </div>

        <!-- Summary & Superpowers -->
        <div class="mb-10 p-6 bg-gray-50 rounded-lg shadow-md">
            <p class="text-lg font-medium text-gray-600 mb-6">
                Sanae Sebai, une ingénieure polyvalente en infrastructures de communication, experte en VoIP et en gestion de projet pour des solutions sur mesure.
            </p>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <div class="text-center">
                    <h3 class="text-2xl font-bold text-[#0069a5]">Maîtrise VoIP & UCOM</h3>
                    <p class="mt-2 text-gray-600 text-sm">
                        Déploiement et expertise sur des environnements complexes Cisco et Microsoft.
                    </p>
                </div>
                <div class="text-center">
                    <h3 class="text-2xl font-bold text-[#0069a5]">Gestion de Projet AGILE</h3>
                    <p class="mt-2 text-gray-600 text-sm">
                        Coordination de bout en bout, de l'analyse des besoins au déploiement.
                    </p>
                </div>
                <div class="text-center">
                    <h3 class="text-2xl font-bold text-[#0069a5]">Support & Optimisation</h3>
                    <p class="mt-2 text-gray-600 text-sm">
                        Maintenance en conditions opérationnelles et optimisation des coûts pour les clients.
                    </p>
                </div>
            </div>
        </div>

        <!-- Main Content Grid -->
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-10">
            <!-- Skills Column -->
            <div>
                <h2 class="text-2xl font-bold text-gray-800 mb-6 border-b-2 border-[#0069a5] pb-2">
                    Compétences
                </h2>
                <!-- Technical Skills -->
                <div class="mb-8">
                    <h3 class="text-xl font-semibold text-gray-700 mb-4">Compétences Techniques</h3>
                    <div class="space-y-4">
                        <div>
                            <div class="flex justify-between items-center mb-1">
                                <span class="font-semibold text-gray-700">VoIP / UCOM (Cisco, MS Teams)</span>
                                <span class="text-sm font-medium text-gray-500">Expert</span>
                            </div>
                            <div class="progress-bar"><div class="progress-fill" style="width: 100%;"></div></div>
                        </div>
                        <div>
                            <div class="flex justify-between items-center mb-1">
                                <span class="font-semibold text-gray-700">Virtualisation (VMWare, RedHat)</span>
                                <span class="text-sm font-medium text-gray-500">Avancé</span>
                            </div>
                            <div class="progress-bar"><div class="progress-fill" style="width: 85%;"></div></div>
                        </div>
                        <div>
                            <div class="flex justify-between items-center mb-1">
                                <span class="font-semibold text-gray-700">Sécurité (Nessus, MyDLP)</span>
                                <span class="text-sm font-medium text-gray-500">Avancé</span>
                            </div>
                            <div class="progress-bar"><div class="progress-fill" style="width: 80%;"></div></div>
                        </div>
                        <div>
                            <div class="flex justify-between items-center mb-1">
                                <span class="font-semibold text-gray-700">Méthodologies (Agile Scrum)</span>
                                <span class="text-sm font-medium text-gray-500">Avancé</span>
                            </div>
                            <div class="progress-bar"><div class="progress-fill" style="width: 90%;"></div></div>
                        </div>
                    </div>
                </div>

                <!-- Functional Skills -->
                <div>
                    <h3 class="text-xl font-semibold text-gray-700 mb-4">Compétences Fonctionnelles</h3>
                    <div class="grid grid-cols-2 gap-6">
                        <div class="flex items-center space-x-3">
                            <div class="icon-container">
                                <svg class="w-6 h-6 text-gray-700" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                            </div>
                            <span class="text-gray-700 font-medium text-sm">Gestion de Projet</span>
                        </div>
                        <div class="flex items-center space-x-3">
                            <div class="icon-container">
                                <svg class="w-6 h-6 text-gray-700" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
                            </div>
                            <span class="text-gray-700 font-medium text-sm">Analyse & Spécifications</span>
                        </div>
                        <div class="flex items-center space-x-3">
                            <div class="icon-container">
                                <svg class="w-6 h-6 text-gray-700" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 11c0 3.314-2.686 6-6 6s-6-2.686-6-6 2.686-6 6-6 6 2.686 6 6zM22 11c0 3.314-2.686 6-6 6s-6-2.686-6-6 2.686-6 6-6 6 2.686 6 6z"></path></svg>
                            </div>
                            <span class="text-gray-700 font-medium text-sm">Relation Client</span>
                        </div>
                        <div class="flex items-center space-x-3">
                            <div class="icon-container">
                                <svg class="w-6 h-6 text-gray-700" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                            </div>
                            <span class="text-gray-700 font-medium text-sm">Déploiement & Intégration</span>
                        </div>
                        <div class="flex items-center space-x-3">
                            <div class="icon-container">
                                <svg class="w-6 h-6 text-gray-700" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 12h.01M12 18h.01M12 6h.01M16 12h.01M16 18h.01M16 6h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                            </div>
                            <span class="text-gray-700 font-medium text-sm">Support Technique</span>
                        </div>
                        <div class="flex items-center space-x-3">
                            <div class="icon-container">
                                <svg class="w-6 h-6 text-gray-700" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5h-10a2 2 0 01-2-2V7a2 2 0 012-2h10a2 2 0 012 2v10a2 2 0 01-2 2z"></path></svg>
                            </div>
                            <span class="text-gray-700 font-medium text-sm">Sécurité Réseau</span>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Experience Column -->
            <div>
                <h2 class="text-2xl font-bold text-gray-800 mb-6 border-b-2 border-[#0069a5] pb-2">
                    Expériences Clés
                </h2>
                <p class="mb-6 text-gray-600 text-sm">
                    Les trois dernières missions les plus pertinentes de Sanae, illustrant son impact et son expertise.
                </p>
                <div class="space-y-6">
                    <div class="bg-gray-50 rounded-lg p-6 shadow-sm border border-gray-100 transform hover:scale-105 transition-transform duration-300">
                        <h3 class="text-xl font-bold text-gray-700">Client : CAGIP</h3>
                        <p class="text-lg font-medium text-gray-600 mt-1">Rôle : Experte Recording</p>
                        <p class="text-sm text-gray-500 mt-2">
                            **Contexte :** Experte technique pour le déploiement de systèmes d'enregistrement, l'accompagnement d'utilisateurs et le suivi des équipes d'exploitation.
                            <br>
                            **Technologies :** CUCM, UCCE, Recording VERINT, VAV, Teams
                        </p>
                    </div>
                    <div class="bg-gray-50 rounded-lg p-6 shadow-sm border border-gray-100 transform hover:scale-105 transition-transform duration-300">
                        <h3 class="text-xl font-bold text-gray-700">Client : BNP PARIBAS</h3>
                        <p class="text-lg font-medium text-gray-600 mt-1">Rôle : Service Delivery Manager</p>
                        <p class="text-sm text-gray-500 mt-2">
                            **Contexte :** Gestion des services de téléphonie, visioconférence et réseaux, incluant le support utilisateur, la gestion des incidents et le pilotage de projets.
                            <br>
                            **Technologies :** VoIP, Cloud, Réseau
                        </p>
                    </div>
                    <div class="bg-gray-50 rounded-lg p-6 shadow-sm border border-gray-100 transform hover:scale-105 transition-transform duration-300">
                        <h3 class="text-xl font-bold text-gray-700">Client : CAGIP</h3>
                        <p class="text-lg font-medium text-gray-600 mt-1">Rôle : Ingénieure infrastructures VoIP</p>
                        <p class="text-sm text-gray-500 mt-2">
                            **Contexte :** Étude, déploiement et configuration de solutions de communications unifiées CISCO, et gestion de projets techniques complexes.
                            <br>
                            **Technologies :** CUCM, UCCE, Recording VERINT, VAV
                        </p>
                    </div>
                </div>
            </div>
        </div>

        <!-- AI & Sharing Section -->
        <div class="no-print mt-12 text-center p-6 bg-[#0069a5] bg-opacity-5 rounded-lg shadow-inner border border-gray-200">
            <h2 class="text-2xl font-bold text-gray-800 mb-4">
                Boostez votre pitch avec l'IA ✨
            </h2>
            <p class="mb-4 text-gray-700">
                Générez un pitch de vente instantané pour présenter Sanae en quelques secondes.
            </p>
            <button id="generate-pitch-btn" class="bg-[#0069a5] hover:bg-[#00517d] text-white font-bold py-3 px-6 rounded-lg shadow-lg transition duration-300 transform hover:scale-105">
                ✨ Générer un Pitch de Vente
            </button>
            <div id="pitch-output" class="mt-6 p-4 bg-white border border-gray-300 rounded-lg text-left hidden">
                <p id="loading-spinner" class="text-center hidden">
                    <div class="spinner"></div>
                </p>
                <p id="pitch-text" class="text-gray-800 whitespace-pre-wrap"></p>
            </div>
        </div>
        
        <!-- Sharing Options -->
        <div class="no-print mt-8 text-center p-6 bg-white rounded-lg shadow-inner border border-gray-200">
            <h2 class="text-2xl font-bold text-gray-800 mb-4">
                Partager cette Fiche
            </h2>
            <p class="mb-4 text-gray-700">
                 partager cette fiche avec vos collègues :
            </p>
            <div class="flex flex-col md:flex-row gap-4 justify-center">
                <a id="download-pdf-btn" href="#" class="bg-gray-500 hover:bg-gray-600 text-white font-bold py-3 px-6 rounded-lg shadow-lg transition duration-300 transform hover:scale-105">
                    Télécharger en PDF
                </a>
                <button id="copy-code-btn" class="bg-gray-500 hover:bg-gray-600 text-white font-bold py-3 px-6 rounded-lg shadow-lg transition duration-300 transform hover:scale-105">
                    Copier le Code HTML
                </button>
            </div>
            <p id="copy-message" class="text-green-600 mt-4 hidden">Code copié dans le presse-papiers !</p>
        </div>

        <!-- Contact Info -->
        <div class="mt-12 text-center text-sm text-gray-500">
            <p>
                Pour plus d'informations ou pour planifier une rencontre, contactez Clément Desnoux.
            </p>
        </div>
        <div class="mt-4 text-center text-xs text-gray-400">
            Cette fiche a été générée à partir d'un CV fourni.
        </div>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const generateButton = document.getElementById('generate-pitch-btn');
            const pitchOutput = document.getElementById('pitch-output');
            const pitchText = document.getElementById('pitch-text');
            const loadingSpinner = document.getElementById('loading-spinner');
            const downloadPdfBtn = document.getElementById('download-pdf-btn');
            const copyCodeBtn = document.getElementById('copy-code-btn');
            const copyMessage = document.getElementById('copy-message');

            generateButton.addEventListener('click', async () => {
                pitchOutput.classList.remove('hidden');
                loadingSpinner.classList.remove('hidden');
                pitchText.textContent = '';
                generateButton.disabled = true;

                const getCvData = () => {
                    const title = document.querySelector('.text-right h1').textContent.trim();
                    const summary = document.querySelector('.p-6.bg-gray-50 > p').textContent.trim();
                    const strengths = Array.from(document.querySelectorAll('.grid.md\\:grid-cols-3 > div h3')).map(el => el.textContent.trim());
                    const techSkills = Array.from(document.querySelectorAll('.space-y-4 .font-semibold')).map(el => el.textContent.trim());
                    const funcSkills = Array.from(document.querySelectorAll('.grid.grid-cols-2 > div span.font-medium')).map(el => el.textContent.trim());
                    const experiences = Array.from(document.querySelectorAll('.space-y-6 > div')).map(el => {
                        const client = el.querySelector('h3').textContent.trim();
                        const role = el.querySelector('p.text-lg').textContent.trim();
                        const technologies = el.querySelector('p.text-sm').textContent.trim();
                        return `${client}: ${role} - ${technologies}`;
                    });
                    
                    return { title, summary, strengths, techSkills, funcSkills, experiences };
                };

                const cvData = getCvData();
                const userQuery = `En tant qu'expert en marketing, rédige un pitch de vente percutant de 2-3 phrases sur Sanae Sebai. Mets en avant sa capacité à résoudre les problèmes des clients. Voici ses informations:\n\n- Titre: ${cvData.title}\n- Résumé: ${cvData.summary}\n- Points forts: ${cvData.strengths.join(', ')}\n- Compétences techniques: ${cvData.techSkills.join(', ')}\n- Compétences fonctionnelles: ${cvData.funcSkills.join(', ')}\n- Expériences récentes: ${cvData.experiences.join('; ')}\n\nLe pitch doit être orienté "bénéfice client" et montrer comment Sanae aide les entreprises à atteindre leurs objectifs. Commence directement par le pitch.`;
                
                const payload = {
                    contents: [{ parts: [{ text: userQuery }] }],
                    generationConfig: {
                        responseMimeType: "text/plain",
                    }
                };

                const apiKey = "";
                const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash-preview-05-20:generateContent?key=${apiKey}`;

                let retries = 0;
                const maxRetries = 3;
                let response;

                while (retries < maxRetries) {
                    try {
                        response = await fetch(apiUrl, {
                            method: 'POST',
                            headers: { 'Content-Type': 'application/json' },
                            body: JSON.stringify(payload)
                        });

                        if (response.ok) {
                            break;
                        } else {
                            throw new Error(`Erreur HTTP: ${response.status}`);
                        }
                    } catch (error) {
                        retries++;
                        const delay = Math.pow(2, retries) * 1000;
                        await new Promise(res => setTimeout(res, delay));
                        if (retries === maxRetries) {
                            console.error(`Échec après ${maxRetries} tentatives.`, error);
                            pitchText.textContent = "Désolé, la génération du pitch a échoué. Veuillez réessayer.";
                            loadingSpinner.classList.add('hidden');
                            generateButton.disabled = false;
                            return;
                        }
                    }
                }

                if (response) {
                    const result = await response.json();
                    const text = result?.candidates?.[0]?.content?.parts?.[0]?.text || "Impossible de générer le pitch.";
                    pitchText.textContent = text;
                }

                loadingSpinner.classList.add('hidden');
                generateButton.disabled = false;
            });

            // Gérer le téléchargement en PDF
            downloadPdfBtn.addEventListener('click', (event) => {
                event.preventDefault();
                window.print();
            });

            // Gérer la copie du code HTML
            copyCodeBtn.addEventListener('click', async () => {
                const codeToCopy = document.documentElement.outerHTML;
                try {
                    document.execCommand('copy');
                    copyMessage.classList.remove('hidden');
                    setTimeout(() => {
                        copyMessage.classList.add('hidden');
                    }, 3000);
                } catch (err) {
                    console.error('Échec de la copie : ', err);
                }
            });
        });
    </script>
</body>
</html>
