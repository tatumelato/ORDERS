<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>San Jo's Restaurant - Online Order</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --gradient-start: #FF4D4D;
            --gradient-end: #D32F2F;
            --white: #FFFFFF;
            --text-color: #333;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Roboto', sans-serif;
            background: linear-gradient(135deg, var(--gradient-start), var(--gradient-end));
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--text-color);
            line-height: 1.6;
            padding: 1rem;
        }

        .order-container {
            width: 100%;
            max-width: 600px;
            background-color: var(--white);
            border-radius: 20px;
            box-shadow: 0 15px 35px rgba(0,0,0,0.1);
            overflow: hidden;
        }

        .order-header {
            background: linear-gradient(135deg, var(--gradient-start), var(--gradient-end));
            color: var(--white);
            text-align: center;
            padding: 1.5rem;
        }

        .order-header h1 {
            font-family: 'Playfair Display', serif;
            font-size: 2rem;
            font-weight: 700;
            letter-spacing: 1px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .order-form {
            padding: 2rem;
        }

        .form-group {
            margin-bottom: 1.5rem;
        }

        label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: 700;
            color: var(--gradient-end);
        }

        input, select, textarea {
            width: 100%;
            padding: 0.75rem;
            border: 2px solid var(--gradient-start);
            border-radius: 10px;
            font-size: 1rem;
            transition: all 0.3s ease;
        }

        .menu-items {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 10px;
        }

        .menu-item {
            display: flex;
            align-items: center;
        }

        .menu-item input[type="checkbox"] {
            margin-right: 10px;
            width: auto;
        }

        .btn {
            display: block;
            width: 100%;
            padding: 1rem;
            background: linear-gradient(135deg, var(--gradient-start), var(--gradient-end));
            color: var(--white);
            border: none;
            border-radius: 10px;
            font-size: 1rem;
            font-weight: 700;
            letter-spacing: 1px;
            cursor: pointer;
            transition: all 0.3s ease;
            margin-top: 1rem;
            text-transform: uppercase;
        }

        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 7px 20px rgba(0,0,0,0.2);
            filter: brightness(1.1);
        }

        .whatsapp-btn {
            background: linear-gradient(135deg, #25D366, #128C7E);
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .whatsapp-btn img {
            width: 24px;
            margin-right: 10px;
        }

        #confirmationModal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.5);
            z-index: 1000;
            justify-content: center;
            align-items: center;
        }

        .confirmation-content {
            background: var(--white);
            padding: 2rem;
            border-radius: 15px;
            max-width: 500px;
            text-align: center;
        }

        @media (max-width: 600px) {
            .menu-items {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="order-container">
        <div class="order-header">
            <h1>San Jo's Restaurant Order</h1>
        </div>
        <div class="order-form">
            <form id="orderForm">
                <div class="form-group">
                    <label for="name">Full Name</label>
                    <input type="text" id="name" placeholder="John Doe" required>
                </div>
                <div class="form-group">
                    <label for="phone">Phone Number</label>
                    <input type="tel" id="phone" placeholder="+27 62 XXX XXXX" required>
                </div>
                <div class="form-group">
                    <label>Order Type</label>
                    <select id="orderType" required>
                        <option value="">Select Order Type</option>
                        <option value="delivery">Delivery</option>
                        <option value="takeaway">Takeaway</option>
                        <option value="eat-in">Eat In</option>
                    </select>
                </div>
                <div class="form-group">
                    <label>Select Menu Items</label>
                    <div class="menu-items">
                        <div class="menu-item">
                            <input type="checkbox" id="pizza" name="item" value="Pizza">
                            <label for="pizza">Pizza</label>
                        </div>
                        <div class="menu-item">
                            <input type="checkbox" id="burger" name="item" value="Burger">
                            <label for="burger">Burger</label>
                        </div>
                        <div class="menu-item">
                            <input type="checkbox" id="pasta" name="item" value="Pasta">
                            <label for="pasta">Pasta</label>
                        </div>
                        <div class="menu-item">
                            <input type="checkbox" id="salad" name="item" value="Salad">
                            <label for="salad">Salad</label>
                        </div>
                    </div>
                </div>
                <div class="form-group">
                    <label>Payment Method</label>
                    <select id="paymentMethod" required>
                        <option value="">Select Payment Method</option>
                        <option value="cash">Cash</option>
                        <option value="card">Card</option>
                        <option value="online">Online Payment</option>
                    </select>
                </div>
                <div class="form-group">
                    <label for="address">Delivery/Pickup Address (if applicable)</label>
                    <textarea id="address" placeholder="Enter your address"></textarea>
                </div>
                <div class="form-group">
                    <label for="specialInstructions">Special Instructions</label>
                    <textarea id="specialInstructions" placeholder="Any special requests?"></textarea>
                </div>
                <button type="submit" class="btn">Place Order</button>
            </form>
        </div>
    </div>

    <div id="confirmationModal">
        <div class="confirmation-content">
            <h2>Confirm Your Order</h2>
            <div id="orderSummary"></div>
            <button id="confirmOrder" class="btn">Confirm</button>
            <button id="cancelOrder" class="btn" style="background: #888;">Cancel</button>
        </div>
    </div>

    <script>
        document.getElementById('orderForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            // Collect form data
            const name = document.getElementById('name').value;
            const phone = document.getElementById('phone').value;
            const orderType = document.getElementById('orderType').value;
            const paymentMethod = document.getElementById('paymentMethod').value;
            const address = document.getElementById('address').value;
            const specialInstructions = document.getElementById('specialInstructions').value;
            
            // Collect selected menu items
            const selectedItems = Array.from(document.querySelectorAll('input[name="item"]:checked'))
                .map(checkbox => checkbox.value);
            
            // Validate form
            if (!name || !phone || !orderType || !paymentMethod || selectedItems.length === 0) {
                alert('Please fill in all required fields and select at least one menu item');
                return;
            }
            
            // Generate order summary
            const orderSummary = `
                <p><strong>Name:</strong> ${name}</p>
                <p><strong>Phone:</strong> ${phone}</p>
                <p><strong>Order Type:</strong> ${orderType.toUpperCase()}</p>
                <p><strong>Payment Method:</strong> ${paymentMethod.toUpperCase()}</p>
                <p><strong>Menu Items:</strong> ${selectedItems.join(', ')}</p>
                ${address ? `<p><strong>Address:</strong> ${address}</p>` : ''}
                ${specialInstructions ? `<p><strong>Special Instructions:</strong> ${specialInstructions}</p>` : ''}
            `;
            
            // Show confirmation modal
            document.getElementById('orderSummary').innerHTML = orderSummary;
            document.getElementById('confirmationModal').style.display = 'flex';
            
            // Confirm order button
            document.getElementById('confirmOrder').onclick = function() {
                // Prepare WhatsApp message
                const whatsappMessage = encodeURIComponent(`Order Details:
Name: ${name}
Phone: ${phone}
Order Type: ${orderType.toUpperCase()}
Payment Method: ${paymentMethod.toUpperCase()}
Menu Items: ${selectedItems.join(', ')}
${address ? `Address: ${address}` : ''}
${specialInstructions ? `Special Instructions: ${specialInstructions}` : ''}`);
                
                // Open WhatsApp with pre-filled message
                window.open(`https://wa.me/27625928143?text=${whatsappMessage}`, '_blank');
                
                // Close modal and reset form
                document.getElementById('confirmationModal').style.display = 'none';
                document.getElementById('orderForm').reset();
            };
            
            // Cancel order button
            document.getElementById('cancelOrder').onclick = function() {
                document.getElementById('confirmationModal').style.display = 'none';
            };
        });
    </script>
</body>
</html>
