# CosmoPhase
Cosmo Phase: A Retro Solar System Simulator

This project is a web-based, interactive 2D model of our solar system, created as a tribute to the iconic Casio Cosmo Phase watch. It combines a nostalgic, retro-futuristic aesthetic with accurate orbital mechanics to provide a beautiful and educational view of our celestial neighborhood.

The entire interface is designed to evoke the feeling of a classic 80s digital watch, featuring a monochrome green-on-black color scheme, blocky UI elements, and pixelated sprites for the sun and planets.
Key Features:

    Accurate Orbital Simulation: Planet positions are not just for show. They are calculated using true Keplerian orbital elements, including semi-major axis, eccentricity, and longitude of perihelion. This means planets follow their correct elliptical paths and vary their speed—moving faster at perihelion (closest to the sun) and slower at aphelion (farthest away).

    Dynamic Time Controls:

        Date Selection: View the precise alignment of the solar system on any given day from the years 1800 to 2100.

        Real-time Mode: See the current positions of the planets, updated live.

        Variable-Speed Timelapse: Watch the planets orbit the sun with an adjustable timelapse feature. The exponential speed slider provides fine control for slower, more detailed animations or incredibly fast forward-time simulations.

    Perfectly Smooth Moon Phase: The moon phase indicator in the top-right corner is rendered dynamically on every frame. By calculating the exact position of the terminator (the line between light and shadow) in real-time, the animation is perfectly fluid and avoids the choppiness of pre-rendered phase images.

    Logarithmic Distance Scaling: To solve the classic problem of visualizing a solar system where outer planets are thousands of times farther away than inner ones, the simulation uses a logarithmic scale for orbital distances. This brings the orbits of all planets, from Mercury to Pluto, into a single, comprehensible view.

    Interactive Viewing: Use the mouse wheel or trackpad to zoom in and out, and hover over any celestial body to identify it.

Technology Stack:

    Frontend: Plain HTML

    Styling: Tailwind CSS

    Rendering & Animation: Three.js for WebGL rendering

This project was built to be a beautiful, interactive piece of digital art that doubles as a fun educational tool.

License:

    MIT License. Check the LICENSE file for details.
