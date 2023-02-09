<!-------- BADGES ------->

<div id="badges" align="center">
	<a name="readme-top"></a>
	<a href="https://www.mandyhpnguyen.com" rel="nofollow"><img src="https://raw.githubusercontent.com/MandyHPNguyen/mGarage4images/main/shield-badges/Website-mandyhpnguyen-com.svg" alt="Mandy HP Nguyen Email"></a>
	<a href="mailto:MandyHPNguyen@gmail.com?subject=Mail from GitHub" rel="nofollow"><img src="https://raw.githubusercontent.com/mandyhpnguyen/mGarage4images/main/shield-badges/Email-mandyhpnguyen-red.svg" alt="Mandy HP Nguyen Email"></a>
	<a href="https://www.linkedin.com/in/mandyhpnguyen/" rel="nofollow"><img src="https://raw.githubusercontent.com/mandyhpnguyen/mGarage4images/main/shield-badges/LinkedIn-%40MandyHPNguyen-blue.svg" alt="Mandy HP Nguyen LinkedIn"></a>
	<a href="https://github.com/mandyhpnguyen" rel="nofollow"><img src="https://raw.githubusercontent.com/mandyhpnguyen/mGarage4images/main/shield-badges/GitHub-%40MandyHPNguyen-black.svg" alt="Mandy HP Nguyen GitHub"></a>
	<a href="https://paypal.me/MandyHPNguyen" rel="nofollow"><img src="https://raw.githubusercontent.com/mandyhpnguyen/mGarage4images/main/shield-badges/BuyMeACoffee%E2%98%95-PayPal-brown.svg" alt="Mandy HP Nguyen PayPal Donate"></a>
</div>

<!------- HEADER ------->

<div id="header" align="center">
	<h1>IMDb Worldwide Top Movies Over 100 Years</h1>
	<a href="https://app.powerbi.com/view?r=eyJrIjoiNzZlMDk0MDAtYmJkNC00OGFhLTk2YWQtNGZmZWI2YmNmMjcwIiwidCI6ImMzMjk5OGJhLWJhZjYtNDBjYS04ZWE0LWM3MzE4OGQzOGQ1OSJ9" target="_blank" rel="noopener noreferrer">
		<img src="https://raw.githubusercontent.com/mandyhpnguyen/mGarage4images/main/shield-badges/Power%20BI-Dashboard-yellow.svg" alt="Mandy HP Nguyen Power BI">
	</a>
	<h3><strong>by Mandy HP Nguyen</strong></h3>
</div>

<!------- ABSTRACT ------->

This project provides a Power BI dashboard, publicly **published on** my website [mandyhpnguyen.com](https://www.mandyhpnguyen.com/data-visualization/gallery/), **of** the best movies of all time over 100 years (1920-2020) **based on** box offices' gross revenues **grouped by** MPAA ratings **with** multiples ways to filter directly on the webpage and quickly lookup definitions (MPAA ratings meaning) **for** data exploratory analysis purpose or simply curiosity reason. The data was published on [Box Office Moji](https://www.boxofficemojo.com/) by IMDb Pro and updated as of March 10, 2022.

<div id="pbi-link" align="center">
	<img src="https://raw.githubusercontent.com/MandyHPNguyen/IMDb-top-movies-over-100-years-powerBI-dashboard/main/images/project/dashboard_overview.gif" alt="Power BI Dashboard by Mandy HP Nguyen">
	<a href="https://app.powerbi.com/view?r=eyJrIjoiNzZlMDk0MDAtYmJkNC00OGFhLTk2YWQtNGZmZWI2YmNmMjcwIiwidCI6ImMzMjk5OGJhLWJhZjYtNDBjYS04ZWE0LWM3MzE4OGQzOGQ1OSJ9" target="_blank" rel="noopener noreferrer">
		<p><i>👉👉 Click the button below to Play with Dashboard 👈👈</i></p>
		<img src="https://raw.githubusercontent.com/mandyhpnguyen/mGarage4images/main/shield-badges/Power%20BI-Dashboard-yellow.svg" alt="Mandy HP Nguyen Power BI">
	</a>
</div>

<!------- TABLE OF CONTENTS ------->

## Table of Contents

<details class="contentTable">	
	<summary>details</summary>
	<ol>
		<li>
			<a href="#about-the-project">About The Project</a>
			<ul>
				<li>
					<a href="#data">Data</a>
				</li>
				<li>
					<a href="#methodology">Methodology</a>
				</li>
				<li>
					<a href="#technology">Technology</a>
				</li>
				<li>
					<a href="#dashboard-and-features">Dashboard and Features</a>
				</li>
			</ul>
		</li>
		<li><a href="#contribution">Contribution</a></li>
		<li><a href="#license">License</a></li>
		<li><a href="#contact">Contact</a></li>
		<li><a href="#acknowledgments"> Acknowledgments</a></li>
	</ol>
</details>

<!-------- ABOUT ------->
## About the Project

### Data
3 sets of data including texts and images were manually collected and updated as of March 2, 2022.
- [GitHub Folder of Text Data](https://github.com/MandyHPNguyen/IMDb-top-movies-over-100-years-powerBI-dashboard/tree/31c385fc2e049bf6fc5ec976b67c94608ef52b9e/masterData)
- [GitHub Folder of Image Data](https://github.com/MandyHPNguyen/IMDb-top-movies-over-100-years-powerBI-dashboard/tree/31c385fc2e049bf6fc5ec976b67c94608ef52b9e/images)
#### Movie Ranking
- The set is publicly provided by [Box Office Mojo](https://www.boxofficemojo.com/) (IMDb)
- The specific category chosen is [**All Time** sub-categorized by MPAA ratings](https://www.boxofficemojo.com/charts/overall/?ref_=bo_nb_rs_tab)
##### Collecting Process
- The data was hand-selected by my data entry and cleaning, stored in [this file](https://github.com/MandyHPNguyen/IMDb-top-movies-over-100-years-powerBI-dashboard/blob/31c385fc2e049bf6fc5ec976b67c94608ef52b9e/masterData/IMDb_Top_Movies_by_MPPA_20220302.xlsx) , each MPAA rating per spreadsheet.
- Then, the spreadsheets were concatenated into [one file](https://github.com/MandyHPNguyen/IMDb-top-movies-over-100-years-powerBI-dashboard/blob/31c385fc2e049bf6fc5ec976b67c94608ef52b9e/masterData/MPPA-Rating_Definition_Pivot_20220302.xlsx) for data input into Power BI file (.pbix).
- The data structure of this set is as follows:

| Attribute      | Definition                                                                  | Data Type |
| -------------- | --------------------------------------------------------------------------- | --------- |
| Title          | Name of Movies                                                              | Text      |
| MPAA Rating    | Types of Movies rating based on MPAA                                        | Text      |
| Lifetime Gross | Gross Revenue of all time                                                   | Integer   |
| MPAA Rank      | Movie rank within each category based on gross revenues within this dataset | Text      |
| Overall Rank   | Movie rank within all category based on gross revenues within this dataset  | Text      |
| Year           | Box Office release year                                                     | Text      |                                                    |           |

- Record Summary: Total number of records (movie titles) is 3,600 including:

| MPPA Rating | Count of Title |
| ----------- | -------------- |
| G           | 558            |
| NC-17       | 42             |
| PG          | 1,000          |
| PG-13       | 1,000          |
| R           | 1,000          |
| Total       | 3,600          |

#### MPAA Definitions
The definitions of 5 movie rating categories defined by MPAA were referenced from [Wikipedia](https://en.wikipedia.org/wiki/Motion_Picture_Association_film_rating_system) as follows:

- G – General Audiences - "Nothing that would offend parents for viewing by children."  On the box: "All ages admitted"

<a align="left"><img height="100" src="https://github.com/mandyhpnguyen/IMDb-top-movies-over-100-years-powerBI-dashboard/blob/main/images/movie_logos/MPA_G_RATING_(block)-White.png?raw=true"></a>

- PG – Parental Guidance Suggested - "Parents urged to give 'parental guidance.' May contain some material parents might not like for their young children."  
On the box: "Some material may not be suitable for children"

<a align="left"><img height="100"  src="https://github.com/mandyhpnguyen/IMDb-top-movies-over-100-years-powerBI-dashboard/blob/main/images/movie_logos/MPA_PG_RATING_(block) White.png?raw=true)"></a>

- PG-13 – Parents Strongly Cautioned - "Parents are urged to be cautious. Some material may be inappropriate for pre-teenagers."  
On the box: "Some material may be inappropriate for children under 13"

<a align="left"><img height="100"  src="https://github.com/mandyhpnguyen/IMDb-top-movies-over-100-years-powerBI-dashboard/blob/main/images/movie_logos/MPA_PG-13_RATING_(block) - White.png?raw=true"></a>

- R – Restricted - "Contains some adult material. Parents are urged to learn more about the film before taking their young children with them."  
On the box: "Under 17 requires accompanying parent or adult guardian"

<a align="left"><img height="100" src="https://github.com/mandyhpnguyen/IMDb-top-movies-over-100-years-powerBI-dashboard/blob/main/images/movie_logos/MPA_R_RATING_(block) - White.png?raw=true"></a>

- NC-17 – Adults Only - "Clearly adult. Children are not admitted." On the box: "No One 17 and Under Admitted"

<a align="left"><img height="100" src="https://github.com/mandyhpnguyen/IMDb-top-movies-over-100-years-powerBI-dashboard/blob/main/images/movie_logos/MPA_NC-17_RATING_(block)-White.png?raw=true"></a>

#### Images
##### MPAA Logos
- [Wikipedia](https://en.wikipedia.org/wiki/Motion_Picture_Association_film_rating_system)
- [GitHub Folder](https://github.com/MandyHPNguyen/IMDb-top-movies-over-100-years-powerBI-dashboard/tree/31c385fc2e049bf6fc5ec976b67c94608ef52b9e/images/movie_logos)
##### IMDb Logos
- [Official IMDb Brand Guideline](https://en.wikipedia.org/wiki/Motion_Picture_Association_film_rating_system)
- [GitHub Folder](https://github.com/MandyHPNguyen/IMDb-top-movies-over-100-years-powerBI-dashboard/tree/31c385fc2e049bf6fc5ec976b67c94608ef52b9e/images/imdb_logos)

##### Taskbar Menu Icons
- [flaticon](https://www.flaticon.com/)
- [GitHub Folder](https://github.com/MandyHPNguyen/IMDb-top-movies-over-100-years-powerBI-dashboard/tree/31c385fc2e049bf6fc5ec976b67c94608ef52b9e/images/menu_icons)


### Methodology
- web-scraping
- data collection
- data processing
- data visualization
- data analysis

### Technology 
- Box Office Moji by IMDb website
- MS Excel
- Power BI
- Power Platform
- Dax
- Power Query

### Dashboard and Features
The dashboard comprises of 4 pages including Home, Overview, and References with the following features and developing plan as follows:
#### Home
#### Overview
#### Rating
#### References

<p align="right"><a href="#readme-top">🔝back to top</a></p>

<!-------- CONTRIBUTION ------->
## Contribution
Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please *fork the repo* and *create a pull request* ([instruction](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/incorporating-feedback-in-your-pull-request)).

OR simply email [mandyhpnguyen@gmail.com](mailto:mandyhpnguyen@gmail.com).

Don't forget to *give the project a star* ⭐! Thanks again 🙏!

<p align="right"><a href="#readme-top">🔝back to top</a></p>

<!-------- LICENSE ------->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right"><a href="#readme-top">🔝back to top</a></p>

<!-------- CONTACT ------->
## Contact

Mandy HP Nguyen
[***Email***: *MandyHPNguyen@gmail.com*](mailto:MandyHPNguyen@gmail.com) - [***LinkedIn***: *@MandyHPNguyen*](https://www.linkedin.com/in/mandyhpnguyen/) - [***Medium***: *@MandyHPNguyen*](https://medium.com/mandyhpnguyen)

Project Links
[***GitHub Repository***](https://github.com/MandyHPNguyen/IMDb-top-movies-over-100-years-powerBI-dashboard) - [***Power BI Dashboard***](https://app.powerbi.com/view?r=eyJrIjoiNzZlMDk0MDAtYmJkNC00OGFhLTk2YWQtNGZmZWI2YmNmMjcwIiwidCI6ImMzMjk5OGJhLWJhZjYtNDBjYS04ZWE0LWM3MzE4OGQzOGQ1OSJ9")

<!--[Medium's Blog]()-->

<p align="right"><a href="#readme-top">🔝back to top</a></p>

<!-------- ACKNOWLEDGMENTS ------->
## Acknowledgments
- [IMDb Ranking Open Source Data](https://www.boxofficemojo.com/)
- [MPAA Film Ratings Official Site](https://www.motionpictures.org/film-ratings/)
- [Wikipedia on MPAA Rating & Logos](https://en.wikipedia.org/wiki/Motion_Picture_Association_film_rating_system)
- [Create Decades Style 1](https://%20https//www.youtube.com/watch?v=ByIUx-HmQbw)﻿
- [Create Decades Style 2](https://community.powerbi.com/t5/Desktop/Drill-by-decade/m-p/32619)
- [Collect IMDb Data](https://www.youtube.com/watch?v=XuGw3tGWmNE)
- [Menu Icons](https://www.flaticon.com/)
- [IMDb Design Toolkit, Logos, and Brand Guidelines](https://brand.imdb.com/imdb)

<p align="right"><a href="#readme-top">🔝back to top</a></p>
