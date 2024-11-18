# Animated Maps using Plolty to Video and GIF


This script generates an animated choropleth map video and GIF showing GDP per capita by country over time using World Bank data.

Steps:
1. Import necessary libraries.
2. Define the World Bank indicators for population and GDP per capita.
3. Fetch data for all countries and preprocess it.
4. Handle missing values and filter data for valid years.
5. Categorize GDP per capita into bins and define color mappings.
6. Create a directory to save frames and remove it if it already exists.
7. Generate and save choropleth map frames for each year.
8. Collect image file paths and create an animation from the image sequence.
9. Save the animation as MP4 and GIF files.
10. Optionally, save an HD version of the video.
11. Remove the frames directory after creating the animations.

Functions:
- Fetch data from World Bank and preprocess it.
- Categorize GDP per capita into bins.
- Generate and save choropleth map frames.
- Create and save animations from the frames.

Output:
- Animated choropleth map video (MP4) and GIF showing GDP per capita by country over time.
