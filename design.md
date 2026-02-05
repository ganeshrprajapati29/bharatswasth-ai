# BharatSwasth AI - System Design

## 1. Architecture Overview
The platform follows a cloud-native microservices architecture deployed on Google Cloud.

Clients:
- Android App
- Web App
- SMS/IVR Gateway

Backend:
- API Gateway
- Auth Service
- AI Orchestration Service
- Notification Service
- Analytics Service

AI Layer:
- Vertex AI LLM
- Speech-to-Text API
- Translation API

Storage:
- Firestore
- Cloud SQL
- BigQuery

## 2. High-Level Flow
1. User submits voice/text input.
2. Speech converted to text.
3. Language detected & translated.
4. LLM analyzes symptoms.
5. Risk scoring performed.
6. Guidance generated.
7. Location service finds nearby clinics.
8. Notifications sent.

## 3. Tech Stack
- Frontend: Flutter / React
- Backend: Node.js / Python FastAPI
- Cloud: Google Cloud Platform
- AI: Vertex AI, Gemini models
- Data: Firestore, BigQuery
- Messaging: Twilio / Gupshup SMS

## 4. Security Design
- OAuth2 authentication.
- Role-based access.
- TLS encryption.
- HIPAA-like privacy controls.
- Audit logs.

## 5. Scalability
- Cloud Run auto-scaling.
- Pub/Sub for async tasks.
- CDN for static assets.

## 6. Offline Strategy
- Local caching in mobile app.
- Sync when network available.

## 7. Monitoring
- Cloud Logging & Monitoring dashboards.
- Alerting for anomalies.

## 8. Future Enhancements
- Wearable integrations.
- Predictive outbreak analytics.
- Telemedicine video calls.
- Government dashboard APIs.

