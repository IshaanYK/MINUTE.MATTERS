<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MINUTE.MATTERS.SAVED'LINKS.ONION</title>
    <style>
        body {
            font-family: 'Verdana', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to right, #a18cd1, #fbc2eb);
            color: #333;
        }
        header {
            background: linear-gradient(to right, #ff7e5f, #feb47b);
            color: white;
            padding: 2rem;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            position: relative;
        }
        header img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-bottom: 1rem;
            border: 2px solid white;
        }
        header h1 {
            font-size: 2.8rem;
            margin: 0;
        }
        header p {
            font-size: 1.2rem;
            margin: 0.5rem 0;
        }
        main {
            max-width: 900px;
            margin: 2rem auto;
            padding: 1rem;
            background: white;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            border-radius: 12px;
        }
        h2 {
            font-size: 1.8rem;
            color: #ff7e5f;
            margin-bottom: 0.5rem;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        ul li {
            margin: 0.8rem 0;
            font-size: 1.1rem;
        }
        a {
            color: #ff7e5f;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .add-link, .add-category {
            margin-top: 2rem;
            padding: 1rem;
            background-color: #f9f9f9;
            border: 1px solid #ddd;
            border-radius: 8px;
        }
        .add-link input, .add-link select, .add-category input {
            width: calc(100% - 2rem);
            padding: 0.8rem;
            margin: 0.5rem 0;
            border: 1px solid #ccc;
            border-radius: 4px;
            display: block;
        }
        .add-link button, .add-category button {
            padding: 0.8rem 1.5rem;
            background-color: #ff7e5f;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        .add-link button:hover, .add-category button:hover {
            background-color: #e64a19;
        }
        .about {
            margin-bottom: 2rem;
        }
        .social-links {
            display: flex;
            justify-content: center;
            margin-top: 2rem;
        }
        .social-links a {
            margin: 0 1rem;
            text-decoration: none;
        }
        .social-links img {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            border: 2px solid #fff;
        }
        footer {
            text-align: center;
            margin: 2rem 0;
            font-size: 1rem;
            color: #555;
        }
    </style>
</head>
<body>
    <header>
        <img src="/mnt/data/461462685_2598653640336766_6699770147676742030_n.jpg" alt="Website Logo">
        <h1>MINUTE.MATTERS.SAVED'LINKS.ONION</h1>
        <p>Your ultimate destination to save and organize all your important links!</p>
    </header>
    <main>
        <section class="about">
            <h2>Why Choose MINUTE.MATTERS.SAVED'LINKS.ONION?</h2>
            <p>This website is designed to help you store, categorize, and quickly access all your important links. Whether it's news, learning resources, or tools, everything is just a click away. With a user-friendly interface and customizable categories, managing your links has never been easier.</p>
        </section>
        <section id="categories">
            <div class="link-category">
                <h2>News</h2>
                <ul id="news-links">
                    <li><a href="https://www.bbc.com/news" target="_blank">BBC News</a></li>
                    <li><a href="https://www.cnn.com" target="_blank">CNN</a></li>
                </ul>
            </div>
            <div class="link-category">
                <h2>Life Lessons</h2>
                <ul id="life-lessons-links">
                    <li><a href="https://www.ted.com/talks" target="_blank">TED Talks</a></li>
                    <li><a href="https://jamesclear.com" target="_blank">Atomic Habits by James Clear</a></li>
                </ul>
            </div>
            <div class="link-category">
                <h2>Useful Tools</h2>
                <ul id="tools-links">
                    <li><a href="https://www.canva.com" target="_blank">Canva</a></li>
                    <li><a href="https://www.notion.so" target="_blank">Notion</a></li>
                </ul>
            </div>
        </section>
        <div class="add-link">
            <h2>Add a New Link</h2>
            <form id="add-link-form">
                <select id="category" required>
                    <option value="news">News</option>
                    <option value="life-lessons">Life Lessons</option>
                    <option value="tools">Useful Tools</option>
                </select>
                <input type="text" id="link-name" placeholder="Link Name" required>
                <input type="url" id="link-url" placeholder="Link URL" required>
                <button type="submit">Add Link</button>
            </form>
        </div>
        <div class="add-category">
            <h2>Add a New Category</h2>
            <form id="add-category-form">
                <input type="text" id="category-name" placeholder="Category Name" required>
                <button type="submit">Add Category</button>
            </form>
        </div>
        <div class="social-links">
            <a href="https://www.youtube.com/@minute.matters" target="_blank">
                <img src="https://upload.wikimedia.org/wikipedia/commons/4/42/YouTube_icon_%282013-2017%29.png" alt="YouTube">
            </a>
            <a href="https://www.instagram.com/minute.matters" target="_blank">
                <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram">
            </a>
        </div>
    </main>
    <footer>
        <p>Created by Ishaan Sen &copy; 2024</p>
    </footer>
    <script>
        document.getElementById('add-link-form').addEventListener('submit', function(e) {
            e.preventDefault();

            const category = document.getElementById('category').value;
            const linkName = document.getElementById('link-name').value;
            const linkUrl = document.getElementById('link-url').value;

            const newLink = document.createElement('li');
            const newAnchor = document.createElement('a');
            newAnchor.href = linkUrl;
            newAnchor.target = '_blank';
            newAnchor.textContent = linkName;
            newLink.appendChild(newAnchor);

            const categoryList = document.getElementById(`${category}-links`);
            categoryList.appendChild(newLink);

            document.getElementById('add-link-form').reset();
        });

        document.getElementById('add-category-form').addEventListener('submit', function(e) {
            e.preventDefault();

            const categoryName = document.getElementById('category-name').value;
            const categoryId = categoryName.toLowerCase().replace(/\s+/g, '-');

            const newCategory = document.createElement('div');
            newCategory.classList.add('link-category');

            const newHeading = document.createElement('h2');
            newHeading.textContent = categoryName;
            newCategory.appendChild(newHeading);

            const newList = document.createElement('ul');
            newList.id = `${categoryId}-links`;
            newCategory.appendChild(newList);

            document.getElementById('categories').appendChild(newCategory);

            const newOption = document.createElement('option');
            newOption.value = categoryId;
            newOption.textContent = categoryName;
            document.getElementById('category').appendChild(newOption);

            document.getElementById('add-category-form').reset();
        });
    </script>
</body>
</html>
