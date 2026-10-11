# GMT 458 Web GIS - Personal Page

This is my personal page project that I prepared for the GMT 458 Web GIS course at Hacettepe University Geomatics Engineering.
I created the project using HTML, CSS, and JavaScript codes. I provided various functions on the map by integrating Leaflet and OpenLayers libraries into the page.

## Project Contents

- **Login Screen:** When you first enter the site, a screen appears where you can log in as Admin or Guest. I provided this authorization using `sessionStorage`. If you want to login as Admin, password is "123456". Admin can add marker or remove marker. If admin add or remove marker for one map its upgraded for both map just for local storage.
- **Dual Map System:** There are both Leaflet and OpenLayers maps on the About Me page. You can switch between the two maps with a button.
- **Point Clustering:** I added the clustering feature to both map libraries to prevent clutter when there are too many points on the map.
- **Browser Memory Save:** When logged in as Admin, we can add or delete new markers by clicking on the map. I saved this data to the browser using `localStorage`, so the added points are not lost when the page is refreshed.
- **My Projects:** I compiled my previously developed artificial intelligence, image processing, and data extraction projects on the Projects page.

## File Structure

- `index.html`: The main page containing the initial login screen and general introduction text.
- `about.html`: The page containing the about me section and interactive maps.
- `projects.html`: The page where the projects I developed are introduced.
- `styles.css`: My CSS file containing all the color, font, and animation settings of the site.

---

## My AI Usage
 
The HTML skeleton, CSS structure, animations, and basic logic of the site are based on an old project I wrote from scratch by studying on YouTube by myself during my previous internship. Although I have more advanced versions of this infrastructure, I chose to use this template that I wrote myself, where I know every line, specifically for the course assignment.

While adapting this site template I created to the GMT 458 course, I used artificial intelligence to expand, decorate, and correct the texts on the page. I explained my own internship experiences and how my other artificial intelligence projects work to the AI in Turkish. I asked it to translate what I told into professional, fluent English and turn them into elegant texts of a suitable length for my site. I also asked for help to correct my ReadMe text in the same way.

--
*Tuncay Furkan Uymaz - Hacettepe University Geomatics Engineering*