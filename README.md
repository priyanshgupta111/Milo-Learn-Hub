# 🎓 Milo Learn Hub

**Code For Bharat Season 2 Hackathon Submission**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-brightgreen)](https://milolearnhub.netlify.app/)
[![Demo Video](https://img.shields.io/badge/Demo%20Video-Watch%20Now-red)](https://youtu.be/W5qUqC3iqGI?si=KQAOWn6r2REhQIJY)

## 🏆 Team Heisenbug Uncertainty

| Team Member | Role | Contributions |
|-------------|------|---------------|
| **Priyansh Gupta** | Frontend Developer & UI/UX Designer | Designed and implemented the complete user interface, created responsive layouts, developed the landing page, and crafted the visual design system |
| **Rudrakshi Bedi** | AI Integration Specialist & Backend Logic | Integrated Google Gemini AI for conversational learning, implemented the chat interface, developed the mode selection system, and handled API integrations |
| **Shreya Dalmia** | QA Engineer & Deployment Specialist | Managed testing procedures, handled deployment pipeline, optimized performance, and created project documentation |

## 🚀 Project Overview

Milo Learn Hub is an innovative AI-powered educational platform that revolutionizes personalized learning through interactive conversations. Our platform features an intelligent tutor named Milo who adapts to different learning styles and provides engaging educational experiences.

### 🎯 Problem Statement
Traditional learning methods often fail to adapt to individual learning preferences and styles. Students struggle with one-size-fits-all approaches that don't cater to their unique needs, leading to decreased engagement and suboptimal learning outcomes.

### 💡 Our Solution
Milo Learn Hub addresses this challenge by providing:
- **Personalized AI Tutoring**: Adaptive learning experiences tailored to individual preferences
- **Multiple Learning Modes**: Sweet, Savage, and Nerdy modes to match different personality types
- **Interactive Conversations**: Natural language processing for engaging educational dialogues
- **Voice Integration**: Text-to-speech functionality for enhanced accessibility
- **Modern Interface**: Clean, responsive design optimized for all devices

## ✨ Key Features

### 🤖 AI-Powered Learning Modes
- **Sweet Mode**: Encouraging and supportive learning approach
- **Savage Mode**: Direct and challenging teaching style  
- **Nerdy Mode**: Detailed and technical explanations

### 💬 Interactive Chat Interface
- Real-time conversations with AI tutor Milo
- Context-aware responses based on learning history
- Seamless chat experience with typing indicators

### 🔊 Accessibility Features
- Text-to-speech integration for audio learning
- Responsive design for mobile and desktop
- Clean, intuitive user interface

### 🎨 Modern Design System
- Beautiful gradient backgrounds
- Smooth animations and transitions
- Dark/light mode compatibility
- Mobile-first responsive design

## 🛠️ Technical Architecture

### Frontend Stack
- **React 18.3.1** - Modern UI library for building interactive components
- **TypeScript** - Type-safe development for better code quality
- **Vite** - Lightning-fast build tool and development server
- **Tailwind CSS** - Utility-first CSS framework for rapid styling

### AI & Integration
- **Google Gemini AI** - Advanced language model for conversational AI
- **ElevenLabs API** - High-quality text-to-speech synthesis
- **React Query** - Efficient data fetching and state management

### UI Components
- **shadcn/ui** - Beautiful, accessible component library
- **Radix UI** - Low-level UI primitives for accessibility
- **Lucide React** - Modern icon library
- **Sonner** - Elegant toast notifications

## 🏗️ Project Structure

```
src/
├── components/
│   ├── ChatInterface.tsx      # Main chat functionality
│   ├── LandingPage.tsx        # Homepage design
│   ├── ModeSelector.tsx       # Learning mode selection
│   ├── TextToSpeech.tsx       # Voice integration
│   └── ui/                    # Reusable UI components
├── pages/
│   ├── Index.tsx              # Main application page
│   └── NotFound.tsx           # 404 error page
├── types/
│   └── index.ts               # TypeScript type definitions
├── lib/
│   └── utils.ts               # Utility functions
└── hooks/                     # Custom React hooks
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn package manager
- Google Gemini API key
- ElevenLabs API key

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-team/milo-learn-hub.git
   cd milo-learn-hub
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   # Add your API keys to the application
   # Google Gemini API key for AI functionality
   # ElevenLabs API key for text-to-speech
   ```

4. **Start development server**
   ```bash
   npm run dev
   ```

5. **Open in browser**
   ```
   http://localhost:5173
   ```

### Build for Production

```bash
npm run build
npm run preview
```

## 🎯 Key Innovations

### 1. Adaptive Learning Personality System
Our unique three-mode system (Sweet, Savage, Nerdy) allows users to choose their preferred learning style, making education more engaging and effective.

### 2. Conversational AI Integration
Seamless integration with Google Gemini AI provides natural, context-aware conversations that adapt to user queries and learning progress.

### 3. Accessibility-First Design
Text-to-speech functionality ensures the platform is accessible to users with different learning preferences and needs.

### 4. Modern Development Practices
Built with cutting-edge technologies and best practices for performance, maintainability, and user experience.

## 📊 Technical Highlights

- **Performance Optimized**: Fast loading times with Vite bundling
- **Type Safety**: Full TypeScript implementation for robust code
- **Responsive Design**: Mobile-first approach for all device types
- **Component Architecture**: Modular, reusable component design
- **State Management**: Efficient data handling with React Query
- **Error Handling**: Comprehensive error boundaries and fallbacks

## 🌟 Future Roadmap

### Phase 1: Enhanced Features
- [ ] Progress tracking and analytics
- [ ] Multiple language support
- [ ] Learning path recommendations
- [ ] Achievement system and badges

### Phase 2: Advanced AI
- [ ] Voice input for hands-free interaction
- [ ] Image and document analysis
- [ ] Personalized curriculum generation
- [ ] Multi-modal learning support

### Phase 3: Community Features
- [ ] Peer-to-peer learning groups
- [ ] Teacher dashboard and insights
- [ ] Content creation tools
- [ ] Collaborative learning spaces

## 🏅 Hackathon Achievements

- **✅ Complete Full-Stack Implementation**: Functional AI-powered learning platform
- **✅ Modern Tech Stack**: Latest React, TypeScript, and AI technologies
- **✅ User-Centric Design**: Intuitive interface with accessibility features
- **✅ Scalable Architecture**: Built for future enhancements and growth
- **✅ Live Deployment**: Fully functional demo available online

## 📱 Demo & Links

- **🌐 Live Website**: [milolearnhub.netlify.app](https://milolearnhub.netlify.app/)
- **🎥 Demo Video**: [Watch on YouTube](https://youtu.be/W5qUqC3iqGI?si=KQAOWn6r2REhQIJY)
- **📂 GitHub Repository**: [View Source Code](https://github.com/your-team/milo-learn-hub)

## 👥 Team Contributions

### Priyansh Gupta - Frontend & Design Lead
- Architected the complete UI/UX design system
- Implemented responsive layouts and component library
- Created the landing page and visual branding
- Optimized user experience and accessibility

### Rudrakshi Bedi - AI Integration Specialist  
- Integrated Google Gemini AI for conversational learning
- Developed the chat interface and mode selection system
- Implemented real-time conversation handling
- Managed API integrations and data flow

### Shreya Dalmia - QA & Deployment Engineer
- Established testing procedures and quality assurance
- Managed deployment pipeline and performance optimization
- Created comprehensive project documentation
- Handled production deployment and monitoring

## 🤝 Contributing

We welcome contributions from the community! Please feel free to submit issues, feature requests, or pull requests.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Built with ❤️ by Team Heisenbug Uncertainty for Code For Bharat Season 2**

*Empowering education through AI innovation*
