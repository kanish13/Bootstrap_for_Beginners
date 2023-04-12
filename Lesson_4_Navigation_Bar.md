Navbar:

Documentation and examples for Bootstrap’s powerful, responsive navigation header, the navbar. Includes support for branding, navigation, and more, including support for our collapse plugin.

Brand:

The .navbar-brand can be applied to most elements, but an anchor works best as some elements might require utility classes or custom styles.

Nav:

Navbar navigation links build on our .nav options with their own modifier class and require the use of toggler classes for proper responsive styling. Navigation in navbars will also grow to occupy as much horizontal space as possible to keep your navbar contents securely aligned.
Active states—with .active—to indicate the current page can be applied directly to .nav-links or their immediate parent .nav-items.

Content alignment:

To align navbar content to the right or left use me-auto or ms-auto classes. For content centering use flexbox utilities.

Left aligned :

Add .me-auto class next to the .navbar-nav to align the content to the left.

Right aligned:

Add .ms-auto class next to the .navbar-nav to align the content to the right.

Centered:

Remove .ms-auto or .me-auto class and add .justify-content-center next to the .navbar-collapse to center the content.
navbar-toggler: Used to determine which button exactly is used as the toggler to toggle the navbar when the viewport precedes the predetermined size.

Here’s an example of all of sub-components that we just learnt included in a responsive light-themed navbar

    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <a class="navbar-brand" href="">tindog</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo02" aria-controls="navbarTogglerDemo02" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarTogglerDemo02">

            <ul class="navbar-nav ms-auto">
                <li class="nav-item">
                    <a class="nav-link" href="">Contact</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="">Pricing</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="">Download</a>
                </li>
            </ul>
        </div>
    </nav>

OUTPUT: 

Pc view:

![image](https://user-images.githubusercontent.com/111358462/231509195-9636cd90-0f3d-40fd-9f59-442a4bb631db.png)

 
Tablet view:   

![image](https://user-images.githubusercontent.com/111358462/231509326-63f1f5eb-3ff1-4d86-8069-55cd14322eec.png)

Mobile view:

![image](https://user-images.githubusercontent.com/111358462/231509410-59162cdc-592d-4825-aec4-f08d28e84860.png)

  





