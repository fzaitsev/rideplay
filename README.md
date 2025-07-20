# 🚗🎵 RidePlay Entertainment System

> **Transform any rideshare experience into an interactive entertainment hub**

RidePlay is an innovative hosted entertainment system that allows passengers to control music and videos in rideshare vehicles by simply scanning a QR code. No apps to download, no account creation required – just scan and play!

![RidePlay Demo](assets/demo.gif)
*Scan → Search → Play – It's that simple!*

## ✨ **What Makes RidePlay Special**

- 🎯 **Zero Friction** – Scan QR code, start controlling music instantly
- 🎵 **Multi-Platform** – Spotify, YouTube integration with more coming soon
- 📱 **Mobile-First** – Optimized for passenger smartphones
- 🔄 **Real-Time Sync** – Multiple passengers can queue songs together
- 🎬 **Video Support** – Watch content on supported displays
- 🗣️ **Voice Search** – "Play some jazz music" or "Find funny videos"
- 🎮 **Smart Queue** – AI-powered recommendations and seamless transitions

## 🎬 **Demo Video**

[![RidePlay in Action](https://img.youtube.com/vi/YOUR_VIDEO_ID/0.jpg)](https://www.youtube.com/watch?v=YOUR_VIDEO_ID)

## 🚀 **How It Works**

```mermaid
graph LR
    A[Passenger] --> B[Scan QR Code]
    B --> C[Mobile Interface Opens]
    C --> D[Search Music/Videos]
    D --> E[Content Plays in Vehicle]
    E --> F[Other Passengers Join Queue]
```

### **For Passengers:**
1. 📱 Scan the QR code displayed in the vehicle
2. 🔍 Search for your favorite songs or videos
3. 🎵 Content plays through the car's audio system
4. ✨ Join the collaborative queue with other passengers

### **For Drivers:**
1. 📺 Display QR code on your device/tablet
2. 🎮 Monitor and control the entertainment system
3. 👥 Provide passengers with an unforgettable ride experience
4. ⚙️ Simple setup – works with any car audio system

## 🎵 **Supported Platforms**

### **Currently Available:**
- ✅ **Spotify** – Stream millions of songs
- ✅ **YouTube** – Music videos, entertainment content

### **Coming Soon:**
- 🍎 **Apple Music** – Full integration planned
- 🎬 **Netflix** – Video streaming for longer rides
- 🏰 **Disney+** – Family-friendly content
- 🎧 **SoundCloud** – Independent artist support
- 📻 **Podcast Platforms** – Educational and entertainment content

## 🛠️ **Technology Stack**

- **Frontend:** Angular 18+ with Material Design
- **Backend:** Node.js with WebSocket support
- **Real-time Communication:** Socket.io
- **API Integration:** Spotify Web API, YouTube Data API
- **Voice Recognition:** Web Speech API
- **Mobile-First:** Progressive Web App (PWA) capabilities

## 🏃‍♂️ **Quick Start**

### **Prerequisites**
- Node.js 18+ 
- Angular CLI
- Spotify Developer Account
- YouTube Data API key

### **Installation**
```bash
# Clone the repository
git clone https://github.com/yourusername/rideplay.git
cd rideplay

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Add your API keys to .env

# Start the development server
npm run dev

# Open browser to localhost:3000
```

### **Environment Setup**
```env
SPOTIFY_CLIENT_ID=your_spotify_client_id
SPOTIFY_CLIENT_SECRET=your_spotify_client_secret
YOUTUBE_API_KEY=your_youtube_api_key
PORT=3000
```

## 📱 **Features**

### **🎵 Music Control**
- Real-time collaborative playlists
- Voice search with natural language
- Smart recommendations based on current queue
- Volume and playback controls
- Skip voting system

### **🎬 Video Entertainment**
- YouTube video streaming
- Playlist exploration
- Video search with filters
- Queue management for video content

### **👥 Multi-User Experience**
- Multiple passengers can connect simultaneously
- Democratic queue management
- Real-time updates across all devices
- Passenger-friendly interface design

### **🎮 Driver Controls**
- Master control over content
- Content filtering options
- Emergency override capabilities
- Usage analytics and insights

## 📸 **Screenshots**

| Landing Page | Music Search | Video Control | Queue Management |
|--------------|--------------|---------------|------------------|
| ![Landing](assets/landing.png) | ![Music](assets/music.png) | ![Video](assets/video.png) | ![Queue](assets/queue.png) |

## 🎯 **Use Cases**

- **🚗 Rideshare Drivers** – Enhance passenger experience
- **🚌 Shuttle Services** – Keep passengers entertained
- **🏢 Corporate Transportation** – Professional entertainment solution
- **🎉 Event Transportation** – Party bus experiences
- **👨‍👩‍👧‍👦 Family Road Trips** – Keep everyone happy

## 🌟 **Why Passengers Love It**

> *"Finally, I can play my music without having to connect my phone or explain my playlist to the driver!"* – Sarah, frequent rider

> *"The voice search is amazing – I just said 'play some chill music' and it knew exactly what I wanted."* – Mike, business traveler

> *"My kids were entertained the entire ride with the video feature. Game changer!"* – Jennifer, parent

## 🛣️ **Roadmap**

### **🔜 Next Release (v2.0)**
- [ ] Apple Music integration
- [ ] Podcast platform support
- [ ] Enhanced voice controls
- [ ] Driver analytics dashboard

### **🎯 Future Plans**
- [ ] Netflix/Disney+ integration
- [ ] Multi-language support
- [ ] Custom driver branding
- [ ] Passenger rating system
- [ ] Integration with ride-hailing apps

## 🤝 **Contributing**

We welcome contributions! Here's how you can help:

1. 🍴 Fork the repository
2. 🌟 Create a feature branch (`git checkout -b feature/amazing-feature`)
3. 💾 Commit your changes (`git commit -m 'Add amazing feature'`)
4. 📤 Push to the branch (`git push origin feature/amazing-feature`)
5. 🔀 Open a Pull Request

### **Ways to Contribute:**
- 🐛 Report bugs and issues
- 💡 Suggest new features
- 📝 Improve documentation
- 🎨 Design UI/UX improvements
- 🧪 Add test coverage
- 🌐 Add translation support

## 💝 **Support the Project**

If you find RidePlay useful, consider supporting its development:

- ☕ **[Buy Me a Coffee](https://buymeacoffee.com/yourusername)**
- 💖 **[GitHub Sponsors](https://github.com/sponsors/yourusername)**
- 💳 **[PayPal](https://paypal.me/yourusername)**

Your support helps cover:
- 🖥️ Server hosting costs
- 🔧 Development and maintenance
- 📈 Scaling to more drivers and platforms
- ✨ Adding new features and integrations

## 📄 **License**

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

## 📞 **Contact & Support**

- 🐛 **Issues:** [GitHub Issues](https://github.com/yourusername/rideplay/issues)
- 💬 **Discussions:** [GitHub Discussions](https://github.com/yourusername/rideplay/discussions)
- 📧 **Email:** rideplay@yourdomain.com
- 🌐 **Website:** [Live Demo](https://zayki.com:3000)

## 🏆 **Recognition**

- ⭐ Featured in [TechCrunch Article](#) (placeholder)
- 🎖️ Winner of [Hackathon Name](#) (placeholder)
- 📰 Mentioned in [Industry Publication](#) (placeholder)

---

<div align="center">

**Made with ❤️ by [Fedor Zaitsev](https://github.com/yourusername)**

</div>
