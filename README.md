This wants to be an example showing how to share *Authentication* and *Authorisation* between an **ASP.NET Core Web Application** and a **Windows Forms Application**.

So far, we have:
- An ASP.NET Core 2.2 Web Application with "Individual User Accounts"
- A .NET Framework 4.7.2 WinForms Application

You can run the Web Application and register a new user. Ie:
- Mail: test@test.com
- Password: Test_1

Then you can login the site with that user account.

The goal is to **login** or **register** new accounts into the same database through the WinForms Application.

It seems the best way to go would be building a Web API similar to [this](http://jasonwatmore.com/post/2019/01/08/aspnet-core-22-role-based-authorization-tutorial-with-example-api) (discussion [here](https://forums.asp.net/t/2152462.aspx)).
