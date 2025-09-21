# Smart Shop

> Empowering small businesses with intelligent tools for sales, stock, and communication.

---

## Features

- **Sales Tracking** – Record daily sales with ease  
- **Stock Management** – Keep track of inventory in real time  
- **AI-Assisted Pricing** – Get intelligent pricing suggestions with LLaMA  
- **Speech-to-Text Recognition** – Log sales and lists hands-free with Google Speech  
- **Work Ticketing** – Create structured delivery and order tickets from natural language input  
- **Push Notifications** – Stay updated with instant alerts for new orders, low stock, and customer messages  
- **Chat & Communication** – Built-in private and group messaging  

---

## Built With

- [React Native](https://reactnative.dev/) + [Expo](https://expo.dev/) – Mobile app framework  
- [Firebase](https://firebase.google.com/) – Authentication, Firestore, Cloud Functions, Push Notifications  
- [Gifted Chat](https://github.com/FaridSafi/react-native-gifted-chat) – Chat interface  
- [LLaMA via Ollama](https://ollama.ai/) – AI-powered features (pricing, NLP parsing, assistant features)  
- [Google Cloud Speech-to-Text](https://cloud.google.com/speech-to-text) – Voice recognition  
- [OCR (Tesseract.js / Expo Camera)](https://github.com/naptha/tesseract.js) – Handwritten item detection & scanning  
- [React Navigation](https://reactnavigation.org/) – App navigation  
- [shadcn/ui](https://ui.shadcn.com/) + [Tailwind](https://tailwindcss.com/) – UI styling  

---

## Installation

Follow these steps to set up Smart Shop on your local machine:

### 1. Clone the repository
```bash
git clone https://github.com/your-username/smart-shop.git
cd smart-shop
```
### 2. Install dependencies

Make sure you have Node.js installed, then run
```bash 
npm install
```
### 3. Configure Firebase

Create a Firebase project in the Firebase Console 
```bash
FIREBASE_API_KEY=your_api_key
FIREBASE_AUTH_DOMAIN=your_auth_domain
FIREBASE_PROJECT_ID=your_project_id
```
---
### 4. Setup AI Capabilities
- **LLaMA (via Ollama)** -
Install Ollama and pull the model:
```bash
ollama pull llama3
```
- **Speech-to-Text (Google Cloud)** -
Point to your service account credentials:
```bash
GOOGLE_APPLICATION_CREDENTIALS=./credentials.json
```
### 5. Run the app
```bash
 npx expo start
```
---
## Usage
Smart Shop is designed to simplify business operations for small shops.  

**Real use cases:**

- **Sales Tracking** – Record daily sales with ease  
- **Stock Management** – Keep track of inventory in real time  
- **AI-Assisted Pricing** – Get intelligent pricing suggestions with LLaMA  
- **Speech-to-Text Recognition** – Log sales and lists hands-free with Google Speech  
- **Work Ticketing** – Create structured delivery and order tickets from natural language input  
- **Push Notifications** – Stay updated with instant alerts for new orders, low stock, and customer messages  
- **Chat & Communication** – Built-in private and group messaging  
*(Screenshots coming soon — see `assets/screenshots/` for placeholders)*

---
## Contributing
We welcome contributions to improve Smart Shop.
For a small team setup:

1. Fork the repository

2. Create a new branch (git checkout -b feature-name)

3. Commit your changes (git commit -m "Add new feature")

4. Push to the branch (git push origin feature-name)

5. Open a Pull Request
    
---
## Credits
Frank Mutegi – Creator & Lead Developer

---
## License
This project is licensed under the MIT License – see the LICENSE
