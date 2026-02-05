# BharatSwasth AI - Requirements Document

## 1. Overview
BharatSwasth AI is a multilingual, AI-powered rural health assistant designed for India. 
It provides symptom checking, preventive care guidance, maternal health tracking, and 
nearby healthcare discovery via mobile and web interfaces.

## 2. Goals
- Provide accessible healthcare guidance in rural regions.
- Support Indian languages.
- Work on low bandwidth connections.
- Assist frontline health workers.
- Improve awareness of preventive care.

## 3. Target Users
- Rural citizens
- ASHA workers
- Primary Health Centers
- NGOs
- Local governments

## 4. Key Features
- Voice and text-based symptom input
- Multilingual NLP (Hindi, Marathi, Tamil, Telugu, Bengali)
- AI triage and guidance
- Clinic and hospital locator
- Appointment reminders
- Maternal & child health tracker
- Offline-first mobile experience
- Government scheme awareness

## 5. Functional Requirements

### 5.1 User Interaction
- Users can speak or type symptoms.
- System converts speech to text.
- AI provides possible conditions and guidance.
- Users receive emergency alerts if critical.
- Location-based clinic recommendations.

### 5.2 Language Support
- Must support at least 5 Indian languages.
- Auto language detection.

### 5.3 Notifications
- SMS reminders for vaccination and checkups.
- Health alerts.

### 5.4 Admin Panel
- NGO/government dashboards.
- Analytics on usage.
- Regional disease heatmaps.

## 6. Non-Functional Requirements
- Availability: 99.5%
- Scalability: handle 1M+ users.
- Data encryption at rest and in transit.
- Low-latency inference.
- Compliance with Indian data regulations.
- Accessibility for low-literacy users.

## 7. Assumptions
- Smartphone penetration in rural areas.
- Integration with telecom SMS gateways.
- Cloud infrastructure via Google Cloud.

## 8. Risks
- Data privacy concerns.
- Language model bias.
- Connectivity issues.

## 9. Success Metrics
- Active users/month.
- Reduction in unnecessary clinic visits.
- Vaccination adherence rate.
- Regional adoption growth.

