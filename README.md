This file contains the API call from a pokemon website. 

Notes:
 // 🔗 Base URL for PokéAPI requests
    private val baseUrl = "https://pokeapi.co/api/v2/pokemon/"

    // UI elements
    private lateinit var pokemonImage: ImageView
    private lateinit var nameText: TextView
    private lateinit var typeText: TextView
    private lateinit var nextButton: Button

    // Create one AsyncHttpClient instance (for network calls)
    // This function runs when the app starts.
    // It sets up the layout, initializes the UI elements, and loads the first Pokémon.
    // Connect Kotlin variables to their XML counterparts
    // Set up the "Next Pokémon" button
    // When pressed, it loads a new random Pokémon
    // Load an initial Pokémon when app starts
    // This function randomly selects a Pokémon ID between 1 and 898,
    // then calls the fetchPokemonById() function to get its data from the API.
    // This function takes a Pokémon ID (or name) and makes an HTTP GET request
    // to the PokéAPI to retrieve details such as name, type(s), and sprite image.
    // Make the HTTP GET request
    // This callback runs if the API request was successful (HTTP 200 OK)
    // The response parameter contains the JSON object returned by PokéAPI
    // Extract the sprite image URL
    // Parse the "types" array (can have multiple types like "Grass" and "Poison")
    // Combine types into a readable string
    // Update UI with Pokémon name and type
    // Load the image using Glide
    // Handle JSON parsing errors
        
