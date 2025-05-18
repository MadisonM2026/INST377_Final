NutriTrack

Description of your project: Our project is a site that collects and displays the nutritional information. Users will be able to track thier calories, find nutrition facts, and search for new recipies.
Description of target browsers (iOS? Android? Which ones?): Our site is most compatible with IOS users.
Link to Developer Manual: 

Welcome to the NutriTrack Developer Manual. This document is designed to help future developers understand, run, and continue building upon this application. 

Please read carefully and follow the setup instructions to get started.

How to access the webiste:

1. Github will provide a link given the site was deployed through vercel
2. Use this template below to view Nutritrack.
   [Click here to view the deployed NutriTrack app](https://your-deployment-url.com)
   2a. This site uses Supabase as a container for caloric tracking, if using supa base locally, a supabase URL and ANON key will be necessary.
   (exa. # Add your SUPABASE_URL and SUPABASE_ANON_KEY in the .env file) where necessary once files are downloaded and opened.
   2b. To run locally use the live server feature on VS code to jew the site.

3. API's used
   - GET https://world.openfoodfacts.org/api/v0/product/:barcode.json
   - GET https://api.spoonacular.com/recipes/complexSearch?query=QUERY

4. Supabase Entries Table
   - GET /rest/v1/entries Fetch all logged food entries
   - POST /rest/v1/entries Add a new food entry (food, calories_per_serving, servings, total_calories)
  
5. Known issues and Bugs
   - Supabase connectivity issues from local computer to supabase servers
       - Solutions: Use paid premium subscription snd or consult with customer services the unpaid verison has dependability and priority issues amongst users.
