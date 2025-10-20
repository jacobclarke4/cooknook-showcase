# Cooknook — System Architecture & Overview

Cooknook is a **production-grade cooking recipe platform** designed to make creating, sharing, and organizing recipes easier and more collaborative.  
This repository showcases the **system design**, **infrastructure**, and **core architectural principles** behind the Cooknook app.

---

## Overview

Cooknook allows users to:
- Create and save custom recipes.
- View and edit others’ recipes collaboratively.
- Share recipes easily via URL or native share actions.
- Manage premium subscriptions via Stripe.

The platform prioritizes **security**, **scalability**, and **real-time collaboration**, leveraging Firebase, AWS, and Next.js.

---

## System Architecture

![Cooknook System Diagram](./docs/system-design-diagram.png)

### Key Components

#### **Frontend (Next.js + React)**
- TypeScript-based, hosted on AWS Amplify.
- Optimized for accessibility and responsive design.
- Uses server and client components for performance.

#### **Backend (Node.js + Firebase Cloud Functions)**
- Handles authentication, payments, and image processing.
- Integrates OpenAI for recipe ingredient suggestions.
- Includes API middleware for input sanitization and validation.

#### **Data Layer**
- **Firestore**: NoSQL database for users, recipes, and relationships.
- **Firebase Storage**: User images, recipe images, and media assets.

#### **Payments**
- **Stripe** for subscription management and customer portal creation.
- Webhooks for subscription status changes.

#### **Infrastructure**
- **AWS Amplify** for frontend hosting.
- **AWS Route 53** for DNS routing.
- **GitHub Actions CI/CD** for build, test, and deployment automation.

#### **Monitoring & Logging**
- **AWS CloudWatch** for frontend metrics/logs.
- **Google Cloud Monitoring** for backend logs and invocations.

---

## Security & Middleware

- Authentication: Firebase Auth (ID Token verification)
- API Gateway: Input sanitization and validation
- HTTPS enforced on all layers
- Minimal reads/writes with Firestore triggers and client-side caching

---

## Technologies Used

| Category | Technology |
|-----------|-------------|
| Frontend | Next.js, React, TypeScript |
| Backend | Node.js, Firebase Functions |
| Database | Firestore, Firebase Storage |
| Hosting | AWS Amplify, Route 53 |
| CI/CD | GitHub Actions |
| Monitoring | AWS CloudWatch, Google Cloud Monitoring |
| Payments | Stripe |
| AI Integration | OpenAI API |

---

## 👨‍🍳 Author
**Jacob Clarke**  
Founder & Developer of Cooknook  
[LinkedIn](https://linkedin.com/in/jacobclarke) • [Website](https://yourportfolio.com)

---
