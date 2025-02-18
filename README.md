<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="output.css">
    <style>
        .box{
            box-shadow:
            -4px 4px rgba(231, 45, 162, 0.4),
            -8px 8px rgba(240, 46, 170,0.3),
            -12px 12px rgba(240, 46, 170,0.2),
            4px 4px 4px yellow;
            font-size: 16pt;
        }
    </style>
</head>
<body class="bg-gradient-to-l from-orange-400 via-orange-200 to-red-600 min-h-screen">
    <div class="bg-gray-600 w-full h-24 top-0">
        <nav>
            <h1 class="text-center font-bold text-white">My Portfolio</h1><br>
            <ul class="flex justify-center font-semibold space-x-8 text-white">
                <li class="hover:text-gray-400  hover:underline">Home</li>
                <li class="hover:text-gray-400  hover:underline">About</li>
                <li class="hover:text-gray-400  hover:underline">Contact</li>
                <li class="hover:text-gray-400  hover:underline">Projects</li>
            </ul>
        </nav>
    </div>
    <div class="container mx-auto flex justify-center">
         <div class=" mt-10 p-6">
            <h2 class="text-2xl font-bold text-gray-900">Build your own WEB presence:</h2>
        
            <div class="bg-white p-6 mt-6 rounded-lg shadow-xl border-gray-800 w-80 grid grid-cols-2 box flex items-center">
                <div>
                    <h3 class="text-3xl font-bold text-gray-800">1</h3>
                </div>
                <div>
                    <p class="mt-2 text-gray-700 font-semibold">Karthik Choubey <br>
                    Ayappa-temple, 509228, Kothur, Telangana</p>
                    </div>
            </div>
            <div class="bg-white p-6 mt-6 rounded-lg shadow-xl border-gray-800 w-80 grid grid-cols-2 box flex items-center">
                <div>
                    <h3 class="text-3xl font-bold text-gray-800">2</h3>
                </div>
                <div>
                    <p class="mt-2 text-gray-700 font-semibold">Skills : <br>
                    HTML, CSS, JavaScript, C, C++</p>
                    </div>
            </div>
        </div>
    </div>
</body>
</html>
