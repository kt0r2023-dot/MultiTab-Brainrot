# MultiTab Script for Steal a Brainrot - v1
MultiTab is a Roblox cheat script designed specifically for the game "Steal a Brainrot." It provides a variety of features to enhance gameplay, including flight mechanics, gravity manipulation, player freezing, and immortality. This script is built to be user-friendly, with a customizable GUI and minimal detection risk. It's free to use—no keys or activations required—just inject and play.
Features
MultiTab offers a robust set of tools to give you an edge in "Steal a Brainrot." Here's a detailed breakdown:

Flight Mode (Fly): Enables smooth flying at 35 m/s using a custom block and rope constraint system. It's physics-based to avoid teleport detection, making it hard for anti-cheats to flag. Toggle with a key (default: F) or via the GUI.
Ascend Mode (Up): Creates an anchored platform under your character that lifts you upward continuously. The platform adjusts to your horizontal movement for seamless control. Speed is optimized for quick elevation without triggering exploits.
Descend Mode (Down): Rapidly drops you to the ground using a raycast to detect the surface below. Now ultra-fast (0.1 seconds tween duration) while remaining smooth to evade anti-cheat systems. Lands you precisely 3 units above the detected surface or defaults to -50 units if no ground is found.
Gravity Control: Adjust gravity from -599 to 599 via a GUI input field. Uses a client-side BodyForce for undetectable simulation—negative values let you float upward. Includes a "SET" button for instant application.
Freeze Players: When activated, flings nearby players (within 5 meters) downward aggressively. Additionally, enables no-clip through other players by disabling their collision locally, allowing you to pass through them like ghosts. Highly effective for crowd control in chaotic scenarios.
God Mode (Immortality): Permanent health regeneration—even at 0 HP, you continue moving without respawning. Features aggressive checks every heartbeat, a health change hook, and a death event override to force revival. You're essentially unkillable, surviving any damage spam.
Leave Button: A customizable red button (toggle visibility in settings) that instantly kicks you from the game and shuts down Roblox. Useful for quick exits without traces.
Customizable Hotkeys: Change keybinds for Fly (F), Up (R), Down (C), and Leave (P) through the settings tab. Saves to a JSON file for persistence across sessions.
Draggable GUI with Animations: Modern interface with tween animations on buttons, an intro splash screen, and drag-and-drop functionality. Tabs for "Main" (features) and "Settings" (customization).
Auto-Health Fix on Respawn: God Mode reactivates automatically after any character reload or death, ensuring continuous protection.

All features are client-side and leverage Roblox's physics engine to minimize detection risks. The script avoids direct teleports, using tweens and body movers for natural movement.
How Well Does It Work?
MultiTab is highly stable and effective in "Steal a Brainrot" as of September 2025. It's designed to be undetectable by most standard Roblox anti-cheats, relying on simulated physics rather than exploits. Testing shows:

Flight and movement features bypass basic speed/position checks.
Freeze and no-clip work reliably in multiplayer, disrupting others without self-flagging.
God Mode holds up against heavy damage, including environmental hazards.
Performance is smooth with no noticeable lag; GUI is responsive.

However, advanced anti-cheats or game updates could detect it—use at your own risk. No bans reported in testing, but always test in a safe environment. The script is optimized for efficiency, running lightweight loops only when needed.
Supported Platforms

Primary: PC/Windows - Works seamlessly with popular injectors like Synapse X, KRNL, Fluxus, or Electron. Recommended for full GUI functionality.
Secondary: Android/Mobile - Compatible with mobile executors (e.g., Delta, Arceus X). GUI may have minor scaling issues, but core features function well.
Roblox Version: Compatible with the latest Roblox client (as of v1 release). No macOS or iOS support due to injection limitations.

Installation

Download the script.lua file from this repository.
Launch Roblox and join "Steal a Brainrot."
Open your injector (e.g., Synapse X).
Paste and execute the script.
The GUI will appear with an intro animation—ready to use!

No additional dependencies or installations needed. The script auto-saves settings to MultiTab_Settings.json in your executor folder.
Usage

Open the menu by clicking the gear icon (⚙) in the top-left.
Toggle features in the "Main" tab.
Customize keys and save in the "Settings" tab.
Press assigned hotkeys for quick activation (e.g., F for Fly).
For Down: It auto-detects ground; no manual input required.
Close the menu with the ❌ button; features stay active.

Pro Tip: Combine Fly with Gravity for insane mobility. Freeze is great for PvP dominance.
Version Info

v1: Initial release. Focus on core cheats with a polished GUI. Future updates may add more game-specific features based on feedback.

If you encounter bugs or have suggestions, open an issue or submit a pull request. Fork and contribute—let's make this even better!
Thanks for using MultiTab
