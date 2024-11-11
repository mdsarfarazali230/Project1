#include <stdio.h>
int main() {
   // printf() displays the string inside quotation
   printf("Hello, World!");
   return 0;
}


# Project1

    <div className={min-h-screen ${darkMode ? 'bg-gray-900 text-white' : 'bg-white text-gray-900'}}>
      <div className="container mx-auto px-4 py-8">
        <div className="flex justify-between items-center mb-8">
          <h1 className="text-2xl font-bold">Easy dark mode</h1>
          <button
            onClick={toggleDarkMode}
            className={p-2 rounded-full ${darkMode ? 'bg-gray-800' : 'bg-gray-200'}}
          >
            {darkMode ? <Sun className="h-6 w-6" /> : <Moon className="h-6 w-6" />}
          </button>
        </div>
        <div className="max-w-md mx-auto">
          <img
            src="/placeholder.svg?height=400&width=300"
            alt="Old-fashioned lamp on cobblestones"
            className="w-full h-auto mb-4 rounded-lg shadow-lg"
          />
          <p className="mt-4">
            The lamp, a beacon of illumination throughout history, has evolved from simple oil-burning vessels to sophisticated electric devices. Its primary function remains unchanged: to provide light in darkness, offering comfort and enabling activities long after the sun has set. From the warm glow of candlelight to the crisp brilliance of LED bulbs, lamps have not only served practical purposes but have also become integral elements of interior design, setting moods and defining spaces with their varied styles and intensities of light.
          </p>
        </div>
      </div>
    </div>
  )
}

<html lang="en"><head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ecommerce</title>
    <link rel="stylesheet" href="style.css">
</head>
<body class="">
    
    <div class="container">
        <header>
            <div class="title">SHOPPER ITEMS</div>
            <div class="icon-cart">
                <svg aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 18 20">
                    <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 15a2 2 0 1 0 0 4 2 2 0 0 0 0-4Zm0 0h8m-8 0-1-4m9 4a2 2 0 1 0 0 4 2 2 0 0 0 0-4Zm-9-4h10l2-7H3m2 7L3 4m0 0-.792-3H1"></path>
                </svg>
                <span>0</span>
            </div>
        </header>
        <div class="listProduct">

        <div data-id="1" class="item"><img src="image/airpohone.jpg" alt="">
                <h2> AIRPHONE </h2>
                <div class="price">₹1599</div>
                <button class="addCart">Add To Cart</button></div><div data-id="2" class="item"><img src="image/banarsi.jpg" alt="">
                <h2> BANARSI-SAREE </h2>
                <div class="price">₹499</div>
                <button class="addCart">Add To Cart</button></div><div data-id="3" class="item"><img src="image/daber.jpg" alt="">
                <h2> DABER </h2>
                <div class="price">₹500</div>
                <button class="addCart">Add To Cart</button></div><div data-id="4" class="item"><img src="image/1qoo z9 s 5g.jpg" alt="">
                <h2> 1QOO Z9 S 5G</h2>
                <div class="price">₹19050</div>
                <button class="addCart">Add To Cart</button></div><div data-id="5" class="item"><img src="image/misture.jpg" alt="">
                <h2> MIXTURE </h2>
                <div class="price">₹1150</div>
                <button class="addCart">Add To Cart</button></div><div data-id="6" class="item"><img src="image/slaeeper.jpg" alt="">
                <h2> SLEEPER</h2>
                <div class="price">₹199</div>
                <button class="addCart">Add To Cart</button></div><div data-id="6" class="item"><img src="image/smart watch.jpg" alt="">
                <h2> SMART-WATCH</h2>
                <div class="price">₹1099</div>
                <button class="addCart">Add To Cart</button></div><div data-id="7" class="item"><img src="image/galxy.jpg" alt="">
                <h2> GALAXY-PHONE</h2>
                <div class="price">₹75999</div>
                <button class="addCart">Add To Cart</button></div><div data-id="14" class="item"><img src="image/7.png" alt="">
                <h2> KING RAHMAT CHAIR</h2>
                <div class="price">₹15000</div>
                <button class="addCart">Add To Cart</button></div><div data-id="8" class="item"><img src="image/3.png" alt="">
                <h2> FLOATING ARM CHAIR</h2>
                <div class="price">₹2090</div>
                <button class="addCart">Add To Cart</button></div><div data-id="9" class="item"><img src="image/2.png" alt="">
                <h2> PARSONS CHAIR</h2>
                <div class="price">₹1150</div>
                <button class="addCart">Add To Cart</button></div><div data-id="10" class="item"><img src="image/5.png" alt="">
                <h2> WINDSOR CHAIR</h2>
                <div class="price">₹900</div>
                <button class="addCart">Add To Cart</button></div></div>
    </div>
    <div class="cartTab">
        <h1>Shopping Cart</h1>
        <div class="listCart">
            
        </div>
        <div class="btn">
            <button class="close">CLOSE</button>
            <button class="checkOut">Check Out</button>
        </div>
    </div>

    <script src="app.js"></script>

</body></html>
