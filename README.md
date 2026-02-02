# Trivia App 🎉

An interactive React trivia application that dynamically fetches questions from the Open Trivia Database API. This project demonstrates modern React development practices, API integration, and deployment to Vercel.

## 🌐 Live Demo

[View Live Application](https://vercel-trivia-self.vercel.app/)

## ✨ Features

- **Dynamic Question Fetching**: Real-time trivia questions from the Open Trivia Database API
- **Interactive UI**: Toggle between showing and hiding answers for each question
- **Responsive Design**: Modern layout built with React Bootstrap for all screen sizes
- **Refresh Functionality**: Load new sets of trivia questions with a single click
- **Clean Architecture**: Well-organized React component structure

## 🛠️ Tech Stack

- **Frontend**: React, Vite
- **UI Framework**: React Bootstrap
- **API**: Open Trivia Database API
- **Deployment**: Vercel
- **Package Manager**: npm

## 📦 Installation

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/pperez90-lab/vercel-trivia.git
cd vercel-trivia
```

2. **Install dependencies**

```bash
npm install
```

3. **Run the development server**

```bash
npm run dev
```

4. **Open your browser**

Navigate to `http://localhost:5173` (or the port shown in your terminal)

## 🚀 Deployment

This project is deployed on Vercel. To deploy your own instance:

1. Fork this repository
2. Create a [Vercel account](https://vercel.com/)
3. Import your GitHub repository to Vercel
4. Vercel will automatically detect the Vite configuration and deploy

## 📁 Project Structure

```
vercel-trivia/
├── src/
│   ├── components/      # React components
│   ├── App.jsx          # Main app component
│   └── main.jsx         # App entry point
├── public/              # Static assets
├── .github/
│   └── workflows/       # GitHub Actions (optional)
├── index.html           # HTML entry point
├── package.json         # Project dependencies
├── vite.config.js       # Vite configuration
└── README.md
```

## 🎯 Usage

1. **View Questions**: The app loads with a set of trivia questions automatically
2. **Show/Hide Answers**: Click on individual questions to reveal or hide answers
3. **Refresh Questions**: Click the "Refresh Questions" button to load a new set
4. **Enjoy**: Test your knowledge across various categories!

## 🔄 API Integration

This project uses the [Open Trivia Database API](https://opentdb.com/), a free JSON API for trivia questions. No API key required!

## 🚧 Future Enhancements

- [ ] Category selection filter
- [ ] Difficulty level selection
- [ ] Score tracking and leaderboard
- [ ] Timer for each question
- [ ] Question history
- [ ] Social sharing functionality

## 📝 License

This project is licensed under the MIT License.

## 👤 Author

**Peter Perez**

- GitHub: [@pperez90-lab](https://github.com/pperez90-lab)
- Portfolio: [vercel-trivia-self.vercel.app](https://vercel-trivia-self.vercel.app/)

## 🙏 Acknowledgments

- Built as part of Coding Temple's Full Stack Development program
- [Open Trivia Database](https://opentdb.com/) for providing the trivia API
- [React Bootstrap](https://react-bootstrap.github.io/) for UI components
- [Vercel](https://vercel.com/) for hosting and deployment

---

**Note**: This is a portfolio/educational project demonstrating API integration, React development, and Vercel deployment.
