<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- Responsive -->
    <link rel="icon" type="image/png" sizes="32x32" href="./assets/images/favicon-32x32.png">
    <link rel="stylesheet" href="css/style.css"> <!-- Lien vers le CSS -->
    <title>Frontend Mentor | Recipe page</title>
</head>
<body>
    <div>
        <!-- Image -->
        <img src="assets/images/image-omelette.jpeg" alt="Simple Omelette" />

        <!-- Title -->
        <h1>Simple Omelette Recipe</h1>
        <p>
            An easy and quick dish, perfect for any meal. This classic omelette combines beaten eggs cooked
            to perfection, optionally filled with your choice of cheese, vegetables, or meats.
        </p>

        <!-- Preparation Time -->
        <div class="prep-time">
            <h2 class="couleur">Preparation time</h2>
            <p><strong>Total:</strong> Approximately 10 minutes</p>
            <p><strong>Preparation:</strong> 5 minutes</p>
            <p><strong>Cooking:</strong> 5 minutes</p>
        </div>

        <!-- Ingredients -->
        <h2 class="couleur">Ingredients</h2>
        <ul>
            <li>2-3 large eggs</li>
            <li>Salt, to taste</li>
            <li>Pepper, to taste</li>
            <li>1 tablespoon of butter or oil</li>
            <li>Optional fillings: cheese, diced vegetables, cooked meats, herbs</li>
        </ul>

        <!-- Instructions -->
        <h2 class="couleur">Instructions</h2>
        <ol>
            <li><strong>Beat the eggs:</strong> In a bowl, beat the eggs with a pinch of salt and pepper until they are well mixed. You can add a tablespoon of water or milk for a fluffier texture.</li>
            <li><strong>Heat the pan:</strong> Place a non-stick frying pan over medium heat and add butter or oil.</li>
            <li><strong>Cook the omelette:</strong> Once the butter is melted and bubbling, pour in the eggs. Tilt the pan to ensure the eggs evenly coat the surface.</li>
            <li><strong>Add fillings (optional):</strong> When the eggs begin to set at the edges but are still slightly runny in the middle, sprinkle your chosen fillings over one half of the omelette.</li>
            <li><strong>Fold and serve:</strong> As the omelette continues to cook, carefully lift one edge and fold it over the fillings. Let it cook for another minute, then slide it onto a plate.</li>
            <li><strong>Enjoy:</strong> Serve hot, with additional salt and pepper if needed.</li>
        </ol>

        <!-- Nutrition -->
        <h2 class="couleur">Nutrition</h2>
        <p>The table below shows nutritional values per serving without the additional fillings.</p>
        <table class="nutrition-table">
            <tr>
                <td><strong>Calories</strong></td>
                <td class="couleur">277kcal</td>
            </tr>
            <tr>
                <td><strong>Carbs</strong></td>
                <td class="couleur">0g</td>
            </tr>
            <tr>
                <td><strong>Protein</strong></td>
                <td class="couleur">20g</td>
            </tr>
            <tr>
                <td><strong>Fat</strong></td>
                <td class="couleur">22g</td>
            </tr>
        </table>

        <!-- Attribution -->
        <div class="attribution">
            Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>.
            Coded by <a href="#">Daniel</a>.
        </div>
    </div>
</body>
</html>
