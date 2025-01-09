<div align="center">
  <img src="public/logo.png" alt="VORI Logo" width="180"/>
  
  # VORI - The Future of Meeting Management
  
  [![Next.js](https://img.shields.io/badge/Next.js-14-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
  [![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
  [![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.0-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)
  [![Framer Motion](https://img.shields.io/badge/Framer_Motion-Latest-ff69b4?style=for-the-badge&logo=framer)](https://www.framer.com/motion/)
</div>

## 🚀 Features

- **🎙️ Voice Recording** - Crystal clear audio with noise cancellation
- **🧠 AI Transcription** - Real-time transcription with 99% accuracy
- **🎫 Smart Tickets** - Automated task generation from discussions
- **💻 Cross-Platform** - Work seamlessly across all your devices
- **📊 Analytics** - Deep insights into meeting productivity
- **🚀 Instant Deploy** - Set up in minutes, not hours

## 📸 Product Tour

<div align="center">
  <img src="public/screenshots/loginpage.png" alt="Login Interface" width="800"/>
  <p><em>Secure Authentication</em></p>
  
  <img src="public/screenshots/dashboard.png" alt="Dashboard" width="800"/>
  <p><em>AI-Powered Dashboard</em></p>
  
  <img src="public/screenshots/meetingpage.png" alt="Meeting Interface" width="800"/>
  <p><em>Real-time Meeting Room</em></p>
  
  <img src="public/screenshots/kanban.png" alt="Kanban Board" width="800"/>
  <p><em>Visual Kanban Board</em></p>
  
  <img src="public/screenshots/ticketspage.png" alt="Tickets Management" width="800"/>
  <p><em>Smart Ticket System</em></p>
  
  <img src="public/screenshots/profilepage.png" alt="User Profile" width="800"/>
  <p><em>Personalized Profile</em></p>
  
  <img src="public/screenshots/settingpage.png" alt="Settings" width="800"/>
  <p><em>Custom Settings</em></p>
  
  <img src="public/screenshots/notificationspopup.png" alt="Notifications" width="800"/>
  <p><em>Real-time Notifications</em></p>
  
  <img src="public/screenshots/landingpage.png" alt="Landing Page" width="800"/>
  <p><em>Modern Landing Page</em></p>
</div>

## 🛠️ Tech Stack

- **Frontend Framework:** Next.js 14 with App Router
- **Styling:** Tailwind CSS with Custom Design System
- **Animations:** Framer Motion
- **State Management:** React Context + Hooks
- **Icons:** Tabler Icons
- **Code Quality:** TypeScript, ESLint, Prettier

## 🚀 Quick Start

1. **Clone the repository**

```bash
git clone https://github.com/nukktae/VoriReborn-Frontend.git
```

2. **Install dependencies**

```bash
cd VoriReborn-Frontend
npm install
```

3. **Start the development server**

```bash
npm run dev
```

4. **Open [http://localhost:3000](http://localhost:3000)**

## 🌟 Key Features

### AI-Powered Meeting Management
- Real-time transcription
- Automated task generation
- Meeting analytics and insights

### Modern User Interface
- Responsive design
- Smooth animations
- Dark/Light mode support

### Enterprise-Ready
- Role-based access control
- Team collaboration features
- Custom integrations

## 📱 Responsive Design

<div align="center">
  <img src="public/screenshots/responsive.png" alt="Responsive Design" width="800"/>
  <p><em>Seamless Experience Across All Devices</em></p>
</div>

### Multi-Device Support
- **📱 Mobile First** - Optimized for smartphones and tablets
  - Touch-friendly interface
  - Gesture-based navigation
  - Optimized media loading
- **💻 Desktop Ready** - Full-featured experience on larger screens
  - Advanced keyboard shortcuts
  - Multi-window support
  - Enhanced data visualization
- **🔄 Sync Everywhere** - Real-time updates across all devices
  - WebSocket connections
  - Offline-first architecture
  - Background sync
- **⚡ Progressive Web App**
  - Service Worker caching
  - Push notifications
  - Install prompts
  - Offline functionality
- **🎨 Adaptive UI**
  - Tailwind CSS breakpoints
  - CSS Grid/Flexbox layouts
  - Container queries
  - Dynamic theming
- **📊 Responsive Charts**
  - SVG-based visualizations
  - Canvas performance optimization
  - Adaptive data points
  - Touch-friendly interactions

### Technical Implementation
```typescript
// Responsive breakpoints using Tailwind CSS
module.exports = {
  theme: {
    screens: {
      'sm': '640px',   // Mobile devices
      'md': '768px',   // Tablets
      'lg': '1024px',  // Laptops
      'xl': '1280px',  // Desktops
      '2xl': '1536px', // Large screens
    }
  }
}
```

### Key Features
- **Dynamic Grid System**
  ```jsx
  <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4">
    {/* Content adapts to screen size */}
  </div>
  ```
- **Flexible Components**
  ```jsx
  <div className="flex flex-col md:flex-row items-center justify-between">
    {/* Stacks vertically on mobile, horizontal on larger screens */}
  </div>
  ```
- **Smart Media Loading**
  ```jsx
  <img
    srcSet="img-sm.jpg 300w, img-md.jpg 600w, img-lg.jpg 1200w"
    sizes="(max-width: 768px) 100vw, (max-width: 1200px) 50vw, 33vw"
    src="img-fallback.jpg"
    alt="Responsive image"
  />
  ```

### Performance Metrics
- **Mobile Loading Time**: < 2 seconds
- **Desktop Loading Time**: < 1 second
- **Lighthouse Score**: 95+ on all devices
- **First Contentful Paint**: < 1.5 seconds
- **Time to Interactive**: < 3.5 seconds

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">
  <p>Built with ❤️ by the VORI team</p>
  <p>
    <a href="https://twitter.com/vori">Twitter</a> •
    <a href="https://discord.gg/vori">Discord</a> •
    <a href="https://vori.com">Website</a>
  </p>
</div>
