# 💇‍♀️ Bookly

**Bookly** is a clone of the [Booksy](https://booksy.com/) app, targeting the Health & Beauty services reservation market. This project is built for educational purposes, utilizing **EventStorming**, **DDD (Domain-Driven Design)**, **CQRS (Command Query Responsibility Segregation)**, and **Event Sourcing** with **Ruby on Rails**.

## 🎯 Project Goal
Bookly enables users to book appointments with Health & Beauty specialists, such as hairdressers, beauticians, or massage therapists, and allows service providers to manage their bookings. This app is inspired by the popular Booksy platform but focuses on implementing advanced architectural concepts like CQRS and Event Sourcing.

## 💡 Motivation
This project is being developed to learn and apply the following concepts:
- **Ruby on Rails**
- **EventStorming**
- **Domain-Driven Design (DDD)**
- **CQRS**
- **Event Sourcing**

## 🔑 Key Features

### For Customers:
- One-click booking of services at any time.
- One-click reservation cancellations.
- Access to multiple services in a single app.
- Appointment reminders.
- Reviews and ratings of service providers.
- Personalized recommendations.
- Online payments.
- Loyalty programs (e.g., $50 for referring a salon).
- Customer cards (e.g., discounts on future visits).
- Reservation history and promotional notifications.

### For Service Providers:
- Appointment management: modifying times, adding/removing services.
- Block off time for holidays or vacations.
- Calendar view – easy and intuitive appointment overview.
- Statistics: monitoring financials and trends.
- Track client visits and manage product usage.
- Notifications about upcoming appointments.
- Inventory management for equipment and supplies.
- Time-saving features: reservations and cancellations without phone calls.

## 📚 Architecture

The project architecture is inspired by [RailsEventStore/ecommerce](https://github.com/RailsEventStore/ecommerce), which serves as a great foundation for learning CQRS and Event Sourcing.

## 🛤 Architecture

1. **EventStorming** – we use this technique to map out all processes, events, aggregates and bounded contexts happening in the application.
2. **Domain-Driven Design (DDD)** – the code structure is based on business concepts, with clearly defined aggregates, entities, and domain services.
3. **CQRS** – separate logic for handling commands (Command) and data retrieval (Query) with ReadModels, improving scalability.
4. **Event Sourcing** – instead of storing only the current state of the system, we store the full history of events, allowing us to replay the entire application's history.

## 💻 How to run the project locally?

1. Clone the repository:
    ```bash
    git clone https://github.com/macias34/bookly.git
    cd bookly
    ```

2. Install dependencies:
    ```bash
    bundle install
    ```

3. Run the database migrations:
    ```bash
    rails db:migrate
    ```

4. Start the server:
    ```bash
    rails server
    ```

## 👥 Collaboration

If you are interested in **EventStorming**, **Domain-Driven Design**, or **CQRS**, I would love to collaborate! I’m looking for people who want to contribute to the project and exchange knowledge.

If you have ideas for new features or improvements, feel free to let me know! 🙌

## 📈 Roadmap

- [x] Overview of key features
- [ ] Big Picture EventStorming
- [ ] Get answers to EventStorming Hotspots from a barber while getting my hair cut
- [ ] Further EventStormings? possibly not needed (Process, Design level)
- [ ] Start Implementation
