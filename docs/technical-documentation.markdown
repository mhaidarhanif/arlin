Technical Documentation
=======================

How to develop, build, and use it? Refer to each particular development README in each application folder/repo, those are in [`app`](https://github.com/gunadarma-academy/asde-michi-app) and [`web`](https://github.com/gunadarma-academy/asde-michi-web).

Requirements
------------

### Development Tools

+ Modern code editor such as Vim, Atom, Sublime, WebStorm
+ Terminal and shell (bash/zsh)
+ Modern web browser (Google Chrome or Firefox)

### Design Tools

+ Inkscape
+ SVGO, pngquant

### Isomorphic

+ nvm, Node.js, npm

### Frontend

+ Semantic UI framework
+ Bower (if needed)

### Backend

+ Nginx
+ Hapi.js

### Database

+ NoSQL MongoDB document database

### Network

+ Uniregistry registrar
+ DigitalOcean VPS
+ Cloudflare
+ Google Analytics

*  *  *  *  *  *  *  *  *  *  *  *  *  *  *  *  *  *  *  *

Initial Data Schema
-------------------

### Users

```
+ _id: UUID
+ createdDate: Date
+ updatedDate: Date
+ username: String
```

### Questions

```
+ _id: UUID
+ createdDate: Date
+ updatedDate: Date
+ createdBy: Users._id
+ title: String
+ content: String
```

### Answers

```
+ _id: UUID
+ answerTo: Quetions._id
+ createdDate: Date
+ updatedDate: Date
+ createdBy: Users._id
+ content: String
```

**Notes:**
We're not using `timestamp` type because it's only for internal use of the database, not for application.

