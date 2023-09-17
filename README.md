
## Setup and Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/arsetufa/threadsclone.git
   cd threadsclone
   ```

2. **Environment Variables**: 
   Create a `.env.local` file in the root directory. Add the necessary environment variables:
   ```bash
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY
   CLERK_SECRET_KEY=your_Next_CLERK_SECRET_KEY
   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
   NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
   NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/
   
   UPLOADTHING_SECRET=your_UPLOADTHING_SECRET
   UPLOADTHING_APP_ID=your_UPLOADTHING_APP_ID
   
   MONGODB_URL=your_MONGODB_URL

   ```

3. **Install Dependencies**:
   ```bash
   npm install
   ```

4. **Run the Application**:
   ```bash
   npm run dev
   ```

5. **Visit the Application**:
   Open your browser and navigate to `http://localhost:3000` to see the application in action.
