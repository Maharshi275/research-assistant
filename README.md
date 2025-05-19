
# Smart Research Assistant

Smart Research Assistant — an AI-powered productivity tool built using Spring Boot, Spring Security, and Gemini API.

This tool is designed to assist researchers, students, and knowledge professionals by enabling intelligent summarization and note-taking directly from web content.
A key component of this solution is a custom-built browser extension that allows users to select any text on a webpage and instantly receive AI-generated summaries.

## Highlights of the Project:

Backend built with Spring Boot and RESTful architecture
Integrated Gemini API for advanced natural language understanding and summarization
Secure authentication and role-based access using Spring Security
Custom browser extension for real-time interaction with web content
Organized note management for enhanced research efficiency

The goal is to create a seamless experience for anyone who regularly consumes large amounts of information online and needs a faster way to process and organize it.


## Features

- 📑 AI-based content summarization using Gemini API
- 🌐 RESTful backend with Spring Boot
- 🧩 Modular and extendable project architecture
- 💬 Scalable backend ready for Chrome Extension integration

## Tech Stack

- Backend: Java 17, Spring Boot 3.4.3
- AI Integration: Google Gemini API (planned)
- Build Tool: Maven
- IDE: Spring Tool Suite / IntelliJ IDEA

---

## Project Structure

```
reserch-assistant/
├── .mvn/                          # Maven wrapper configuration
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/research/assistant/
│   │   │       └── ReserchAssistantApplication.java  # Spring Boot main app
│   │   └── resources/
│   │       └── application.properties                # App configuration
│   └── test/
│       └── java/com/research/assistant/
│           └── ReserchAssistantApplicationTests.java # Sample test
├── pom.xml                        # Maven project descriptor
├── mvnw, mvnw.cmd                 # Maven wrapper scripts
└── .gitignore, HELP.md           # Misc project files
```

---

## Getting Started

### Prerequisites

- JDK 17 or higher
- Maven 3.8+
- Internet connection (for dependency downloads)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Maharshi275/research-assistant.git
   cd reserch-assistant
   ```

2. Build the project:

   ```bash
   ./mvnw clean install
   ```

3. Run the application:

   ```bash
   ./mvnw spring-boot:run
   ```

   The backend service will start on: `http://localhost:8080`

---

## Configuration

Modify the `application.properties` file for custom configurations:

```properties
spring.application.name=reserch-assistant
```

> Optionally add Gemini API keys and other configs when integrating AI summarization.

---

## Future Plans

- 🌐 Chrome Extension for content capture
- 📘 Gemini AI integration for real-time summarization
- 🗃️ MongoDB/MySQL support for storing summaries
- 🧠 NLP-based content tagging

---

## Author

Maharshi Pandya

GitHub: [@Maharshi275](https://github.com/Maharshi275)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
