AYO Chat Agent v1 - Windows Demo Package

Purpose
This package lets a reviewer test the working AYO Chat Agent v1 desktop app without downloading the private source code.

Contents
- ayo.exe
- sample_doc.txt
- AYO_DEMO_README.txt

Requirements
- Windows
- Ollama installed and running
- Phi-3 model available locally

Setup
1. Install Ollama from https://ollama.com/download
2. Open PowerShell or Terminal.
3. Pull the model:

   ollama pull phi3

4. Confirm the model is available:

   ollama list

Run the Demo
1. Unzip the demo package.
2. Double-click ayo.exe.
3. If the sample does not load automatically, click Load Sample.
4. Click Generate Map.
5. If this is the first run, give Ollama a little time to wake up and load the local model.

Optional: click Save Output to export the result as production_map.md.

Troubleshooting
If the demo says it cannot connect to Ollama, open Ollama first, wait a few seconds, then click Generate Map again.

Expected Result
The app generates a Markdown production map with sections for Characters, World and Lore, Abilities, Story, and Uncategorized Review.

Source Review
The full source code is private by design. Technical reviewers can request source access from Matthew Mitchell at memitchell@mmkpcstudios.com.

Security Note
This Windows executable is unsigned, so Windows may show a security confirmation. Only run the file if it was downloaded from the official AYO Chat Agent v1 portfolio page.
