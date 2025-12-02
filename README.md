# ECHO - Emergent Communication with Hand Organisms

An interactive 3D particle entity that learns your gestures, recognizes your face, and communicates through visuals and spatial sound.

## [Try it Live](https://benpomme.github.io/ECHOENTITY/)

## Features

### Hand Gesture Recognition
- **10+ static gestures**: Open palm, fist, peace sign, pointing, pinch, thumbs up, rock, and more
- **Motion detection**: Wave, circular movements
- **Real-time tracking**: Uses MediaPipe for precise hand landmark detection

### Face Recognition & Memory
- **Recognizes returning visitors** by their facial features
- **Remembers your name** and interaction history
- **Personalized greetings** based on how long you've been away
- **Tracks favorite gestures** and adapts responses

### Visual Communication
The entity responds to your gestures with different particle formations:
- 🖐 **Open Palm** → Explosion/Sphere
- ✊ **Fist** → Pulsing Sphere
- ☝️ **Pointing** → Laser Beam
- ✌️ **Peace Sign** → Heart Shape
- 🌀 **Circle Motion** → Spiral/Ring
- 👌 **Pinch** → Converging Particles
- 👋 **Wave** → Wave Pattern

### Spatial Audio
- **8-voice synthesizer** controlled by your fingers
- **Hand height** controls pitch
- **Horizontal position** controls stereo panning
- **Movement speed** controls filter brightness
- **Different moods** trigger harmonic, dissonant, rhythmic, or melodic modes

### Emotional AI
The entity has emotional states that evolve based on interaction:
- **Curious** - When seeing new patterns
- **Learning** - When starting to understand
- **Excited** - When recognizing familiar gestures
- **Playful** - During active interaction
- **Calm** - During peaceful moments

## How to Use

1. **Allow camera access** when prompted
2. **Click "Enter ECHO's World"** to start audio
3. **Enter your name** (ECHO will remember you!)
4. **Move your hands** in front of the camera
5. **Try different gestures** and watch ECHO respond

## Technology Stack

- **Three.js** - 3D particle rendering with custom shaders
- **MediaPipe** - Hand and face landmark detection
- **Web Audio API** - Spatial sound synthesis
- **localStorage** - User memory persistence

## Local Development

```bash
# Clone the repository
git clone https://github.com/BenPomme/ECHOENTITY.git
cd ECHOENTITY

# Serve locally (any static server works)
npx serve .
# or
python -m http.server 8000

# Open http://localhost:8000
```

## Browser Support

Best experienced in:
- Chrome (recommended)
- Edge
- Firefox (with WebGL enabled)

Requires:
- Camera access
- WebGL support
- Modern JavaScript (ES modules)

## Privacy

- All face and gesture data is processed **locally in your browser**
- User data is stored in **localStorage only** (never sent to servers)
- No external tracking or analytics

## License

MIT License - Feel free to fork, modify, and create your own ECHO experiences!

## Credits

Created with love using Claude Code.
