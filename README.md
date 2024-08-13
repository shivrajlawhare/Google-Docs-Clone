# Google Docs Clone

This is a Google Docs clone built using Next.js, Clerk for authentication, and Liveblocks for real-time collaboration. The project is designed to allow multiple users to edit documents simultaneously, similar to Google Docs.

## Live Demo

Check out the live demo here: [Google Docs Clone](https://google-docs-clone-ochre-beta.vercel.app/)

## Features

👉 **Authentication**: User authentication using GitHub through NextAuth, ensuring secure sign-in/out and session management.

👉 **Collaborative Text Editor**: Multiple users can edit the same document simultaneously with real-time updates.

👉 **Documents Management**:
- **Create Documents**: Users can create new documents, which are automatically saved and listed.
- **Delete Documents**: Users can delete documents they own.
- **Share Documents**: Users can share documents via email or link with view/edit permissions.
- **List Documents**: Display all documents owned or shared with the user, with search and sorting functionalities.

👉 **Comments**: Users can add inline and general comments, with threading for discussions.

👉 **Active Collaborators on Text Editor**: Show active collaborators with real-time presence indicators.

👉 **Notifications**: Notify users of document shares, new comments, and collaborator activities.

👉 **Responsive**: The application is responsive across all devices.

…and many more, including code architecture and reusability.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/google-docs-clone.git
    cd google-docs-clone
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Create a `.env.local` file and add your environment variables:
    ```
    NEXT_PUBLIC_CLERK_FRONTEND_API=<your-clerk-frontend-api>
    CLERK_API_KEY=<your-clerk-api-key>
    LIVEBLOCKS_SECRET_KEY=<your-liveblocks-secret-key>
    ```

4. Run the development server:
    ```bash
    npm run dev
    ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.

## Challenges Faced

- **Real-time Collaboration**: Setting up real-time collaboration using Liveblocks was challenging but rewarding. It involved ensuring that multiple users could edit documents without conflicts.
  
- **Authentication**: Integrating Clerk for user authentication required careful handling of user sessions and permissions.

- **UI Consistency**: Maintaining a consistent and responsive UI across different devices was also a key challenge.

## Future Enhancements

- **Offline Mode**: Allowing users to edit documents offline and sync later.
- **Version Control**: Implementing version history and rollback.

## License

This project is licensed under the MIT License.
