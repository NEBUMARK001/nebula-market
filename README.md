# 🌌 Nebula Market - AI-Powered Trading Platform

A modern, responsive trading dashboard built with Next.js, TypeScript, and Tailwind CSS, featuring AI-powered insights and real-time market analytics.

![Nebula Market Dashboard](https://img.shields.io/badge/Next.js-15.4.7-black?style=for-the-badge&logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?style=for-the-badge&logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.0-38B2AC?style=for-the-badge&logo=tailwind-css)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-12.23.12-black?style=for-the-badge&logo=framer)

## ✨ Features

### 🎯 Core Functionality
- **Real-time Market Data**: Live price feeds for forex and commodities
- **AI-Powered Signals**: Machine learning-based trading recommendations
- **Interactive Charts**: Dynamic sparkline charts and trading view integration
- **Portfolio Management**: Comprehensive portfolio tracking and analytics
- **Risk Management**: Built-in risk assessment and position sizing

### 🎨 UI/UX Features
- **Glassmorphic Design**: Modern glassmorphism with backdrop blur effects
- **Animated Starfield**: Dynamic background with animated stars
- **Responsive Layout**: Fully responsive design for all devices
- **Dark Theme**: Elegant dark theme with gradient accents
- **Smooth Animations**: Framer Motion powered transitions and micro-interactions

### 🔧 Technical Features
- **Next.js 15**: Latest Next.js with App Router
- **TypeScript**: Full type safety and better developer experience
- **Tailwind CSS 4**: Utility-first CSS framework
- **Framer Motion**: Smooth animations and transitions
- **Lucide Icons**: Beautiful, customizable icons
- **Component Library**: Custom UI components with shadcn/ui patterns

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/NEBUMARK001/nebula-market.git
   cd nebula-market
   ```

2. **Install dependencies**
   ```bash
   cd web
   npm install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📁 Project Structure

```
nebula-market/
├── web/                          # Next.js application
│   ├── app/                      # App Router pages
│   │   ├── (dashboard)/          # Dashboard routes
│   │   │   ├── dashboard/        # Main dashboard
│   │   │   ├── markets/          # Markets page
│   │   │   ├── trades/           # Trades page
│   │   │   └── ai-insights/      # AI insights page
│   │   ├── auth/                 # Authentication pages
│   │   └── cta-demo/             # Demo pages
│   ├── components/               # React components
│   │   └── ui/                   # UI components
│   │       ├── button.tsx        # Button component
│   │       ├── card.tsx          # Card components
│   │       ├── input.tsx         # Input component
│   │       ├── progress.tsx      # Progress bar
│   │       ├── select.tsx        # Select dropdown
│   │       ├── dropdown-menu.tsx # Dropdown menu
│   │       ├── avatar.tsx        # Avatar component
│   │       ├── badge.tsx         # Badge component
│   │       ├── separator.tsx     # Separator component
│   │       └── ...               # Other UI components
│   ├── lib/                      # Utility functions
│   ├── hooks/                    # Custom React hooks
│   └── public/                   # Static assets
```

## 🎨 Design System

### Color Palette
- **Primary**: Cyan to Purple gradient (`from-cyan-500 to-purple-600`)
- **Background**: Dark slate with purple accents (`from-slate-900 via-purple-900 to-slate-900`)
- **Text**: White and gray variations for hierarchy
- **Accents**: Green for positive, red for negative, yellow for warnings

### Typography
- **Headings**: Bold, large text with gradient effects
- **Body**: Clean, readable text with proper contrast
- **Code**: Monospace for technical content

### Components
All UI components follow a consistent design pattern with:
- Glassmorphic backgrounds (`bg-white/10 backdrop-blur-lg`)
- Subtle borders (`border-white/20`)
- Hover effects and transitions
- Responsive design principles

## 🔧 Configuration

### Environment Variables
Create a `.env.local` file in the `web/` directory:

```env
NEXT_PUBLIC_API_URL=your_api_url_here
NEXT_PUBLIC_WS_URL=your_websocket_url_here
```

### Tailwind Configuration
The project uses Tailwind CSS 4 with custom configurations for:
- Glassmorphism effects
- Custom gradients
- Animation utilities
- Responsive breakpoints

## 📊 Features in Detail

### Dashboard Overview
- **Market Cards**: Real-time price updates with sparkline charts
- **AI Signals**: Machine learning predictions with confidence scores
- **Quick Trade**: Fast trade execution interface
- **Portfolio Summary**: Balance, equity, and P&L tracking
- **Recent Trades**: Transaction history with status indicators

### AI Insights
- **Signal Generation**: AI-powered buy/sell/hold recommendations
- **Confidence Scoring**: Percentage-based confidence levels
- **Reason Analysis**: Detailed explanations for each signal
- **Pattern Recognition**: Technical analysis and trend detection

### Market Data
- **Forex Pairs**: Major currency pairs (EUR/USD, GBP/USD, etc.)
- **Commodities**: Gold (XAU/USD), Silver, Oil
- **Cryptocurrencies**: Bitcoin, Ethereum, and other major cryptos
- **Real-time Updates**: Live price feeds and market movements

## 🚀 Deployment

### Vercel (Recommended)
1. Connect your GitHub repository to Vercel
2. Configure environment variables
3. Deploy automatically on push to main branch

### Other Platforms
The app can be deployed to any platform that supports Next.js:
- Netlify
- Railway
- DigitalOcean App Platform
- AWS Amplify

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Development Guidelines
- Follow TypeScript best practices
- Use Tailwind CSS for styling
- Maintain component consistency
- Write meaningful commit messages
- Test thoroughly before submitting PRs

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Next.js Team**: For the amazing React framework
- **Tailwind CSS**: For the utility-first CSS framework
- **Framer Motion**: For smooth animations
- **Lucide**: For beautiful icons
- **shadcn/ui**: For component design patterns

## 📞 Support

- **Email**: support@nebulamarket.com
- **Documentation**: [docs.nebulamarket.com](https://docs.nebulamarket.com)
- **Issues**: [GitHub Issues](https://github.com/NEBUMARK001/nebula-market/issues)

## 🔮 Roadmap

- [ ] Real-time WebSocket integration
- [ ] Advanced charting with TradingView
- [ ] Mobile app (React Native)
- [ ] Advanced AI models integration
- [ ] Social trading features
- [ ] Multi-language support
- [ ] Advanced portfolio analytics
- [ ] API documentation

---

**Built with ❤️ by the Nebula Market Team**

[![GitHub stars](https://img.shields.io/github/stars/NEBUMARK001/nebula-market?style=social)](https://github.com/NEBUMARK001/nebula-market)
[![GitHub forks](https://img.shields.io/github/forks/NEBUMARK001/nebula-market?style=social)](https://github.com/NEBUMARK001/nebula-market)
[![GitHub issues](https://img.shields.io/github/issues/NEBUMARK001/nebula-market)](https://github.com/NEBUMARK001/nebula-market/issues)
