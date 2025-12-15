<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Odyssée Dentaire - L'Expertise au Service de Votre Sourire</title>
    <!-- Chargement de Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Configuration de la police Inter -->
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #F8FAFC; /* Fond très clair, presque blanc */
        }
    </style>
    <!-- Configuration des couleurs Tailwind pour une palette professionnelle et clinique -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'clinical-blue': '#004AAD', /* Bleu profond, synonyme d'autorité et confiance */
                        'mint-accent': '#00C4CC',  /* Teal/menthe, frais et moderne */
                        'text-slate': '#2D3748',   /* Gris ardoise, très lisible */
                        'bg-silver': '#E5E7EB',
                        'highlight-section': '#E0F3FF', /* Bleu très pâle */
                    }
                }
            }
        }
    </script>
</head>
<body class="antialiased text-text-slate">

    <!-- 1. Barre de Navigation (Header) -->
    <header class="sticky top-0 z-30 bg-white shadow-xl/50 backdrop-blur-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
            <!-- Logo/Nom du Blog -->
            <a href="#" class="text-3xl font-extrabold tracking-tighter text-clinical-blue hover:text-blue-700 transition duration-300">
                <span class="text-mint-accent mr-1">○</span> Odyssée Dentaire
            </a>
            <!-- Menu de Navigation (Desktop) -->
            <nav class="hidden md:flex space-x-8 text-gray-700 font-medium">
                <a href="#expertise" class="hover:text-clinical-blue transition duration-200 border-b-2 border-transparent hover:border-mint-accent py-1">Notre Expertise</a>
                <a href="#ressources" class="hover:text-clinical-blue transition duration-200 border-b-2 border-transparent hover:border-mint-accent py-1">Ressources Clés</a>
                <a href="#contact" class="hover:text-clinical-blue transition duration-200 border-b-2 border-transparent hover:border-mint-accent py-1">Consultation</a>
                <a href="#" class="px-5 py-2 bg-mint-accent text-text-slate rounded-lg shadow-lg hover:bg-teal-400 transition duration-300 font-semibold transform hover:translate-y-0.5">Inscription</a>
            </nav>
            <!-- Bouton de menu mobile -->
            <button class="md:hidden text-gray-700 hover:text-clinical-blue transition duration-300">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
            </button>
        </div>
    </header>

    <!-- 2. Section Héro (Introduction) -->
    <section class="bg-highlight-section py-20 sm:py-32 text-text-slate shadow-inner border-b-4 border-clinical-blue/20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <p class="text-lg uppercase tracking-widest text-mint-accent font-semibold mb-3">La science au service de l'esthétique</p>
            <h2 class="text-5xl sm:text-6xl lg:text-7xl font-extrabold mb-6 leading-tight text-clinical-blue">
                Maîtriser l'Art de la Santé Bucco-Dentaire
            </h2>
            <p class="text-xl sm:text-2xl font-light max-w-4xl mx-auto mb-10 text-gray-700">
                Naviguez à travers nos analyses pointues sur l'hygiène, les traitements avant-gardistes et les pratiques préventives qui définiront la longévité de votre sourire.
            </p>
            <a href="#expertise" class="inline-block px-10 py-4 bg-clinical-blue text-white text-xl font-bold rounded-xl shadow-2xl shadow-clinical-blue/40 hover:bg-blue-800 transition transform hover:scale-105 duration-300">
                Explorer l'Expertise &rarr;
            </a>
        </div>
    </section>

    <main class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16" id="expertise">

        <!-- 3. Article Phare (Feature - Design Asymétrique Équilibré) -->
        <h3 class="text-4xl font-extrabold text-text-slate mb-12 border-b border-mint-accent pb-3">Dossier Spécial du Mois</h3>
        <article class="bg-white rounded-3xl shadow-2xl shadow-gray-200 overflow-hidden mb-16 border border-bg-silver">
            <div class="lg:grid lg:grid-cols-12">
                
                <!-- Bloc Image (3/5) -->
                <div class="lg:col-span-7 p-6 sm:p-10 lg:p-12 order-2 lg:order-1">
                    <span class="text-base font-semibold text-mint-accent uppercase tracking-wider mb-3 block">Régénération et Longévité</span>
                    <h4 class="text-4xl lg:text-5xl font-black text-text-slate mb-6 leading-snug">
                        Le Microbiome Buccal : Notre Défense Immunitaire Secrète
                    </h4>
                    <p class="text-gray-600 mb-8 text-xl leading-relaxed">
                        Loin d'être un simple espace de nettoyage, la bouche est un écosystème complexe. Cet article de fond explore comment l'équilibre du microbiome influence tout, de la prévention de la carie à la santé systémique. Nous détaillons les stratégies de modulation et les nutriments essentiels.
                    </p>
                    <div class="flex items-center text-sm text-gray-500 mb-8 border-t border-b py-4">
                        <img class="w-12 h-12 rounded-full mr-4 object-cover ring-2 ring-clinical-blue" src="https://placehold.co/48x48/004AAD/ffffff?text=PhD" alt="Portrait du Docteur Éloïse Vasseur, chercheuse">
                        <div>
                            <p class="font-bold text-text-slate text-lg">Dr. Éloïse Vasseur, PhD</p>
                            <p class="text-sm">Recherche Biomédicale | 15 min d'analyse</p>
                        </div>
                    </div>
                    <a href="#" class="inline-block px-8 py-3 bg-mint-accent text-text-slate text-lg font-bold rounded-lg shadow-md hover:bg-teal-400 transition duration-300">
                        Lire l'étude approfondie &rarr;
                    </a>
                </div>

                <!-- Bloc Texte (2/5) -->
                <div class="lg:col-span-5 order-1 lg:order-2">
                    <img src="https://placehold.co/800x600/004AAD/ffffff?text=Microbiome+Buccal" alt="Illustration scientifique d'un microbiome en équilibre." class="h-80 lg:h-full w-full object-cover">
                </div>
            </div>
        </article>

        <!-- 4. Grille des Publications Récentes -->
        <h3 class="text-4xl font-extrabold text-text-slate mb-12" id="ressources">Publications Récentes</h3>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10">

            <!-- Article 1: Pression et Brossage -->
            <article class="bg-white rounded-xl shadow-lg hover:shadow-2xl transition duration-500 overflow-hidden border border-bg-silver/80">
                <img src="https://placehold.co/500x300/F0F7F9/004AAD?text=Pression+de+Brossage" alt="Schéma d'une brosse à dents appliquant la pression optimale." class="w-full h-52 object-cover">
                <div class="p-6">
                    <span class="text-xs font-semibold text-clinical-blue uppercase tracking-widest mb-2 block">Technique</span>
                    <h5 class="text-2xl font-bold text-text-slate mb-3 leading-snug">
                        L'Impact de la Force de Brossage sur l'Usure de l'Émail
                    </h5>
                    <p class="text-gray-600 text-sm mb-4">
                        Une analyse biomécanique démontrant pourquoi "fort" ne signifie pas "efficace" et comment la pression excessive érode la protection naturelle de la dent.
                    </p>
                    <a href="#" class="text-base font-semibold text-mint-accent hover:text-teal-400 transition">
                        Comprendre la biomécanique &rarr;
                    </a>
                </div>
            </article>

            <!-- Article 2: Rôle des Minéraux -->
            <article class="bg-white rounded-xl shadow-lg hover:shadow-2xl transition duration-500 overflow-hidden border border-bg-silver/80">
                <img src="https://placehold.co/500x300/00C4CC/ffffff?text=Calcium+Fluorure" alt="Molécules de calcium et de fluorure pour l'illustration." class="w-full h-52 object-cover">
                <div class="p-6">
                    <span class="text-xs font-semibold text-clinical-blue uppercase tracking-widest mb-2 block">Nutrition</span>
                    <h5 class="text-2xl font-bold text-text-slate mb-3 leading-snug">
                        Reminéralisation : Les Minéraux Qui Protègent Au Niveau Cellulaire
                    </h5>
                    <p class="text-gray-600 text-sm mb-4">
                        Au-delà du fluorure : exploration du rôle du calcium, du phosphate et de la Vitamine D dans le processus de fortification dentaire.
                    </p>
                    <a href="#" class="text-base font-semibold text-mint-accent hover:text-teal-400 transition">
                        Étudier les nutriments &rarr;
                    </a>
                </div>
            </article>

            <!-- Article 3: Orthodontie Invisible -->
            <article class="bg-white rounded-xl shadow-lg hover:shadow-2xl transition duration-500 overflow-hidden border border-bg-silver/80">
                <img src="https://placehold.co/500x300/B5F5D4/004AAD?text=Aligners+Invisibles" alt="Aligneurs orthodontiques transparents sur un modèle de dents." class="w-full h-52 object-cover">
                <div class="p-6">
                    <span class="text-xs font-semibold text-clinical-blue uppercase tracking-widest mb-2 block">Esthétique Avancée</span>
                    <h5 class="text-2xl font-bold text-text-slate mb-3 leading-snug">
                        L'Orthodontie Transparente : Innovation ou Compromis ?
                    </h5>
                    <p class="text-gray-600 text-sm mb-4">
                        Évaluation objective des aligneurs invisibles par rapport aux méthodes traditionnelles : efficacité, confort et coût à long terme.
                    </p>
                    <a href="#" class="text-base font-semibold text-mint-accent hover:text-teal-400 transition">
                        Évaluer les traitements &rarr;
                    </a>
                </div>
            </article>

        </div>

        <!-- 5. Appel à l'Action (Newsletter - Plus de crédibilité) -->
        <section class="mt-20 py-16 bg-clinical-blue/95 rounded-3xl shadow-2xl text-white border-t-8 border-mint-accent/70">
            <div class="text-center max-w-3xl mx-auto px-4" id="contact">
                <h3 class="text-4xl font-extrabold mb-4">Rejoignez Notre Cercle d'Experts</h3>
                <p class="text-xl font-light opacity-90 mb-8">
                    Abonnez-vous à notre synthèse hebdomadaire pour recevoir des analyses exclusives et des alertes sur les percées en dentisterie.
                </p>
                <form class="flex flex-col sm:flex-row gap-4 justify-center">
                    <input type="email" placeholder="Saisissez votre email professionnel ici" required class="flex-grow px-6 py-4 rounded-xl border-2 border-white/30 bg-white/10 text-white placeholder-gray-300 focus:ring-mint-accent focus:border-mint-accent shadow-lg text-lg">
                    <button type="submit" class="px-8 py-4 bg-mint-accent text-text-slate font-extrabold rounded-xl shadow-xl hover:bg-teal-400 transition duration-300 transform hover:-translate-y-1 text-lg">
                        M'abonner à l'Expertise
                    </button>
                </form>
            </div>
        </section>

    </main>

    <!-- 6. Pied de Page (Footer - Thème sombre et professionnel) -->
    <footer class="bg-text-slate mt-20 py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-gray-300">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-10 mb-10 border-b border-gray-700 pb-8">
                <!-- Colonne 1: Mission -->
                <div>
                    <h6 class="text-2xl font-bold mb-4 text-mint-accent">Odyssée Dentaire</h6>
                    <p class="text-sm text-gray-400 leading-relaxed">
                        Plateforme dédiée à l'information scientifique rigoureuse pour les professionnels et les patients exigeants en matière de santé bucco-dentaire.
                    </p>
                </div>
                <!-- Colonne 2: Thématiques -->
                <div>
                    <h6 class="font-semibold mb-4 text-white uppercase tracking-wider">Thématiques</h6>
                    <ul class="space-y-3 text-sm">
                        <li><a href="#" class="hover:text-mint-accent transition">Prévention</a></li>
                        <li><a href="#" class="hover:text-mint-accent transition">Chirurgie & Implants</a></li>
                        <li><a href="#" class="hover:text-mint-accent transition">Esthétique & Alignement</a></li>
                    </ul>
                </div>
                <!-- Colonne 3: Institutionnel -->
                <div>
                    <h6 class="font-semibold mb-4 text-white uppercase tracking-wider">Institutionnel</h6>
                    <ul class="space-y-3 text-sm">
                        <li><a href="#" class="hover:text-mint-accent transition">Qui Sommes-Nous ?</a></li>
                        <li><a href="#" class="hover:text-mint-accent transition">Éthique et Source</a></li>
                        <li><a href="#" class="hover:text-mint-accent transition">Carrières</a></li>
                    </ul>
                </div>
                <!-- Colonne 4: Support -->
                <div>
                    <h6 class="font-semibold mb-4 text-white uppercase tracking-wider">Support</h6>
                    <p class="text-sm">contact@odysseedentaire.com</p>
                    <div class="flex space-x-4 mt-4">
                        <a href="#" class="text-gray-400 hover:text-clinical-blue transition transform hover:scale-110">
                            <!-- Linkedin Icon -->
                            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.575-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/></svg>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-clinical-blue transition transform hover:scale-110">
                            <!-- Twitter/X Icon -->
                            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"><path d="M22.46 6c-.77.34-1.59.57-2.45.69.88-.53 1.56-1.37 1.88-2.37-.83.49-1.75.85-2.72 1.05-.78-.83-1.89-1.35-3.13-1.35-2.37 0-4.3 1.93-4.3 4.3 0 .34.04.68.12 1-.36-.02-.72-.03-1.08-.03-3.16 0-5.96-1.68-7.86-4-.33.58-.52 1.25-.52 1.98 0 1.49.76 2.8 1.92 3.56-.71-.02-1.38-.22-1.97-.54v.05c0 2.08 1.48 3.82 3.44 4.2-.36.1-.73.15-1.12.15-.28 0-.55-.03-.81-.07.54 1.71 2.11 2.95 3.97 2.99-1.48 1.16-3.34 1.85-5.37 1.85-.35 0-.7-.02-1.04-.06 1.91 1.22 4.17 1.94 6.6 1.94 7.92 0 12.27-6.55 12.27-12.28 0-.19-.01-.39-.01-.58.84-.6 1.57-1.34 2.15-2.22z"/></svg>
                        </a>
                    </div>
                </div>
            </div>
            <div class="text-center pt-8">
                <p class="text-sm text-gray-500">Odyssée Dentaire | Publication Médicale Indépendante &copy; 2025</p>
            </div>
        </div>
    </footer>

</body>
</html>

