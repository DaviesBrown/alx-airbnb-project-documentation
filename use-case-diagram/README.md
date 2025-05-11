# Airbnb Clone Backend - Use Case Diagram

This directory contains the UML Use Case Diagram for the Airbnb Clone Backend, visualizing the interactions between key actors and system functionalities.

## 📂 File Structure

```
features-and-functionalities/
└── airbnb-backend-use-cases.png    # UML Use Case Diagram
```

## 📝 Diagram Overview

The **Use Case Diagram** illustrates the main actors and their interactions with the system:

* **Actors**

  * `Guest`: Browses properties, makes bookings, cancels bookings, leaves reviews, receives notifications.
  * `Host`: Manages property listings, views bookings, updates profile, receives notifications.
  * `Admin`: Administers users, listings, bookings, and payments; monitors system activity.
  * `Payment Gateway` (external): Processes guest payments and host payouts.

* **Key Use Cases**

  * **Register / Login**: Secure sign-up and authentication via JWT or OAuth.
  * **Manage Profile**: Update profile details and preferences.
  * **Create / Edit Listing**: Add, update, or remove property listings.
  * **Search Properties**: Filter available listings by location, date, price, and amenities.
  * **Book Property**: Reserve a listing for specific dates with date conflict checks.
  * **Cancel Booking**: Cancel existing reservations per policy.
  * **Process Payment**: Handle secure transactions and payouts via Stripe/PayPal.
  * **Leave Review**: Guests submit reviews; hosts may respond.
  * **Receive Notifications**: Email and in-app alerts for bookings, cancellations, and payments.
  * **Admin Management**: CRUD operations for system administration.

## 🔍 How to View

1. Ensure you have an image viewer that supports `.png` files.
2. Open the diagram:

   * In Draw\.io/diagrams.net: File > Import From > Device > select `airbnb-backend-use-cases.png`
   * In any standard image viewer: Double-click the file.

## 🚀 Usage

* Reference this diagram during backend implementation to understand system flows and actor responsibilities.
* Share with frontend teams to align on API interactions and user journeys.
* Use as documentation for project planning, design reviews, and stakeholder presentations.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/add-diagram-details`).
3. Commit your changes (`git commit -m 'Add more use cases'`).
4. Push to the branch (`git push origin feature/add-diagram-details`).
5. Open a Pull Request.

## 📄 License

This project is licensed under the [MIT License](LICENSE).
