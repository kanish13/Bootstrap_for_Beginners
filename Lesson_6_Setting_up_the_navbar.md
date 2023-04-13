Open the index.html of Tindog file in the vs code or any other ide

Now paste the navbar code that we did earlier in this learning (Lesson_4) in navbar section in index.html:

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

Now if you refresh , you see now change happened to your website . to make it work add css link into head tag:


    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">


Again refresh if you can see we got navigation bar as expected . But your toggle button will be working if you keep the window in mobile size . This is because toggle button require some javasript . so include the below java scrip code to your head section:


    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>


![image](https://user-images.githubusercontent.com/111358462/231832319-50ee708e-8fd4-4584-8690-526cd5cdc1b2.png)

![image](https://user-images.githubusercontent.com/111358462/231832358-7a29795d-eda3-48d9-bc03-a8b4444a36c2.png)


  
