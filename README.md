
```sh
# Step 1: Clone the repository using the project's Git URL.
git clone <YOUR_GIT_URL>

# Step 2: Navigate to the project directory.
cd <YOUR_PROJECT_NAME>

# Step 3: Install the necessary dependencies.
npm i

# Step 4: Start the development server with auto-reloading and an instant preview.
npm run dev
```

**Edit a file directly in GitHub**

- Navigate to the desired file(s).
- Click the "Edit" button (pencil icon) at the top right of the file view.
- Make your changes and commit the changes.

**Use GitHub Codespaces**

- Navigate to the main page of your repository.
- Click on the "Code" button (green button) near the top right.
- Select the "Codespaces" tab.
- Click on "New codespace" to launch a new Codespace environment.
- Edit files directly within the Codespace and commit and push your changes once you're done.

to install and run manually

Create a new file called .env.local and add these exact lines:

VITE_SUPABASE_URL=https://zuawgikivwqvkdxbqdyj.supabase.co
VITE_SUPABASE_ANON_KEY=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6Inp1YXdnaWtpdndxdmtkeGJxZHlqIiwicm9sZSI6ImFub24iLCJpYXQiOjE3NDk4NDkxMDMsImV4cCI6MjA2NTQyNTEwM30.F1L5BAWNFJ3YxY9y41QqMut-oRiMqBlBo72E66KA5y8

npm install

npm run dev
