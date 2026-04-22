# 🚀 AI Vertical Streamer: Realtime Horizontal Webcam to TikTok/Instagram/YT Shorts Vertical

**AI Magic for Live Streams – CPU Only, No GPU Needed!**

Your regular webcam works great... but TikTok, Instagram Reels, and YouTube Shorts all want vertical video. Manual cropping? Annoying. Basic center crop? Misses the action.

**Enter AI Vertical Streamer** – the smart AI tool that **automatically turns your regular horizontal webcam into perfect vertical video for TikTok, Instagram Reels, and YouTube Shorts**. It tracks you, follows your gestures, and focuses on what you're showing. No extra hardware, no hassle – works perfectly on any laptop **with CPU only (no GPU required!)**.

## 🎬 What Makes This Special? The Magic Under the Hood (No Tech Jargon Overload)

Picture yourself presenting: 

1. **Solo Mode**: Locks onto your face with buttery-smooth tracking. You pace left? Crop follows. Turn your head? It stays centered.

2. **Gesture Awareness**: Point to the side? Crop intelligently extends to follow your gesture. Hold up a laptop, phone, or book? It zooms to include what you're showing.

3. **Group Conversations**: Multiple people? Smart group framing – tight for 2-3, wide when needed, weighted by who's most prominent (closest to camera).

4. **Show Mode**: Automatically kicks in when you present slides, demos, or props. Detects pointing arms, held objects (bottles, books, laptops), and expands the frame accordingly.

5. **Hollywood Transitions**: No jarring jumps. Silky smooth blends between solo, group, wide, and show modes.

Powered by super-lightweight AI (smart detection + pose tracking), **optimized to run lightning-fast on CPU only – no GPU needed!** Smooth 30fps realtime on regular laptops, using under 20% CPU.

## 🎥 Live Demo in Seconds

```
# 🚀 Super Easy Install (Windows – 30 Seconds!)
git clone <repo> && cd ai-vertical-streamer
uv sync   # One command installs everything
uv run python main.py
```

**Instant start!** Browser opens `http://localhost:8000`:

- **Start Camera** → Live side-by-side (original vs vertical)
- Share `/view` link to any phone (**auto vertical on mobile**)
- Live stats: CPU/RAM usage, inference device

Models auto-download (~10MB). First run exports OpenVINO (~30s). Next starts are instant.

## 🌐 Perfect for Streamers & Creators

- **TikTok/Instagram Reels/YT Shorts**: Perfect vertical, ready to upload
- **Live Presentations/Zoom**: Smart tracking for you + screen shares
- **Twitch/Streaming**: Vertical feed for phone viewers
- **Content Creation**: Record vertical masters directly

## 🛠 Basic Tech Stack (For the Curious)

- **Backend**: FastAPI + MJPEG streaming
- **AI**: YOLOv8n detect + pose (OpenVINO optimized)
- **Video**: OpenCV (Haar faces + YOLO)
- **Frontend**: Simple HTML/JS viewer
- **Python 3.11+**, `uv` for deps (single `uv sync`)

Polished for Windows laptops – lightning fast CPU performance anywhere!

## 🚀 Get Started Now

1. Grab the code
2. `uv sync && uv run main.py`
3. Hit **Start Camera**
4. Go viral with perfect vertical framing!


