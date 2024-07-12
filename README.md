# Payment Gateway

## Getting Started

To integrate Razorpay payment gateway into your project, follow these steps:

1. **Create a Razorpay Account:**
   - Visit [Razorpay](https://razorpay.com/) and create an account if you haven't already.

2. **Setup Environment Variables:**
   - Add your Razorpay API keys and other necessary environment variables to your project. It's crucial to keep these variables secure and not expose them in your codebase. Consider using environment variables management tools or `.env` files.

3. **Integrate Razorpay SDK:**
   - Follow the [Razorpay documentation](https://razorpay.com/docs/payment-gateway/web-integration/standard/) to integrate the Razorpay SDK into your frontend or backend codebase.

4. **Start Accepting Payments:**
   - Once integrated, you can start accepting payments securely using Razorpay's payment gateway.

## Environment Variables

Make sure to set the following environment variables:

- `RAZORPAY_API_KEY`: Your Razorpay API key.
- `RAZORPAY_API_SECRET`: Your Razorpay API secret.
- `MONGO_URI`
- `PORT`
These variables should be kept confidential and not hard-coded in your application code for security reasons. Use environment-specific methods to manage them securely.

## Contributing

Feel free to contribute to this project by forking it and submitting a pull request. If you encounter any issues or have suggestions, please open an issue.
