# shopping-Cart-System
A modular and extensible shopping cart system built in C++ that simulates real-world e-commerce discount processing. The project demonstrates advanced object-oriented design, modern memory management, and multiple software design patterns to apply dynamic pricing and coupon strategies.
Shopping Cart Discount Engine (C++)

🚀 Features
✔ Add, edit, and remove products from cart
✔ Dynamic product price updates
✔ Automatic cart total recalculation
✔ Loyalty membership support
✔ Bank/payment method based discounts
✔ Category-based seasonal offers
✔ Bulk purchase discount rules
✔ Coupon stacking & combinability logic
✔ Interactive console-based menu

🎟 Supported Discounts
🟢 Seasonal Offer
Percentage discount on specific product categories
🟢 Loyalty Discount
Extra discount for loyalty members
🟢 Bulk Purchase Discount
Flat discount when cart exceeds threshold
Non-combinable with other coupons
🟢 Banking Coupon
Payment method-based discount
Percentage discount with maximum cap
🧠 Design Patterns Implemented
🔹 Strategy Pattern
Encapsulates different discount calculations:
Flat discount
Percentage discount
Percentage discount with cap
➡ Enables easy addition of new discount types.
🔹 Chain of Responsibility
Coupons are applied sequentially:
Each coupon checks applicability
Applies discount if valid
Stops chain if non-combinable
➡ Mimics real-world coupon stacking logic.
🔹 Singleton Pattern
Used for centralized management:
Discount strategy manager
Coupon manager
➡ Ensures a single point of control.
🛠 Technologies & Concepts
C++ (OOP & STL)
Smart pointers (unique_ptr)
RAII & memory safety
Exception handling & input validation
Modular & scalable architecture

📊 How It Works
1️⃣ Add products to cart
2️⃣ Modify quantities or prices
3️⃣ Set loyalty membership
4️⃣ Select payment method
5️⃣ View applicable coupons
6️⃣ Apply discounts automatically
7️⃣ View final payable amount

🖥 Sample Products
Product	Category	Price
Winter Jacket	Clothing	₹1000
Jeans	Clothing	₹1000
Smartphone	Electronics	₹20000
Headphones	Electronics	₹2000
