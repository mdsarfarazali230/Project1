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
