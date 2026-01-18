# Aegis-Q

Aegis-Q: Sovereign Cyber-Resilience Framework
Project Overview
Aegis-Q is a 2026-ready autonomous cyber-resilience dashboard designed to protect critical national infrastructure such as Healthcare, Agriculture, and Urban Systems. Unlike traditional reactive security, Aegis-Q focuses on Resilience—the ability to identify threats, isolate breaches using Post-Quantum Cryptography, and self-heal via the Lazarus Protocol.

Key Features
1. Neural Sentinel (AI Ensemble): Real-time anomaly detection using Isolation Forest logic to detect Zero-Day attacks.
2. Lattice Barrier (PQC): Quantum-safe data protection using NIST FIPS 203 (Kyber-768) standards.
3. Lazarus Protocol: Automated system re-imaging to restore integrity in seconds (Self-Healing).
4. Ghost Ledger: An immutable audit trail powered by private blockchain and SHA-256 hashing for CIRCIA 2026 compliance.

Tech Stack
1. Frontend: React.js, Tailwind CSS (for the Cyber-Hacker UI aesthetic)
2. Icons: Lucide-React
3. State Management: React Hooks
4. Deployment: Vite (Build Tool)

Setup and Installation
Follow these steps to run the Aegis-Q Dashboard locally on your machine.

1. Prerequisites
Node.js (v18 or higher)
npm (v9 or higher)

Installation Steps
1. Clone the repository: git clone <your-repo-link> cd aegis-q-dashboard
2. Install dependencies: npm install
3. Initialize Tailwind CSS: npx tailwindcss init -p
4. Run the development server: npm run dev
5. Open your browser: Navigate to http://localhost:5173

Environment Variables and Credentials
Environment Variables: This prototype runs entirely client-side for simulation purposes. No .env file is required for the basic dashboard.

Test Login Credentials:

Username: admin_aegis
Password: quantum_2026 (Note: This is a simulation credential for UI bypass)

Basic Error Handling
1. Port Conflict: If 5173 is in use, Vite will automatically assign a different port. Check the terminal output.
2. Missing Dependencies: If icons do not appear, run npm install lucide-react again.
3. Tailwind Styles Not Loading: Ensure tailwind.config.js is in the root directory and contains the correct content paths.

Security Confirmation
1. No Secrets: We confirm that no API keys, private tokens, or sensitive credentials have been committed to this repository.
2. Integrity: All security protocols displayed (PQC, Blockchain) are simulated to demonstrate the architectural logic.

