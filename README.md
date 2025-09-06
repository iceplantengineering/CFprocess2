# Carbon Fiber Manufacturing Dashboard System

A comprehensive web-based monitoring and analytics platform for carbon fiber manufacturing processes with specialized sub-UIs and unified design system.

## 🎯 Project Overview

This system provides real-time monitoring, analytics, and management capabilities for carbon fiber manufacturing operations through multiple interconnected dashboards, all with professional UI/UX design and English language interface.

## 🏗️ System Architecture

### Main Components

1. **Main Dashboard** (`carbon_fiber_dashboard.html`)
   - Real-time process flow visualization
   - KPI monitoring and alerts
   - Interactive manufacturing stage tracking

2. **Machine Status Monitoring** (`machine-status.html`)
   - Individual equipment monitoring
   - Performance metrics and alerts
   - Maintenance scheduling interface

3. **Product Traceability** (`product-traceability.html`)
   - End-to-end batch tracking
   - Quality parameter history
   - Batch genealogy visualization

4. **Operator Management** 
   - **Attendance** (`operator-attendance.html`) - Shift tracking and attendance monitoring
   - **Training & Certifications** (`operator-training.html`) - Training records, license tracking, compliance monitoring

5. **Quality Tracking & Analysis** (`quality-tracking.html`)
   - Statistical Process Control (SPC)
   - Defect analysis and trends
   - Specification compliance monitoring

6. **Correlation Analysis** (`correlation-analysis.html`)
   - Multi-variable relationship analysis
   - Machine/quality/energy/operator correlations
   - Predictive analytics and insights

7. **Energy Monitoring** (`energy-monitoring.html`)
   - Real-time power consumption tracking
   - Equipment-wise energy breakdown
   - Efficiency optimization recommendations

8. **Chronological Review** (`chronological-review.html`)
   - Historical event timeline
   - Pattern recognition and analysis
   - Predictive maintenance insights

## ✨ Key Features

### Technical Excellence
- **Responsive Design**: Optimized for desktop, tablet, and mobile
- **Real-time Updates**: Simulated live data with periodic refresh
- **Interactive Visualizations**: Chart.js integration for dynamic charts
- **Unified Design System**: Consistent styling across all interfaces
- **Professional UI/UX**: Modern, industrial-grade interface design

### Manufacturing-Specific Capabilities
- **Process Flow Monitoring**: Animated 4-stage manufacturing visualization
- **Equipment Status Tracking**: Real-time machine performance and alerts
- **Quality Control**: SPC charts, defect analysis, compliance tracking
- **Batch Traceability**: Complete product lifecycle tracking
- **Workforce Management**: Attendance, training, certification tracking
- **Energy Optimization**: Consumption monitoring and efficiency analysis
- **Predictive Analytics**: AI-driven insights and forecasting

### Advanced Analytics
- **Correlation Analysis**: Multi-dimensional relationship mapping
- **Pattern Recognition**: Historical trend identification
- **Predictive Maintenance**: Equipment failure prediction
- **Process Optimization**: Data-driven improvement recommendations

## 🗂️ File Structure

```
CFprocess2/
├── common-styles.css              # Unified design system
├── dashboard-index.html           # Main navigation hub
├── carbon_fiber_dashboard.html    # Main manufacturing dashboard
├── machine-status.html           # Equipment monitoring
├── product-traceability.html     # Batch tracking system
├── operator-attendance.html      # Workforce attendance
├── operator-training.html        # Training & certifications
├── quality-tracking.html         # Quality control & SPC
├── correlation-analysis.html     # Advanced analytics
├── energy-monitoring.html        # Energy management
├── chronological-review.html     # Historical analysis
└── README.md                     # Project documentation
```

## 🎨 Design System

### Color Palette
- **Primary Blue**: #1e3c72, #2a5298
- **Secondary Purple**: #667eea, #764ba2
- **Status Colors**: 
  - Success: #10b981, #34d399
  - Warning: #f59e0b, #fbbf24
  - Error: #dc2626, #ef4444
  - Info: #3b82f6, #60a5fa

### Typography
- **Primary Font**: Segoe UI, system fonts
- **Monospace**: Courier New (for technical data)

### Component Standards
- **Border Radius**: 8px (md), 12px (lg), 16px (xl)
- **Spacing**: 4px increments (4px to 48px)
- **Shadows**: Layered shadow system for depth

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional, for development)

### Installation
1. Download all files to a local directory
2. Open `dashboard-index.html` in a web browser
3. Navigate through the various dashboards using the main interface

### Usage
1. **Start with Main Hub**: Open `dashboard-index.html` for overview and navigation
2. **Main Dashboard**: Real-time process monitoring via `carbon_fiber_dashboard.html`
3. **Specialized Views**: Access specific modules through navigation menu
4. **Data Export**: Use export functions in individual dashboards

## 📊 Data & Functionality

### Mock Data Features
- **Real-time Simulation**: Periodic data updates every 5-30 seconds
- **Interactive Elements**: Clickable charts, filterable tables, responsive controls
- **Dynamic Visualizations**: Live charts with Chart.js integration
- **Status Indicators**: Color-coded alerts and status displays

### Key Metrics Tracked
- Production rates and efficiency
- Quality parameters (tensile strength, modulus, diameter)
- Energy consumption and costs
- Operator attendance and performance
- Equipment status and maintenance
- Training compliance and certifications

## 🔧 Customization

### Adding New Dashboards
1. Create new HTML file following existing structure
2. Include `common-styles.css` for consistency
3. Add navigation entry to all existing files
4. Implement interactive features with JavaScript

### Modifying Styles
- Edit `common-styles.css` for global changes
- Use CSS custom properties (variables) for consistent theming
- Follow established design patterns for new components

## 📱 Responsive Design

The system is fully responsive with breakpoints at:
- **Desktop**: 1024px and above
- **Tablet**: 768px - 1023px  
- **Mobile**: Below 768px

All interfaces adapt layout, navigation, and content presentation for optimal viewing across devices.

## 🔒 Security Considerations

- Client-side only implementation (no server dependencies)
- No sensitive data storage or transmission
- Safe for development and demonstration purposes
- Production deployment would require proper authentication and authorization

## 🎯 Manufacturing Process Coverage

### Process Stages Monitored
1. **Polymerization & Spinning** (62°C, solution concentration control)
2. **Stabilization** (200-300°C, tension and atmosphere control)
3. **Carbonization** (1000-1500°C, inert atmosphere)
4. **Surface Treatment & Sizing** (electrolysis and coating application)

### Key Performance Indicators
- Overall Equipment Effectiveness (OEE)
- Production rate (kg/hr)
- Quality compliance percentage
- Energy efficiency metrics
- Operator performance scores
- Training compliance rates

## 🚀 Deployment

### GitHub Repository Setup

1. **Clone or Fork the Repository**
   ```bash
   git clone https://github.com/iceplantengineering/CFprocess2.git
   cd CFprocess2
   ```

2. **File Structure for Deployment**
   ```
   CFprocess2/
   ├── index.html                    # Main entry point (renamed from dashboard-index.html)
   ├── carbon_fiber_dashboard.html   # Manufacturing process dashboard
   ├── machine-status.html          # Equipment monitoring
   ├── product-traceability.html    # Batch tracking
   ├── operator-attendance.html     # Workforce attendance
   ├── operator-training.html       # Training & certifications
   ├── quality-tracking.html        # Quality control & SPC
   ├── correlation-analysis.html    # Advanced analytics
   ├── energy-monitoring.html       # Energy management
   ├── chronological-review.html    # Historical analysis
   ├── common-styles.css           # Unified design system
   └── README.md                   # Documentation
   ```

### Netlify Deployment

1. **Automatic Deployment**
   - Connect your GitHub repository to Netlify
   - Build settings: None required (static HTML)
   - Publish directory: root (`/`)
   - Deploy branch: `main`

2. **Manual Deployment**
   - Zip all files in the project directory
   - Drag and drop to Netlify deploy interface
   - Site will be automatically deployed

3. **Custom Domain (Optional)**
   - Configure custom domain in Netlify dashboard
   - Set up DNS records as instructed by Netlify

### GitHub Pages Alternative

1. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Source: Deploy from branch `main`
   - Folder: `/ (root)`

2. **Access Your Site**
   - URL: `https://iceplantengineering.github.io/CFprocess2/`

### Deployment Checklist

- ✅ `index.html` is the main entry point
- ✅ All navigation links updated to use correct filenames
- ✅ All CSS and JavaScript dependencies are included
- ✅ Responsive design works across devices
- ✅ All dashboard links are functional
- ✅ Mock data simulation is working

## 📈 Future Enhancements

- Real-time data integration via WebSocket or REST APIs
- Database integration for historical data storage
- Advanced AI/ML algorithms for predictive analytics
- Mobile app companion for field operations
- Integration with enterprise systems (ERP, MES)
- Multi-language support for international operations

## 🤝 Contributing

This is a demonstration system showcasing modern web technologies for industrial monitoring applications. The codebase serves as a foundation for real-world manufacturing dashboard development.

## 📄 License

This project is a demonstration system created for educational and development purposes. All code follows web standards and best practices for industrial dashboard development.

---

**Note**: This system contains mock data and simulated processes for demonstration purposes. Real-world implementation would require integration with actual manufacturing equipment and data sources.