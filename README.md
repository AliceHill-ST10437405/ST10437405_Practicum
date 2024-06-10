# ST10437405_Practicum
Alice Hill
ST10437405
I  created a Weather app that shows you the from Monday - Friday 
WeatherApp
Overview
WeatherApp is an Android application designed to record, display, and manage weekly weather data. Users can input daily weather conditions, view the calculated average temperature for the week, and navigate to a detailed screen displaying the inputted data.

### Splash Screen 
The first screen you see when opennig the app.
Tells you what the app is about.
Button to proceed to the Main Screen 
### Main Screen 
### Features
The user will input their daily minimum and maximum temperatures along with weather conditions for each day of the week.
Clear all inputted data if a mistake was made.
Calculates and displays the average temperature for the week.
View detailed weather information on a separate screen.
### Installation
 Clone the repository:
git clone https: https://github.com/AliceHill-ST10437405/ST10437405_Practicum.git 
Open the project in Android Studio.
Build and run the project on an emulator or physical device.
### Usage
Launch the application.
Input the minimum and maximum temperatures along with the weather conditions for each day of the week.
Click the Clear button to reset all inputs.
Click the Next button to navigate to the detailed screen.
Click the Exit button to close the application.
### Final Screen 
Output all the data the was inputted in the MainScreen
Exit button to exit.
![Screenshot 2024-06-10 143320](https://github.com/AliceHill-ST10437405/ST10437405_Practicum/assets/164025376/fdc7d5f7-442e-48ab-a901-353695f14028)
![Screenshot 2024-06-10 142631](https://github.com/AliceHill-ST10437405/ST10437405_Practicum/assets/164025376/15efb453-f491-48c5-b8a4-fca8e6d60db9)
![Screenshot 2024-06-10 153846](https://github.com/AliceHill-ST10437405/ST10437405_Practicum/assets/164025376/b4a869c7-6c5b-490c-ab99-1103d4056015)
![Screenshot 2024-06-10 153846](https://github.com/AliceHill-ST10437405/ST10437405_Practicum/assets/164025376/6226497a-1658-4d1c-8c14-bac6c4fe27b7)

![Screenshot 2024-06-10 143438](https://github.com/AliceHill-ST10437405/ST10437405_Practicum/assets/164025376/da9f28fc-eefc-4890-86c8-bac49e754799)
![Screenshot 2024-06-10 143444](https://github.com/AliceHill-ST10437405/ST10437405_Practicum/assets/164025376/380a60f0-b060-4007-acb5-dda73786a593)
![Screenshot 2024-06-10 143450](https://github.com/AliceHill-ST10437405/ST10437405_Practicum/assets/164025376/88af9476-d973-4d5c-815f-079699e478dc)
![Screenshot 2024-06-10 143455](https://github.com/AliceHill-ST10437405/ST10437405_Practicum/assets/164025376/843ea8d9-8796-49e6-8615-b7c8f0e58701)
![Screenshot 2024-06-10 144620](https://github.com/AliceHill-ST10437405/ST10437405_Practicum/assets/164025376/feddf943-b8b9-4411-b576-2a9236babd19)
![Screenshot 2024-06-10 144626](https://github.com/AliceHill-ST10437405/ST10437405_Practicum/assets/164025376/c99072da-99d2-4a7a-be77-5e0d85f7b913)
![Screenshot 2024-06-10 144626](https://github.com/AliceHill-ST10437405/ST10437405_Practicum/assets/164025376/558af320-72aa-4602-9d23-2b2d6d595e37)
![Screenshot 2024-06-10 144629](https://github.com/AliceHill-ST10437405/ST10437405_Practicum/assets/164025376/0b025dc6-638e-41ca-a4f1-3277e21bb534)
![Screenshot 2024-06-10 144931](https://github.com/AliceHill-ST10437405/ST10437405_Practicum/assets/164025376/a2aadaec-12ea-47fa-a89d-04d3e7f9215b)
![Screenshot 2024-06-10 144620](https://github.com/AliceHill-ST10437405/ST10437405_Practicum/assets/164025376/f9946bc0-6d6f-46d9-9a14-1a7418f29112)
![Screenshot 2024-06-10 153846](https://github.com/AliceHill-ST10437405/ST10437405_Practicum/assets/164025376/8d62df15-dc9c-4ea9-94cc-d233d05d4796)
![Screenshot 2024-06-10 153846](https://github.com/AliceHill-ST10437405/ST10437405_Practicum/assets/164025376/13af3516-80db-44c3-903e-a4dbd6409544)

Cloud Image URL: https://www.google.com/url?sa=i&url=https%3A%2F%2Fpngtree.com%2Ffree-backgrounds-photos%2Fweather&psig=AOvVaw3vz157stWT5NTc7ffjAm9E&ust=1718111004616000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCMiRjdWM0YYDFQAAAAAdAAAAABAJ

### FlowChart for the Weather App.
             +-------------------------------+
             |          onCreate             |
             +-------------------------------+
                           |
                           v
        +-----------------------------------------+
        |  Initialize UI components and table rows|
        +-----------------------------------------+
                           |
                           v
             +-------------------------------+
             |  Set up button click listeners |
             +-------------------------------+
                           |
                           v
+--------------+       +---------------+      +-------------+      +---------------------+
| Clear Button | ----> | Next          | ---> | Exit Button | ---> | Input Temperature   |
|  Clicked     |       |  Button       |      |  Clicked    |      | Data (Manually)     |
|              |       |  Clicked      |      |             |      |                     |
+--------------+       +---------------+      +-------------+      +---------------------+
       |                      |                       |                      |
       v                      v                       v                      |
+--------------+    +--------------------+      +-------------+    +--------------------+
| Clear Data   |    | Navigate to Final  |      | Finish Activity|  | Update Temperature |
| Method       |    | Screen             |      |                |  | Method             |
+--------------+    +--------------------+      +-------------+    +--------------------+
       |                                                               |
       v                                                               v
+--------------+                                              +--------------------+
| Reset Table  |                                              | Calculate Average  |
| Rows and     |                                              | Temperature Method |
| Text Views   |                                              +--------------------+
+--------------+                                                         |
                                                                         v
                                                              +--------------------+
                                                              | Display Average    |
                                                              | Temperature        |
                                                              +--------------------+
### Contributing
Fork the repository.
Create your feature branch: git checkout -b my-new-feature.
Commit your changes: git commit -am 'Add some feature'.
Push to the branch: git push origin my-new-feature.
Submit a pull request.


#### Copy of the Code:
package com.example.weatherapp

import android.annotation.SuppressLint
import android.content.Intent
import android.os.Bundle
import android.widget.Button
import android.widget.EditText
import android.widget.TableLayout
import android.widget.TableRow
import android.widget.TextView
import androidx.appcompat.app.AppCompatActivity

class SecondScreen : AppCompatActivity() {

    private lateinit var button6Next: Button
    private val daysOfWeek = arrayOf("Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday", "Sunday")
    private val minTemperatures = DoubleArray(7)
    private val maxTemperatures = DoubleArray(7)
    private val weatherConditions = arrayOfNulls<String>(7)
    private lateinit var tableLayout: TableLayout
    private lateinit var averageTemperatureTextView: TextView
    private lateinit var clearButton: Button
    private lateinit var viewDetailsButton: Button
    private lateinit var exitButton: Button

    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.screenscreen)

        tableLayout = findViewById(R.id.tableLayout)
        averageTemperatureTextView = findViewById(R.id.textView2Temp)
        clearButton = findViewById(R.id.button8Clear)
        button6Next = findViewById(R.id.button6Next)
        exitButton = findViewById(R.id.button7Exit)

        for (i in daysOfWeek.indices) {
            val tableRow = TableRow(this)
            val dayTextView = TextView(this)
            dayTextView.text = daysOfWeek[i]
            tableRow.addView(dayTextView)

            val minTemperatureEditText = EditText(this)
            minTemperatureEditText.hint = "Min Temp"
            tableRow.addView(minTemperatureEditText)

            val maxTemperatureEditText = EditText(this)
            maxTemperatureEditText.hint = "Max Temp"
            tableRow.addView(maxTemperatureEditText)

            val weatherConditionEditText = EditText(this)
            weatherConditionEditText.hint = "Weather Condition"
            tableRow.addView(weatherConditionEditText)

            tableLayout.addView(tableRow)
        }

        clearButton.setOnClickListener { clearData() }
        nextButton.setOnClickListener { next() }
        exitButton.setOnClickListener { finish() }
    }

    private fun clearData() {
        minTemperatures.fill(0.0)
        maxTemperatures.fill(0.0)
        weatherConditions.fill(null)
        tableLayout.removeAllViews()
        for (i in daysOfWeek.indices) {
            val tableRow = TableRow(this)
            val dayTextView = TextView(this)
            dayTextView.text = daysOfWeek[i]
            tableRow.addView(dayTextView)

            val minTemperatureEditText = EditText(this)
            minTemperatureEditText.hint = "Min Temp"
            tableRow.addView(minTemperatureEditText)

            val maxTemperatureEditText = EditText(this)
            maxTemperatureEditText.hint = "Max Temp"
            tableRow.addView(maxTemperatureEditText)

            val weatherConditionEditText = EditText(this)
            weatherConditionEditText.hint = "Weather Condition"
            tableRow.addView(weatherConditionEditText)

            tableLayout.addView(tableRow)
        }
        averageTemperatureTextView.text = "Average Temperature: 0.0°C"
    }

    private fun viewDetails() {
        val intent = Intent(this, FinalScreen::class.java)
        intent.putExtra("minTemperatures", minTemperatures)
        intent.putExtra("maxTemperatures", maxTemperatures)
        intent.putExtra("weatherConditions", weatherConditions)
        startActivity(intent)
    }

    @SuppressLint("SetTextI18n")
    private fun calculateAverageTemperature() {
        var sum = 0.0
        for (i in minTemperatures.indices) {
            sum += (minTemperatures[i] + maxTemperatures[i]) / 2
        }
        val averageTemperature = sum / minTemperatures.size
        averageTemperatureTextView.text = "Average Temperature: ${String.format("%.1f", averageTemperature)}°C"
    }

    private fun updateTemperatures() {
        for (i in daysOfWeek.indices) {
            val tableRow = tableLayout.getChildAt(i) as TableRow
            val minTemperatureEditText = tableRow.getChildAt(1) as EditText
            val maxTemperatureEditText = tableRow.getChildAt(2) as EditText
            val weatherConditionEditText = tableRow.getChildAt(3) as EditText

            minTemperatures[i] = minTemperatureEditText.text.toString().toDoubleOrNull() ?: 0.0
            maxTemperatures[i] = maxTemperatureEditText.text.toString().toDoubleOrNull() ?: 0.0
            weatherConditions[i] = weatherConditionEditText.text.toString()
        }
        calculateAverageTemperature()
    }
}
