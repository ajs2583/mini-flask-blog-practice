# Mini Flask Blog

This is a simple blog web app built with Flask. It fetches post data from a mock API (or local JSON file) and renders blog posts using Jinja templates.

## Features

- Home page listing all posts
- Individual blog post pages
- Object-oriented post model
- Templating with Jinja2

## Setup

1. Clone the repository
2. Install requirements:

       pip install -r requirements.txt

3. Run the app:

       python main.py

4. Open your browser and visit:

       http://localhost:5000

## Structure

- `main.py`: Flask routes
- `post.py`: Blog post class
- `post.html`: Template for post view
- `fake_blogs.json`: Sample blog data

## License

MIT
