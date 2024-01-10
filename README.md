# 🚀 Project: E-Commerce Search Service 🛍️

## Business Requirement:

Create a web service that supports website search operations for a fictional e-commerce platform. Users should be able to search for products based on keywords and retrieve relevant results quickly. The system should be scalable, efficient, and user-friendly.

## Technical Specifications:

### 1. Technology Stack:
   - Use **Spring Boot** as the primary framework for building the service.

### 2. Search Functionality:
   - Implement a search endpoint that accepts user queries and returns relevant product results.
   - Utilize a search engine or indexing mechanism (e.g., **Elasticsearch**) to enhance search performance.
   - Implement **fuzzy search** and **full-text search** for improved accuracy.

### 3. Data Model:
   - Define a data model for storing product information, including attributes like name, description, quantity, and price.

### 4. API Design:
   - Design **RESTful APIs** for search functionality, including endpoints for searching products and retrieving detailed product information.
   - Explore the API documentation using **Swagger UI**: [Swagger Documentation](http://localhost:8080/swagger-ui/index.html/)

### 5. Documentation:
   - Create comprehensive documentation for the APIs, including usage examples and response formats.
   - Document the database schema and any external dependencies.

## Implementation Details:

- **Elasticsearch Integration:**
   - Elasticsearch is used both as a database and for searching.
   - Fuzzy search and full-text search have been implemented for enhanced search capabilities.

- **API Demonstration:**
   - Utilized **Postman** to expose endpoints and demonstrate search mechanisms.
   - Access and explore the API using **Swagger UI** at [Swagger Documentation](http://localhost:8080/swagger-ui/index.html/)

### 📹 Small Demonstration:
   - Check out a brief video demonstration of the E-Commerce Search Service [here](
https://github.com/Ayush20021989/Staples_Intern_Task2/assets/100331783/4fbebe94-2e35-4707-b5a3-44c1a173336a).


## 🏃‍♀️ Running the Application:

1. Clone the repository.
2. Change the `application.properties` file:
    ```
    spring.data.elasticsearch.cluster-name=your_elasticsearch_cluster_name
    spring.data.elasticsearch.cluster-nodes=http://your_elasticsearch_node:9200
    ```
    Replace `your_elasticsearch_cluster_name` and `your_elasticsearch_node` with your Elasticsearch details.

3. Run the application and access the search service.

## 🛠️ Suggestions:
Feel free to explore and suggest improvements to enhance the scalability, efficiency, or user-friendliness of the system. Contributions are welcome! 🤝

## 📚 Additional Information:
For detailed information on the API usage, please refer to the project documentation.

Happy coding! 🚀🔍🛒
