# Job Portal

A full-featured job portal web application built with Spring Boot that connects job seekers with recruiters.

## Screenshots

![1](https://github.com/user-attachments/assets/11b3a9f1-dca4-4b6e-bf24-7bed06e7c5be)
![2](https://github.com/user-attachments/assets/459a79ec-ec1d-4717-b7db-48977bd492b2)
![3](https://github.com/user-attachments/assets/17921e47-e702-470a-972a-c922af8776c3)
![4](https://github.com/user-attachments/assets/e035ebe9-42a1-4639-8038-3240ee7644ae)
![5](https://github.com/user-attachments/assets/924cb508-ceb3-453e-9155-8c4edc9bf558)

## Technology Stack

- **Backend**: Java 23, Spring Boot 3.4.2
- **Frontend**: Thymeleaf, Bootstrap 5.3.3, jQuery 3.7.1, Font Awesome
- **Database**: MySQL
- **Security**: Spring Security
- **Build Tool**: Maven

## Features

### For Job Seekers
- Create and manage profile
- Search for jobs
- Apply to job postings
- Save jobs for later
- Track application status

### For Recruiters
- Create company profile
- Post job opportunities
- Manage job listings
- Review applications
- Contact candidates

## Project Structure

- `config/` - Application configuration classes
- `controller/` - MVC controllers
- `entity/` - Domain model objects
- `repository/` - Data access interfaces
- `services/` - Business logic implementation
- `util/` - Utility classes

## Setup and Installation

1. Clone the repository
   ```
   git clone https://github.com/Zhangwen-Hu/jobportal.git
   ```

2. Configure MySQL database in `application.properties`
   ```
   spring.datasource.url=jdbc:mysql://localhost:3306/jobportal
   spring.datasource.username=your_username
   spring.datasource.password=your_password
   ```

3. Build the project
   ```
   ./mvnw clean install
   ```

4. Run the application
   ```
   ./mvnw spring-boot:run
   ```

5. Access the application at `http://localhost:8080`

## Usage

1. Register an account as either a job seeker or recruiter
2. Complete your profile
3. For job seekers: Search and apply for jobs
4. For recruiters: Post job openings and review applications

## License

This project is open-source and available under the [MIT License](LICENSE).

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
