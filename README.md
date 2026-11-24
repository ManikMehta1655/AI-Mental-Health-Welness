
# MindSphere AI 🧠

### AI-Powered Mental Wellness & Emotional Support Platform

![AI Powered](https://img.shields.io/badge/AI-Powered-blue)
![Blockchain](https://img.shields.io/badge/Blockchain-Sonic-purple)
![TypeScript](https://img.shields.io/badge/TypeScript-Enabled-blue)
![Solidity](https://img.shields.io/badge/Solidity-Smart_Contracts-black)
![License](https://img.shields.io/badge/License-MIT-green)

## 📖 About the Project

MindSphere AI is an intelligent mental wellness platform
that combines Artificial Intelligence, blockchain technology,
and interactive wellness activities to provide personalized
emotional support.

The project focuses on creating a secure, accessible,
and user-friendly digital environment where individuals
can express their emotions, manage stress, practice
mindfulness, and track their mental wellness journey.

By integrating AI-driven conversations with decentralized
technology, MindSphere AI explores innovative approaches
to digital mental wellness.

## 🎯 Project Objectives

- Provide accessible AI-powered emotional support.
- Help users manage everyday stress and anxiety.
- Encourage healthy mental wellness habits.
- Enable personalized wellness recommendations.
- Explore privacy-focused data management.
- Encourage mindfulness through interactive activities.
- Integrate blockchain-based achievement tracking.

## ✨ Key Features

### 🤖 Intelligent AI Assistant

- Personalized AI-powered conversations.
- Context-aware emotional support.
- Natural Language Processing (NLP).
- Adaptive responses based on user interactions.
- Emotion and stress signal identification.
- Personalized mindfulness recommendations.
- Supportive and interactive conversations.

### 🧘 Interactive Wellness Activities

MindSphere AI provides interactive activities designed
to encourage relaxation and emotional well-being.

- Guided breathing exercises.
- Interactive digital Zen garden.
- Virtual forest relaxation experiences.
- Ocean wave meditation.
- Stress management activities.
- Mindfulness exercises.

### 📊 Mental Wellness Dashboard

- Daily mood tracking.
- Emotional wellness insights.
- Session history management.
- Personal progress visualization.
- Wellness achievement tracking.
- Activity monitoring.

### 🔗 Blockchain Integration

The platform explores blockchain technology for
verifiable achievements and decentralized interactions.

- Sonic blockchain integration.
- Smart contract-based session management.
- NFT-based achievement certificates.
- Digital wellness milestones.
- Token-based participation rewards.
- Privacy-focused blockchain architecture.

Sensitive mental health information should remain
off-chain and protected through appropriate access
controls and encryption.

### 🚨 Stress Detection and Safety

The platform includes mechanisms for identifying
potential stress-related signals during conversations.

- Stress keyword identification.
- Emotional pattern analysis.
- Supportive response generation.
- Mindfulness activity suggestions.
- Recommendations to seek professional support
  when appropriate.

MindSphere AI is a wellness support tool and is not
a replacement for professional mental health care
or emergency services.

## 🛠️ Technology Stack

| Technology | Purpose |
|------------|---------|
| React.js | Frontend development |
| TypeScript | Application development |
| Node.js | Backend environment |
| Gemini API | AI-powered conversations |
| Zerepy | AI agent integration |
| Solidity | Smart contract development |
| Sonic Blockchain | Blockchain infrastructure |
| Hardhat | Smart contract deployment |
| Web3 | Decentralized interactions |

## 🏗️ System Architecture

```text
                User Interface
                      |
                      v
              MindSphere Platform
                      |
          +-----------+-----------+
          |                       |
          v                       v
     AI Assistant          Wellness Dashboard
          |                       |
          v                       v
    Emotion Analysis        Progress Tracking
          |                       |
          +-----------+-----------+
                      |
                      v
              Blockchain Layer
                      |
                      v
              Smart Contracts
```

## 💻 Technical Implementation

### AI Assistant Configuration

```typescript
interface WellnessAgentConfig {
    name: string;
    personality: string;
    specialties: string[];
    languageModel: string;
    temperature: number;
    wellnessApproach: string;
    safetyProtocol: object;
}
```

### Wellness Session Structure

```solidity
struct WellnessSession {
    uint256 sessionId;
    uint256 timestamp;
    uint256 duration;
    bool completed;
}
```

The smart contract structure is designed to avoid
directly storing sensitive emotional information
on a public blockchain.

### Stress Signal Detection

```typescript
const detectStressSignals = (message: string): boolean => {
    const stressKeywords = [
        "stress",
        "anxiety",
        "worried",
        "panic",
        "overwhelmed",
        "nervous",
        "pressure"
    ];

    return stressKeywords.some(keyword =>
        message.toLowerCase().includes(keyword)
    );
};
```

Keyword detection provides a basic indication of
potential stress and is not a clinical assessment.

## 🚀 Installation and Setup

### Prerequisites

Make sure the following tools are installed:

- Node.js
- npm
- Git
- MetaMask or a compatible Web3 wallet
- Required AI API credentials

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/mindsphere-ai.git
cd mindsphere-ai
```

### Step 2: Install Dependencies

```bash
npm install
```

### Step 3: Configure Environment Variables

```bash
cp .env.example .env
```

Add the required credentials to your `.env` file.

```env
GEMINI_API_KEY=your_api_key
ZEREPY_API_KEY=your_api_key
SONIC_PRIVATE_KEY=your_testnet_private_key
```

Never upload your `.env` file or private keys
to a public repository.

### Step 4: Deploy Smart Contracts

```bash
npx hardhat run scripts/deploy.ts --network sonic_blaze_testnet
```

### Step 5: Start the Application

```bash
npm run dev
```

Open the local development URL displayed
in your terminal.

## 📸 Project Screenshots

Add screenshots of your own running application here.

### Home Page

![Home Page](screenshots/home.png)

### AI Wellness Assistant

![AI Assistant](screenshots/assistant.png)

### Wellness Dashboard

![Dashboard](screenshots/dashboard.png)

### Mindfulness Activities

![Activities](screenshots/activities.png)

## 🔐 Security and Privacy

The project prioritizes responsible handling
of user information through the following
security design objectives:

- Secure API credential management.
- Encrypted communication.
- Privacy-focused data storage.
- Secure wallet integration.
- Smart contract security testing.
- User consent management.
- Protection of sensitive information.
- Authentication and access control.

Formal security audits and regulatory compliance
assessments are required before production use.

## 🌍 Applications

MindSphere AI can be explored in areas such as:

- Student mental wellness.
- Workplace stress management.
- Personal emotional wellness.
- Daily mindfulness routines.
- Digital wellness education.
- Personal development and habit tracking.

## 🔮 Future Enhancements

- Voice-based AI conversations.
- Multilingual support.
- Android and iOS applications.
- Advanced emotional analysis.
- Personalized meditation programs.
- Smartwatch and wearable integration.
- IoT-based relaxation environments.
- Improved wellness analytics.
- Community wellness features.
- Professional support integration.
- Enhanced blockchain security.

## 👨‍💻 Developer

**Your Name**

Computer Science Student | Software Developer |
AI and Blockchain Enthusiast

This version of MindSphere AI is maintained as a
project exploring the integration of Artificial
Intelligence, modern web development, and
blockchain technology for mental wellness.

- GitHub: https://github.com/YOUR_USERNAME
- Email: YOUR_EMAIL

## 🤝 Contributing

Contributions, suggestions, and improvements
are welcome.

Feel free to fork this repository, create a new
branch, and submit a pull request.

## 📜 License and Attribution

This project is distributed under the MIT License.

MindSphere AI is an adapted version of the
open-source Aura3.0 project.

Original copyright and license notices are
retained in the LICENSE file.

See the LICENSE file for more information.

## ⭐ Support the Project

If you find this project interesting or useful,
consider giving the repository a star.

---

<p align="center">
  <b>MindSphere AI</b><br>
  Technology for a healthier mind.<br>
  Artificial Intelligence × Mental Wellness × Blockchain
</p>

