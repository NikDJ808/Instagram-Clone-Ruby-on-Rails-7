# Instagram Clone Using Rails 7

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)


## Introduction

This project is an Instagram clone built using Ruby on Rails 7. It aims to replicate some of the core functionalities of Instagram, including user authentication, photo uploads, liking posts, and following other users. This project is intended to demonstrate a full-stack web application using modern web technologies.

## Features

- User authentication (sign up, log in, log out)
- Profile creation and management
- Photo uploads with image preview
- Liking and commenting on posts
- Following and unfollowing other users
- Real-time updates and notifications
- Responsive design

## Technologies Used

- **Ruby on Rails 7**: The web application framework used for development.
- **PostgreSQL**: Database management system.
- **Devise**: Authentication solution for Rails.
- **Active Storage**: For handling file uploads.
- **StimulusJS**: For frontend interactivity.
- **Bootstrap**: For responsive design and styling.
- **FilePond**: For file uploads with image previews.
- **RSpec**: For testing the application.

## Setup and Installation

### Prerequisites

Ensure you have the following installed on your local development environment:

- Ruby 3.0.0 or newer
- Rails 7.0.0 or newer
- PostgreSQL
- Node.js
- Yarn

### Installation Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/instagram-clone-rails-7.git
   cd instagram-clone-rails-7
   ```

2. **Install dependencies:**

   ```bash
   bundle install
   yarn install
   ```

3. **Setup the database:**

   ```bash
   rails db:create
   rails db:migrate
   rails db:seed
   ```

4. **Start the Rails server:**

   ```bash
   rails server
   ```

5. **Visit the application:**

   Open your web browser and go to `http://localhost:3000`.

## Usage

Once the application is up and running, you can:

- Sign up for a new account.
- Create and edit your profile.
- Upload photos and see them on your feed.
- Like and comment on posts.
- Follow other users to see their posts in your feed.

## Folder Structure

Here is an overview of the main directories and files in the project:

```
Instagram-clone-using-rails-7-main/
├── app/
│   ├── assets/
│   │   ├── config/
│   │   ├── images/
│   │   └── stylesheets/
│   ├── controllers/
│   ├── helpers/
│   ├── javascript/
│   ├── models/
│   ├── views/
│   └── channels/
├── bin/
├── config/
│   ├── environments/
│   ├── initializers/
│   ├── locales/
│   └── application.rb
├── db/
│   ├── migrate/
│   ├── schema.rb
│   └── seeds.rb
├── lib/
├── log/
├── public/
├── test/
├── tmp/
├── vendor/
├── Gemfile
├── Gemfile.lock
├── Rakefile
├── config.ru
└── README.md
```

