# 🚀 Welcome to the Full Stack Discord Clone with Next.js, React, Socket.io, Prisma, TailwindCSS and MySQL! 🌟


### 📨 Key Features:



📬 Real-time Messaging: Experience the thrill of real-time communication using Socket.io. 📣📱

📎 Attachments Galore: Share files with ease! Got you covered with UploadThing. 📂📤

✏️ Edit & Delete on the Fly: Make mistakes disappear in real-time with message editing and deletion feature! ✏️❌

📞 Voice & Video Calls: Connect like never before with text, audio, and video call channels. 📞🎥

👥 1:1 Conversations: Dive into intimate conversations with fellow members. 👥💬

🎙️ Video Calls: Take it a step further with one-on-one video calls between members. 🎥🤝

🛡️ Member Management: Flex admin muscles with options to kick members and change their roles. 🦸‍♂️🚫

💌 Invite Magic: Generate unique invite links and explore the fully functional invite system. 💌✉️

📜 Infinite Loading: Seamlessly browse through messages with batched loading feature (thanks to tanstack/query)! 🔄📜

🏰 Server Customization: Build and personalize own server with ease. 🌆🖌️

🎨 Sleek UI: Designed it up beautifully with TailwindCSS and ShadcnUI. 🎉🖼️

📱 Responsive & Mobile-Friendly: Access from anywhere, anytime, with full responsivity and a mobile-friendly UI. 📱💼

🌓 Light/Dark Mode: Choose your vibe with light and dark mode options. 🌞🌚

🔄 Websocket Fallback: Never lose connection – Got you covered with polling and alerts! 🔄🚨

💼 ORM Power: Prisma keeps things organized and efficient. 💼📊

🗄️ Rock-Solid Database: Relies on MySQL from Planetscale to ensure the data is in safe hands. 🗄️🌠

🔐 Secure Authentication: Rest easy knowing that information is protected with Clerk. 🔒🔐

## Let's build the future of communication together! 🌐🚀

### Prerequisites

**Node version 18.x.x**

### Cloning the repository

```shell
git clone https://github.com/PrajapatiShefali/DISCORD.git
```

### Install packages

```shell
npm i
```

### Setup .env file


```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=


DATABASE_URL=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

LIVEKIT_API_KEY=
LIVEKIT_API_SECRET=
NEXT_PUBLIC_LIVEKIT_URL=
```

### Setup Prisma

Add MySQL Database (I used PlanetScale)

```shell
npx prisma generate
npx prisma db push

```

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command         | description                              |
| :-------------- | :--------------------------------------- |
| `dev`           | Starts a development instance of the app |

