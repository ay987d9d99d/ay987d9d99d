---
const title = "About Us";
const description = "This is the about page of our basic Astro app.";
---

<html>
<head>
    <title>{title}</title>
    <meta name="description" content={description} />
</head>
<body>
    <h1>{title}</h1>
    <p>{description}</p>
    <a href="/">Go back home</a>
</body>
</html>
