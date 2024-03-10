# Application Rules

- [ ] The application must have two types of users, delivery person and/or admin.
- [ ] It must be possible to log in with CPF (Brazilian taxpayer registry) and Password.
- [ ] It must be possible to perform CRUD operations on delivery persons.
- [ ] It must be possible to perform CRUD operations on orders.
- [ ] It must be possible to perform CRUD operations on recipients.
- [ ] It must be possible to mark an order as awaiting pickup (Available for pickup).
- [ ] It must be possible to pick up an order.
- [ ] It must be possible to mark an order as delivered.
- [ ] It must be possible to mark an order as returned.
- [ ] It must be possible to list orders with delivery addresses near the delivery person's location.
- [ ] It must be possible to change a user's password.
- [ ] It must be possible to list a user's deliveries.
- [ ] It must be possible to notify the recipient of any changes in the order status.

# Business Rules

- [ ] Only admin users can perform CRUD operations on orders.
- [ ] Only admin users can perform CRUD operations on delivery persons.
- [ ] Only admin users can perform CRUD operations on recipients.
- [ ] To mark an order as delivered, sending a photo is mandatory.
- [ ] Only the delivery person who picked up the order can mark it as delivered.
- [ ] Only the admin can change a user's password.
- [ ] A delivery person should not be able to list another delivery person's orders.
