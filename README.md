## UFOs

In this project I used JavaScript, bootstrap, CSS Style sheets in order to create a webpage that ha dynamic tables of UFO sighting data. Using the webpage, users can filter the data using criteria in order to see results dynamically. 

The Resources used included:

 - Data Source: data.js
 - Software: HTML, CSS, Bootstrap, D3, and E6+

## #1 Overview of the Project:

The purpose of this analysis was to build an HTML page that allows uses to find information for the city, state, country, shape, and date through the table filters that were created using JavaScript and HTML. 
<img width="1179" alt="Screen Shot 2022-05-10 at 12 37 23 PM" src="https://user-images.githubusercontent.com/93094173/167679370-146c97cd-1006-4411-9bb0-a27bee20eedf.png">

<img width="1189" alt="Screen Shot 2022-05-10 at 12 37 29 PM" src="https://user-images.githubusercontent.com/93094173/167679380-e055e684-50c2-4876-8200-58c7fd0638b5.png">

## #2 Results: Describe to Dana how someone might use the new webpage by walking her through the process of using the search criteria. Use images of your webpage during the filtering process to support your explanation.

Someone may use the new webpage by searching for UFO activity within a certain state. For instance, let's say an end user was looking for all UFO activity in the state of MA in United States, they could select the filter for state: "MA" and country: "USA" to return the following results with specific information per the user request.

<img width="1374" alt="Screen Shot 2022-05-10 at 12 57 13 PM" src="https://user-images.githubusercontent.com/93094173/167682698-90892570-0cb9-416a-b5c3-a8539114587f.png">

By design, this website is intuitive to use and similar to other websites and filtering available in say, travel booking websites like Hotwire, or when searching for items on a Target website using specific filters.

In order to create a new search, the user can Refresh the page or clear their previous selections. 

Another potential search could be by dates. Let's say a user is looking for information on all UFO sightings for the date of 1/2/2010, they would search using the following criteria that would render the following results:

<img width="1296" alt="Screen Shot 2022-05-10 at 1 00 53 PM" src="https://user-images.githubusercontent.com/93094173/167683190-441c170a-cd55-4c59-b730-2ae0910fb163.png">


## #3 Summary: In a summary statement, describe one drawback of this new design and two recommendations for further development.

The page created with JavaScript, CSS, HTML, bootstrap allows for a cleaner, more intuitive user interface allowing users to seamlessly filter data in a dynamic way. 

Some potential drawbacks with the current setup include the following:

- The date filter is rather cumbersome and clunky for the end user who expect a date selector or calendar click option that they are used to in other websites and applications. Further, it doesn't account for localization considerations or regional differences in the order of the fields (e.g. m/d/y, or d/m/y). It isn't agnostic to users outside of the US.
- The shape field should provide suggestions or a drop-down option so that users know what these options may be - without being a subject matter expert or knowing what the shape classification types might be, it puts an unnecessary cognitive burden on the user and thus limiting potential results for the user.
- Case sensitivity is an issue given that all the data on the back-end is lower case with the exception of the Comments field. In other words, typing a specific city such as "Madison" doesn't render results, however lowercase "madison" provides results. Further, perhaps a wildcard functionality that users are familiar with in organic searches could be a possible solution to ensure that results are listed. 
- The overall web page design provides a functioning and operating v1, but I think there are opportunities to enhance the user experience as mentioned above, and conducting other user experience research studies that could uncover other enhancements.

