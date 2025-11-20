<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Cryptic Archive - Art Portfolio</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Custom font import for a slight gothic/classic touch */
        @import url('https://fonts.googleapis.com/css2?family=Cinzel:wght@400;700&family=Inter:wght@400;600&display=swap');
        
        /* Apply Cinzel for headings and Inter for body text */
        .font-gothic {
            font-family: 'Cinzel', serif;
        }
        .font-body {
            font-family: 'Inter', sans-serif;
        }

        /* Subtle text shadow for a worn, dramatic effect */
        .text-dramatic-shadow {
            text-shadow: 1px 1px 3px rgba(180, 0, 0, 0.4);
        }

        /* Custom scrollbar for aesthetic, if supported by the browser */
        body::-webkit-scrollbar {
            width: 8px;
        }
        body::-webkit-scrollbar-thumb {
            background-color: #4a0000;
            border-radius: 4px;
        }
        body::-webkit-scrollbar-track {
            background-color: #0d0d0d;
        }
    </style>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'gothic-black': '#0d0d0d',
                        'gothic-accent': '#780000', /* Deep, blood-red accent */
                        'gothic-gray': '#1c1c1c',
                        'gothic-light': '#c0c0c0',
                    },
                }
            }
        }
    </script>
</head>
<body class="bg-gothic-black text-gothic-light font-body transition-colors duration-500 min-h-screen">
    
    <!-- 
        *** NOTE FOR BLOGGER INTEGRATION ***
        This is where you would typically insert the Blogger `<b:skin>` and `<b:template-skin>` 
        tags, and use `<b:section>` tags to define editable areas for the user.
        e.g., <b:section id='main-body' class='main' showaddelement='yes'>
    -->

    <div class="max-w-7xl mx-auto p-4 sm:p-6 lg:p-8">
        
        <!-- HEADER AND BANNER SECTION -->
        <header class="mb-10 border-b-2 border-gothic-accent/50 pb-6">
            <h1 class="font-gothic text-4xl sm:text-6xl text-center mb-6 pt-4 text-gothic-light tracking-widest text-dramatic-shadow">
                The Obsidian Archive
            </h1>
            <p class="text-center text-sm uppercase tracking-wider mb-8 text-gothic-light/70">
                A Compendium of Shadow, Dream, and Form
            </p>

            <!-- IMAGE BANNER AREA -->
            <div id="image-banner" class="w-full aspect-[3/1] bg-gothic-gray border-2 border-gothic-accent/70 rounded-lg overflow-hidden shadow-2xl shadow-gothic-accent/20">
                <!-- 
                    This is where you would place your large, custom banner image.
                    For a Blogger theme, you'd use a dynamic image URL here. 
                -->
                <img src="https://placehold.co/1200x400/1c1c1c/780000?text=Custom+Surreal+Banner+Artwork" 
                     alt="Large featured artwork banner" 
                     class="w-full h-full object-cover transition duration-700 hover:scale-[1.03]"
                     onerror="this.src='https://placehold.co/1200x400/1c1c1c/780000?text=Custom+Surreal+Banner+Artwork'">
            </div>
        </header>

        <!-- CATEGORY NAVIGATION -->
        <nav class="mb-12">
            <ul class="flex justify-center space-x-2 sm:space-x-8 border-t border-b border-gothic-accent/30 py-3 bg-gothic-gray/20 rounded-lg shadow-inner shadow-gothic-black/50">
                <li>
                    <a href="#3d-art" class="block px-4 py-2 uppercase font-gothic text-lg tracking-wider text-gothic-light hover:text-gothic-accent transition duration-300 border-b-2 border-transparent hover:border-gothic-accent/80 hover:bg-gothic-gray/50 rounded-md">
                        3D Sculptures
                    </a>
                </li>
                <li>
                    <a href="#2d-art" class="block px-4 py-2 uppercase font-gothic text-lg tracking-wider text-gothic-light hover:text-gothic-accent transition duration-300 border-b-2 border-transparent hover:border-gothic-accent/80 hover:bg-gothic-gray/50 rounded-md">
                        2D Canvases
                    </a>
                </li>
                <li>
                    <a href="#media-art" class="block px-4 py-2 uppercase font-gothic text-lg tracking-wider text-gothic-light hover:text-gothic-accent transition duration-300 border-b-2 border-transparent hover:border-gothic-accent/80 hover:bg-gothic-gray/50 rounded-md">
                        Media & Digital
                    </a>
                </li>
            </ul>
        </nav>

        <!-- MAIN ARTWORK GRID -->
        <main class="space-y-16">
            
            <!-- 3D ART SECTION -->
            <section id="3d-art" class="border-2 border-gothic-gray p-6 rounded-xl shadow-lg shadow-gothic-black/50">
                <h2 class="font-gothic text-3xl mb-8 text-gothic-accent/90 border-b border-gothic-accent/30 pb-3 text-dramatic-shadow uppercase tracking-widest">
                    The Formless In Form (3D)
                </h2>
                
                <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
                    <!-- Artwork Placeholder Item 1 -->
                    <div class="group bg-gothic-gray p-2 border border-gothic-accent/20 rounded-lg overflow-hidden shadow-xl hover:shadow-gothic-accent/30 transition duration-300">
                        <img src="https://placehold.co/400x400/151515/c0c0c0?text=3D+Piece+I" 
                             alt="3D Artwork 1" 
                             class="w-full aspect-square object-cover rounded transition-transform duration-500 group-hover:scale-105">
                        <p class="mt-3 text-sm font-gothic uppercase tracking-wider text-center text-gothic-light/80 group-hover:text-gothic-accent">
                            The Architect's Folly
                        </p>
                    </div>
                     <!-- Artwork Placeholder Item 2 -->
                    <div class="group bg-gothic-gray p-2 border border-gothic-accent/20 rounded-lg overflow-hidden shadow-xl hover:shadow-gothic-accent/30 transition duration-300">
                        <img src="https://placehold.co/400x400/151515/c0c0c0?text=3D+Piece+II" 
                             alt="3D Artwork 2" 
                             class="w-full aspect-square object-cover rounded transition-transform duration-500 group-hover:scale-105">
                        <p class="mt-3 text-sm font-gothic uppercase tracking-wider text-center text-gothic-light/80 group-hover:text-gothic-accent">
                            Whispers of Clay
                        </p>
                    </div>
                     <!-- Artwork Placeholder Item 3 -->
                    <div class="group bg-gothic-gray p-2 border border-gothic-accent/20 rounded-lg overflow-hidden shadow-xl hover:shadow-gothic-accent/30 transition duration-300">
                        <img src="https://placehold.co/400x400/151515/c0c0c0?text=3D+Piece+III" 
                             alt="3D Artwork 3" 
                             class="w-full aspect-square object-cover rounded transition-transform duration-500 group-hover:scale-105">
                        <p class="mt-3 text-sm font-gothic uppercase tracking-wider text-center text-gothic-light/80 group-hover:text-gothic-accent">
                            The Shroud Weaver
                        </p>
                    </div>
                     <!-- Artwork Placeholder Item 4 -->
                    <div class="group bg-gothic-gray p-2 border border-gothic-accent/20 rounded-lg overflow-hidden shadow-xl hover:shadow-gothic-accent/30 transition duration-300">
                        <img src="https://placehold.co/400x400/151515/c0c0c0?text=3D+Piece+IV" 
                             alt="3D Artwork 4" 
                             class="w-full aspect-square object-cover rounded transition-transform duration-500 group-hover:scale-105">
                        <p class="mt-3 text-sm font-gothic uppercase tracking-wider text-center text-gothic-light/80 group-hover:text-gothic-accent">
                            Subterranean Bloom
                        </p>
                    </div>
                </div>
            </section>
            
            <!-- 2D ART SECTION -->
            <section id="2d-art" class="border-2 border-gothic-gray p-6 rounded-xl shadow-lg shadow-gothic-black/50">
                <h2 class="font-gothic text-3xl mb-8 text-gothic-accent/90 border-b border-gothic-accent/30 pb-3 text-dramatic-shadow uppercase tracking-widest">
                    Veiled Dimensions (2D)
                </h2>
                
                <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
                    <!-- Artwork Placeholder Item 1 -->
                    <div class="group bg-gothic-gray p-2 border border-gothic-accent/20 rounded-lg overflow-hidden shadow-xl hover:shadow-gothic-accent/30 transition duration-300">
                        <img src="https://placehold.co/400x400/151515/c0c0c0?text=2D+Piece+I" 
                             alt="2D Artwork 1" 
                             class="w-full aspect-square object-cover rounded transition-transform duration-500 group-hover:scale-105">
                        <p class="mt-3 text-sm font-gothic uppercase tracking-wider text-center text-gothic-light/80 group-hover:text-gothic-accent">
                            The Crimson Gaze
                        </p>
                    </div>
                     <!-- Artwork Placeholder Item 2 -->
                    <div class="group bg-gothic-gray p-2 border border-gothic-accent/20 rounded-lg overflow-hidden shadow-xl hover:shadow-gothic-accent/30 transition duration-300">
                        <img src="https://placehold.co/400x400/151515/c0c0c0?text=2D+Piece+II" 
                             alt="2D Artwork 2" 
                             class="w-full aspect-square object-cover rounded transition-transform duration-500 group-hover:scale-105">
                        <p class="mt-3 text-sm font-gothic uppercase tracking-wider text-center text-gothic-light/80 group-hover:text-gothic-accent">
                            Monochrome Lament
                        </p>
                    </div>
                     <!-- Artwork Placeholder Item 3 -->
                    <div class="group bg-gothic-gray p-2 border border-gothic-accent/20 rounded-lg overflow-hidden shadow-xl hover:shadow-gothic-accent/30 transition duration-300">
                        <img src="https://placehold.co/400x400/151515/c0c0c0?text=2D+Piece+III" 
                             alt="2D Artwork 3" 
                             class="w-full aspect-square object-cover rounded transition-transform duration-500 group-hover:scale-105">
                        <p class="mt-3 text-sm font-gothic uppercase tracking-wider text-center text-gothic-light/80 group-hover:text-gothic-accent">
                            The Empty Chapel
                        </p>
                    </div>
                </div>
            </section>

            <!-- MEDIA ART SECTION -->
            <section id="media-art" class="border-2 border-gothic-gray p-6 rounded-xl shadow-lg shadow-gothic-black/50">
                <h2 class="font-gothic text-3xl mb-8 text-gothic-accent/90 border-b border-gothic-accent/30 pb-3 text-dramatic-shadow uppercase tracking-widest">
                    Spectral Projections (Media)
                </h2>
                
                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <!-- Media Placeholder Item 1 -->
                    <div class="bg-gothic-gray p-4 border border-gothic-accent/20 rounded-lg shadow-xl">
                        <div class="aspect-video bg-black flex items-center justify-center border border-gothic-accent/40 rounded">
                            <span class="text-gothic-light/70 font-gothic">Video/Animation Placeholder</span>
                        </div>
                        <p class="mt-4 text-center font-gothic uppercase tracking-wider text-gothic-light/80">
                            Digital Haunting Loop
                        </p>
                    </div>
                     <!-- Media Placeholder Item 2 -->
                    <div class="bg-gothic-gray p-4 border border-gothic-accent/20 rounded-lg shadow-xl">
                        <div class="aspect-video bg-black flex items-center justify-center border border-gothic-accent/40 rounded">
                            <span class="text-gothic-light/70 font-gothic">Interactive Art Placeholder</span>
                        </div>
                        <p class="mt-4 text-center font-gothic uppercase tracking-wider text-gothic-light/80">
                            The Glitching Abyss
                        </p>
                    </div>
                </div>
            </section>

        </main>
    </div>

    <!-- FOOTER -->
    <footer class="mt-20 py-8 border-t-2 border-gothic-accent/50 bg-gothic-gray/20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center text-sm font-body">
            <p class="text-gothic-light/60">
                &copy; 2024 The Obsidian Archive. All Rights Reserved.
            </p>
            <p class="mt-2 text-gothic-accent/70">
                <a href="#" class="hover:text-gothic-accent transition duration-300">Contact the Curator</a>
            </p>
        </div>
    </footer>
</body>
</html>
