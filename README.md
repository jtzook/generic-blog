# Generic Blog Platform

This is a web application that allows users to create, read, update and delete (CRUD) posts on a blog platform.

## Setup

### Building and Running Postgres Container

```bash
    docker-compose build
    docker-compose up -d
```

### Running the API

```bash
    cd api
    mvn spring-boot:run
```

## Features

- Users can sign up and log in with their email and password
- Users can create new posts with a title, a content and a timestamp
- Users can view all posts or filter them by author or date
- Users can edit or delete their own posts
- Users can comment on any post
- Users can like or dislike any post or comment

## Dependencies

This project uses the following technologies:

- Java 17 for the backend (Bellsoft Liberica JDK)
- Spring Boot for the web framework
- Postgres for the database
- Hibernate for the object-relational mapping
- React for the frontend
- JUnit 5 for the backend testing framework
- Vitest for the frontend testing framework

## Usage

To use this application, you need to sign up with your email and password first. Then you can log in with your credentials and start creating posts.

To create a new post, click on the `New Post` button on the top right corner of the home page. You will be redirected to a form where you can enter the title and content of your post. Click on the `Submit` button to save your post.

To view all posts, click on the `All Posts` button on the top left corner of the home page. You will see a list of all posts ordered by date. You can also filter them by author or date using the dropdown menus on the top.

To edit or delete your own post, click on the `Edit` or `Delete` button below your post. You will be redirected to an edit form or a confirmation dialog respectively.

To comment on any post, click on the `Comment` button below any post. You will see a form where you can enter your comment. Click on the `Submit` button to save your comment.

To like or dislike any post or comment, click on the `Like` or `Dislike` button below any post or comment. You will see an updated count of likes and dislikes.

### Testing

#### API

`mvn clean verify`
```
