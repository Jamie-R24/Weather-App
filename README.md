# Weather-App
Simple web-based weather application using JavaScript, HTML, and CSS

This is a simple web based weather app I build utilizing html, javascript, and CSS. I started by building the HTML elements and formatting them with CSS. Then I took the inputs provided by the user and formatted then with an API key to get the weather data for the location they were requesting. From there, I updated the elements within the HTML to display the data they requested. All weather data was gathered by using the free Open Weather App API. 

# How to Use:

Enter city, state, country in search box then press enter or the search button.

To use this program, you can clone the repo onto your device from GitHub and from there launch the index.html page in your browser. Make sure you are connected to the Internet and then you can search for a location in the search box. You can search in many different formats, but for the most specific results, utilize the search bar in the format "city name, state, country." You can search by just city name or city name and country, but you are not guaranteed to find the city you desire, especially if it is a common name. For example, just typing "San Jose" into the box produces San Jose, CA, US data, but if I wanted to find data for San Jose, Costa Rica, typing in just "San Jose" would never produce that. For San Jose, Costa Rica, you must type "San Jose, CR" for weather data corresponding to this location. 


# Additional Notes: 

1. Challenges:
    One challenge I ran into was the CSS for the HTML. I have very limited knowledge of CSS and overall my frontend design experience isn't as heavy as my backend experience. With this, I used a lot of help from online resources to properly format my page the way I wanted it and utilize the correct CSS elements. Additionally, another challenge I ran into was displaying the proper information. By utilizing a basic free API key from Open Weather App, I was able to gather the information for a specific area specified by user input. However, this API call did not return any data about the state of the location for example San Jose, CA. I had to make a separate API call that returned the state and country of the location and then format that into the information displayed on-screen. This created some additional formatting and API call trouble, but ulitimately ended up working. Another challenge I ran into that still sometimes appears in the code is the wrong data being shown based on what the user types in. For example, typing in "Naples, Florida, US" or "Naples, Florida" will display weather data from Naples, Italy but typing in "Naples, US" will display data from "aples, Florida, US. I could not figure out why this was happening and ultimately attributed it to the API key search functionality. 

2. Additional Additions:
    An additional item I wanted to add was the weather data for the upcoming days as seen in the default weather apps on most devices. The problem I ran into was that this information was not accessible with a free API key. Unfortunately for me, I was ultimately unable to implement this feature as I could not find an API key with this information that was also free to use. I also wanted to change the colors of the window depending on the time of day, but I could not figure out how to do this and ultimately left it as it was. This is something I will continue to work on in the future of this project.

3. How many hours:
    This project didn't take me that long. It spanned for basically an entire day and it took me around 5-6 hours to complete. Overall, I learned a lot about CSS, HTML, API calls, and JavaScript. 

4. Which areas took the longest:
    The areas that took the longest were definitely the creation and organization of the HTML page itself. The JavaScript was pretty simple with just two API calls being made and the returned JSONs being easy to handle. My inexperience with frontend design definitely led me to seek help online and ultimately I created a page I was satisfied with. Additionally, the API key took a while to activate, but I did this at the start so while I was designing the HTML, the key would be processed and functioning. 