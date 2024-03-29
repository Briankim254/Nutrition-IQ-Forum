
# Nutrition-IQ Forum - A Modern Fullstack Forum

Built with the Next.js App Router, TypeScript & Tailwind

![Screenshot from 2024-01-13 21-17-50](https://github.com/Briankim254/Nutrition-IQ-Forum/assets/91450029/dc3db1bc-cae5-4303-a4e1-4450a2e38427)

## Features

 - Infinite scrolling for dynamically loading posts
 - Authentication using NextAuth & Google
 - Custom feed for authenticated users
 - Advanced caching using [Upstash Redis](https://upstash.com/?utm_source=Josh2)
 - Optimistic updates for a great user experience
 - Modern data fetching using React-Query
 - A beautiful and highly functional post editor
 - Image uploads & link previews
 - Full comment functionality with nested replies
 - ... and much more


## Getting started

To get started with this project, run

```bash
  git clone -b starter-code https://github.com/Briankim254/Nutrition-IQ-Forum.git
```

and copy these .env.example variables into a separate .env file:

```bash
DATABASE_URL=
NEXTAUTH_SECRET=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

REDIS_URL=
REDIS_SECRET=
```

and that's all you need to get started!


## Acknowledgements

- Shadcn's [Taxonomy respository](https://github.com/shadcn/taxonomy) for showcasing the post editor

## License

[MIT](https://choosealicense.com/licenses/mit/)
