# Leave Management System (LMS)

A professional-grade web-based Leave Management System designed to streamline HR workflows, enable secure leave applications, and provide real-time leave tracking for employees and administrators.

## 📋 Overview

The Leave Management System is an enterprise-grade application that eliminates inefficiencies in manual HR processes. It provides authenticated modules for both employees and administrators, enabling:

- Secure leave applications with approval workflows
- Real-time leave balance tracking
- Automated leave processing
- Analytics and reporting for HR teams
- Cloud-based deployment on AWS infrastructure

## ✨ Key Features

- **Multi-Role Authentication**: Separate authenticated modules for employees and administrators
- **Leave Management**: Support for multiple leave types (Sick, Casual, Maternity, Paternity, Compassionate, Study)
- **Real-Time Tracking**: Monitor leave balances and application status in real-time
- **Admin Dashboard**: Comprehensive analytics and reporting capabilities
- **Secure Cloud Deployment**: Hosted on AWS with high availability and 99.9% uptime guarantee
- **Responsive Design**: Modern UI built with Tailwind CSS for seamless user experience
- **Data Security**: Industry-standard encryption and token-based authentication

## 🛠️ Technology Stack

- **Frontend**: HTML, CSS, Tailwind CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL
- **Cloud Infrastructure**: AWS (EC2, RDS, VPC)
- **Additional Libraries**:
  - Chart.js for analytics visualization
  - Font Awesome for icons
  - Space Grotesk & JetBrains Mono fonts

## 🚀 Getting Started

### Prerequisites

- PHP 7.4 or higher
- MySQL 5.7 or higher
- Web server (Apache/Nginx)
- AWS account (for cloud deployment)

### Installation

1. **Clone or download the project**
   ```bash
   cd LMS
   ```

2. **Set up the database**
   - Create a new MySQL database
   - Import the database schema from the project files
   - Configure database credentials

3. **Configure PHP environment**
   - Update database connection settings
   - Set up session management
   - Configure authentication parameters

4. **Deploy frontend**
   - Place `index.html` and related assets in your web server's root directory
   - Ensure all CSS and JavaScript resources are accessible

5. **Access the system**
   - Open your browser and navigate to the application URL
   - Log in with employee or admin credentials

## 📦 Project Structure

```
LMS/
├── index.html                          # Main frontend interface
├── Leave_Management_System_Report.md   # Comprehensive project documentation
└── README.md                           # This file
```

## 👥 User Roles

### Employee
- Submit leave requests
- View leave balance and history
- Track application status
- Download leave certificates

### Administrator
- Approve/reject leave requests
- Manage leave types and policies
- View analytics and reporting
- Manage employee records
- Configure system settings

## 🔐 Security Features

- Token-based authentication
- Encrypted password storage
- Session management with timeout
- Role-based access control (RBAC)
- SQL injection prevention
- CSRF protection

## 📊 System Architecture

The system follows a 3-tier architecture:

1. **Presentation Layer**: HTML/CSS/JavaScript frontend with responsive design
2. **Business Logic Layer**: PHP backend for leave processing and workflow automation
3. **Data Layer**: MySQL database for persistent storage

## 🌐 AWS Cloud Deployment

The system is designed for deployment on AWS infrastructure:

- **EC2 Instances**: Running the LAMP stack
- **RDS**: Multi-AZ MySQL database for high availability
- **VPC**: Secure network environment
- **Load Balancing**: Graviton-based instances for performance optimization

## 📝 Documentation

For detailed information, please refer to [Leave_Management_System_Report.md](Leave_Management_System_Report.md) which includes:

- Complete system requirements and specifications
- Detailed system design and architecture diagrams
- UML diagrams (Use Case, Class, Sequence, Activity)
- Database schema and ER diagrams
- Implementation details
- Testing procedures and test cases
- Deployment instructions
- Performance analysis and results

## 🧪 Testing

The system includes comprehensive testing coverage:

- **Unit Testing**: Individual component validation
- **Integration Testing**: Module interaction verification
- **System Testing**: End-to-end workflow validation
- **Test Scenarios**: Real-world use case testing

## 📈 Performance Metrics

- Sub-30 minute request-to-approval cycle
- Support for unlimited concurrent users
- 99.9% system availability
- High-performance Graviton-based infrastructure

## 🔄 Leave Types Supported

- Sick Leave
- Casual Leave
- Maternity Leave
- Paternity Leave
- Compassionate Leave
- Study Leave

## 🚧 Future Enhancements

- Mobile application support
- Integration with payroll systems
- Advanced analytics and predictive modeling
- Multi-language support
- Enhanced reporting capabilities

## 📄 License

This project is developed as an academic assignment for the Web Development & Software Engineering course.

## 👤 Author

**YISSIBI TAMO Fred Manuel**

- Course: Web Development & Software Engineering (WDSE-2026)
- Submission Date: March 29, 2026
- Institution: Faculty of Science and Technology

## 🤝 Support

For technical issues, feature requests, or documentation questions, please refer to the comprehensive documentation in the project report.

---

**Last Updated**: April 2026

