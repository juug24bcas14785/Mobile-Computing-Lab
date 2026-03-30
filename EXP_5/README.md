AIM

To create an Android application that uses a ToggleButton to change the state between ON and OFF, and then show the state using a Toast message.



ALGORITHM

Step 1: Open Android Studio.

Step 2: Create a new project for the Android application by selecting the Empty Activity option.

Step 3: Open the activity_main.xml file.

Step 4: Design the UI and add a ToggleButton with the id as "toggleButton."

Step 5: Open the MainActivity.java file.

Step 6: Import the required packages as follows:
import android.os.Bundle;
import android.widget.ToggleButton;
import android.widget.Toast;

Step 7: Inside the onCreate() method, add the following line of code:
setContentView(R.layout.activity_main);

Step 8: Initialize the ToggleButton as follows:
ToggleButton toggleButton = findViewById(R.id.toggleButton);

Step 9: Add a listener to the button to check the state change by using the following method:
toggleButton.setOnCheckedChangeListener();

Step 10: Check the state of the button as follows:
If the state is ON, then display the message as "Status: ON";
If the state is OFF, then display the message as "Status: OFF"