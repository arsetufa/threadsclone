
## Setup and Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/arsetufa/threadsclone.git
   cd threadsclone
   ```

2. **Environment Variables**: 
   Create a `.env.local` file in the root directory. Add the necessary environment variables:
   ```bash
   MONGODB_URI=your_mongodb_uri
   CLERK_FRONTEND_API=your_clerk_frontend_api
   CLERK_SECRET=your_clerk_secret
   UPLOADTHING_KEY=your_uploadthing_key
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
