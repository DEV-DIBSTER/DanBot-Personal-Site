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
    background-attachment: fixed; /* Makes the background stationary */
    z-index: -1; /* Ensures it is behind other content */
  }

  .dim-overlay {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.836); /* Dim effect with opacity */
    z-index: -1; /* Ensures it is behind other content but above the background */
  }

  .content {
    position: relative;
    z-index: 1; /* Ensures content is above the background and dim overlay */
    color: white; /* Example text color to stand out against the dimmed background */
  }

  .grid-container {
    padding: 20px; /* Add padding to the grid container */
  }

  .grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 4px;
  }

  .box {
    background-color: white;
    border-radius: 8px;
    padding: 16px;
  }
</style>

<div class="background-container"></div>
<div class="dim-overlay"></div>

<div class="pb-20"></div>

<div class="content pb-60">
  <center>
    <img src="/DIBSTER-2.png" alt="DIBSTER Logo" class="w-28 h-auto pt-24">
    <h1 class="text-4xl font-bold pt-5">"DIBBY" DIBSTER</h1>
    <p style="max-width: 600px;" class="pt-5 font-sans text-lg leading-relaxed">
      Hello, I'm DIBSTER, also known as DIBBY or DIB. I'm a full stack developer from the United States.
      Currently working as the Staff Manager, Head of the Beta Testing Program, as well as a Developer and System Administrator for DanBot Hosting.
    </p>
  </center>
</div>

<div class="grid-container">
  <div class="max-w-md mx-auto"> <!-- Added max-w-md and mx-auto for centering and limiting width -->
    <div class="grid gap-8"> <!-- Increased gap to 8 for more spacing between grid items -->
      <div class="box p-4 bg-black shadow-md rounded-lg">
      <div class="flex items-center mb-2">
        <svg class="w- h-6 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 19l9 2-9-18-9 18 9-2zm0 0v-8"></path>
        </svg>
        <h2 class="text-lg font-semibold">Box 1</h2>
      </div>
      <p class="text-gray-600">This is the description for Box 1.</p>
      </div>

      
      <div class="box p-4 bg-black shadow-md rounded-lg">
      <div class="flex items-center mb-2">
        <svg class="w-6 h-6 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 19l9 2-9-18-9 18 9-2zm0 0v-8"></path>
        </svg>
        <h2 class="text-lg font-semibold">Box 2</h2>
      </div>
      <p class="text-gray-600">This is the description for Box 2.</p>
      </div>
    </div>
  </div>
</div>
