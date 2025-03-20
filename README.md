# EduUniDAO-3.0

A Web3 University platform powered by DAO governance where companies can offer authentic courses, and users only need 1 DAO token to participate.

## Overview

EduUniDAO-3.0 is a decentralized education platform that combines Web3 technologies with learning management systems, offering both traditional web interfaces and immersive VR experiences. The platform is governed by a DAO (Decentralized Autonomous Organization) that enables community-driven decision making through proposals and voting.

## Key Features

- **DAO Governance**: Create, view, and vote on proposals that shape the direction of the platform
- **Dual LMS Experience**: Choose between traditional web interfaces or immersive VR learning
- **Course Marketplace**: Browse, purchase, and complete courses from various providers
- **Web3 Authentication**: Connect with crypto wallets and verify identity through AnonAadhaar
- **Workshop System**: Participate in specialized workshops with trending analytics
- **Teacher Panel**: Tools for educators to create and manage course content
- **Rewards System**: Incentives for learning achievements and contributions

## Tech Stack

- **Frontend**: Next.js, React, TypeScript, Tailwind CSS
- **Web3 Integration**: Thirdweb SDK, Ethers.js, Wagmi
- **Authentication**: AnonAadhaar for anonymous identity verification
- **UI Components**: Shadcn UI, Radix UI primitives
- **Animations**: Framer Motion, Nivo, Recharts
- **3D/VR**: Spline, Cobe for globe visualization

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Application Structure

- `/app` - Next.js App Router pages and layouts
- `/components` - Reusable React components
  - `/ui` - Base UI components
  - `/landing` - Landing page components
  - `/lms` - Learning management system components
  - `/thirdweb` - Web3 integration components
  - `/magicui` - Special effects and animations
- `/lib` - Utility functions and helpers
- `/public` - Static assets

## DAO Governance

The platform is governed by a DAO where token holders can:
- Submit proposals for platform changes
- Vote on active proposals
- Execute approved proposals

Connect your wallet through the interface to participate in governance activities.

## Learning Experience

Users can access courses through:
1. Web-based LMS - Traditional browser-based learning interface
2. VR LMS - Immersive virtual reality learning experience

## Connecting Your Wallet

To fully participate in the platform:
1. Click "Enroll now!" on the landing page
2. Connect your wallet using our Web3 integration
3. You'll gain access to courses, workshops, and governance features

