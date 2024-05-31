# CSS-Framework

## Name
Bootstrap

## Description
A CSS framework with components and utility classes for creating responsive and mobile-first websites and applications.

## Introduction
This custom CSS framework is built using Sass, providing a customizable theme for standard HTML elements and utility classes for common styling needs. It aims to simplify the development process by offering a robust, mobile-first, and responsive design system.

## Installation
To use this framework in your project, follow these steps:

1. **Download the Compiled CSS**: Ensure you have the compiled CSS file (`framework.css`) in your `css` directory.
   
   If you need to compile it yourself, use the following command:
   ```bash
   sass scss/main.scss css/framework.css

2. Include the CSS in Your HTML: Add the following line to the <head> section of your HTML file:
    
   <link rel="stylesheet" href="css/framework.css">

## Usage
# Utility Classes

The framework provides a variety of utility classes to simplify common styling tasks.
Spacing Utilities

# Control margin and padding with spacing utilities:

    Margin: .m-t-1, .m-b-2, .m-x-3 (top, bottom, horizontal margins)
    Padding: .p-t-1, .p-b-2, .p-x-3 (top, bottom, horizontal padding)

# Color Utilities

Apply text and background colors:

    Text Colors: .text-primary, .text-secondary, .text-success
    Background Colors: .bg-primary, .bg-secondary, .bg-success

# Typography Utilities

Adjust font properties with these utilities:

    Font Weight: .font-weight-bold, .font-weight-normal
    Font Style: .font-italic
    Font Size: .font-size-sm, .font-size-lg

## Components

The framework includes several pre-styled components:
Buttons

Use the .btn class for buttons:

<button class="btn">Primary Button</button>
<button class="btn btn-secondary">Secondary Button</button>

# Forms

Structure forms with the following classes:

<form>
  <div class="form-group">
    <label for="exampleInputEmail1">Email address</label>
    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
  </div>
  <div class="form-group">
    <label for="exampleInputPassword1">Password</label>
    <input type="password" class="form-control" id="exampleInputPassword1">
  </div>
  <button type="submit" class="btn">Submit</button>
</form>

# Tables

Style tables with the .table class:

<table class="table">
  <thead>
    <tr>
      <th scope="col">#</th>
      <th scope="col">First</th>
      <th scope="col">Last</th>
      <th scope="col">Handle</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>Mark</td>
      <td>Otto</td>
      <td>@mdo</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>Jacob</td>
      <td>Thornton</td>
      <td>@fat</td>
    </tr>
    <tr>
      <th scope="row">3</th>
      <td>Larry</td>
      <td>the Bird</td>
      <td>@twitter</td>
    </tr>
  </tbody>
</table>

# Navbar

Create a responsive navbar with the .navbar class:

<nav class="navbar">
  <a href="#" class="navbar-brand">My Framework</a>
  <div class="navbar-nav">
    <div class="nav-item">
      <a class="nav-link" href="#">Home</a>
    </div>
    <div class="nav-item">
      <a class="nav-link" href="#">About</a>
    </div>
    <div class="nav-item">
      <a class="nav-link" href="#">Contact</a>
    </div>
  </div>
</nav>

# Customization

To customize the framework, you can modify the _variables.scss file. This file contains all the configurable variables for colors, spacing, typography, and more.
Example Customization

``` scss
$primary-color: #007bff;
$secondary-color: #6c757d;
$success-color: #28a745;
$danger-color: #dc3545;
$warning-color: #ffc107;
$info-color: #17a2b8;
$light-color: #f8f9fa;
$dark-color: #343a40;

$font-family-base: "Helvetica Neue", Arial, sans-serif;
$font-size-base: 1rem;
$line-height-base: 1.5;

$border-radius: 0.25rem;
```
Modify the variables as needed and recompile the SCSS to apply the changes:

```bash 
    sass scss/main.scss css/framework.css
```
This will regenerate the CSS with your customized values.
