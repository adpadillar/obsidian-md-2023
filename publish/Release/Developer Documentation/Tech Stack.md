I want to have a familiar Tech Stack to build Release's Mobile app. This are the priorities for the technologies we'll choose:

- **Shipping** features as **quickly as possible**
- Having **type-safety** for confident refactoring
- Use **familiar tech**, so new devs get up to speed quickly
- **Multiplatform** development

For this reason, these are some of the major decisions regarding the Tech Stack.

1. **We structure our code in a [[Monorepo]],** where we can develop each app separately and share code between them. We will use [[Turborepo]] for structuring the monorepo and handling caching and build
2. **We use [[React Native]] for developing mobile apps.** We will use [[Expo]] as the solution for using React Native with the best developer experience.
3. **We (mostly) use [[Nextjs]] for web development**. There may be some moments where a framework like [[Astro]] looks like a better tool for the job, and it can be used too. However, the main Release website should be built in Next because it will also contain the main API, this follows nicely to the next point.
4. **We use [[tRPC]] for developing our API**. This API will live in the main website's codebase written in Next. However, the tRPC API can be consumed from different apps, most notably our Expo Mobile app, giving us a type-safe API
5. **We use [[Clerk]] for authentication?** We don't know yet. [[Firebase auth]] looks like a solid replacement and also the current team is more familiar with it. However, Clerk seems to bring some big developer experience gains and first-party support for things like edge-functions, and React Native.
6. **We use [[Tailwind CSS]] for our stylings**. For our mobile apps, we use [[NativeWind]] to make Tailwind work in React Native.
7. **We don't have a database yet**. Leaning towards [[Firestore]] because of all of it's realtime features, as well as it's ease of use. However, our stack also favors using an [[SQL database]] with [[Prisma]] as it's type-safe ORM