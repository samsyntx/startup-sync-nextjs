# Startup Sync

**Startup Sync** is a web application built with **Next.js**, **TypeScript**, and **NextAuth.js** that allows users to easily register their startups. The app integrates **GitHub authentication**, enabling users to log in seamlessly using their GitHub credentials.

---

## Features

- **GitHub Authentication**: Users can sign up and log in with their GitHub accounts using **NextAuth.js** for secure authentication.
- **Startup Registration**: After logging in, users can register their startups and manage their startup details.
- **Next.js**: The app uses **Next.js** for both server-side rendering and client-side interactions, providing fast and responsive user experiences.
- **TypeScript**: Developed with **TypeScript** for type safety and better developer productivity.

---

## Tech Stack

- **Frontend & Backend**: **Next.js**
- **Authentication**: **NextAuth.js** with **GitHub OAuth**
- **Type Safety**: **TypeScript**

---

## Getting Started

### Prerequisites

Make sure you have the following installed on your local machine:

- **Node.js** (v16.0.0 or later)
- **npm** or **yarn**

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/startup-sync.git
```

2. Navigate to the project folder:
```bash
cd startup-sync-nextjs
```

3. Install dependencies:
   ```bash
   npm install
```

4. Set up environment variables:
Create a .env.local file in the root directory and add your GitHub OAuth credentials:
```bash
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=your-next-auth-secret
GITHUB_ID=your-github-client-id
GITHUB_SECRET=your-github-client-secret
```

### Running the App
To run the app in development mode:
```bash
npm run dev
```

The app will be available at http://localhost:3000

## Contributing
If you would like to contribute to the development of Startup Sync, feel free to fork the repository and submit a pull request with your changes. Make sure to follow the project’s code style and write tests for any new features or bug fixes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
