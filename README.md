# Conference Expense Planner

A modern React-based web application for planning and budgeting conference events. Built with Redux Toolkit for state management, this application helps event organizers efficiently plan their conferences by selecting venues, audio-visual equipment, and meal options while tracking costs in real-time.

## 🌟 Features

### Venue Selection

- **Multiple venue options** with different capacities (5-200 people)
- **Real-time availability tracking** (e.g., Auditorium Hall limited to 3 bookings)
- **Cost calculation** based on quantity selection
- **Visual venue previews** with images

### Audio-Visual Equipment

- **Add-on equipment selection** for enhanced presentations
- **Quantity management** for each equipment type
- **Cost tracking** for AV requirements

### Meal Planning

- **Per-person meal pricing** for different catering options
- **Attendee count management** for accurate meal cost calculation
- **Flexible meal selection** based on event requirements

### Cost Management

- **Real-time total cost calculation** across all categories
- **Detailed breakdown** of expenses by section
- **Interactive cost summary** with itemized details

## 🚀 Live Demo

Visit the live application: [Conference Expense Planner](https://mansour-ar.github.io/conference_event_planner/)

## 🛠️ Technology Stack

- **Frontend Framework**: React 18.2.0
- **State Management**: Redux Toolkit 2.2.3
- **Build Tool**: Vite 5.2.0
- **Styling**: CSS3 with custom components
- **Deployment**: GitHub Pages

## 📦 Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/mansour-ar/conference_event_planner.git
   cd conference_event_planner
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the development server**

   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to view the application

## 🎯 Usage

### Getting Started

1. Click the **"Get Started"** button on the landing page
2. Navigate through the different sections using the navigation bar:
   - **Venue**: Select conference rooms and halls
   - **Add-ons**: Choose audio-visual equipment
   - **Meals**: Plan catering for attendees

### Planning Your Event

1. **Select Venues**: Choose from various room options with different capacities
2. **Add Equipment**: Select audio-visual equipment as needed
3. **Plan Meals**: Choose catering options and specify attendee count
4. **Review Costs**: Use the "Show Details" button to see a complete cost breakdown

### Cost Tracking

- View real-time cost updates as you make selections
- See detailed breakdowns by category (venue, AV, meals)
- Track total expenses across all selections

## 📁 Project Structure

```
conference_event_planner/
├── public/                 # Static assets
│   ├── AUdi.png
│   ├── bgevent.png
│   └── conference.png
├── src/
│   ├── assets/            # Application assets
│   ├── App.jsx           # Main application component
│   ├── ConferenceEvent.jsx # Core event planning component
│   ├── TotalCost.jsx     # Cost calculation component
│   ├── AboutUs.jsx       # About section component
│   ├── store.js          # Redux store configuration
│   ├── venueSlice.js     # Venue state management
│   ├── avSlice.js        # Audio-visual state management
│   ├── mealsSlice.js     # Meals state management
│   └── *.css             # Component stylesheets
├── package.json          # Dependencies and scripts
└── README.md            # Project documentation
```

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint for code quality
- `npm run deploy` - Deploy to GitHub Pages

## 🎨 Key Components

### State Management

The application uses Redux Toolkit for efficient state management across three main slices:

- **Venue Slice**: Manages venue selections and quantities
- **AV Slice**: Handles audio-visual equipment selections
- **Meals Slice**: Controls meal planning and attendee counts

### Responsive Design

- Modern, clean interface optimized for desktop and tablet use
- Intuitive navigation with clear visual hierarchy
- Interactive elements with hover states and feedback

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 About BudgetEase Solutions

Welcome to BudgetEase Solutions, your trusted partner in simplifying budget management and financial solutions. At BudgetEase, we understand the importance of effective budget planning and strive to provide intuitive, user-friendly solutions to meet the diverse needs of our clients.

With a commitment to efficiency and innovation, we empower individuals and businesses to take control of their finances and achieve their goals with ease.

## 📞 Support

For support or questions about this project, please open an issue on GitHub or contact the development team.

---

**Built with ❤️ by BudgetEase Solutions**
