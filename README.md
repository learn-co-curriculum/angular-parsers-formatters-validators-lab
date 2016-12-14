# Parsing and displaying form data and errors

## Objectives

- Use $parsers, $formatters and $validators to format form Models
- Use ngMessages to display relevant error messages

## Instructions

In this repo we've got a sign up form. This requires the user's name, and their coupon code.

1. Add a directive that uses `$parsers` and `$formatters` to ensure that the coupon is always displayed in lowercase in the view, no matter what case we type in.

2. We also need to make sure the coupon code is correct. This should conform to the regular expression `/\d{2}[a-z]{4}\d{2}/i` (two digits, then 4 characters, then 2 digits). Add a directive to validate this! If there's an error with the code, it should be displayed on the view!
3. Use ng-click to pass the lab http://www.w3schools.com/angular/ng_ng-click.asp 

<p class='util--hide'>View <a href='https://learn.co/lessons/angular-parsers-formatters-validators-lab'>Angular Parsing and Displaying Lab</a> on Learn.co and start learning to code for free.</p>
