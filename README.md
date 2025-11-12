# Entangle Chat

Quantum-inspired secure PWA for private text & voice chat. Two "twin AIs" simulate entanglement to generate shared OTP pads via QR pairing. No phone number, no server logs, no metadata.

## Features
- QR seed pairing (offline)
- E2EE text encrypt/decrypt
- P2P voice calls (WebRTC + OTP)
- Offline-first (SW cache)
- Firebase signaling (free)

## Deploy
- Vercel: https://entangle-chat.vercel.app/
- GitHub Pages: Fork & enable Pages

## Tech
- TensorFlow.js (twin net)
- QRCode.js / jsQR
- WebRTC (P2P)
- Firebase RTDB (signaling)
- Service Worker (offline)

MIT License. Privacy first.
