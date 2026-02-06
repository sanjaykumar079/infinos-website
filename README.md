# InfinosTech - Smart Temperature-Controlled Logistics Platform

<div align="center">
  <img src="src/images/logo.jpg" alt="InfinosTech Logo" width="200"/>
  
  ### The World's First Sustainable, Dual-Zone, AIoT-Enabled Portable Container System
  
  [![React](https://img.shields.io/badge/React-19.2.3-61DAFB?style=for-the-badge&logo=react)](https://reactjs.org/)
  [![License](https://img.shields.io/badge/License-Proprietary-orange?style=for-the-badge)](LICENSE)
  [![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)]()
  
  [Live Demo](https://infinostech.com) · [Report Bug](https://github.com/infinostech/website/issues) · [Request Feature](https://github.com/infinostech/website/issues)
</div>

---

## 📋 Table of Contents

- [About The Project](#about-the-project)
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Core Components](#core-components)
- [Our Solution](#our-solution)
- [Market Opportunity](#market-opportunity)
- [Traction & Validation](#traction--validation)
- [Sustainability](#sustainability)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [Contact](#contact)
- [Acknowledgments](#acknowledgments)

---

## 🎯 About The Project

**InfinosTech** is revolutionizing the cold chain logistics industry with cutting-edge technology that addresses critical infrastructure gaps in temperature-controlled delivery systems.

### The Problem We Solve

- **20-30%** of perishable food is lost due to inadequate temperature management
- **50%** of vaccines are wasted annually due to temperature control failures
- Traditional cold chain infrastructure is too heavy and power-hungry for last-mile delivery
- Lack of compatibility with modern delivery systems (drones, bicycles, EVs)
- No scalable eco-friendly alternatives to chemical coolants

### Our Mission

To make temperature-controlled delivery accessible, affordable, and sustainable for last-mile logistics worldwide.

---

## ✨ Key Features

### 🌡️ Dual-Zone Temperature Control
- **Cool Zone**: 0°C to 10°C (vaccines, medicines, fresh produce)
- **Heat Zone**: 40°C to 80°C (hot meals, medical incubation)
- **Independent Control**: Both zones operate simultaneously

### 📱 AIoT-Enabled Platform
- Real-time temperature and location tracking
- Mobile app control for remote adjustments
- Instant alerts for temperature deviations
- Cloud-based analytics dashboard
- Fleet management insights

### 🔋 Portable & Versatile
- Battery-powered (no constant electrical connection)
- Lightweight design for drone compatibility
- Works with EVs, bikes, bicycles, and 2-wheelers
- Customizable sizes: 30L, 60L, 80L

### 🌿 Eco-Friendly
- Organic, sustainable coolants
- EV-compatible for green transport
- Aligned with UN SDG Goals 9, 11, and 13
- Reduces food and vaccine waste

### 🛡️ Built-in Safety
- UV sanitization for hygiene
- Multi-insulated design
- Pharmaceutical-grade compliance
- Real-time quality monitoring

---

## 🛠️ Technology Stack

### Frontend
- **React 19.2.3** - Modern UI framework
- **React Router DOM 7.10.1** - Navigation and routing
- **CSS3** - Custom styling with CSS variables

### Backend Services
- **Google Generative AI** - AI-powered chatbot assistant
- **AIoT Platform** - Real-time device monitoring
- **Cloud Analytics** - Data processing and insights

### Development Tools
- **Create React App** - Project scaffolding
- **Web Vitals** - Performance monitoring
- **Testing Library** - Component testing

### APIs & Integrations
- Google Generative AI API
- Custom AIoT device API
- Real-time temperature sensors
- GPS tracking integration

---

## 🚀 Getting Started

### Prerequisites

```bash
node >= 14.0.0
npm >= 6.0.0
```

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/infinostech/website.git
cd website
```

2. **Install dependencies**
```bash
npm install
```

3. **Set up environment variables**

Create a `.env` file in the root directory:

```env
# Port Configuration
PORT=3000

# App URL
REACT_APP_APP_URL=http://localhost:3001

# Admin URL (optional)
REACT_APP_ADMIN_URL=http://localhost:3002

# Gemini API Key for Chatbot
REACT_APP_GEMINI_API_KEY=your_gemini_api_key_here
```

4. **Start the development server**
```bash
npm start
```

The application will open at [http://localhost:3000](http://localhost:3000)

### Build for Production

```bash
npm run build
```

This creates an optimized production build in the `build/` folder.

### Run Tests

```bash
npm test
```

---

## 📁 Project Structure

```
infinostech-website/
├── public/
│   ├── index.html
│   └── favicon.ico
├── src/
│   ├── components/
│   │   ├── Chatbot.js          # AI-powered customer support
│   │   └── Chatbot.css         # Chatbot styling
│   ├── images/
│   │   ├── logo.jpg            # InfinosTech logo
│   │   ├── hero-1.jpg          # Hero carousel images
│   │   ├── hero-2.jpg
│   │   ├── hero-3.jpg
│   │   ├── home_page.png       # Product showcase
│   │   └── i1.jpg - i9.png     # Gallery images
│   ├── App.js                  # Main application component
│   ├── App.css                 # Global app styles
│   ├── Home.js                 # Landing page component
│   ├── Home.css                # Landing page styles
│   ├── AboutSection.css        # About section styles
│   ├── index.js                # React entry point
│   └── index.css               # Root styles
├── .env                        # Environment variables
├── .gitignore                  # Git ignore rules
├── package.json                # Dependencies and scripts
└── README.md                   # This file
```

---

## 🧩 Core Components

### 1. **Hero Section**
- Dynamic image carousel with 3 slides
- Responsive design with overlay content
- Call-to-action buttons for demo requests
- Feature highlights with animated pills

### 2. **About Section**
- Company mission and vision
- Problem statement with statistics
- Professional card-based layout
- Key metrics dashboard

### 3. **Products Section**
- 3-in-1 operation modes (Cool, Heat, Dual-Zone)
- Visual product showcase
- Animated delivery tagline
- Zone-specific temperature specifications

### 4. **Gallery Section**
- Horizontal sliding carousel
- 9 showcase images with categories
- Auto-scroll with manual navigation
- Hover effects and descriptions

### 5. **Contact Section**
- Professional contact form
- Company information display
- Multi-field inquiry types
- Real-time form validation

### 6. **AI Chatbot**
- Comprehensive product knowledge base
- Real-time customer support
- Context-aware responses
- Professional UI with animations

---

## 💡 Our Solution

### 3-in-1 Smart Container System

| Mode | Temperature Range | Use Cases |
|------|------------------|-----------|
| **Cool Only** | 0°C to 10°C | Vaccines, medicines, fresh produce |
| **Heat Only** | 40°C to 80°C | Hot meals, medical incubation |
| **Dual-Zone** | Both simultaneously | Mixed deliveries, maximum flexibility |

### Key Advantages Over Competitors

| Competitor | Limitation | InfinosTech Solution |
|------------|-----------|---------------------|
| Godrej ChotuKool | Heavy, electric-only | Lightweight, drone-compatible |
| Hi-Rapid Labs | No smart features | AIoT-enabled, dual-zone control |
| Vaara | Bulky, not last-mile ready | Portable, versatile, multi-vehicle |
| Generic Ice Boxes | Passive cooling only | Active temperature control |

---

## 📊 Market Opportunity

### Market Size
- **TAM (Total Addressable Market)**: $16B - India's temperature-controlled logistics
- **SAM (Serviceable Available Market)**: $10B - Food delivery, quick commerce, B2B
- **SOM (Serviceable Obtainable Market)**: $3B - Last-mile delivery with bikes/EVs

### Target Customers
- Food delivery platforms (Swiggy, Zomato, etc.)
- Quick commerce companies
- Healthcare & pharmaceutical distributors
- Diagnostic laboratories
- Restaurant chains
- B2B cold storage providers

### Revenue Model

| Stream | Description | Revenue % |
|--------|-------------|-----------|
| AIoT Devices | Hardware sales ($30-$100/unit) | 30% |
| SaaS Platform | Analytics & monitoring subscription | 20% |
| B2B Solutions | Complete logistics packages | 20% |
| Subscriptions | Bulk order recurring revenue | 15% |
| Coolant Refills | Ongoing consumables | 15% |

---

## 🎯 Traction & Validation

### Proven Success

✅ **3 Purchase Orders**
- Sepal
- Mirai Millet
- Blitz Food

✅ **Active Paid Pilots**
- Lavin Labs (Diagnostics)
- Bluecloudsoftech (Technology)
- Agrighar Community (Rural logistics)

✅ **Strategic Discussions**
- Bharat Biotech (Vaccines)
- Vijay Diagnostics (Medical logistics)

✅ **Partnerships & Recognition**
- ISF Junicorn Cohort 2 member
- MOU with Yubhas Renewables
- Dalit Indian Chamber of Commerce partner
- Hitex Kisan Expo participant

✅ **Field Testing**
- EV trials completed in Hyderabad
- Drone delivery tests successful
- 2-wheeler deployment validated

---

## 🌍 Sustainability

### UN Sustainable Development Goals

| SDG | Goal | Our Impact |
|-----|------|-----------|
| **9** | Industry, Innovation & Infrastructure | Advanced AIoT logistics technology |
| **11** | Sustainable Cities & Communities | Last-mile urban delivery optimization |
| **13** | Climate Action | Eco-friendly coolants, EV compatibility |

### Environmental Impact
- **Reduces food waste** by preventing temperature failures
- **Prevents vaccine spoilage** through precise control
- **Uses organic coolants** instead of harmful chemicals
- **EV-compatible** for zero-emission transport
- **Scalable sustainable operations** for global deployment

---

## 🗺️ Roadmap

### Phase 1: MVP & Market Entry (Current)
- [x] Patent filed (India, 2023)
- [x] Initial pilots completed
- [x] Purchase orders secured
- [ ] Raise $360K seed funding
- [ ] Manufacture first 20-30 production units

### Phase 2: Scale & Expansion (6-12 months)
- [ ] Deploy with quick commerce partners
- [ ] Expand to medical/vaccine logistics
- [ ] Build dedicated sales team
- [ ] Launch 60L and 80L variants
- [ ] Establish 5 strategic partnerships

### Phase 3: Growth & Innovation (12-24 months)
- [ ] Pan-India deployment network
- [ ] International market entry (SEA, Africa)
- [ ] AI-powered route optimization
- [ ] Predictive maintenance features
- [ ] Series A fundraising ($2-3M)

### Phase 4: Market Leadership (24+ months)
- [ ] Become India's #1 last-mile cold chain provider
- [ ] Launch drone-exclusive delivery pods
- [ ] Open-source AIoT platform for developers
- [ ] Global expansion to 10+ countries
- [ ] Achieve carbon neutrality

---

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

### Reporting Bugs
1. Check if the bug has already been reported in [Issues](https://github.com/infinostech/website/issues)
2. If not, create a new issue with:
   - Clear title and description
   - Steps to reproduce
   - Expected vs actual behavior
   - Screenshots if applicable

### Suggesting Features
1. Open a new issue with the `enhancement` label
2. Describe the feature and its benefits
3. Include use cases and examples

### Code Contributions
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Development Guidelines
- Follow existing code style and conventions
- Write clear commit messages
- Add comments for complex logic
- Test thoroughly before submitting PR
- Update documentation as needed

---

## 📞 Contact

**InfinosTech Pvt Ltd**

- 📧 Email: contact@infinostech.com
- 🌐 Website: [www.infinostech.com](https://www.infinostech.com)
- 📍 Location: Hyderabad, India
- 💼 LinkedIn: [InfinosTech](https://www.linkedin.com/company/infinostech-pvt-ltd/)
- 🐦 Twitter: [@infinostech](https://x.com/infinostech)
- 📸 Instagram: [@infinostech](https://www.instagram.com/infinostech/)

### Investment Inquiries
For partnership, investment, or pilot opportunities:
- Email: contact@infinostech.com
- Current Raise: $360K USD (Convertible Note)
- Valuation Cap: $7-9M

---

## 🙏 Acknowledgments

Special thanks to:

- **ISF Junicorn Cohort 2** for incubation support
- **Yubhas Renewables** for strategic partnership
- **All pilot customers** for valuable feedback
- **Dalit Indian Chamber of Commerce** for networking opportunities
- **React & Open Source Community** for amazing tools

---

## 📜 License

This project is proprietary and confidential. All rights reserved by InfinosTech Pvt Ltd.

For licensing inquiries, please contact: contact@infinostech.com

---

## 🌟 Star Us!

If you find this project interesting or useful, please consider giving it a star ⭐

<div align="center">
  
  **Making Temperature-Controlled Logistics Accessible, Affordable, and Sustainable**
  
  Built with ❤️ by the InfinosTech Team
  
  © 2025 InfinosTech Pvt Ltd. All rights reserved.
  
</div>
