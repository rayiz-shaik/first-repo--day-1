# first-repo: 

DAY-1
<!DOCTYPE html>
<html>
<head>
    <title>My First HTML Page</title>
    <meta charset="UTF-8">
</head>
<body>

    <!-- Task 2Y: Add a comment with your name and today's date -->
    <!-- Name: Rayiz Shaik -->
    <!-- Date: 23-04-2025-->

    <!-- Task 1: Display the text "Welcome to Web Development" -->
    <h1>Welcome to Web Development</h1>

    <!-- Task 5: Div with a Paragraph -->
    <div>
        <p>Hello, welcome to learning HTML!</p>
    </div>

    <!-- Task 6: Use strong, em, and mark tags -->
    <p>This is <strong>important</strong>, <em>italicized</em>, and <mark>highlighted</mark> text.</p>

    <!-- Task 7: Hyperlink with target="_blank" -->
    <a href="https://www.google.com" target="_blank">Visit Google</a>

    <!-- Task 8: Image tag with src and alt attributes -->
    <img src="image.jpg" alt="Description of image">

    <!-- Task 9: Use all heading tags -->
    <h1>HTML Headings</h1>
    <h2>HTML Headings</h2>
    <h3>HTML Headings</h3>
    <h4>HTML Headings</h4>
    <h5>HTML Headings</h5>
    <h6>HTML Headings</h6>

    <!-- Task 10: Write a short article -->
    <h1>Understanding HTML</h1>
    <p>HTML stands for HyperText Markup Language. It is used to structure web pages.</p>
    <p>It includes elements like headings, paragraphs, images, and links.</p>

    <!-- Task 11: Formatting Tags -->
    <p><b>Bold</b> <i>Italic</i> <u>Underlined</u></p>

    <!-- Task 12: Superscript and Subscript -->
    <p>Water is written as H<sub>2</sub>O</p>
    <p>Squared number is written as x<sup>2</sup></p>

    <!-- Task 13: Internal Link -->
    <a href="#section1">Go to Section 1</a>
    <h2 id="section1">Section 1</h2>
    <p>Welcome to section 1.</p>

    <!-- Task 14: Navigation Links -->
    <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>

    <!-- Task 15: Image with width and height attributes -->
    <img src="image.jpg" width="300" height="200">

    <!-- Task 16: Image with a caption -->
    <figure>
        <img src="local-image.jpg" alt="A beautiful scene">
        <figcaption>A beautiful scene description</figcaption>
    </figure>

    <!-- Task 17: Unordered List -->
    <h2>Unordered List - Favorite Foods</h2>
    <ul>
        <li>Pizza</li>
        <li>Burger</li>
        <li>Pasta</li>
        <li>Ice Cream</li>
        <li>Sushi</li>
    </ul>

    <!-- Task 18: Ordered List -->
    <h2>Ordered List - Making Tea</h2>
    <ol>
        <li>Boil water.</li>
        <li>Steep tea.</li>
        <li>Strain tea.</li>
        <li>Serve and enjoy.</li>
    </ol>

    <!-- Task 19: Definition List -->
    <h2>Definition List - HTML Tags</h2>
    <dl>
        <dt>p</dt>
        <dd>Defines a paragraph.</dd>

        <dt>a</dt>
        <dd>Creates a hyperlink.</dd>

        <dt>img</dt>
        <dd>Embeds an image.</dd>
    </dl>

</body>
</html>

DAY-2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Tasks</title>
</head>
<body>

    <!-- Task 1: Create a table with Name, Age, and Country -->
    <table border="1">
        <tr>
            <th>Name</th>
            <th>Age</th>
            <th>Country</th>
        </tr>
        <tr>
            <td>Aman</td>
            <td>25</td>
            <td>India</td>
        </tr>
        <tr>
            <td>Raj</td>
            <td>30</td>
            <td>India</td>
        </tr>
        <tr>
            <td>Kumar</td>
            <td>22</td>
            <td>India</td>
        </tr>
    </table>

    <!-- Task 2: Create a table with thead, tbody, and tfoot -->
    <table border="1">
        <thead>
            <tr>
                <th>Name</th>
                <th>Score</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Rajesh</td>
                <td>85</td>
            </tr>
            <tr>
                <td>Kishore</td>
                <td>90</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <td colspan="2">Total Students: 2</td>
            </tr>
        </tfoot>
    </table>

    <!-- Task 3: Add a table caption -->
    <table border="1">
        <caption>Student Data</caption>
        <tr>
            <th>Name</th>
            <th>Marks</th>
        </tr>
        <tr>
            <td>Zakir</td>
            <td>78</td>
        </tr>
    </table>

    <!-- Task 4: Use colspan to span 2 columns -->
    <table border="1">
        <tr>
            <th>Name</th>
            <th colspan="2">Details</th>
        </tr>
        <tr>
            <td>Kartik</td>
            <td>20</td>
            <td>India</td>
        </tr>
    </table>

    <!-- Task 5: Use rowspan to span 2 rows -->
    <table border="1">
        <tr>
            <th>Name</th>
            <th>Age</th>
        </tr>
        <tr>
            <td rowspan="2">Rajesh</td>
            <td>20</td>
        </tr>
        <tr>
            <td>21</td>
        </tr>
    </table>

    <!-- Task 6-10: HTML Form and Inputs -->
    <form>
        <!-- Task 6: Basic form -->
        <label>Name:</label>
        <input type="text" name="name"><br>
        <label>Email:</label>
        <input type="email" name="email"><br>
        <input type="submit" value="Submit"><br>

        <!-- Task 7: Password field and checkbox -->
        <label>Password:</label>
        <input type="password" name="password"><br>
        <input type="checkbox" name="remember"> Remember Me<br>

        <!-- Task 8: Radio buttons -->
        <input type="radio" name="gender" value="Male"> Male
        <input type="radio" name="gender" value="Female"> Female
        <input type="radio" name="gender" value="Other"> Other<br>

        <!-- Task 9: Dropdown -->
        <label>Country:</label>
        <select>
            <option>USA</option>
            <option>UK</option>
            <option>India</option>
        </select><br>

        <!-- Task 10: Textarea and reset button -->
        <label>Feedback:</label>
        <textarea></textarea><br>
        <input type="reset" value="Reset">
    </form>

    <!-- Task 11-15: Semantic Elements -->
    <header><h1>Welcome to My Page</h1></header>
    <nav><a href="#">Home</a> | <a href="#">About</a></nav>
    <main>
        <!-- Task 12: Article -->
        <article><h2>About Us</h2><p>We are a tech company.</p></article>

        <!-- Task 13: Section -->
        <section><h3>Services</h3><p>We provide web development.</p></section>
        <section><h3>Portfolio</h3><p>Check our work.</p></section>
        <section><h3>Contact</h3><p>Email us at info@example.com.</p></section>
    </main>
    <aside><p>Related Links:</p><a href="#">Blog</a></aside>
    <footer>&copy; 2025 My Website</footer>

    <!-- Task 15: Figure -->
    <figure>
        <img src="image.jpg" alt="Example Image">
        <figcaption>Sample Image</figcaption>
    </figure>

    <!-- Task 16-18: HTML Entities -->
    <p>@ &reg; &trade; &gt; &lt; &amp;</p>
    <p>H&nbsp;e&nbsp;l&nbsp;l&nbsp;o&nbsp; W&nbsp;o&nbsp;r&nbsp;l&nbsp;d</p>
    <p>Love &hearts; Money &dollar; Euros &euro;</p>

    <!-- Task 19: HTML Comments -->
    <!-- This is the header section -->
    <header><h1>My Website</h1></header>
    <!-- Navigation -->
    <nav><a href="#">Home</a> | <a href="#">Contact</a></nav>
    <!-- Footer section -->
    <footer>End of the page</footer>

    <!-- Task 20: File Paths -->
    <img src="./images/sample.jpg" alt="Relative Path">
    <img src="https://example.com/sample.jpg" alt="Absolute Path">

</body>
</html>
