## Presto-FoodOrderingAndDeliveryApp
A comprehensive food delivery platform built with .NET Core Web API, .NET MVC, and Angular, featuring multiple user roles (Admin, Restaurant, Customer, DeliveryMan) and real-time communication capabilities.

#Architecture & Design Patterns

   •	Dependency Injection Pattern: The application extensively uses interfaces for both repositories and services - this architectural approach is called the Interface Segregation Principle and Dependency Inversion Principle from SOLID principles. 
   
   •	Service Layer Pattern: Clear separation between business logic (services) and data access (repositories).
   
   •	Repository Pattern: Data access abstraction through interfaces like ICustomerRepo, IOrderRepo, etc.
   
#Key Strengths:

1. Robust Authentication & Authorization

   •	ASP.NET Core Identity integration
   
   •	JWT token-based authentication
   
   •	Role-based access control (Admin, Restaurant, Customer, DeliveryMan)
   
   •	Email confirmation system
   
   •	Reset password
   
2. Real-time Communication

   •	SignalR implementation for live chat functionality
   
   •	Real-time order status updates
   
   •	Instant notifications
   
3. Advanced Geospatial Features

   •	NetTopologySuite integration for location-based services
   
   •	Delivery route optimization using OpenRouteService
   
   •	Distance calculations for delivery assignment
   
4. AI-Powered Features

   •	Gemini AI integration for embeddings and chat responses
   
   •	Knowledge base with RAG (Retrieval-Augmented Generation)
   
   •	Intelligent customer support through chat services
   
5. Payment Integration

   •	Stripe payment processing
   
   •	Secure checkout with session management
   
   •	Payment link generation and validation
   
6. Comprehensive Business Logic

   •	Multi-restaurant support
   
   •	Shopping cart management with restaurant validation
   
   •	Order lifecycle management (status tracking)
   
   •	Delivery man assignment algorithms
   
   •	Promo code and discount systems
   
   •	Review and rating system
   
7. File Management

   •	Image upload and processing for restaurants and items
   
   •	Secure file storage with validation
   
8. Email Services

   •	SMTP-based email notifications refer to sending automated email messages using the Simple
   
   •	HTML email templates for confirmations
   
9. Frontend Integration

   •	Angular frontend with singleton component architecture
   
   •	MVC Admin panel for administrative functions

10. Data Management

   •	Entity Framework Core with SQL Server
   
   •	AutoMapper for object-to-object mapping
   
   •	Database transactions for data consistency
