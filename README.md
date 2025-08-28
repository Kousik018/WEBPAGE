# WEBPAGE<!DOCTYPE html>
<html>

<head>

    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>

    <header>
        <nav class="navbar navbar-expand-lg navbar-dark bg-danger">
            <div class="container-fluid">

                <h1><b>My portfolio</b></h1>
                <ul class="navbar-nav ">
                    <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
                </ul>
            </div>
        </nav>
    </header>


    <div class="container-fluid bg-primary ">
        <h1 class="pt-2"><b>About Me</b></h1>
        <p class="mb-0">My name is M. Kousik . I started my journey as a frontend developer.</p>
    </div>


    <div class="container-fluid bg-warning p-2">
        <div class="row ">
            <div class="col-md-6 sm-12 mb-1">
                <div class="card " style="width: 18rem;">
                    <div class="card-body">
                        <h1 class="card-title"><b>Soft Skills</b></h1>

                        <ul>
                            <li>Communication</li>
                            <li>Critical-Thinking</li>
                            <li>Problem-solving</li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="col-md-6 sm-12 ">
                <div class="card" style="width: 18rem;">
                    <div class="card-body">
                        <h1 class="card-title">Technical Skills</h1>
                        <ul>
                            <li>Python</li>
                            <li>SQL</li>
                            <li>Html</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div>
        <h1><b>Subject and Marks</b></h1>
        <table class="table table-striped table-bordered ">
            <thead class="table-dark">



                <tr>
                    <th>Subjects</th>
                    <th>Marks</th>
                </tr>

                <tr>
                    <td>Python</td>
                    <td>90</td>
                </tr>
                <tr>
                    <td>SQL</td>
                    <td>85</td>

                </tr>
                <tr>
                    <td>HTML</td>
                    <td>82</td>
                </tr>
        </table>
    </div>
  

    <div>
        <h1><b>Inquiry Form</b></h1>
        <form action="">
            <div>
                <label for="Name">Name:</label>
                <input type="text" id="name" name="name" required>
            </div>


            <div>
                <label for="Email">Email:</label>
                <input type="email" id="email" name="email" required>
            </div>

            <div>
                <label for="Phone">Phone No.:</label>
                <input type="tel" id="phone" name="phone" required>
            </div>

            <div>
                <label for="file">Upload file:</label>
                <input type="file" id="file" name="file" accept=".jpg, .jpeg, .pdf" required>
            </div>

            <div>
                <input type="submit" value="Submit">
            </div>
        </form>
    </div>
    <hr>
    </main>

    <footer>
        <p>&copy; 2025 M.Kousik. All rights reserved.</p>
        <a href="https://www.linkedin.com/">LinkedIn</a>,
        <a href="https://github.com/Kousik018">GitHub</a>,
    </footer>
</body>

</html>
