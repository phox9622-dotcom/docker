# docker





👋 Welcome to Codespaces! You are on our default image. 
   - It includes runtimes and tools for Python, Node.js, Docker, and more. See the full list here: https://aka.ms/ghcs-default-image
   - Want to use a custom image instead? Learn more here: https://aka.ms/configure-codespace

🔍 To explore VS Code to its fullest, search using the Command Palette (Cmd/Ctrl + Shift + P or F1).

📝 Edit away, run your app as usual, and we'll automatically make it available for you to access.

@phox9622-dotcom ➜ /workspaces/docker (main) $ docker run -d -p 3000:8080 \
  -v open-webui:/app/backend/data \
  -e ENABLE_OLLAMA_API=false \
  --name open-webui \
  --restart always \
  ghcr.io/open-webui/open-webui:main
Unable to find image 'ghcr.io/open-webui/open-webui:main' locally
main: Pulling from open-webui/open-webui
4f4fb700ef54: Pull complete 
6aa2b8be1530: Pull complete 
40748add9f4f: Pull complete 
30cf67d7101c: Pull complete 
e3e428093f5e: Pull complete 
286d8c291daa: Pull complete 
43bf1bb9eea8: Pull complete 
eb5e92abd0d8: Pull complete 
8e089f64e126: Pull complete 
62c7f7862e57: Pull complete 
38de3bdf6bc5: Pull complete 
2d36af6b3870: Pull complete 
8ad25319df03: Pull complete 
319f63d20d54: Pull complete 
765e6175d15b: Pull complete 
44136fa355b3: Download complete 
bb0ac0e5ca3e: Download complete 
8d3a09722e57: Download complete 
Digest: sha256:ff7f7cbb4545aacec2c22d085b2bc406b299c119bd98747421124a1a6c03795f
Status: Downloaded newer image for ghcr.io/open-webui/open-webui:main
1f31b044f2a9d2337667940809cb667f12c6837931450d46a1d4272258db6c01
@phox9622-dotcom ➜ /workspaces/docker (main) $ 
