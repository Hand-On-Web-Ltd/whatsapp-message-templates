# Order Updates

Templates for order confirmations, shipping updates, and delivery notifications.

---

### 1. Order Confirmation
```
Order confirmed! 🎉

Hi {{name}}, we've got your order:

🛒 Order #{{order_number}}
📦 {{item_summary}}
💰 Total: {{total}}

We'll let you know when it ships. Thanks for your order!
```

### 2. Order Shipped
```
Your order is on its way! 📦

Hi {{name}}, order #{{order_number}} has been dispatched.

🚚 Courier: {{courier_name}}
📋 Tracking: {{tracking_number}}
📅 Expected delivery: {{delivery_date}}

Track it here: {{tracking_link}}
```

### 3. Out for Delivery
```
Heads up, {{name}} — your order is out for delivery today! 🚛

Order #{{order_number}}
Expected: by {{delivery_time}}

Make sure someone's around to receive it, or let us know if you need to change anything.
```

### 4. Delivered
```
Your order has been delivered! ✅

Hi {{name}}, order #{{order_number}} was dropped off at {{delivery_time}}.

Everything look good? Let us know if there are any issues.

Happy with your purchase? We'd love a review: {{review_link}}
```

### 5. Order Delayed
```
Hi {{name}},

Quick update on order #{{order_number}} — there's been a slight delay. Your new estimated delivery date is {{new_date}}.

Sorry about this. {{reason_if_applicable}}

Questions? Just reply here.
```

### 6. Refund Processed
```
Hi {{name}},

Your refund for order #{{order_number}} has been processed.

💰 Amount: {{refund_amount}}
💳 Back to: {{payment_method}}
⏱️ Should arrive in: 3-5 working days

Thanks for your patience.
```

### 7. Ready for Collection
```
Hi {{name}}! Your order is ready to pick up 🎉

Order #{{order_number}}
📍 {{collection_address}}
⏰ Collection hours: {{hours}}

Just show this message when you arrive. See you soon!
```
