<h1 align="center">Realtime Spotify Application ✨</h1>

![Demo App](/frontend/public/screenshot-for-readme.png)

[Watch Full Tutorial on Youtube](https://youtu.be/4sbklcQ0EXc)

About This Course:

-   🎸 Listen to music, play next and previous songs
-   🔈 Update the volume with a slider
-   🎧 Admin dashboard to create albums and songs
-   💬 Real-time Chat App integrated into Spotify
-   👨🏼‍💼 Online/Offline status
-   👀 See what other users are listening to in real-time
-   📊 Aggregate data for the analytics page
-   🚀 And a lot more...

### Setup .env file in _backend_ folder

```bash
PORT=...
MONGODB_URI=...
ADMIN_EMAIL=...
NODE_ENV=...

CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...
CLOUDINARY_CLOUD_NAME=...


CLERK_PUBLISHABLE_KEY=...
CLERK_SECRET_KEY=...
```

### Setup .env file in _frontend_ folder

```bash
VITE_CLERK_PUBLISHABLE_KEY=...
```
### tools i was used
```
dot env | mongose | cloudnary | clerk | ui.shadcn | 
```
### front end command termnal
cd frontend
npm create vite@latest .
npm i

npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p

# (so you can import "path" without error)
npm i -D @types/node
npx shadcn@latest init

npm install @clerk/clerk-react

npm i react-router-dom 2.16
