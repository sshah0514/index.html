# index.html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Google Clone</title>
        <script src="https://use.fontawesome.com/2180418238.js"></script>
        <link rel="stylesheet" type="text/css" href="style.css">
    </head>
    
    <body>
        <header>
            <ul>
                <li><a href="image_search.html">Search Images</a></li>
                <li><a href="advanced_search.html">Advanced Search</a></li>
                <li><i class="fa fa-th"></i></li>
                <li><i class="fa fa-user"></i></li>
            </ul>
        </header>

        <section>
            <div class="image_container"><img src="images/google_img.png"></div>
            <form action="https://google.com/search" target="_blank">
                <div class="search_bar">
                    <i class="fa fa-search"></i>
                    <input type="text" name="q">
                </div>
                <div class="search_buttons">
                    <input type="submit" value="Google Search">
                    <input type="submit" name="btnI" value="I'm Feeling Lucky">
                </div>
            </form>
            <p>Google offered in: <a href="#">Français</a></p>
        </section>
        <footer>
            <div class="footer1">
                <ul>
                    <li><a href="#">Canada</a></li>
                </ul>
            </div>
            <div class="footer2">
                <ul>
                    <li><a href="#">Advertising</a></li>
                    <li><a href="#">Business</a></li>
                    <li><a href="#">How Search Works</a></li>
                    <li><a href="#">Privacy</a></li>
                    <li><a href="#">Terms</a></li>
                    <li><a href="#">Settings</a></li>
                </ul>
            </div>
        </footer>
    </body>
</html>
