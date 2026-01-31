# 🌙 Whats Your Dream Web: System Design

Project Goal: Create a high-aesthetic, voice-first platform where users can speak their dreams into existence. Integrated with NVIDIA PersonaPlex (Full Duplex) for real-time, soulful conversations.

## 🏗️ Architecture Overview

### 1. The Soul (Model & Backend)
- **Model:** NVIDIA PersonaPlex 7B (Full Duplex).
- **Hosting:** **Modal** (Serverless NVIDIA A100).
- **Optimization:** Memory Snapshots for <2 second "Cold Starts."
- **Scaling:** Scale-to-Zero (billed by the millisecond, $0 when idle).
- **Framework:** FastAPI (Python) + WebSockets for real-time duet streaming.

### 2. The Aesthetic (Frontend)
- **UI/UX:** Minimalist "Soft Life" aesthetic. The site should feel like a safe, ethereal space.
- **The Dream Core:** A central glowing orb or aurora that grows/shifts color as the user speaks their dream.
- **Audio:** Real-time 24kHz capture via Web Audio API.

## 🚀 Integration Strategy
1. **The "Manifestation" Prompt:** Pre-conditioned voice and text prompts specifically designed to help users articulate vague dreams into concrete goals.
2. **Ghost Architect:** Using the **Market Oracle** logic to help builders dream up businesses that actually fill gaps in the market.

## 💰 Resource Strategy
- **Credit Fuel:** Use the secured Google/Anthropic credits to host on Vertex AI / high-end GPUs.
- **Viral Launch:** SCALE mode for when you drop the reel to your 200k+ audience.

---
*Built for Mia's story - Jan 31, 2026* 🦾✨🌙
