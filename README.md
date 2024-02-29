<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NepalLiga</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
  
 <header>
        <a href="/">
            <img id="logo" src="logo.png" alt="Your Company Name">
        </a>
    </header>
    
   <p id="currentDateTime"></p>
   
  <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About Us</a></li>
            <li><a href="#contact">Contact</a></li>
            <li><a href="#registration">Registration</a></li>
        </ul>
    </nav>

   <section id="home">
        <h1>Welcome to My Webpage</h1>
        <p>.</p>
    </section>
   
   <video width="500" height="500" controls>
        <source src="https://example.com/path/to/your/video.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>

  <section id="about">
        <h2>About Us</h2>
        <p>Information about us.</p>
    </section>

   <section id="contact">
        <h2>Contact</h2>
        <p>Contact information.</p>
    </section>

  <section id="registration">
        </section>
        
   <div class="container mt-5">
        <div class="row justify-content-center">
            <div class="col-md-6">
                <div class="card">
                    <div class="card-header text-center">
                        <h3>Registration Form</h3>
                    </div>
                    <div class="card-body">
                        <form>
                            <div class="form-group">
                                <label for="fullName">Full Name</label>
                                <input type="text" class="form-control" id="fullName" placeholder="Enter your full name">
                            </div>
                            <div class="form-group">
                                <label for="age">Age</label>
                                <input type="number" class="form-control" id="age" placeholder="Enter your age">
                            </div>
                            <div class="form-group">
                                <label for="email">Email</label>
                                <input type="email" class="form-control" id="email" placeholder="Enter your email">
                            </div>
                            <div class="form-group">
                                <label for="contact">Contact</label>
                                <input type="text" class="form-control" id="contact" placeholder="Enter your contact number">
                            </div>
                            <button type="submit" class="btn btn-primary btn-block">Submit</button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>
    
   <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>

<footer>
    <p>&copy;NepalLiga. All rights reserved.</p>
</footer>


</body>
</html>
