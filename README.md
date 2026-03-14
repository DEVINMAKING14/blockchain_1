# IdeaVault — Web3 Startup Idea Protection

IdeaVault is a Web3-based platform designed to help founders, innovators, and creators **secure their startup ideas before sharing them with the world**.

Many founders hesitate to discuss their ideas openly because they fear someone might copy or steal them. IdeaVault solves this problem by creating a **cryptographic proof of idea ownership** using hashing and timestamp verification.

When a user submits an idea, the platform generates a **unique cryptographic hash** of the idea text. This hash is stored securely along with the **submission timestamp**, creating verifiable proof that the idea existed at that specific moment in time. Since only the hash is stored, the original idea content remains private and protected.

This approach ensures that even if someone later claims the same idea, the creator can **verify ownership using the original timestamp and hash record**.

## Core Features

**Idea Hashing and Proof of Ownership**
Every submitted idea is converted into a unique cryptographic hash. This ensures that the idea cannot be altered without changing its hash.

**Timestamped Records**
Each idea hash is stored with the exact date and time of submission, providing clear proof of when the idea was first registered.

**Idea Verification Tool**
Users can check whether a similar idea has already been registered by generating and comparing hashes.

**Privacy First**
The actual idea content is not publicly stored. Only the hash and timestamp are saved, ensuring that sensitive startup ideas remain confidential.

**Web3 Inspired Architecture**
The system follows decentralized verification principles to ensure transparency and trust.

## How It Works

1. A user submits their startup idea on the platform.
2. The system generates a **cryptographic hash** of the idea.
3. The hash and timestamp are stored as proof of creation.
4. The creator can later verify ownership using the same idea text.
5. Anyone can check if a particular idea has already been registered.

## Tech Stack

* Next.js
* React
* Node.js
* Cryptographic Hashing
* Web3 Principles

## Running the Project Locally

Install dependencies:

```
npm install
```

Run the development server:

```
npm run dev
```

Then open:

```
http://localhost:3000
```

The page automatically updates when you edit files inside the project.

## Vision

IdeaVault aims to become a **secure digital vault for innovation**, where creators can confidently register their ideas without fear of them being stolen.

By combining **cryptographic hashing, timestamp verification, and Web3-inspired infrastructure**, the platform provides a simple but powerful way to prove **who had the idea first**.
