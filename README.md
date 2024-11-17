# EmailService

## Overview
The **EmailService** is responsible for managing email notifications for the eCommerce platform. It ensures timely and reliable delivery of emails, including order confirmations, registration acknowledgments, and promotional offers.

---

## Features
- Sending transactional emails (e.g., order confirmations, password resets)
- Integration with Kafka for event-driven notifications
- Support for third-party email platforms like Amazon SES
- Configurable email templates

---

## Technologies Used
- **Java 8**
- **Spring Boot**
- **Kafka** (Message Broker)
- **Amazon SES** (Third-Party Email Service)
- **Docker** (Containerization)

---

## Installation

### Prerequisites
1. Install:
   - Java 8 or higher
   - Kafka
   - Amazon SES (credentials required)
2. Clone the repository:
   ```bash
   git clone https://github.com/username/EmailServiceNew.git
   cd EmailServiceNew
