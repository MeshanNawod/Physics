Quantum Lab (quantum_lab.html)
An interactive, single-file web application built with Three.js and vanilla JavaScript that visualizes fundamental concepts in quantum mechanics.
Overview & Features
The application features a responsive tabbed interface allowing users to explore different quantum physics simulations:
 * Hydrogen Atom (3D Visualization):
   * Interactive electron clouds, angular momentum (L) vector orientations, radial probability densities, and spin (S) states.
   * Customization options for quantum numbers (n, l, m_l), color maps (plasma, fire, cool, viridis), and point densities (4k to 15k points).
   * 3D orbit controls (rotate via mouse/touch, zoom via scroll).
 * Quantum Tunneling:
   * Time-dependent Schrödinger equation (TDSE) simulation using a staggered leapfrog (Visscher) algorithm.
   * Visualizes wave packet propagation through a rectangular potential barrier, showing transmission and reflection over time.
 * Particle in a Box:
   * Explores energy eigenstates and superpositions (sloshing effect between n=1 and n=2) within an infinite square well.
 * Quantum Harmonic Oscillator:
   * Visualizes wave functions (\psi), probability densities (\vert{}\psi\vert{}^2), and classically forbidden regions where quantum tunneling/leaking occurs.
 * Heisenberg Uncertainty Principle:
   * Demonstrates the relationship between position spread (\Delta x) and momentum spread (\Delta p) using a Gaussian wave packet.
Technology Stack
 * Rendering Engine: Three.js (r128) for 3D WebGL graphics.
 * Styling & UI: Pure CSS with support for dark/light system color schemes via native CSS variables (@media (prefers-color-scheme: dark)).
 * Architecture: Zero-dependency build setup—contained entirely within a single HTML file combining numerical physics computations and UI rendering logic.
Getting Started
 * Save the source code locally as quantum_lab.html.
 * Open the file in any modern web browser that supports WebGL (Chrome, Firefox, Safari, Edge). An active internet connection is required on first load to fetch the Three.js library from Cloudflare CDN.
