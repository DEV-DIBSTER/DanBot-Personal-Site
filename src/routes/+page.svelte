<style>
  .background-container {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: url('/background.jpg');
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
    z-index: -1;
  }

  .dim-overlay {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.836);
    z-index: -1;
  }

  .content {
    position: relative;
    z-index: 1;
    color: white;
  }

  /* Center the Projects Section */
  .projects-section {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
  }

  /* Project Grid */
  .project-grid {
    display: flex;
    justify-content: center;
    gap: 1rem;
    flex-wrap: wrap;
  }

  .project-box {
    background-color: rgba(17, 17, 17, 0.6);
    border-radius: 8px;
    padding: 16px;
    min-height: 100px;
    min-width: 150px;
    display: flex;
    justify-content: center;
    align-items: center;
  }
</style>

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" type="image/png" href="/DIBSTER-2.png">
    <title>DIBSTER</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  </head>

  <body>
    <div class="background-container"></div>
    <div class="dim-overlay"></div>

    <div class="pb-20"></div>

    <div class="content pb-48">
      <center>
        <img src="/DIBSTER-2.png" alt="DIBSTER Logo" class="w-28 h-auto pt-24">
        <h1 class="text-4xl font-bold pt-5">"DIBBY" DIBSTER</h1>
        <p style="max-width: 600px;" class="pt-5 font-sans text-lg leading-relaxed">
          Hello, I'm DIBSTER, also known as DIBBY or DIB. I'm a full stack developer from the United States. Currently working as the Staff Manager, Head of the Beta Testing Program, as well as a Developer and System Administrator for DanBot Hosting.
        </p>
      </center>
    </div>

    <!-- Projects Section Centered -->
    <div id="projects" class="projects-section py-10">
      <div class="mx-auto max-w-7xl px-6 lg:px-8">
        <div class="max-w-2xl">
          <h2 class="text-3xl font-bold tracking-tight text-gray-200 sm:text-4xl">Projects</h2>
          <p class="mt-6 text-lg leading-8 text-gray-400">Here are the projects I work on here at DBH.</p>
        </div>

        <!-- Project Boxes in Centered Grid -->
        <div class="project-grid mt-4">
          <!-- Pterodactyl Eggs Box -->
          <div class="project-box">
            <li>
              <div class="flex items-center justify-center gap-x-6">
                <div class="text-center">
                  <h3 class="text-2xl font-semibold leading-7 tracking-tight text-blue-500 hover:text-blue-600">
                    <a href="https://github.com/DanBot-Hosting/pterodactyl-eggs" target="_blank">Pterodactyl Eggs - Maintenance</a>
                  </h3>
                </div>
              </div>
            </li>
          </div>

          <!-- Discord Bots Box -->
          <div class="project-box">
            <li>
              <div class="flex items-center justify-center gap-x-6">
                <div class="text-center">
                  <h3 class="text-2xl font-semibold leading-7 tracking-tight text-blue-500 hover:text-blue-600">
                    <a href="https://github.com/DanBot-Hosting/DanBot-Hosting/DanBotHostingStats" target="_blank">DBH Main Discord Bot</a>
                  </h3>
                </div>
              </div>
            </li>
          </div>
        </div>
      </div>
    </div>

    <hr class="h-0.5 bg-gray-700 border-none">

    <footer class="bg-[#141414fc]">
      <div class="max-w-screen-xl px-4 py-6 mx-auto space-y-6 overflow-hidden sm:px-6 lg:px-8">
        <div class="flex justify-center space-x-4">
          <a href="https://x.com/DEV-DIBSTER" target="_blank" class="text-gray-400 hover:text-gray-300">
            <span class="sr-only">X</span>
            <i class="fa-brands fa-x-twitter"></i>
          </a>
          <a href="https://discord.com/users/757296951925538856" class="text-gray-400 hover:text-gray-300">
            <span class="sr-only">Discord</span>
            <i class="fa-xl fa-brands fa-discord"></i>
          </a>
          <a href="https://gtihub.com/DEV-DIBSTER" class="text-gray-400 hover:text-gray-300">
            <span class="sr-only">GitHub</span>
            <i class="fa-xl fa-brands fa-github"></i>
          </a>
        </div>
        <p class="text-base leading-8 text-center text-gray-400">&copy; <script>document.write(new Date().getFullYear())</script> <span class="font-semibold">DIBSTER</span> - All Rights Reserved.</p>
      </div>
    </footer>
  </body>
</html>
