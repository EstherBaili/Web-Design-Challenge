# Web Design - Web Visualization Dashboard (Latitude)

## Latitude - Latitude Analysis Dashboard with Attitude

Creating a visualization dashboard website using visualizations (plotting weather data(Resources/cities.csv))

In building this dashboard, individual pages are created for each plot and a means by which people can navigate between them. These pages will contain the visualizations and their corresponding explanations. it also has a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website Specifications


The website consist of 7 pages total, including:

* A [landing page](#landing-page) containing:
  * An explanation of the project.
  * Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
* Four [visualization pages](#visualization-pages), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](#comparisons-page) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
* A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table is a bootstrap table component.
    * The data come from exporting the `.csv` file as HTML using Pandas which has a nifty method approprately called `to_html` that allows to generate a HTML table from a pandas dataframe. 

The website, at the top of every page, have a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive (using media queries). The nav must have similar behavior as the screenshots 

Finally, the website is deployed to GitHub pages.