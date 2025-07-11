# Stockit Desktop

Stockit Desktop is an ElectronJS-based stock management application, designed for efficient offline inventory, sales, and customer tracking. Enjoy a modern, responsive dashboard for managing your business operations directly from your desktop.

## Related Projects

- **Frontend Next.js GitHub:** [https://github.com/VaibhavTalkhande/stockit](https://github.com/VaibhavTalkhande/stockit)
- **Frontend Deployed App:** [https://stockit-wine.vercel.app](https://stockit-wine.vercel.app)
- **ElectronJS Desktop App:** [https://github.com/VaibhavTalkhande/stockit-desktop](https://github.com/VaibhavTalkhande/stockit-desktop)
- **Backend GitHub:** [https://github.com/VaibhavTalkhande/stockit-backend](https://github.com/VaibhavTalkhande/stockit-backend)

---
## Features

- 📦 Product management: Add, edit, and track products.
- 🛒 Sales tracking: Manage sales orders.
- 👥 Customer insights: Monitor customer activity.
- 📊 Dashboard: Real-time statistics on revenue, orders, customers, and inventory.
- 🔒 Authentication: Secure login and user management.
- ⚡ Fast, responsive desktop UI.
- 🖥️ Offline support for desktop usage.

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

Made with ❤️ using ElectronJS and React.