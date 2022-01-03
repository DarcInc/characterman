# Sample App
Tracking investments for a user.

## User Management

### Register
A user can come to the site and register for an account.
They'll need to provide:

1. Username
2. Password
3. Email

### Login
The user provide their credentials for login.

1. Username
1. Password

### Reset Password
If the user forgets their password.
They can get a password reset link.

1. Username

## Add Stocks to Follow
Add stocks that the user wants to follow.

### Download Charting Data
Download data from Yahoo.

#### Cache Downloads

### Generate Charts
Create a chart from the downloaded data.

### Make Notes on Stocks
Allow the user to add notes for various tocks.

## Allow The User to Track Portfoloi

### Add the Date Purchased or Sold, Amount, and Price
Keep track of the user purchases, sales and profit so far.

### Performance Relative to Market
Calculate user's performance relative to market.

## A. Structure
To create a library module.
Then add a 'cmds' directory.
That contains our application.

## B. Charting Libraries
What charting library to use?
Go-Chart has not been updated for a while.
Chart looks like it's been abanoned.
Plot, which doesn't seem as sophisticate bit it's relatively current.

Plot is the best choice.
It's relatively active (among the choices).
It has a larger contributor base.
It seems to be in good shape from a build and test perspective.

1. https://github.com/wcharczuk/go-chart
    1. 14 Months ago
    1. 3.3k Stars
    1. 258 Forks
    1. Some CI/CD Badging
    1. 17 contributors
2. https://github.com/vdobler/chart
    1. 3 Years ago
    1. 707 Stars
    1. 103 Forks
    1. No test/ci badges
    1. 8 contributors
3. https://github.com/gonum/plot
    1. 3 Months Ago
    1. 2.1k Stars
    1. 185 Forks
    1. Good test coverage - CI in good shape
    1. 34 contributors

