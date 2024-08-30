

# LiveDocs

LiveDocs is a collaborative online text editor that allows multiple users to work on the same document in real-time. Users can be assigned different permissions, such as view-only or editing rights, making it ideal for collaborative projects, document sharing, and more.

## Features

- **Real-time Collaboration**: Multiple users can edit the same document simultaneously.
- **Permission Management**: Assign view-only or editing permissions to collaborators.
- **User Authentication**: Secure user authentication and management powered by Clerk.
- **Seamless UI**: A modern, responsive UI built with Tailwind CSS and Shadcn/UI.
- **Optimized Performance**: Efficient document synchronization with Liveblocks.
- **Error Tracking**: Integrated with Sentry for real-time error monitoring and alerting.
- **Type Safety**: Built with TypeScript for enhanced code quality and maintainability.

## Tech Stack

- **Next.js 14**: React framework for building server-side rendered and static web applications.
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development.
- **Shadcn/UI**: A collection of customizable UI components.
- **Clerk**: User authentication and access management.
- **Liveblocks**: Real-time collaboration infrastructure.
- **Sentry**: Application monitoring and error tracking.
- **TypeScript**: Superset of JavaScript providing static type definitions.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/diegovilhalva/livedocs.git
    cd livedocs
    ```

2. Install dependencies:
    ```bash
    npm install
    # or
    yarn install
    ```

3. Set up environment variables:

   Create a `.env.local` file in the root of your project and configure the following variables:

   ```plaintext
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=<your-clerk-frontend-api>
   CLERK_SECRET_KEY=<your-clerk-api-key>
   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
   LIVEBLOCKS_PUBLIC_KEY=<your-liveblocks-public-key>
   SENTRY_AUTH_TOKEN=<your-sentry-auth-token>
   ```

4. Run the development server:
    ```bash
    npm run dev
    # or
    yarn dev
    ```

5. Open your browser and navigate to `http://localhost:3000`.

### Deployment

To deploy the application, you can use platforms like Vercel or Netlify. Ensure your environment variables are properly configured in the deployment platform.

### Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a Pull Request.

### License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.



