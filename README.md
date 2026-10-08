<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Gaming Hub</title>

    <!-- Bootstrap CSS -->
    <link
        href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css"
        rel="stylesheet">

    <style>
        body {
            background-color: #f8f9fa;
        }

        .hero {
            background: linear-gradient(135deg, #e30d51, #6466eb);
            color: rgb(243, 236, 236);
            padding: 100px 0;
        }

        .hero h1 {
            font-size: 3rem;
            font-weight: bold;
        }

        .section-title {
            font-weight: bold;
            margin-bottom: 40px;
        }

        .course-card {
            transition: 0.3s;
        }

        .course-card:hover {
            transform: translateY(-5px);
        }

        .icon-box {
            font-size: 45px;
        }

        footer {
            background-color: #d24120;
            color: white;
        }
    </style>
</head>

<body>

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">

            <a class="navbar-brand fw-bold" href="#">
                Gaming Hub
            </a>

            <div class="navbar-nav ms-auto">
                <a class="nav-link active" href="#home">Battle Ground</a>
                <a class="nav-link" href="#about">Background fire</a>
                <a class="nav-link" href="#courses">main fire</a>
                <a class="nav-link" href="#contact">Contact</a>
            </div>

        </div>
    </nav>


    <!-- Hero Section -->
    <section class="hero text-center" id="home">

        <div class="container">

            <h1>Learn. Build. Grow.</h1>

            <p class="lead mt-3">
                Start your web development journey with simple and practical learning.
            </p>

            <a href="#courses" class="btn btn-light btn-lg mt-3">
                Explore Courses
            </a>

        </div>

    </section>


    <!-- About Section -->
    <section class="py-5" id="about">

        <div class="container">

            <div class="row align-items-center">

                <div class="col-md-6 mb-4 mb-md-0">

                    <h2 class="fw-bold">
                        Welcome to Gaming Hub
                    </h2>

                    <p class="text-muted">
                        Gaming Hub is a simple learning platform created for
                        first-year students who want to understand the basics
                        of web development.
                    </p>

                    <p>
                        Students can how to build, Games and Conquer the world of games
                        
                    </p>

                    <a href="#courses" class="btn btn-primary">
                        Start Grinding
                    </a>

                </div>


                <div class="col-md-6">

                    <div class="bg-white shadow rounded p-5 text-center">

                        <div class="display-1">
                            💻
                        </div>

                        <h3 class="mt-3">
                            Game Development
                        </h3>

                        <p class="text-muted">
                            Learn by creating real games.
                        </p>

                    </div>

                </div>

            </div>

        </div>

    </section>


    <!-- Courses Section -->
    <section class="py-5 bg-white" id="courses">

        <div class="container">

            <h2 class="text-center section-title">
                What You Will Learn about Gaming Hub
            </h2>

            <div class="row g-4">

                <!-- Card 1 -->
                <div class="col-md-4">

                    <div class="card course-card border-0 shadow-sm h-100">

                        <div class="card-body text-center p-4">

                            <div class="icon-box">
                                🌐
                            </div>

                            <h4 class="card-title mt-3">
                                Basic Game Development
                            </h4>

                            <p class="card-text text-muted">
                                Learn Gaming Hub containers, grid, buttons, cards, spacing, colors and responsive utilities.
                            </p>

                            <a href="#" class="btn btn-outline-primary">
                                explore 
                            </a>

                        </div>

                    </div>

                </div>


                <!-- Card 2 -->
                <div class="col-md-4">

                    <div class="card course-card border-0 shadow-sm h-100">

                        <div class="card-body text-center p-4">

                            <div class="icon-box">
                                🎨
                            </div>

                            <h4 class="card-title mt-3">
                                Advanced Game Development
                            </h4>

                            <p class="card-text text-muted">
                                Learn advanced game development concepts and techniques.
                            </p>

                            <a href="#" class="btn btn-outline-primary">
                                Explore
                            </a>

                        </div>

                    </div>

                </div>


                <!-- Card 3 -->
                <div class="col-md-4">

                    <div class="card course-card border-0 shadow-sm h-100">

                        <div class="card-body text-center p-4">

                            <div class="icon-box">
                                📱
                            </div>

                            <h4 class="card-title mt-3">
                                God level Game Development
                            </h4>

                            <p class="card-text text-muted">
                                Create your own games and become a master of game development.
                            </p>

                            <a href="#" class="btn btn-outline-primary">
                                Explore
                            </a>

                        </div>

                    </div>

                </div>

            </div>

        </div>

    </section>


    <!-- Features Section -->
    <section class="py-5">

        <div class="container">

            <h2 class="text-center section-title">
                Why Learn With Us?
            </h2>

            <div class="row text-center g-4">

                <div class="col-sm-6 col-lg-3">

                    <div class="p-4 bg-white shadow-sm rounded">

                        <h2>📚</h2>

                        <h5>
                            Easy Lessons
                        </h5>

                        <p class="text-muted">
                            Learn step-by-step with clear explanations.
                        </p>

                    </div>

                </div>


                <div class="col-sm-6 col-lg-3">

                    <div class="p-4 bg-white shadow-sm rounded">

                        <h2>💻</h2>

                        <h5>
                            Practical Work
                        </h5>

                        <p class="text-muted">
                            Learn by creating Games
                        </p>

                    </div>

                </div>


                <div class="col-sm-6 col-lg-3">

                    <div class="p-4 bg-white shadow-sm rounded">

                        <h2>📱</h2>

                        <h5>
                           make your own dream game
                        </h5>

                        <p class="text-muted">
                            Games work on every screen.
                        </p>

                    </div>

                </div>


                <div class="col-sm-6 col-lg-3">

                    <div class="p-4 bg-white shadow-sm rounded">

                        <h2>🚀</h2>

                        <h5>
                            Beginner Friendly
                        </h5>

                        <p class="text-muted">
                            Perfect for first-year students.
                        </p>

                    </div>

                </div>

            </div>

        </div>

    </section>


    <!-- Contact Section -->
    <section class="py-5 bg-white" id="contact">

        <div class="container">

            <div class="row justify-content-center">

                <div class="col-md-8 col-lg-6">

                    <h1 class="text-center section-title">
                        Contact Us
                    </h1>

                    <form>

                        <div class="mb-3">

                            <label class="form-label">
                                Your Gaming name
                            </label>

                            <input
                                type="text"
                                class="form-control"
                                placeholder="Enter your name">

                        </div>


                        <div class="mb-3">

                            <label class="form-label">
                                Game Email
                            </label>

                            <input
                                type="email"
                                class="form-control"
                                placeholder="Enter your email">

                        </div>


                        <div class="mb-3">

                            <label class="form-label">
                                About games you created and learning by your self
                            </label>

                            <textarea
                                class="form-control"
                                rows="4"
                                placeholder="Enter your message"></textarea>

                        </div>


                        <button
                            type="submit"
                            class="btn btn-primary w-100">

                            Send Message

                        </button>

                    </form>

                </div>

            </div>

        </div>

    </section>


    <!-- Footer -->
    <footer class="text-center py-4">

        <div class="container">

            <p class="mb-1">
                © 2026 StudentHub
            </p>

            <small>
               Gaming Hub 
            </small>

        </div>

    </footer>

</body>

</html>
