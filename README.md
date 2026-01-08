# 🎧 LyricLens

**LyricLens** is a music-tech prototype that explores how song meaning can be surfaced directly within a streaming experience — without redistributing copyrighted lyrics.

Inspired by Spotify’s AI-driven discovery features, LyricLens generates human-readable interpretations of songs using **audio features and metadata**, with optional user-provided lyric line explanations.

---

## 🚀 What It Does
- Accepts a Spotify track URL or ID
- Uses track metadata + audio features (valence, energy, tempo, etc.)
- Generates:
  - A plain-English song meaning
  - Themes and emotional tone
  - Listening cues based on audio features
- Optionally explains **user-pasted lyric lines** (processed in-session only)

---

## 🧠 Why This Matters
Music discovery often focuses on *what* to listen to, not *why a song feels meaningful*.
LyricLens explores a product direction where interpretation and context are built directly into the listening experience.

---

## ⚙️ Technical Details
- Python (Jupyter Notebook)
- Local Spotify-style dataset (JSON)
- Audio-feature-driven interpretation logic
- Designed to integrate with the Spotify Web API (currently using a local dataset due to temporary API restrictions)

---

## 🔮 Future Improvements
- Live Spotify API integration
- Playlist-level meaning & narrative
- AI DJ-style narration
- Evaluation framework for interpretation quality

---

## 📝 Notes
This project intentionally avoids storing or redistributing full song lyrics and focuses on explainable, metadata-driven interpretation.
