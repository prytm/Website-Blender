# Website-Blender
Website that contains my bleder project

Here is the Code :

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
        <title>Website Tammam</title>
        <style>
            .nav-menu {
              display: none;
            }
        
            @media (min-width: 768px) {
              .nav-menu {
                display: flex;
              }
            }
          </style>
        </head>
        <body>
          <nav class="bg-black py-4">
            <div class="container mx-auto flex items-center justify-between">
              <div>
                <a href="#" class="text-white text-xl font-bold">Priya Musyaffa Tammam</a>
              </div>
        
              <button id="nav-toggle" class="block md:hidden">
                <svg class="text-white fill-current" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" width="20" height="20">
                  <path d="M0 3h20v2H0zm0 6h20v2H0zm0 6h20v2H0z"/>
                </svg>
              </button>
            </div>
          </nav>

          <section class="bg-gray-900 py-4">
            <div class="container mx-auto text-center">
              <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold text-white mb-6">Welcome!!</h1>
              <p class="text-lg md:text-xl lg:text-xl text-gray-500 mb-5">Here are the blender projects I've created over the years: </p>
            </div>
          </section>

          <section class="bg-gray-100 py-12">
            <div class="container mx-auto grid gap-6 grid-cols-1 md:grid-cols-2 lg:grid-cols-4">
      
              <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                <img src="C:\Users\USER\Documents\Blender\untitled.png" alt="Gambar 1" class="w-full h-72 object-cover">
                <div class="p-4">
                  <h2 class="text-xl font-bold mb-2" style="text-align: center;">Paradise</h2>
                  <p class="text-gray-700" style="text-align: justify;">A woman that look at her afterlife.</p>
                </div>
              </div>
          
              <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                <img src="C:\Users\USER\Documents\Blender\robot.png" alt="Gambar 2" class="w-full h-72 object-cover">
                <div class="p-4">
                  <h2 class="text-xl font-bold mb-2" style="text-align: center;">AI</h2>
                  <p class="text-gray-700" style="text-align: justify;">The structure of AI that everybody thinks of.</p>
                </div>
              </div>
          
              <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                <img src="C:\Users\USER\Documents\Blender\IMG_2439.png" alt="Gambar 3" class="w-full h-72 object-cover">
                <div class="p-4">
                  <h2 class="text-xl font-bold mb-2" style="text-align: center;">Talk To God</h2>
                  <p class="text-gray-700" style="text-align: justify;">A warrior facing giant rocked texture man</p>
                </div>
              </div>
          
              <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                <img src="C:\Users\USER\Documents\Blender\DONE_PROJECT_101.png" alt="Gambar 4" class="w-full h-72 object-cover">
                <div class="p-4">
                  <h2 class="text-xl font-bold mb-2" style="text-align: center;">Space</h2>
                  <p class="text-gray-700" style="text-align: justify;">A man casually look at the stars through the circle</p>
                </div>
              </div>
            </div>
          </section>

          <footer class="bg-gray-900 py-8">
            <div class="container mx-auto text-center">
            <h3 class="text-white">Website By Priya Musyaffa Tammam</h3>
              <p class="text-gray-500">Feel free to connect</p>
              <div class="flex items-center justify-center mt-4">
                <a href="https://www.instagram.com/pry_tm/" class="text-gray-500 hover:text-white mx-2">
                  <svg class="h-12 w-12" fill="currentColor" viewBox="0 0 23 24" xmlns="http://www.w3.org/2000/svg">
                    <path d="M16.5 3H7.5C5.57 3 4 4.57 4 6.5V15.5C4 17.43 5.57 19 7.5 19H16.5C18.43 19 20 17.43 20 15.5V6.5C20 4.57 18.43 3 16.5 3ZM18 15.5C18 16.88 16.88 18 15.5 18H8.5C7.12 18 6 16.88 6 15.5V8.5C6 7.12 7.12 6 8.5 6H15.5C16.88 6 18 7.12 18 8.5V15.5Z"/>
                    <path d="M12 7C9.24 7 7 9.24 7 12C7 14.76 9.24 17 12 17C14.76 17 17 14.76 17 12C17 9.24 14.76 7 12 7ZM12 15.5C10.07 15.5 8.5 13.93 8.5 12C8.5 10.07 10.07 8.5 12 8.5C13.93 8.5 15.5 10.07 15.5 12C15.5 13.93 13.93 15.5 12 15.5Z"/>
                    <circle cx="17.5" cy="6.5" r="1.5"/>
                  </svg>
                </a>
                <a href="https://www.linkedin.com/in/prytm/" class="text-gray-500 hover:text-white mx-2">
                  <svg class="h-11 w-11" fill="currentColor" viewBox="0 0 24 27" xmlns="http://www.w3.org/2000/svg">
                    <path d="M20.25 4H3.75C2.7835 4 2 4.7835 2 5.75V20.25C2 21.2165 2.7835 22 3.75 22H20.25C21.2165 22 22 21.2165 22 20.25V5.75C22 4.7835 21.2165 4 20.25 4ZM8.75 18.5H6.5V9H8.75V18.5ZM7.625 7.75H7.5625C6.60725 7.75 6.3125 7.0405 6.3125 6.609V6.547C6.3125 6.1155 6.60725 5.406 7.5625 5.406H7.625C8.58075 5.406 8.8755 6.1155 8.8755 6.547V6.609C8.8755 7.0405 8.58075 7.75 7.625 7.75ZM18.5 18.5H16.25V14.5C16.25 13.214 15.6905 12.375 14.579 12.375C13.526 12.375 13.106 13.194 12.9445 13.875H12.875V12.125H10.625C10.694 12.7855 10.75 14.5 10.75 14.5V18.5H8.5V9H10.5V10.75C10.973 9.931 11.869 8.75 13.9275 8.75C16.411 8.75 18.5 10.6455 18.5 14.134V18.5Z"/>
                  </svg>
                </a>
              </div>
            </div>
          </footer>

    <script>

        const navToggle = document.getElementById('nav-toggle');
        const navMenu = document.querySelector('.nav-menu');

        navToggle.addEventListener('click', function() {
        navMenu.classList.toggle('hidden');
        });
    </script>
        </body>
        </html>
