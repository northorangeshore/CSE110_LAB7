## 1:Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.
The best to fit automated tests in the development pipeline is **"within a GitHub action that runs whenever code is pushed"**
Automated tests are meant to be run continuously and incrementally, so implemeting them into GitHub Actions make certain that every code change is tested immediately.This will reduce the chance of humman error and save time compared to test manually. It also catchs issues early, before code is merged.
## 2:Would you use an end to end test to check if a function is returning the correct output? (yes/no)  
**No. End-to-end tests** are designed to test the entire application flow by emulating user actions from start to finish, ensuring that all components work together correctly. If I am checking whether a specific function returns the correct output, I would use a **unit test**, which is faster and easier to debug.
## 3:What is the difference between navigation and snapshot mode?  
**Navigation** mode analyzes a web page by loading full page, just like a user visiting the page. It also measures performance, evaluates accessibility. **Snapshot** mode, in contrast, takes a picture of the page and checks for things like missing tag, accessibility issues. It does not reload the page or measure how fast it could load.  
## 4:Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
1.  The site is missing a <meta name="viewport"> tag, as returned in navigation mode, which is essential for ensuring the layout scales correctly on mobile devices.  
2.  The site lacks a meta description, as returned in snapshot mode, which can negatively impact search engine optimization (SEO) and reduce visibility in search results.  
3.  Image performance can be improved by resizing large images to fit their display size by using other image format.  
