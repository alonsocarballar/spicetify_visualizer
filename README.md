# Spicetify Visualizer
A high-performance, ultra-smooth physics-based audio visualizer for Spicetify. Featuring real-time physics customization, dynamic album-based coloring, and an optional Neon bloom effect.

Features
Spring Physics: Advanced inertia-based bar movement using Hooke's Law for organic, elastic animations.

Real-time Settings: Adjust sensitivity, friction, tension, and bars on the fly via a hidden UI panel.

Dual Color Engine: Switch between automatic album-art extraction or custom manual gradients.

Neon Mode: Toggleable bloom effect that reacts to audio intensity.

Frame-perfect Sync: Custom synchronization engine to eliminate stuttering between Spotify segments.

Installation
Open your Spicetify config directory by running spicetify config-dir in your terminal.

Navigate to the CustomApps folder.

Create a new folder named visualizador_pro.

Copy your index.js and manifest.json files into this new visualizador_pro folder.

Add the app to your Spicetify configuration:

Bash
spicetify config custom_apps visualizador_pro
Apply the changes:

Bash
spicetify apply
Configuration
To access the settings panel:

Open the Visualizador tab in Spotify.

Hover your mouse over the top-right corner of the screen.

A transparent panel will appear where you can tweak:

Friction & Tension: Controls how "bouncy" or "heavy" the bars feel.

Delay: Micro-adjust audio/visual sync in milliseconds.

Manual Color: Enable this to use the integrated Color Pickers for a custom look.

Neon Effect: Toggle the glow/bloom rendering.

Updating
Navigate to your Spicetify config directory: spicetify config-dir.

Go to CustomApps/visualizador_pro.

Replace the old index.js with the new version.

Run spicetify apply.

Uninstallation
Navigate to CustomApps and delete the visualizador_pro folder.

Remove the app from your Spicetify config:

Bash
spicetify config custom_apps visualizador_pro-
Run spicetify apply.

Troubleshooting
Bars not moving? Ensure you are playing a song. If it still doesn't work, try spicetify restore backup apply.

UI not showing? The settings panel is hidden by default. Remember to hover your mouse in the top-right area of the visualizer.

Color stuck? Toggle "Manual Color" on and off to refresh the album art extraction.
