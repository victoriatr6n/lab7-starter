Victoria Tran

1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

**Within a Github action that runs whenever code is pushed** because you should be testing incrementally and continuously, and since they are automated tests, it makes more sense to run them in a Github action instead of manually, which could be error prone and time consuming. The GitHub action will also catch errors before the code gets merged. This will speed things up, and the Github actions are in place for us to use in order to make the development process more efficient. 

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)

No, you should use a unit test to check if a function is returning the correct output since it is a mor eisolated test. I think the process would be too complex to test this with an end to end test as you'd have to mimic a full user flow.

3) What is the difference between navigation and snapshot mode?
Navigation mode assesses the website right after the page loads while the snapshot mode will assess the website at the current state it is in. They both cannot make changes to the content of the page or analyze interactions (like with JavaScript).

4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
- To enhance the search engine optimization, as returned from the navigation mode, the document should have a meta description.
- To improve the accessibility of the site, we could add a [lang] attribute to the <html> element.
- To improve the performane of the site, we could resize the images of the items because they are larger than their display size. If we resize the images appropriately, we can save cellular data and improve the loading time.






