
# Re-Former Project

This project demonstrates the fundamentals of building forms in Rails by creating a simple application for managing users.

## Introduction

The **Re-Former** project gives you hands-on experience in creating forms with Rails, progressing from raw HTML forms to Rails helpers such as `form_with`. The project covers the entire process, including creating and handling forms for user registration and editing.

---

## Features

- Build forms using plain HTML.
- Enhance forms with Rails helpers (`form_tag` and `form_with`).
- Implement CSRF protection in forms.
- Create user registration and editing functionality.
- Validate user inputs with Rails validations.
- Integrate Turbo for seamless form submissions.
- Handle errors and display validation messages effectively.

---

## Technologies Used

- **Ruby on Rails**: The main framework for this project.
- **HTML**: Used for the raw form structure.
- **Turbo**: For enabling AJAX-like form submissions without full-page reloads.

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone git@github.com:fabortwell/re-former.git
cd re-former
```

### 2. Install Dependencies

Make sure you have Ruby and Rails installed. Then, run:

```bash
bundle install
```

### 3. Database Setup

Run the following commands to set up the database:

```bash
rails db:create
rails db:migrate
```

### 4. Start the Server

Start the Rails server:

```bash
rails server
```

Visit [http://localhost:3000/users/new](http://localhost:3000/users/new) to access the app.

---

## How It Works

### 1. Plain HTML Form
- Build a user registration form in pure HTML.
- Handle CSRF protection by adding an authenticity token manually.

### 2. Rails Forms
- Replace the plain HTML form with `form_tag` helpers.
- Progress to `form_with` for model-backed forms.

### 3. Editing Users
- Add functionality to edit an existing user.
- Implement form submissions with `PATCH` requests for updates.

---

## Validations and Error Handling

- Validates presence of `username`, `email`, and `password`.
- Displays validation error messages when input is invalid.

---

## Learning Objectives

- Understand the differences between HTML forms and Rails forms.
- Learn how Rails helpers simplify form-building.
- Use Turbo for better user experience with Rails 8.
- Practice working with user input and validations in Rails.

---

## Contributing

Feel free to fork this project and contribute. To suggest changes, create a pull request or open an issue.

---

## License

This project is open-source and available under the [MIT License](LICENSE).

---
