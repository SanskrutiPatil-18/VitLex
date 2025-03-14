# VitaLex: Mental Health Counseling Chatbot

VitaLex is a mental health counseling chatbot designed to provide users with a safe, empathetic, and confidential space to discuss their concerns. Developed as part of the IBM SkillsBuild Maharashtra State-Level Hackathon, VitaLex leverages Artificial Intelligence, Natural Language Processing (NLP), and IBM Cloud services to deliver real-time mental health support.

---

## Project Overview

**Objective:**
To create a chatbot that offers mental health support to individuals by providing:
- Emotional assistance
- Resources for mental well-being
- General guidance

**Key Features:**
- Personalized responses based on user input.
- Secure and confidential user interaction.
- Cloud-based deployment for scalability and accessibility.

**Hackathon Evaluation Criteria Addressed:**
1. **Innovative Idea:** VitaLex focuses on bridging the gap in mental health support using AI-powered technology.
2. **Usage of IBM Cloud Platform:** Deployed on IBM Cloud, utilizing Watson services for NLP and sentiment analysis.
3. **Societal Benefits:** Supports mental well-being, helping users manage stress, anxiety, and other mental health challenges.
4. **Future Scope:** Expandable to support multi-language communication and integrate with healthcare professionals.

---

## Technology Stack

**Frontend:**
- HTML, CSS, JavaScript (User interface for chatbot interaction)

**AI/ML:**
- IBM Watson Natural Language Understanding (NLP and sentiment analysis)
- Pre-trained machine learning models for enhanced response generation

**Cloud:**
- IBM Cloud for deployment and hosting

---

## Installation and Setup

### Prerequisites
- IBM Cloud account with access to Watson services
- Basic knowledge of web development

### Steps to Run the Project Locally

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/username/vitalex.git
   cd vitalex
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set Up IBM Cloud Services:**
   - Sign up or log in to [IBM Cloud](https://www.ibm.com/cloud).
   - Create an instance of Watson Natural Language Understanding.
   - Retrieve API credentials (API Key and Endpoint).
   - Update the `.env` file with your credentials:
     ```
     IBM_API_KEY=your_api_key
     IBM_ENDPOINT=your_endpoint
     ```

4. **Run the Application:**
   ```bash
   flask run
   ```

5. **Access the Application:**
   Open your browser and navigate to `http://127.0.0.1:5000`.

---

## Deployment on IBM Cloud

1. **Create a Cloud Foundry App:**
   - Log in to IBM Cloud and navigate to the Cloud Foundry dashboard.
   - Create a new app and link it to your Git repository.

2. **Push the Application:**
   ```bash
   ibmcloud cf push
   ```

3. **Access the Application:**
   The deployed app will be available at the URL generated by IBM Cloud.

---

## Future Enhancements
- Integration with video or voice-based communication.
- Expansion of the chatbot knowledge base to include more mental health topics.
- Multi-language support for broader accessibility.
- Integration with healthcare professionals for advanced guidance.

---

## Contributors
- **Sanskruti Patil**:  Chatbot Development
- **Vaishnavi Pokale**: Frontend Development, Presentation

---

## Acknowledgments
- IBM SkillsBuild Maharashtra Hackathon organizers
- Mentors and judges for their valuable guidance
- IBM Watson for providing AI and cloud services
