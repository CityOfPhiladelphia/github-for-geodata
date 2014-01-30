# Publishing Geodata to GitHub

This page will detail a workflow for City staff to publishing geodata to GitHub. If this is your first time using this workflow, read the [Getting Started](https://github.com/CityOfPhiladelphia/github-for-geodata/blob/master/getting_started.md) page first. For help on getting started with GitHub, consult the [Guides](http://guides.github.com).

1. Load the dataset that you want to export into either ArcGIS Desktop or ArcGIS Catalog from GeoDb2 or another source
2. Export the data using ArcOpen [(full instructions)](https://github.com/CityOfPhiladelphia/arc-open/blob/master/README.md) and confirm that the files look how you want them to be (see "Testing" below)
3. Make sure you have the latest version of your department repository as a local repository:  
    1. If this is your first time with GitHub, find your department's repository in GitHub for Windows and click the "CLONE" button. Now navigate to your local repositories (in the left sidebar) and view the repository you just cloned. Once it's done downloading everything you are all set  
    2. Select your department's repository under "Local repositories" and make sure the "sync" has finished.  
4. Copy the newly created files into your local filesystem directory for your department repository.
5. The GitHub for Windows app should now show you the changes between your local repository and the remote on GitHub.com. If everything looks ok, type a informative "Summary" in the upper left and optionally a more verbose "Description" of your changes and click "Commit to master." Remember that at this point you've only commited a "snapshot" of your changes to your local repository. You now have to push to them to the canoncial remote.
6. Click "Publish" to publish your changes! If your files are large, this may take some time.
7. Confirm that everything looks ok by viewing your department's repo in a web browser. Good work! 

### Testing

After exporting your files, you may want to test them to make sure everything looks like it should. Luckily there are tools to do this for each format:

* **For GeoJSON**: [geojson.io](http://geojson.io) - This tool will allow you to load a GeoJSON file from your computer into a web map although it may have trouble loading files with a lot of features. This is a great tool for more than just testing your data - you can use it to save secret or public GISTs using your GitHub account and so much more.  
* **For KMZ**: [Google Earth](http://www.google.com/earth/) is probably your easiest option.
* **For Markdown**: [dillinger.io](http:http://dillinger.io/) - Copy the `README.md` exported by ArcOpen into the panel on the left - changes will show up on the right. There are many online Markdown editors but this is the best that I've found.
