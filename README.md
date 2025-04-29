# Swasth AI Healthcare Chatbot : AI diagnosis And Medical llm fusion model 🏥

A modern, AI-powered healthcare assistant built with React and Supabase that provides personalized medical guidance, medicine analysis, and vital monitoring.

View the webApp demo : https://statuesque-gecko-2ee8ea.netlify.app

## Features 🌟

- **AI-Powered Chat Interface**
  - Natural language processing for medical queries
  - Context-aware responses with medical knowledge
  - Support for image uploads (prescriptions, reports)

- **Medicine Identifier**
  - Upload medicine images for instant analysis
  - Get detailed medication information
  - Find nearby pharmacies with stock availability
  - Price comparison across stores

- **Vitals Monitor**
  - Real-time tracking of vital signs
  - Heart rate monitoring
  - Blood pressure tracking
  - Body temperature
  - Oxygen saturation levels
  - Respiration rate
  - Hydration levels

- **Medical Records**
  - Upload and manage medical documents
  - Track health history
  - View test results and reports
  - Timeline of medical events

- **Accessibility Features**
  - Multi-language support (English, Hindi, Punjabi, Tamil)
  - Voice commands
  - Dark mode support
  - Responsive design

## Tech Stack 💻

- **Frontend**
  - React 18
  - TypeScript
  - Tailwind CSS
  - Framer Motion
  - Lucide Icons

- **Backend**
  - Supabase
  - Edge Functions
  - OpenAI Integration

- **Authentication**
  - ABHA ID Integration
  - Aadhaar-based verification

## Getting Started 🚀

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/swasth-ai.git
   cd swasth-ai
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   ```env
   VITE_SUPABASE_URL=your_supabase_url
   VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
   OPENAI_API_KEY=your_openai_api_key
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

## Project Structure 📁

```
src/
├── components/
│   ├── auth/         # Authentication components
│   ├── chat/         # Chat interface components
│   ├── dashboard/    # Dashboard and analytics
│   ├── medical/      # Medical tools and monitors
│   ├── medicine/     # Medicine analysis features
│   ├── navigation/   # Navigation components
│   ├── upload/       # File upload components
│   └── voice/        # Voice control features
├── stores/           # Zustand state management
├── lib/              # Utility functions
└── types/           # TypeScript definitions
```

## Contributing 🤝

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Support 💪

If you like this project, please give it a ⭐️!
