<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jewelry Sales Store</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" integrity="sha512-9usAa10IRO0HhonpyAIVpjrylPvoDwiPUiKdWk5t3PyolY1cOd4DSE0Ga+ri4AuTroPR5aQvXU9xC6qOPnzFeg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <style>
        body {
            font-family: sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
        }

        header {
            background-color: #b39ddb;
            color: white;
            text-align: center;
            padding: 2em 0;
        }

        section {
            padding: 2em;
            display: flex;
            flex-wrap: wrap;
            justify-content: center; /* Center boxes horizontally */
        }

        .box {
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            margin: 1em;
            padding: 1.5em;
            width: 250px;
            text-align: center;
            transition: transform 0.3s ease;
            border: 1px solid #ddd;
        }
        .box:hover {
            transform: scale(1.05);
        }

        footer {
            background-color: #e0e0e0;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .box i {
            font-size: 3em; /* Increased Icon size */
            margin-bottom: 0.5em;
            color: #b39ddb;
        }

         h2 {
            width: 100%;
            text-align: center;
            margin-bottom: 1em;
            padding: 0.5em; /* Add some padding around h2 */
            border-bottom: 1px solid #ddd; /* Add a line below the header */
        }

    </style>
</head>
<body>
    <header>
        <h1><i class="fas fa-gem"></i> Welcome to Our Jewelry Store</h1>
    </header>

    <section>
         <h2>Our Collection</h2>

        <div class="box">
            <i class="fas fa-ring"></i>
            <h3>Rings</h3>
            <p>Elegant rings made with precision.</p>
        </div>

        <div class="box">
            <i class="fas fa-necklace"></i>
            <h3>Necklaces</h3>
             <p>Stylish necklaces for every occasion.</p>
        </div>

         <div class="box">
            <i class="fas fa-earrings"></i>
            <h3>Earrings</h3>
            <p>Beautiful earrings to add elegance.</p>
        </div>
        <div class="box">
            <i class="fas fa-gem"></i>
            <h3>Special Collection</h3>
            <p>One of a kind jewelry that stands out.</p>
        </div>
    </section>


    <footer>
        <p><i class="fas fa-envelope"></i> Contact us: info@jewelrystore.com</p>
    </footer>
</body>
</html>
