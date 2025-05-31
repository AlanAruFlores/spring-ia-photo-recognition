# Spring IA Azure Photo Recognition

A Spring Boot application that integrates with Azure's Computer Vision services for photo recognition and analysis.

## Overview

This project demonstrates the integration of Spring Boot with Azure's Computer Vision services to perform image analysis and recognition tasks. It provides a RESTful API for processing and analyzing images using Azure's AI capabilities.

## Prerequisites

- Java 17 or higher
- Maven 3.6 or higher
- Azure subscription with Computer Vision service enabled
- Azure Computer Vision API key and endpoint

## Technology Stack

- Spring Boot 3.5.0
- Spring Web
- Spring Boot DevTools
- Lombok
- Azure Computer Vision SDK
- Maven

## Project Structure

```
demo/
├── src/
│   ├── main/
│   │   ├── java/        # Java source files
│   │   └── resources/   # Application properties and resources
│   └── test/            # Test files
├── pom.xml              # Maven configuration
└── README.md           # Project documentation
```

## Getting Started

1. Clone the repository:
   ```bash
   git clone [repository-url]
   cd spring-ia-photo-recognition
   ```

2. Configure Azure credentials:
   - Create an Azure Computer Vision resource in your Azure portal
   - Get your API key and endpoint URL
   - Add these credentials to your application.properties or environment variables

3. Build the project:
   ```bash
   mvn clean install
   ```

4. Run the application:
   ```bash
   mvn spring-boot:run
   ```

The application will start on `http://localhost:8080` by default.

## Features

- Image analysis and recognition
- RESTful API endpoints for image processing
- Integration with Azure Computer Vision services
- Spring Boot auto-configuration
- Development tools for hot reloading

## Development

The project uses Spring Boot DevTools for development convenience, providing features like:
- Automatic application restart when files change
- Live reload for web applications
- Enhanced development experience

## Testing

Run the test suite using Maven:
```bash
mvn test
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Spring Boot team for the excellent framework
- Microsoft Azure for the Computer Vision services
- All contributors who have helped shape this project 