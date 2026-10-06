<div align="center">

<img src="next-reads/public/assets/Logo.png" alt="NextReads logo" width="120" />

# NextReads

**Search, discover and organize your books.**

[**🌐 Live Demo**](https://hci-project-three.vercel.app/) · [**📄 Final Report**](https://app.notion.com/p/NextReads-Search-discover-and-organize-your-books-2610424e489a80b7b89dcde756d059a2?source=copy_link)

</div>

---

## 📖 About

NextReads is a Goodreads-inspired web app for searching books, creating a reader profile and saving your favourites to a personal bookshelf.

## 🏗️ Architecture

```mermaid
flowchart LR
    U["👤 User<br/>(browser)"] <--> V["▲ Vercel<br/>NextReads (Next.js)"]
    V <--> C["📦 Contentful<br/>(data / CMS)"]
```

- **Vercel** — hosts the app
- **Contentful** — stores all the data (books, authors, genres, lists, series, users)

## 📸 Screenshots

| Home page | Book details |
| :---: | :---: |
| ![Home page](docs/screenshots/home_page_FINAL.png) | ![Book details](docs/screenshots/bookdetails.png) |

| Genres | My Books |
| :---: | :---: |
| ![Genres page](docs/screenshots/genres%20pageeeee.png) | ![My Books bookshelf](docs/screenshots/bookshelves.png) |

| Lists | Information architecture |
| :---: | :---: |
| ![Lists page](docs/screenshots/ListsPage.png) | ![Information architecture](docs/screenshots/inf%20arh.png) |

## 🛠️ Built With

Next.js · React · TypeScript · Tailwind CSS · Contentful · Vercel
