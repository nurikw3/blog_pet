# Blog Pet

A simple blog application built with Python. This project demonstrates basic CRUD operations, user management, and image handling.

## Features
- User registration and authentication
- Blog post creation, editing, and deletion
- Image upload and display
- Database integration with Alembic migrations

## Project Structure
```
blog/
├── app/
│   ├── app.py
│   ├── db.py
│   ├── images.py
│   ├── schemas.py
│   ├── users.py
│   └── alembic/
├── frontend.py
├── index.html
├── main.py
├── pyproject.toml
├── README.md
├── theory.md
├── src/  # Contains screenshots and images
```

## How It Works
1. Start the backend server using `app/app.py`.
2. Access the frontend via `index.html` or `frontend.py`.
3. Register, log in, and create blog posts.
4. Upload images to showcase your posts.

## Screenshots
Below are some screenshots showing how the app works:

![Home Page](src/home.png)
*Home page of the blog application.*

![Create Post](src/create_post.png)
*Form for creating a new blog post.*

![Post List](src/post_list.png)
*List of all blog posts.*

![User Profile](src/profile.png)
*User profile page.*

> Replace the image filenames above with your actual image files in the `src` folder.

## Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/nurikw3/blog_pet.git
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run database migrations:
   ```sh
   alembic upgrade head
   ```
4. Start the application:
   ```sh
   python app/app.py
   ```

## License
MIT

## Author
nurikw3