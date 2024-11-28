-- Insert into Customer
INSERT INTO Customer (CustomerID, FirstName, LastName, PhoneNumber, EmailAddress)
VALUES
(1, 'John', 'Doe', '123-456-7890', 'john.doe@example.com'),
(2, 'Jane', 'Smith', '987-654-3210', 'jane.smith@example.com');

-- Insert into Order
INSERT INTO `Order` (OrderID, CustomerID, OrderDate, TotalAmount)
VALUES
(1, 1, '2024-01-01', 100.00),
(2, 2, '2024-01-02', 200.00);

-- Insert into Product
INSERT INTO Product (ProductID, ProductName, UnitPrice)
VALUES
(1, 'Laptop', 1000.00),
(2, 'Mouse', 20.00);

-- Insert into OrderDetails
INSERT INTO OrderDetails (OrderID, ProductID, Quantity)
VALUES
(1, 1, 1),
(2, 2, 2);
