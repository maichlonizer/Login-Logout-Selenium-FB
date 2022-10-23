# Login-Logout-Selenium-FB

Implementing LogIn And Logout Functions In Selenium WebDriver
Right now, We are learning some commonly used functions which can actually helps us to minimize our webdriver test case code size. As you know, You need to perform some actions (Example : Comparing Strings, Comparing Integers, Compare Double, And More Like This) many times during your test case execution so repeating same code In every test case Is not a good practice. You can create and common function In some common class and then call that function whenever required.

Login and Logout from your application's admin panel or application account Is also this kind of repeating task which you need to perform very frequently during test execution. So why not create It once and then use It whenever required In your test? Let we try to Implement It.

Supposing you are testing facebook application and you wants to Implement LogIn and LogOut function on It. Then steps will looks like bellow.

Step 1 : Implement initData(), initBrowser(), and closeBrowser() functions In your CommonFunctions class as described In PREVIOUS POST.

Step 2 : Copy paste bellow given LogIn() and LogOut() functions In your CommonFunctions class.

Step 3 : Now Its time to call LogIn() and LogOut() functions In your webdriver test as bellow. Create class with name FBLogin and copy paste bellow given lines In It. Replace dummy user Id and password with your actual user Id and Password before running test.

Now run your test and observe result. It will login In your account and then logout from It. You can Include your test activity between logIn() and logOut() functions.

Now you can call logIn() and logOut() functions anywhere In your test or any of the test case. I hope you understand what I am trying to tell you.




****source: https://www.software-testing-tutorials-automation.com/2014/06/implementing-login-and-logout-functions.html
