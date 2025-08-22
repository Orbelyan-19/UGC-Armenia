# ContentBridge Armenia - UGC Marketplace

A modern, dark-themed UGC (User Generated Content) marketplace website connecting Armenian creators with businesses through a secure escrow system.

## 🌟 Features

### Main Website (`index.html`)
- **Dark Theme with Glassmorphism**: Modern design with glass effects and gradients
- **EN/RU Language Switching**: Full bilingual support with localStorage persistence
- **Responsive Design**: Mobile-optimized with premium animations
- **Top Creators Section**: Showcase of verified Armenian creators
- **Formspree Integration**: Working contact form with email notifications
- **Google Analytics**: GA4 tracking with event monitoring
- **Anti-bypass Protection**: Hidden contact information and security features

### Creators Directory (`creators.html`)
- **Advanced Search & Filters**: Search by name, category, and rating
- **Creator Cards**: Detailed profiles with ratings, projects, and pricing
- **Responsive Grid**: Mobile-optimized layout
- **Direct Booking**: Quick access to hire creators

### Creator Profiles (`creator.html`)
- **Detailed Profiles**: Complete creator information and portfolio
- **Portfolio Showcase**: Visual gallery of past work
- **Client Reviews**: Authentic testimonials and ratings
- **Pricing Information**: Transparent pricing and features
- **Booking Integration**: Direct project initiation

### Business Page (`clients.html`)
- **Business Benefits**: Clear value proposition for companies
- **Process Overview**: Step-by-step workflow explanation
- **Client Testimonials**: Success stories and case studies
- **Statistics**: Impact metrics and achievements
- **Call-to-Action**: Multiple conversion opportunities

### Admin Panel (`admin.html`)
- **Comprehensive Dashboard**: Real-time stats, charts, and analytics
- **Order Management**: Complete order lifecycle management
- **Creator Management**: Creator profiles, ratings, and verification
- **Client Management**: Business accounts and subscription plans
- **Financial Analytics**: Revenue tracking and commission management
- **Content Moderation**: Review and approval system
- **Interactive Charts**: Revenue trends, order status, and performance metrics

### Thank You Page (`thanks.html`)
- **Confirmation Flow**: Clear next steps and expectations
- **Contact Options**: Multiple communication channels
- **Social Integration**: Links to social media platforms

## 🚀 Quick Start

### Local Development
1. Clone or download the project files
2. Open `index.html` in your web browser
3. The website is fully functional with all features working

### Formspree Setup
1. Create a free account at [Formspree.io](https://formspree.io)
2. Create a new form and get your form ID
3. Replace `mgvzgvag` in `index.html` with your form ID:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

### Google Analytics Setup
1. Create a Google Analytics 4 property
2. Replace `G-5BJ9JRVE9C` with your tracking ID in all HTML files
3. Verify tracking in Google Analytics dashboard

## 📁 File Structure

```
ContentBridge Armenia/
├── index.html          # Main landing page with top creators section
├── creators.html       # Creators directory with search and filters
├── creator.html        # Individual creator profile pages
├── clients.html        # Business-focused page for clients
├── admin.html          # Admin dashboard
├── thanks.html         # Thank you page
├── robots.txt          # SEO configuration
└── README.md           # This file
```

## 🎨 Design System

### Color Palette
- **Primary**: `#6366f1` (Indigo)
- **Secondary**: `#ec4899` (Pink)
- **Accent**: `#06b6d4` (Cyan)
- **Success**: `#10b981` (Green)
- **Warning**: `#f59e0b` (Amber)
- **Danger**: `#ef4444` (Red)
- **Dark**: `#0f172a` (Slate)
- **Light**: `#f8fafc` (Slate)

### Typography
- **Font**: Inter (Google Fonts)
- **Weights**: 300, 400, 500, 600, 700

### Components
- **Glassmorphism**: Backdrop blur with transparency
- **Gradients**: Linear and radial gradients
- **Animations**: Smooth transitions and hover effects
- **Responsive**: Mobile-first design approach

## 🔧 Configuration

### Business Model
- **Commission**: 25% on transactions
- **Creator PRO**: $15/month
- **Business Plans**: $49-299/month
- **Rush Orders**: +50% fee
- **Target Revenue**: $45K Y1 → $300K Y2 → $1.125M Y3

### Video Categories
- Beauty & Fashion
- Technology
- Food & Cooking
- Sports & Fitness
- Automotive
- Travel & Lifestyle

### Pricing Tiers
- **Simple**: $30-70
- **Standard**: $70-150
- **Premium**: $150-300

## 📊 Analytics & Tracking

### Google Analytics Events
- `page_view`: Page visits
- `form_submit`: Contact form submissions
- `form_completion`: Thank you page views
- `creator_view`: Creator profile views

### Key Metrics
- Conversion rates (visitor → registration → order → repeat)
- GMV (Gross Merchandise Value)
- Take rate and commission revenue
- CAC (Customer Acquisition Cost)
- LTV (Lifetime Value)
- NPS (Net Promoter Score)

## 🚀 Deployment

### Vercel (Recommended)
1. Connect your GitHub repository to Vercel
2. Deploy automatically on push
3. Custom domain: `contentbridge-armenia.vercel.app`

### Other Platforms
- **Netlify**: Drag and drop deployment
- **GitHub Pages**: Free hosting for static sites
- **AWS S3**: Scalable cloud hosting

## 🔒 Security Features

### Anti-bypass Protection
- Hidden contact information
- Deposit requirements for high-value products
- NDA generator for sensitive projects
- AI monitoring for content quality

### Escrow System
- **Category A**: <$100 (no deposit)
- **Category B**: $100-500 (partial deposit)
- **Category C**: >$500 (full deposit)

## 📱 Mobile Optimization

- Responsive design for all screen sizes
- Touch-friendly interface
- Optimized loading speeds
- Progressive Web App features

## 🌐 SEO Optimization

- Meta tags and descriptions
- Structured data markup
- Robots.txt configuration
- Sitemap generation
- Fast loading times
- Mobile-friendly design

## 🔄 Next Steps

### Phase 3: Escrow + Automation (Month 3)
- [ ] Payment gateway integration
- [ ] Automated escrow system
- [ ] Creator verification workflow
- [ ] Order tracking system

### Phase 4: Mobile App + AI (Months 4-6)
- [ ] React Native mobile app
- [ ] AI-powered creator matching
- [ ] Automated content moderation
- [ ] Advanced analytics dashboard

## 📞 Support

For technical support or questions:
- **Email**: info@contentbridge-armenia.com
- **WhatsApp**: +374 XX XXX XXX
- **Telegram**: @contentbridge_armenia

## 📄 License

© 2024 ContentBridge Armenia. All rights reserved.

---

**Built with ❤️ for the Armenian creator community**
