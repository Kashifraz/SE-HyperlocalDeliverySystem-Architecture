# 📦 Hyperlocal Delivery System

## Group Members
1) Syed Mohammad Kashif
2) Abdul Raheem Shahzad
3) Danish Ali
4) Juraev Dilshodbek

## Project Description
This project aims to build a `hyperlocal delivery` platform tailored for customers located within a `3-mile radius` of local shops and food vendors. The platform allows users to `browse` nearby grocery stores, restaurants, and small-scale food points, `view item details` including prices and availability, `add items` to a cart, and `place orders` for home delivery. Customers receive `live updates` on their order status—from confirmation to preparation and delivery—and can `track` the order and delivery agent’s.

To ensure quality and trust, customers are encouraged to leave `feedback and ratings` for each vendor, product, and delivery experience. This helps other users make informed decisions and motivates vendors and delivery personnel to maintain high service standards.

Vendors have access to a dedicated `dashboard` where they can manage their `inventory`, update product availability, set business hours, and view incoming orders. Delivery personnel use a mobile interface to accept `delivery requests`, navigate to destinations, and update the order status at each step.

The platform emphasizes ease of use, responsiveness, and seamless interactions among all user types. Key non-functional goals include maintaining a fast user interface, ensuring high system availability, and reliability. The user experience is designed to be intuitive and efficient, even for individuals with limited digital literacy.

Overall, this system supports the growing demand for convenient, reliable, and locally focused delivery services, fostering stronger connections between neighborhood vendors and their surrounding communities.

## Features
- **Customer Experience:**
  - Browse local vendors and food points.
  - Add items to the cart and place orders.
  - Real-time order tracking and delivery status updates.
  - Secure payment options and transaction management.
  - Ability to leave feedback and ratings for vendors, products, and delivery experiences.
  
- **Vendor Dashboard:**
  - Manage inventory and update product availability.
  - Set business hours and manage orders.
  - View and respond to customer feedback.

- **Delivery Agent Mobile Interface:**
  - Accept delivery requests and navigate to destinations.
  - Update order status at each step of the delivery process.
  
## Non-Functional Requirements (Quality Attributes)
- **Performance:** Fast and responsive user interface.
- **Reliability:** High system availability to ensure uptime and minimize outages.
- **Maintainability:** Maintainable codebase, allowing for easy updates, improvements, and issue resolution.
- **Usability:** Designed for easy navigation, even for users with limited digital literacy.
  
## Benefits
The platform supports the growing demand for convenient, reliable, and locally focused delivery services. It helps strengthen connections between neighborhood vendors and their surrounding communities by providing an efficient, trustworthy solution for local deliveries.

## 📄 System Overview
We included the system `Overview diagram` showing the system's end users. It shows that our system has different interfaces for end users, such as the `Customer Mobile App` for customers and the `vendor dashboard` for vendors. Then, it shows we have a common `API Gateway` for the whole system, which helps us interact with a distributed microservices backend. The system also has three main databases to store its data.
<img src="./system.png" alt="System Overview" width="1000"/>

## Stakeholder Analysis

The following are the primary stakeholders for this hyperlocal delivery platform. Each stakeholder influences the system design based on their specific needs and expectations:

- **Customers**: End-users who browse, order, and receive products. Their satisfaction directly impacts platform adoption and success. A seamless and responsive user experience is critical.
- **Vendors**: Local shops and food vendors who list products and manage inventory. Vendor participation ensures a wide variety of offerings; they require a stable and reliable system to manage daily operations.
- **Delivery Agents**: Personnel responsible for picking up and delivering orders. Their efficiency affects order fulfillment speed and customer satisfaction; they need a simple and dependable app to manage deliveries.
- **Product Owner**: Oversees the platform’s strategic direction and growth. They are concerned with building a scalable system that can support future expansions without major redesigns.
- **Developers**: Technical team responsible for developing, maintaining, and improving the platform. They prioritize clean, maintainable code to ensure long-term system health and rapid feature updates.

---

## Key Stakeholder Concerns

| **Stakeholder** | **Key Concerns**                          | **Quality Attribute**               |
|-----------------|-------------------------------------------|-------------------------------|
| **Customers**   | Easy-to-use app for browsing, ordering products, and receiving deliveries quickly. | Usability, Performance       |
| **Vendors**     | System must be highly available and consistently operational to manage inventory and orders effectively. | Reliability                  |
| **Delivery Agents** | Simple, reliable app to accept deliveries and update statuses easily. | Reliability, Usability        |
| **Product Owner** | The system architecture should support easy scaling to accommodate business growth. | Scalability                   |
| **Developers**  | Codebase should be maintainable, allowing for easy updates, improvements, and issue resolution. | Maintainability               |

## 📄 Context Viewpoint
The `Context View` describes the `system’s boundaries` by showing its interactions with external actors such as users, vendors, delivery agents, and other systems. It highlights what is inside the system and what lies outside, helping stakeholders understand how the system fits into its environment and what major inputs and outputs exist.

The `Context Diagram` below shows how external entities, such as users and external systems, interact with our system. It shows that `vendors` provide their products and working hours information to our system, and the system provides customers with orders and business. The `customer` provides their delivery information and the products they added to the cart, and the system returns order confirmation and tracking of their orders. Similarly, the `delivery agent` receives the pending orders for delivery and completes the order delivery. Our system also interacts with external systems such as `Location API` (Google Maps) by providing the addresses and receiving the coordinates (longitude and latitude).
<img src="./context.png" alt="Context Diagram" width="800"/>

## 📄 Use Case Viewpoint
The Use Case Viewpoint captures the primary ways different users (customers, vendors, and delivery agents) interact with the delivery platform to achieve their goals. It outlines the major functionalities the system must support, such as browsing vendors, placing orders, tracking deliveries, managing inventory, and updating order statuses. This viewpoint helps in understanding user requirements clearly by focusing on user-system interactions and ensures that the system is designed around real-world activities and expectations of its stakeholders.
<img src="./Hyperlocal usecase-1.png" alt="Use Case Diagram" width="1000"/>

## 📄 Process Viewpoint
The Process Viewpoint focuses on the system’s dynamic behavior and describes how different parts of the system interact at runtime to achieve specific tasks. It models processes such as order placement, payment handling, delivery tracking, and inventory updates, often showing how components communicate, synchronize, and handle concurrent activities. In this delivery platform, the process view ensures smooth coordination between customers, vendors, and delivery agents by managing workflows like order processing, delivery assignment, and real-time status updates.

## 📄 Development Viewpoint
The Development View focuses on the system’s internal structure from a developer’s perspective. It describes how the software is organized in the codebase — such as modules, packages, layers, and components — and how they are built and managed. This view helps developers understand how to develop, maintain, and extend the system efficiently. It also covers aspects like version control, build processes, coding standards, and team organization.
## 📜 History Log

| Date           | Task Description                                                                                 | Contributor                  |
|----------------|--------------------------------------------------------------------------------------------------|------------------------------|
| 2025, April 6  | Discussion and selection of project ideas for MSA course project.                                | Syed, Danish, Shahzad, Juraev|
| 2025, April 6  | Finalized the idea of a hyperlocal delivery platform and created the GitHub repository.          | Syed, Danish, Shahzad, Juraev|
| 2025, April 6  | Drafted 150-word and 250-word project descriptions for GitHub and course use.                    | Syed, Danish, Shahzad, Juraev|


