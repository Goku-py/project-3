# SmartSpend

<div align="center">
  
![SmartSpend Logo](https://via.placeholder.com/150)

**A financial tracking web application designed specifically for users in India**

</div>

## 📖 Overview

SmartSpend empowers individuals to manage their income, expenses, and savings effectively. With features like receipt uploads via camera, multilingual support, and an AI chatbot for personalized financial tips, SmartSpend is designed to make financial tracking accessible and user-friendly.

### Key Features

- **Expense/Income Tracking**: Add, edit, and delete entries with categories (e.g., salary, rent, groceries)
- **Receipt Upload**: Capture receipts via device camera or file upload
- **Multilingual Support**: Switch between Hindi, English, Telugu, Tamil, and Odia
- **AI Chatbot**: Get personalized financial advice based on spending patterns
- **Visual Analytics**: Interactive dashboard with charts and progress bars
- **Dark/Light Mode**: Toggle between color schemes for comfortable viewing
- **Accessibility**: High-contrast colors, keyboard navigation, screen reader support

## 🛠️ Tech Stack

- **Frontend**: React + Next.js
- **UI Library**: Tailwind CSS + ShadCN
- **Backend**: Supabase (BaaS)
- **Deployment**: Vercel

## 📱 Screenshots

<div align="center">
  <img src="https://via.placeholder.com/250x150" alt="Dashboard" width="30%">
  <img src="https://via.placeholder.com/250x150" alt="Expense Tracking" width="30%">
  <img src="https://via.placeholder.com/250x150" alt="AI Chatbot" width="30%">
</div>

## 💻 Local Development

### Prerequisites

- Node.js (v18+)
- npm or yarn
- Git
- Supabase CLI

### Setup Instructions

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/SmartSpend.git
   cd SmartSpend
   ```

2. Install dependencies
   ```bash
   npm install
   # or
   yarn install
   ```

3. Configure environment variables
   - Create a `.env.local` file in the root directory
   - Add the following variables:
     ```
     NEXT_PUBLIC_SUPABASE_URL=your-supabase-url
     NEXT_PUBLIC_SUPABASE_ANON_KEY=your-supabase-anon-key
     OPENAI_API_KEY=your-openai-api-key
     ```

4. Run the development server
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## 🚀 Deployment

The app is configured for automatic deployment on Vercel:

1. Fork this repository
2. Connect to Vercel
3. Set up environment variables
4. Deploy!

## 🔐 Authentication

- Secure user authentication using Supabase Auth
- Email/password and OAuth (Google, GitHub) options
- Role-based access control (admin vs. regular user)
- Session management with JWT tokens

## 🌐 User Flow

1. **Landing Page**: Clean, responsive landing with login/signup option
2. **Authentication**: Log in or sign up using email/password or OAuth
3. **Dashboard**: View financial analytics through charts and progress bars
4. **Add Entry**: Log income/expense with category and optional receipt upload
5. **Language**: Toggle between supported languages in settings
6. **Chatbot**: Ask for financial advice through the AI assistant
7. **Theme**: Switch between dark and light modes

## 📐 Design Guidelines

- **Typography**: Sans-serif fonts (Roboto, Inter) for readability
- **Colors**:
  - Light mode: Soft pastels (light blue, white, gray)
  - Dark mode: Dark gray/navy with vibrant accents
- **Icons**: Flat, minimalistic for consistency
- **Accessibility**: High-contrast, keyboard navigation, ARIA labels

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Contact

Project Link: [https://github.com/your-username/SmartSpend](https://github.com/your-username/SmartSpend)
