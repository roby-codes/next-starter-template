## NextStart - A Custom Next.JS Starter Template

Starter template for quickly setting up your Next.js apps with pre-configured settings and best practices to save your precious time.

#### What's Included in this starter template?

###### Pre-installed Libraries 👇

![Shadcn/UI](https://img.shields.io/badge/Shadcn/UI-000000?logo=shadcnui)
![Zod](https://img.shields.io/badge/Zod-000000?logo=zod)
![T3_Env](https://img.shields.io/badge/T3_Env-000000?logo=dotenv)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-000000?logo=framer)

###### Pre-configured useful settings 👇

| Completed | Name                                 | Description                                                                                                 |
| --------- | ------------------------------------ | ----------------------------------------------------------------------------------------------------------- |
| ✅        | **Sitemap**                          | Default sitemap.xml file generated by the [`Sitemap()`](/src/app/sitemap.ts) function.                      |
| ✅        | **Robots**                           | Default robots.txt file generated by the [`Robots()`](/src/app/robots.ts) function.                         |
| ✅        | **Basic + Open Graph + Twitter SEO** | All the important SEO tags generated automatically thorough the [`getSeoTags()`](/src/lib/seo.ts) function. |
| ✅        | **Prettier TailwindCSS**             | TailwindCSS plugin added to re-order your TailwindCSS variables in an optimal way automatically on save.    |
| ✅        | **T3 Env**                           | Fix most of the common issues related to your environment variables.                                        |
| ✅        | **Resend**                           | Send emails seamlessly from your next.js application.                                                       |
| ✅        | **Framer Motion**                    | Easy web animations for your web application.                                                               |
| ✅        | **Docker**                           | Dockerfile and .dockerignore to build performant containers for next.js.                                    |
| ✅        | **React Icons**                      | Easy to integrate svg icons for your web application.                                                       |
| -         | **More Feature**                     | Coming Soon...                                                                                              |

#### How to setup this template with your own configuration?

- **1** Navigate to the [app configuration file](/src/config/app.config.ts) in your project folder
- **2** Change the default information inside the appData object with your own project's information to benefit from instant SEO optimization

###### Here is what each element of the appData object means 👇

| item        | description                                                                                           |
| ----------- | ----------------------------------------------------------------------------------------------------- |
| name        | The name of your project                                                                              |
| description | The description of your project                                                                       |
| domain      | The domain where you deploy your project                                                              |
| creator     | Your name and your personal link (i use my GitHub profile link)                                       |
| keywords    | An array of keywords that you should choose for your website depending on your research               |
| brandColor  | Hexcode of your brand's primary color, white by default, it will set this brand color in the Viewport |

> Developed By **[Robert Kovacs](https://instagram.com/aka_ale_xander)** - Find my other projects on **[robycodes.com](https://robycodes.com)**
