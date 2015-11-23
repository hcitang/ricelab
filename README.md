# RICELab Website Source

## Setting it up
1. Clone the repository on your own machine
2. Install jekyll, jekyll-scholar, jekyll-gist on your own machine

## Making a change to the website
1. Create a branch on your own copy
2. Make the appropriate changes
3. Try compiling on your own machine by using `jekyll build` or `jekyl --serve`
4. If this works, then push your changes to the github server
5. Login to the ricelab account (`ssh ricelab@ricelab.cpsc.ucalgary.ca`)
6. Run `make-ricelab`. This will pull the source from git, and then run the jekyll command to compile and deploy the site.
