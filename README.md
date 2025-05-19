Victoria Tran

1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

**Within a Github action that runs whenever code is pushed** because you should be testing incrementally and continuously, and since they are automated tests, it makes more sense to run them in a Github action instead of manually, which could be error prone and time consuming. The GitHub action will also catch errors before the code gets merged. This will speed things up, and the Github actions are in place for us to use in order to make the development process more efficient. 

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)

No, you should use a unit test to check if a function is returning the correct output since it is a mor eisolated test. I think the process would be too complex to test this with an end to end test as you'd have to mimic a full user flow.






