<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Simple Web Page</title>
    <style>
        /* CSS 스타일 */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            color: #333;
        }

        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
        }

        main {
            padding: 20px;
            max-width: 800px;
            margin: 0 auto;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        h1, h2 {
            color: #4CAF50;
        }

        p {
            line-height: 1.6;
        }

        ul {
            list-style-type: square;
            padding-left: 20px;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        a {
            color: #4CAF50;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <!-- 헤더 -->
    <header>
        <h1>Welcome to My Simple Web Page</h1>
        <p>Explore the basic structure of an HTML page</p>
    </header>

    <!-- 메인 콘텐츠 -->
    <main>
        <section>
            <h2>About This Page</h2>
            <p>This is a simple web page created with HTML and CSS. It demonstrates how to structure content and apply basic styles for a clean and professional look.</p>
        </section>

        <section>
            <h2>Features</h2>
            <ul>
                <li>Simple, clean design</li>
                <li>Responsive layout</li>
                <li>Easy to read content</li>
                <li>Basic styling with CSS</li>
            </ul>
        </section>

        <section>
            <h2>Get in Touch</h2>
            <p>If you have any questions, feel free to <a href="mailto:info@example.com">contact us</a>.</p>
        </section>
    </main>

    <!-- 푸터 -->
    <footer>
        <p>&copy; 2024 My Simple Web Page</p>
    </footer>

</body>
</html>
