🎧 SarvBeats
SarvBeats is a high-precision, self-hostable web audio player built for synchronized, multi-device playback. Designed for developers, musicians, and audio engineers looking for seamless time alignment and cross-platform flexibility, SarvBeats delivers an exceptional web-native listening experience.

🚀 Features
⏱️ Millisecond-Accurate Sync
Leverages NTP-inspired time synchronization primitives to keep playback tightly aligned across devices.

🌐 Cross-Platform
Works on any device with a modern browser (Chrome recommended for best performance).

🎚️ Spatial Audio Control
Simulate spatial sound by adjusting device volumes relative to a virtual listener.

🧼 Polished UI
Built-in loading states, status indicators, and fully styled controls for a smooth UX.

🛠️ Self-Hostable
Deploy your own instance with just a few commands using Bun + Turborepo.

⚠️ Note
SarvBeats is in early development.
Mobile support is experimental. Please open an issue or contribute a PR if you encounter bugs or limitations.

⚡ Quickstart
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/Shiva-Bajpai/sarvbeats.git
cd sarvbeats
2. Configure Environment Variables
Create a .env file in apps/client/ and add the following:

env
Copy
Edit
NEXT_PUBLIC_API_URL=http://localhost:8080
NEXT_PUBLIC_WS_URL=ws://localhost:8080/ws
3. Install Dependencies
bash
Copy
Edit
bun install
Installs dependencies for all workspaces via Turborepo.

4. Run the Development Servers
bash
Copy
Edit
bun dev
Client: http://localhost:3000

Server: http://localhost:8080

📁 Project Structure
Directory	Purpose
apps/server	Bun HTTP + WebSocket server for time sync & audio
apps/client	Next.js frontend using Tailwind & Shadcn/ui
packages/shared	Shared types and functions between client/server

📣 Contributions Welcome
Found a bug? Got an idea?
Please open an issue or submit a pull request to help improve SarvBeats.

🛠️ Tech Stack
Bun — Fast all-in-one JavaScript runtime

Next.js — React framework for frontend

Tailwind CSS + shadcn/ui — Beautiful, utility-first UI

Turborepo — Monorepo tooling

WebSockets — Real-time synchronization



