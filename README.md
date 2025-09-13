<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - Mamadou Ndao</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
        }
        .section {
            padding-top: 5rem;
            padding-bottom: 5rem;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- Header & Navigation -->
    <header class="bg-white shadow-sm fixed w-full z-10 top-0">
        <nav class="container mx-auto px-6 py-3 flex justify-between items-center">
            <a href="#accueil" class="text-2xl font-bold text-blue-600">MN</a>
            <div class="space-x-4 hidden md:flex">
                <a href="#a-propos" class="text-gray-600 hover:text-blue-500 transition-colors duration-300">À Propos</a>
                <a href="#experience" class="text-gray-600 hover:text-blue-500 transition-colors duration-300">Expérience</a>
                <a href="#competences" class="text-gray-600 hover:text-blue-500 transition-colors duration-300">Compétences</a>
                <a href="#certifications" class="text-gray-600 hover:text-blue-500 transition-colors duration-300">Certifications</a>
            </div>
            <!-- Mobile Menu Button -->
            <button id="menu-button" class="md:hidden text-gray-600 hover:text-blue-500 focus:outline-none">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
            </button>
        </nav>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white shadow-lg py-2">
            <a href="#a-propos" class="block px-4 py-2 text-gray-600 hover:bg-gray-100">À Propos</a>
            <a href="#experience" class="block px-4 py-2 text-gray-600 hover:bg-gray-100">Expérience</a>
            <a href="#competences" class="block px-4 py-2 text-gray-600 hover:bg-gray-100">Compétences</a>
            <a href="#certifications" class="block px-4 py-2 text-gray-600 hover:bg-gray-100">Certifications</a>
        </div>
    </header>

    <!-- Main Content -->
    <main class="container mx-auto px-6 mt-20">
        <!-- Hero/About Me Section -->
        <section id="accueil" class="section text-center md:text-left">
            <div class="flex flex-col md:flex-row items-center justify-center md:justify-start space-y-6 md:space-y-0 md:space-x-12">
                <div class="w-48 h-48 bg-gray-200 rounded-full flex items-center justify-center text-4xl font-bold text-gray-500">
                    MN
                </div>
                <div class="max-w-xl">
                    <h1 class="text-4xl md:text-5xl lg:text-6xl font-extrabold text-blue-600">Mamadou Ndao</h1>
                    <p class="text-xl md:text-2xl font-light text-gray-700 mt-2">Bioinformaticien</p>
                    <p class="text-lg text-gray-600 mt-4 leading-relaxed">
                        Bioinformaticien diplômé d’un Master en Bioinformatique-Biomathématique de l’Université
                        Cheikh Anta Diop (UCAD), avec une solide expérience dans l’analyse génomique d’agents
                        pathogènes humains et le traitement de données omiques (génomique, transcriptomique,
                        métagénomique). Formé aux outils avancés de séquençage et d’analyse bioinformatique, je me
                        spécialise dans l’identification de gènes de résistance, de virulence et de plasmides. Passionné
                        par l’étude des bactéries multirésistantes, je suis engagé dans plusieurs projets de surveillance
                        de l’antibiorésistance en Afrique. Autonome, rigoureux, doté d’un esprit d’équipe et d’une forte
                        capacité pédagogique.
                    </p>
                    <div class="flex justify-center md:justify-start space-x-4 mt-6">
                        <a href="mailto:ndaom403@gmail.com" class="text-blue-500 hover:text-blue-700 transition-colors duration-300">
                            <svg class="w-8 h-8" fill="currentColor" viewBox="0 0 20 20">
                                <path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z"></path>
                                <path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z"></path>
                            </svg>
                        </a>
                        <a href="https://www.linkedin.com/in/mamadou-ndao-6869741b1/" target="_blank" rel="noopener noreferrer" class="text-blue-500 hover:text-blue-700 transition-colors duration-300">
                            <svg class="w-8 h-8" fill="currentColor" viewBox="0 0 20 20">
                                <path fill-rule="evenodd" d="M16 4a2 2 0 00-2-2h-4a2 2 0 00-2 2v2a2 2 0 002 2h2v4h-2a2 2 0 00-2 2v2a2 2 0 002 2h4a2 2 0 002-2v-4h2a2 2 0 002-2V6a2 2 0 00-2-2h-2zM9 16V9a2 2 0 01-2-2V5a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2v7H9z" clip-rule="evenodd"></path>
                            </svg>
                        </a>
                        <!-- GitHub Icon -->
                        <a href="https://github.com/bioinfosif" target="_blank" rel="noopener noreferrer" class="text-blue-500 hover:text-blue-700 transition-colors duration-300">
                            <svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387 0.599 0.111 0.793-0.261 0.793-0.577 0-0.285-0.01-1.040-0.015-2.040-3.338 0.724-4.042-1.61-4.042-1.619-0.542-1.373-1.328-1.743-1.328-1.743-1.089-0.745 0.083-0.729 0.083-0.729 1.205 0.084 1.839 1.237 1.839 1.237 1.07 1.834 2.809 1.305 3.49-0.200 0.102-0.785 0.418-1.305 0.762-1.605-2.665-0.304-5.467-1.334-5.467-2.964 0-1.313 0.468-2.389 1.236-3.228-0.125-0.301-0.537-1.524 0.117-3.176 0 0 1.008-0.322 3.301 1.230 0.957-0.266 1.983-0.399 3.001-0.399 1.017 0 2.044 0.133 3.001 0.399 2.293-1.552 3.301-1.230 3.301-1.230 0.655 1.652 0.243 2.875 0.117 3.176 0.77 0.839 1.236 1.915 1.236 3.228 0 1.63-2.802 2.666-5.475 2.964 0.422 0.363 0.812 1.106 0.812 2.228 0 1.605-0.015 2.897-0.015 3.295 0 0.319 0.192 0.694 0.801 0.576 4.765-1.589 8.199-6.088 8.199-11.386 0-6.627-5.373-12-12-12z" />
                            </svg>
                        </a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Experience Section -->
        <section id="experience" class="section bg-white rounded-xl shadow-lg p-8">
            <h2 class="text-3xl font-bold text-blue-600 mb-8 text-center">Expérience Professionnelle</h2>
            <div class="space-y-12">
                <!-- IRESSEF -->
                <div class="flex items-start">
                    <div class="w-16 h-16 bg-gray-200 rounded-full flex-shrink-0 mr-6"></div>
                    <div>
                        <h3 class="text-2xl font-semibold text-gray-800">Bioinformaticien - IRESSEF</h3>
                        <p class="text-gray-500 mt-1">Mars 2024 - Août 2025</p>
                        <ul class="list-disc list-inside text-gray-600 mt-4 space-y-2">
                            <li>Caractérisation moléculaire et génétique de souches d'agents biologiques.</li>
                            <li>Séquençage et analyse de Mycobacterium tuberculosis.</li>
                            <li>Étude métagénomique du microbiote intestinal.</li>
                        </ul>
                    </div>
                </div>
                <!-- Laboratoire UCAD -->
                <div class="flex items-start">
                    <div class="w-16 h-16 bg-gray-200 rounded-full flex-shrink-0 mr-6"></div>
                    <div>
                        <h3 class="text-2xl font-semibold text-gray-800">Bioinformaticien - Laboratoire de Génétique Humaine - UCAD</h3>
                        <p class="text-gray-500 mt-1">Février 2024</p>
                        <ul class="list-disc list-inside text-gray-600 mt-4 space-y-2">
                            <li>Étude génétique de l'adermatoglyphie chez l'Homme.</li>
                            <li>Séquençage du génome humain.</li>
                        </ul>
                    </div>
                </div>
                <!-- Institut Pasteur de Dakar (IPD) -->
                <div class="flex items-start">
                    <div class="w-16 h-16 bg-gray-200 rounded-full flex-shrink-0 mr-6"></div>
                    <div>
                        <h3 class="text-2xl font-semibold text-gray-800">Bioinformaticien - Institut Pasteur de Dakar (IPD)</h3>
                        <p class="text-gray-500 mt-1">Août 2022 – Mai 2025</p>
                        <ul class="list-disc list-inside text-gray-600 mt-4 space-y-2">
                            <li>Surveillance de l'antibiorésistance en Afrique.</li>
                            <li>Développement de pipeline bioinformatique pour la résistance aux antimicrobiens.</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <!-- Skills Section -->
        <section id="competences" class="section">
            <h2 class="text-3xl font-bold text-blue-600 mb-8 text-center">Compétences Techniques</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6 text-center">
                <div class="bg-white p-6 rounded-xl shadow-md">
                    <h3 class="text-xl font-semibold text-blue-700">Systèmes et Outils</h3>
                    <p class="text-gray-600 mt-2">Linux, Bash, Git, Galaxy, Conda</p>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-md">
                    <h3 class="text-xl font-semibold text-blue-700">Langages</h3>
                    <p class="text-gray-600 mt-2">Python, R</p>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-md">
                    <h3 class="text-xl font-semibold text-blue-700">Omiques</h3>
                    <p class="text-gray-600 mt-2">NGS, Métagénomique, Transcriptomique</p>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-md">
                    <h3 class="text-xl font-semibold text-blue-700">Bioinformatique</h3>
                    <p class="text-gray-600 mt-2">Gènes, Annotation, Phylogénie</p>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-md">
                    <h3 class="text-xl font-semibold text-blue-700">Data Science</h3>
                    <p class="text-gray-600 mt-2">ML, Deep Learning, Traitement d'images</p>
                </div>
            </div>
        </section>

        <!-- Certifications Section -->
        <section id="certifications" class="section bg-white rounded-xl shadow-lg p-8">
            <h2 class="text-3xl font-bold text-blue-600 mb-8 text-center">Certifications</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div class="bg-gray-50 p-4 rounded-lg shadow-md">
                    <h3 class="font-semibold text-blue-700">Multi-Omique: Génomique, Transcriptomique et Métagénomique</h3>
                    <p class="text-sm text-gray-500 mt-1">OmicsLogic (2024)</p>
                </div>
                <div class="bg-gray-50 p-4 rounded-lg shadow-md">
                    <h3 class="font-semibold text-blue-700">Next Generation Sequencing Bioinformatics</h3>
                    <p class="text-sm text-gray-500 mt-1">H3ABioNet (2022)</p>
                </div>
                <div class="bg-gray-50 p-4 rounded-lg shadow-md">
                    <h3 class="font-semibold text-blue-700">Intelligence Artificielle avec Python, R et MATLAB</h3>
                    <p class="text-sm text-gray-500 mt-1">(2022)</p>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="text-center text-gray-600 py-8">
        <p>&copy; 2024 Mamadou Ndao. Tous droits réservés.</p>
    </footer>

    <script>
        document.getElementById('menu-button').addEventListener('click', function() {
            document.getElementById('mobile-menu').classList.toggle('hidden');
        });
    </script>

</body>
</html>
