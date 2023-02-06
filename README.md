# Blog application
Blog app in Scala and Akka

## Current file structure:
```
├── LICENSE
├── README.md
├── build.sbt
├── project
│   ├── build.properties
...
├── src
│   ├── main
│   │   ├── scala
│   │   │   ├── BlogEngine.scala
│   │   │   ├── controllers
│   │   │   │   └── BlogController.scala
│   │   │   └── src
│   │   │       └── main
│   │   └── views
│   │       └── template
│   │           └── index.html
│   └── test
│       └── scala
│           └── MySuite.scala
```

## How to run this app:
Clone or download this repo:
```
git clone https://github.com/nikpalyi/blog-app.git
```
After cloning or download, run:
```
cd blog-app
```
OR
```
cd blog-app-master
```
Run:
```
sbt compile
```

Run:
```
sbt run
```

•• Plan:

TBD

### TODO Checklist:
- [ ] Testing
- [ ] Refactoring
- [ ] ... 

### Additional feature ideas for nice to hvae future:

- User authentication and authorization: You can allow users to sign up, log in, and log out of the application. You can also restrict access to certain pages or actions based on the user's role (e.g. admin, author, reader).

- Comment system: You can allow users to leave comments on blog posts. You can implement moderation controls to approve or reject comments.

- Categories and tags: You can allow users to categorize their blog posts into different categories and add tags to make it easier for readers to find related content.

- Image and media uploads: You can allow users to upload images and other media files to accompany their blog posts.

- Search and filtering: You can implement a search bar that allows users to search for specific posts based on keywords, categories, tags, author, etc. You can also implement filtering options to allow users to sort posts by date, popularity, etc.

- Email notifications: You can send email notifications to users when new posts are published, comments are added, etc.

- Social sharing: You can add social sharing buttons to allow users to share blog posts on social media platforms.

- Responsive design: You can make the blog application responsive so that it looks good on different devices and screen sizes.