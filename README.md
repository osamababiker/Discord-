# Fullstack Discord Clone: Next.js 13, React, Socket.io, Prisma, Tailwind, MySQL
<br /><br />
Features:
<br />
- Real-time messaging using Socket.io
- Send attachments as messages using UploadThing
- Delete & Edit messages in real time for all users
- Create Text, Audio and Video call Channels
- 1:1 conversation between members
- 1:1 video calls between members
- Member management (Kick, Role change Guest / Moderator)
- Unique invite link generation & full working invite system
- Infinite loading for messages in batches of 10 (tanstack/query)
- Server creation and customization
- Beautiful UI using TailwindCSS and ShadcnUI
- Full responsivity and mobile UI
- Light / Dark mode
- Websocket fallback: Polling with alerts
- ORM using Prisma
- MySQL database using Planetscale
- Authentication with Clerk
<br />
### Prerequisites
<br />
**Node version 18.x.x**
<br />
### Cloning the repository
<br />
### Install packages
<br />
```shell
npm i
```
<br />
### Setup .env file
<br />
<br />
```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=
<br />
<br />
DATABASE_URL=
<br />
UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=
<br />
LIVEKIT_API_KEY=
LIVEKIT_API_SECRET=
NEXT_PUBLIC_LIVEKIT_URL=
```
<br />
### Setup Prisma
<br />
Add MySQL Database (I used PlanetScale)
<br />
```shell
npx prisma generate
npx prisma db push
<br />
```
<br />
### Start the app
<br />
```shell
npm run dev
```
<br />
## Available commands
<br />
Running commands with npm `npm run [command]`
<br />
| command         | description                              |
| :-------------- | :--------------------------------------- |
| `dev`           | Starts a development instance of the app |

 
 
