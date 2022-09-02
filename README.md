# UFOs

## Project Overview

This in-depth analysis is helping Dana to build a webpage with a dynamic table of UFOs sightings. This time, it allowed users to filter for multiple criteria as the same time, not only they can filter date, but also the city, state, country, and shape.

#### Resources

Using Visual Studio Code to add and update Javascript running on Live Server. 

## Results

### Filter UFOs sightings on miltiple criteria 

How to perform a search? 

A correct search box will be included 5 search box where users can put date, city, state, country, and shape in the left side of the webpage. 

![Screen Shot 2022-09-02 at 2 19 58 PM](https://user-images.githubusercontent.com/107448172/188236884-f2889496-a519-4fc8-a69e-19a43efacd7f.png)

For the saearch to happened, here is some changes added to the index.html file for the magic to work. In this case, all empty box was preset to 1/10/2010, in Norton city, Massachusetts MA, US with the shape triangle. 

![Screen Shot 2022-09-02 at 2 23 02 PM](https://user-images.githubusercontent.com/107448172/188237194-e5f4fade-a3ac-48ae-b02c-4d4d4a76f27f.png)


On the right side, the table of none filtered data will be list before any of filtered data requested. 

![Screen Shot 2022-09-02 at 2 20 02 PM](https://user-images.githubusercontent.com/107448172/188236920-7c41a3eb-bde1-4255-924f-2769782b526b.png)

Once the user starts to punch in the date, the search list will be shorter, and hence the search will be completed when there is one or no result displayed. 

![Screen Shot 2022-09-02 at 2 26 30 PM](https://user-images.githubusercontent.com/107448172/188237534-aac990bc-ce24-439a-a5fe-50712efe2c6d.png)

And now, user has completed the search!

## Summary

This analysis is very simple but intricated at the same time. I would not know that a very simple and clean dynamic table will require a lot of function and html in order to modify the data. One of the drawbacks that I had was how to display a preset data before the user goes into searching. 

I believe the data is very inconsistent, there are a few things I want to help Dana to improve this project:
- Preset input box with dropdown list using Bootstrap. It's easier for user to narrow down the search. 
- Cleaner data will be much better looking. Some of the comment on the comment column are typo and error. 
