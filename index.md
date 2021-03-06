<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- displays site properly based on user's device -->

    <link
      rel="icon"
      type="image/png"
      sizes="32x32"
      href="./images/favicon-32x32.png"
    />

    <title>Frontend Mentor | Huddle landing page with curved sections</title>
    <!-- font awesome -->
    <link
      rel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.15.3/css/all.css"
      integrity="sha384-SZXxX4whJ79/gErwcOYf+zWLeJdY/qpuqC4cAa9rOGUstPomtqpuNWT9wdPEn2fk"
      crossorigin="anonymous"
    />
    <!-- google fonts  -->
    <!-- poppis -->
    <link rel="preconnect" href="https://fonts.gstatic.com" />
    <link
      href="https://fonts.googleapis.com/css2?family=Poppins:wght@700&display=swap"
      rel="stylesheet"
    />
    <!-- open-san -->
    <link rel="preconnect" href="https://fonts.gstatic.com" />
    <link
      href="https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,400;0,700;1,600&display=swap"
      rel="stylesheet"
    />
    <!-- bootstrap reboot -->
    <link rel="stylesheet" href="css/bootstrap-reboot.min.css" />
    <!-- bootstrap all style -->
    <link rel="stylesheet" href="css/bootstrap.min.css" />
    <!-- style sheet  -->
    <link rel="stylesheet" href="css/style.css" />

  </head>
  <body>
    <!-- ########################################################### -->
    <!-- header -->
    <header>
      <nav
        class="contianer-lg mb-5 container-md container-fluid d-flex justify-content-between align-items-center py-lg-5 py-2"
      >
        <div
          class="col-lg-3 col-4 d-flex align-items-start justify-content-start"
        >
          <img src="images/logo.svg" class="img-fluid" alt="" />
        </div>
        <div class="col-md-3 col-lg-2 col-5">
          <div class="mx-auto">
            <button
              class="btn rounded-pill py-0 p-lg-2 p-md-2 w-100 mx-auto d-block btn-outline-primary btn-header"
            >
              Try it free
            </button>
          </div>
        </div>
      </nav>
      <!-- ####################################################################################### -->
      <!-- main section -->
      <main>
        <!-- ############################## intro section ############################## -->
        <section
          class="intro my-5 container d-flex flex-column text-center justify-content-center align-items-center"
        >
          <div class="heading col-lg-10 mt-4">
            <h2>Build The Community Your Fans Will Love</h2>
          </div>
          <div class="col-lg-5 my-3">
            <p>
              Huddle re-imagines the way we build communities. You have a voice,
              but so does your audience. Create connections with your users as
              you engage in genuine discussion.
            </p>
          </div>
          <div class="col-lg-3 col-md-4 col-10">
            <button
              class="btn py-2 px-3 w-100 btn-primary rounded-pill btn-intro"
            >
              Get Started For Free
            </button>
          </div>
        </section>
        <!-- #################################### stat section ############################### -->
        <section class="stats container">
          <!-- row for image  -->
          <div class="row my-3">
            <div class="col-lg-8 mx-auto">
              <img src="images/screen-mockups.svg" alt="" class="img-fluid" />
            </div>
          </div>
          <!-- row for the statistics -->
          <div class="row my-4">
            <div
              class="col-lg-8 d-flex justify-content-lg-between justify-content-md-between align-items-center justify-content-center flex-wrap mx-auto"
            >
              <!-- first stat  -->
              <div
                class="col-lg-4 col-md-6 my-5 d-flex justify-content-center stat"
              >
                <div class="con-stat">
                  <img src="images/icon-communities.svg" alt="" />
                  <h1>1.4k+</h1>
                  <p>Communities Formed</p>
                </div>
              </div>
              <!-- second stat  -->
              <div
                class="col-lg-4 stat col-md-6 my-5 d-flex justify-content-center"
              >
                <div class="con-stat">
                  <img src="images/icon-messages.svg" alt="" />
                  <h1>2.7m+</h1>
                  <p>Messages Sent</p>
                </div>
              </div>
            </div>
          </div>
        </section>
        <!-- ################################### appearance section ################################### -->
        <section class="app my-3 p-0 container-fluid text-lg-left text-center">
          <!-- top point  -->
          <div class="row top">
            <div
              class="container d-flex justify-content-lg-between justify-content-center flex-wrap-reverse align-items-center"
            >
              <div class="col-lg-5 col-md-6">
                <div class="text my-4">
                  <h2>Grow Together</h2>
                  <p>
                    Generate meaningful discussions with your audience and build
                    a strong, loyal community. Think of the insightful
                    conversations you miss out on with a feedback form.
                  </p>
                </div>
              </div>
              <div class="img-con-app my-4 col-lg-6 col-md-8">
                <img
                  src="images/illustration-grow-together.svg"
                  class="img-fluid"
                  alt=""
                />
              </div>
            </div>
          </div>
          <!-- middle point  -->
          <div class="row middle">
            <div
              class="container d-flex justify-content-lg-between flex-lg-row-reverse justify-content-center flex-wrap-reverse align-items-center"
            >
              <div class="col-lg-5 col-md-6">
                <div class="text my-4">
                  <h2>Flowing Conversations</h2>
                  <p>
                    You wouldn't paginate a conversation in real life, so why do
                    it online? Our threads have just-in-time loading for a more
                    natural flow.
                  </p>
                </div>
              </div>
              <div class="img-con-app my-4 col-lg-6 col-md-8">
                <img
                  src="images/illustration-flowing-conversation.svg"
                  class="img-fluid"
                  alt=""
                />
              </div>
            </div>
          </div>
          <!-- bottom point  -->
          <div class="row bottom">
            <div
              class="container d-flex justify-content-lg-between justify-content-center flex-wrap-reverse align-items-center"
            >
              <div class="col-lg-5 col-md-6">
                <div class="text my-4">
                  <h2>Your Users</h2>
                  <p>
                    It takes no time at all to integrate Huddle with your app's
                    authentication solution. This means, once signed in to your
                    app, your users can start chatting immediately.
                  </p>
                </div>
              </div>
              <div class="img-con-app my-4 col-lg-6 col-md-8">
                <img
                  src="images/illustration-your-users.svg"
                  class="img-fluid"
                  alt=""
                />
              </div>
            </div>
          </div>
        </section>
        <!-- #################################### join section #################################### -->
        <section
          class="join d-flex flex-column p-3 text-center container justify-content-center"
        >
          <div class="col-lg-6 col-md-8 mx-auto my-3">
            <h2>Ready To Build Your Community?</h2>
          </div>
          <div class="col-lg-4 col-md-6 mx-auto my-3">
            <button
              class="btn py-3 px-5 w-100 btn-primary rounded-pill btn-join"
            >
              Get Started For Free
            </button>
          </div>
        </section>
      </main>
      <!-- ############################ footer section ######################### -->
      <footer
        class="container-fluid d-flex flex-lg-row flex-column-reverse p-0"
      >
        <!-- column one  -->
        <div
          class="col-one container ml-auto ml-md-0 d-flex flex-column col-lg-6 col-md-8 py-4"
        >
          <!-- row one  -->
          <div class="col-lg-4 col-md-6 img my-2">
            <img src="images/logo footer.svg" alt="" class="img-fluid" />
          </div>
          <!-- ########################## -->
          <!-- row two  -->
          <div class="col-lg-7 my-2 col-md-6">
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris
              nulla quam, hendrerit lacinia vestibulum a, ultrices quis sem.
            </p>
          </div>
          <!-- ################################### -->
          <!-- row three -->
          <div class="col-lg-6 col-md-6 my-1">
            <div class="d-flex">
              <i class="mr-3 mt-2 fas fa-phone-volume"></i>
              <p class="mt-1">Phone: +1-543-123-4567</p>
            </div>
            <div class="d-flex">
              <i class="mr-3 mt-2 fas fa-envelope-square"></i>
              <p class="mt-1">example@huddle.com</p>
            </div>
          </div>
          <!-- #################################### -->
          <!--row four -->
          <div class="col-lg-4 col-md-6">
            <i class="fas fa-facebook-square"></i>
            <i class="fas fa-twitter"></i>
            <i class="fas fa-instagram"></i>
          </div>
        </div>
        <!-- ########################################################### -->
        <!-- col two  -->
        <div class="col-lg-6 col-md-8 mr-auto py-4">
          <!-- row one  -->
          <div class="col-lg-4">
            <h3>Newsletter</h3>
          </div>
          <!-- row two  -->
          <div class="col-lg-8 col-md-10">
            <p>
              To recieve tips on how to grow your community, sign up to our
              weekly newsletter. We???ll never send you spam or pass on your email
              address
            </p>
          </div>
          <!-- row three and four -->
          <div class="col d-flex flex-column flex-lg-row">
            <div class="col-lg-7 my-3 pl-0">
              <input
                type="email"
                class="form-control"
                name=""
                id=""
                placeholder="enter valid email"
              />
            </div>
            <!-- row four ***  -->
            <div class="col-lg-3 col-6 ml-auto ml-lg-0 my-3">
              <button
                class="btn btn-primary w-100 form-control btn-form rounded"
              >
                Subscribe
              </button>
              <!-- button  -->
            </div>
          </div>
        </div>
      </footer>
    </header>
    <div style="display: none"></div>

    <p class="attribution">
      Challenge by
      <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
        >Frontend Mentor</a
      >. Coded by <a href="#">Your Name Here</a>.
    </p>

  </body>
</html>
