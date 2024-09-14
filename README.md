<!DOCTYPE html>

<html lang="en">
    <!-- Start of HTML Document -->
    <head>
        <meta charset="UTF-8">
        <!-- Title of the Page -->
        <title>CatPhotoApp</title>
    </head>
    <body>
        <!-- Main content starts here -->
        <main>
            <!-- Main heading for the app -->
            <h1>CatPhotoApp</h1>

            <!-- Section for displaying cat photos -->
            <section>
                <h2>Cat Photos</h2>
                <!-- TODO: Add more links to cat photos if needed -->
                <p>See more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a> in our gallery.</p>
                <a href="https://freecatphotoapp.com">
                    <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back.">
                </a>
            </section>

            <!-- Section for listing things cats love and hate -->
            <section>
                <h2>Cat Lists</h2>

                <!-- Unordered list of things cats love -->
                <h3>Things cats love:</h3>
                <ul>
                    <li>cat nip</li>
                    <li>laser pointers</li>
                    <li>lasagna</li>
                </ul>

                <!-- Image with a caption describing cats' love for lasagna -->
                <figure>
                    <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
                    <figcaption>Cats <em>love</em> lasagna.</figcaption>
                </figure>

                <!-- Ordered list of things cats hate -->
                <h3>Top 3 things cats hate:</h3>
                <ol>
                    <li>flea treatment</li>
                    <li>thunder</li>
                    <li>other cats</li>
                </ol>

                <!-- Image with a caption describing cats' hatred for other cats -->
                <figure>
                    <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
                    <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
                </figure>
            </section>

            <!-- Section with a form for cat details -->
            <section>
                <h2>Cat Form</h2>
                <!-- Form for cat details submission -->
                <form action="https://freecatphotoapp.com/submit-cat-photo">
                    <!-- Radio buttons to choose if the cat is indoor or outdoor -->
                    <fieldset>
                        <legend>Is your cat an indoor or outdoor cat?</legend>
                        <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor" checked> Indoor</label>
                        <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label>
                    </fieldset>

                    <!-- Checkbox for selecting cat's personality -->
                    <fieldset>
                        <legend>What's your cat's personality?</legend>
                        <input id="loving" type="checkbox" name="personality" value="loving" checked> 
                        <label for="loving">Loving</label>
                        <input id="lazy" type="checkbox" name="personality" value="lazy"> 
                        <label for="lazy">Lazy</label>
                        <input id="energetic" type="checkbox" name="personality" value="energetic"> 
                        <label for="energetic">Energetic</label>
                    </fieldset>

                    <!-- Text input for submitting cat photo URL -->
                    <input type="text" name="catphotourl" placeholder="cat photo URL" required>

                    <!-- Submit button for the form -->
                    <button type="submit">Submit</button>
                </form>
            </section>
        </main>

        <!-- Footer section -->
        <footer>
            <p>No Copyright - <a href="https://www.freecodecamp.org">freeCodeCamp.org</a></p>
        </footer>
        <!-- End of HTML Document -->
    </body>
</html>

