# pharmanager
manage ur pharmacy online
# Pharmanger

**Pharmanger** is a web application built with Next.js and MongoDB that helps pharmacies manage their inventory online, track medicines, and streamline operations.

## Features

- 📦 **Inventory Management:** Add, edit, and delete medicine stock.
- 🏷️ **Barcode Support:** Search and update by barcode.
- 📊 **Stock Tracking:** See what’s low, what’s out, and get alerts.
- 🔍 **Powerful Search:** Find medicines quickly by name, code, or category.
- 👨‍⚕️ **Role-Based Access:** Pharmacists and admins have different permissions.
- 📝 **Order History:** Log sales, see usage history.
- 🌐 **Modern Web App:** Fast, mobile-friendly interface.

## Tech Stack

- **Frontend:** [Next.js](https://nextjs.org/) (React)
- **Backend/API:** Next.js API routes
- **Database:** [MongoDB Atlas](https://www.mongodb.com/atlas) (cloud)
- **ORM:** Mongoose
- **Authentication:** (Add your method, e.g., NextAuth, JWT, or custom)

## Getting Started

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/pharmanger.git
    cd pharmanger
    ```

2. **Install dependencies:**

    ```bash
    npm install
    ```

3. **Set up your environment variables:**

    - Create a `.env.local` file in the root directory:
    ```env
    MONGODB_URI=your_mongodb_connection_string
    # Add any other env variables you need (e.g., authentication secrets)
    ```

4. **Run the development server:**

    ```bash
    npm run dev
    ```

    Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

5. **Deploying:**
    - Deploy easily for free on [Vercel](https://vercel.com/).  
    - Connect your GitHub repo, set `MONGODB_URI` in Vercel's environment variables.

## Screenshots

*(Add screenshots here!)*

## License

This project is licensed under the MIT License.

---

**Pharmanger** — Pharmacy Inventory, managed the smart way.

