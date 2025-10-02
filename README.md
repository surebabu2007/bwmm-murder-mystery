# Blackwood Manor Mystery (BWMM)

An interactive murder mystery visual novel built with Ren'Py and deployed on Vercel.

## 🎮 Game Description

Step into the shoes of Detective Sarah Chen as you investigate the mysterious death of Victoria Blackwood in her Gothic mansion. With immersive video backgrounds, voice acting, and multiple story paths, this murder mystery will test your detective skills.

## 🚀 Quick Start

### Local Development
```bash
# Install dependencies
npm install

# Start local development server
npm run dev
```

### Deploy to Vercel
```bash
# Install Vercel CLI
npm i -g vercel

# Deploy to Vercel
vercel

# Deploy to production
vercel --prod
```

## 🎯 Features

- **Immersive Storytelling**: Rich narrative with multiple character interactions
- **Video Backgrounds**: Cinematic video backgrounds for each location
- **Voice Acting**: Full voice acting for all characters
- **Interactive Investigation**: Make choices that affect the story outcome
- **Multiple Endings**: Different conclusions based on your investigation
- **AI Voice Assistant**: ElevenLabs integration for enhanced interaction
- **Responsive Design**: Works on desktop and mobile devices

## 🎭 Characters

- **Detective Sarah Chen**: The protagonist investigating the case
- **Victoria Blackwood**: The victim, a wealthy socialite
- **Marcus Reynolds**: Business partner with financial motives
- **Dr. Elena Rodriguez**: Family doctor with professional secrets
- **James Blackwood**: Victoria's brother with gambling debts
- **Lily Chen**: Victoria's niece with emotional conflicts

## 🕵️ Gameplay

1. **Investigate**: Examine the crime scene and gather evidence
2. **Interview**: Question suspects and witnesses
3. **Analyze**: Review evidence and testimonies
4. **Decide**: Make your final accusation

## 🛠️ Technical Details

- **Engine**: Ren'Py (compiled for web)
- **Deployment**: Vercel
- **Audio**: MP3/OGG format with voice acting
- **Video**: WebM format for backgrounds
- **AI Integration**: ElevenLabs ConvAI Widget

## 📁 Project Structure

```
├── index.html              # Main game file
├── manifest.json           # PWA manifest
├── vercel.json            # Vercel configuration
├── package.json           # Node.js dependencies
├── game/                  # Game assets
│   ├── audio/            # Voice acting files
│   ├── images/           # Character and UI images
│   └── videos/           # Background videos
├── icons/                 # PWA icons
└── service-worker.js     # PWA service worker
```

## 🌐 Deployment

This game is optimized for Vercel deployment with:
- Static file serving
- Proper CORS headers for Ren'Py
- Caching optimization for assets
- PWA support

## 🎵 Audio Credits

All voice acting and audio assets are included in the game package.

## 📱 Browser Support

- Chrome/Chromium (recommended)
- Firefox
- Safari
- Edge

## 🔧 Troubleshooting

If the game doesn't load:
1. Ensure you're using a modern browser
2. Check that all assets are loading properly
3. Verify CORS headers are set correctly
4. Try clearing browser cache

## 📄 License

MIT License - See LICENSE file for details.

## 🤝 Contributing

This is a hackathon project. Contributions and feedback are welcome!

---

**Enjoy solving the mystery of Blackwood Manor!** 🕵️‍♀️
