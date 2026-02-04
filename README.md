# INFO 490/491 Capstone: CyberAware

**Team Innov8 – Retired**  
Alani Gayles, Logan Hosoda, Justin Le, Sunghee Park, Jayden Set  

**Team Hash Outs**  
Tristan Khieu, Justin Mai, Megan Pham, Alex Han, Ryan Louie  

---

## About

CyberAware is an application designed to help older adults of all levels of technological literacy improve their knowledge of cybersecurity. The platform provides a safe online community along with accessible educational resources to help users recognize scams, understand online threats, and build confidence navigating the digital world.

---

## Features

- **Video Modules** with captions and quizzes to test user comprehension  
- **AI Chatbot Scam Detection** that allows users to copy/paste an email or text to detect the likelihood of a scam  
- **Social Forums** to keep the community updated about recent scams and cyber attacks  
- **Become a Cyber Guardian** certification pathway to reinforce learning  
- **Live Updates** of common scams and cybersecurity threats  

---

## Scam Detection System

The AI Scam Detection feature allows users to paste suspicious emails or messages into the application. The system analyzes language patterns commonly found in phishing and scam attempts and provides a likelihood score along with an explanation to help users understand potential risks.

This tool is designed to promote awareness and learning rather than replace professional cybersecurity tools.

---

## Repository Structure

Below is an overview of how the codebase is organized:

```
/public          # Static assets and HTML template
/src
  /components    # Reusable React UI components
  /pages         # Main page-level views and routes
  /services      # Firebase configuration and external service logic
  /assets        # Images, icons, and media used in the app
firebase.json    # Firebase hosting configuration
package.json     # Project dependencies and scripts
```

This structure separates presentation logic, application views, and backend service integrations to keep the project modular and maintainable.

---

# Getting Started

## Requirements

Please install the following before running CyberAware:

- Node.js 16+  
- npm or yarn  
- Firebase CLI  

---

## Environment Variables

This project uses Firebase services. If configuration values are not already included in the repository, create a `.env` file in the root directory and add:

```
REACT_APP_FIREBASE_API_KEY=your_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
REACT_APP_FIREBASE_PROJECT_ID=your_project_id
REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
REACT_APP_FIREBASE_APP_ID=your_app_id
```

These values can be found in your Firebase project settings.

---

## Installation

1. Clone the repository:

```
git clone https://github.com/TristanK117/info490_capstone.git
```

2. Install dependencies:

```
npm install
```

3. Run the application locally:

```
npm start
```

Open **http://localhost:3000** in your browser.

---

## Production Build

To create an optimized production version of the app:

```
npm run build
```

This generates a `/build` folder containing static files used for deployment.

---

## Deployment

1. Install Firebase tools:

```
npm install -g firebase-tools
```

2. Log in to Firebase:

```
firebase login
```

3. Initialize Firebase (if not already configured):

```
firebase init
```

4. Deploy the app:

```
firebase deploy
```

---

## Contributing

We welcome contributions to improve CyberAware. Please follow these guidelines:

1. Fork the repository  
2. Create a feature branch:

```
git checkout -b feature/your-feature-name
```

3. Make your changes and ensure the app runs locally  
4. Write clear, descriptive commit messages  
5. Push your branch and open a Pull Request  

Pull Requests should include:
- A clear description of what was changed  
- Why the change was necessary  
- Screenshots for UI updates (if applicable)  

For major changes or feature ideas, please open an issue first to discuss.

---

## License

This project is licensed under the iSchool
