# Stockit Desktop

Stockit Desktop is an ElectronJS-based stock management application for efficient offline inventory, sales, and customer tracking. It connects to the Stockit Backend (Node.js/Express/MongoDB REST API) to provide a seamless experience for retail stores, including authentication, billing, payment integration, and AI-powered business suggestions.

## Related Projects

- **Frontend Next.js GitHub:** [https://github.com/VaibhavTalkhande/stockit](https://github.com/VaibhavTalkhande/stockit)
- **Frontend Deployed App:** [https://stockit-wine.vercel.app](https://stockit-wine.vercel.app)
- **ElectronJS Desktop App:** [https://github.com/VaibhavTalkhande/stockit-desktop](https://github.com/VaibhavTalkhande/stockit-desktop)
- **Backend GitHub:** [https://github.com/VaibhavTalkhande/stockit-backend](https://github.com/VaibhavTalkhande/stockit-backend)

---

## Features & Functionality

- **User Authentication:** Secure login, logout, and JWT-based session management.
- **Password Management:** Forgot/reset password flows with email tokens.
- **Store Management:** Each user is linked to a store for isolated data.
- **Product Management:** Add, edit, delete, and track products and stock.
- **Customer Management:** CRUD operations, purchase history, and insights.
- **Sales Management:** Create sales, update stock, track payments, and integrate with Stripe.
- **Billing & Email:** Generate and email bills/receipts to customers.
- **Payment Integration:** Stripe Checkout for online payments and payment link resending.
- **AI Business Suggestions:** Get actionable advice using Gemini AI based on store data.
- **Role-based Access:** Auth middleware for route protection.
- **Analytics:** Daily sales, top-selling products, and more.
- **Dashboard:** Real-time statistics on revenue, orders, customers, and inventory.


## Getting Started

To run Stockit Desktop locally:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/VaibhavTalkhande/stockit-desktop.git
    cd stockit-desktop
    ```

2. **Install dependencies:**
    ```bash
    npm install
    # or
    yarn install
    ```

3. **Run the Electron app:**
    ```bash
    npm run electron
    # or
    yarn electron
    ```

4. **Use the app:**  
   The desktop window will open automatically.

## Project Structure

- `src/` - Main Electron and React source code
- `public/` - Static assets
- `main.js` - Electron main process
- `preload.js` - Preload scripts for secure IPC

## Technologies Used

- [ElectronJS](https://www.electronjs.org/)
- [React](https://react.dev/)
- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Stripe](https://stripe.com/)
- [Gemini AI](https://ai.google.dev/)

## Packaging & Distribution

Stockit Desktop can be packaged for Windows, macOS, and Linux using [Electron Forge](https://www.electronforge.io/) or [Electron Builder](https://www.electron.build/).

1. Configure packaging in `package.json`.
2. Run the packaging command:
    ```bash
    npm run make
    # or
    yarn make
    ```
3. Distribute the generated installer.

See the [Electron packaging documentation](https://www.electronjs.org/docs/latest/tutorial/application-distribution/) for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

---

Made with ❤️ using ElectronJS.
