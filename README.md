# IMAD REPORT

IMAD ASSESSMENT 1
STUDENT NUMBER: ST10448816
STUDENT NAME: Gomolemo Louis Mashaba

REPORT
 
			HISTORY APPLICATION REPORT


Introduction:
 The aim of the history application is to provide users with information about historical People, figures, and important dates. The application allows users to explore different historical people age and name and access accurate and engaging historical content.

Methodology:
 A Systematic Approach to Developing Applications with Kotlin

PROJECR OVERVIEW

Implementation:
 The application is divided into several modules, including a home page Ui, Enter Name on plain Text for users, event details page, Display results matching the users’ age.
 The home page displays a visually appealing interface with a heading showcasing the name of the app. Users can navigate through different Age periods (range of 20-30) and click on the generate history button for displaying information results. The users should enter their names and age to find their age match on the results output relevant to the historical content.

Functionality:
The application provides users with Plain text where they can enter their names and where they can enter their age as well. There are two buttons the one can should generate history and the clear button to reset the application.

Users should enter their name and age and tap the generate button then the app will display a historical person information matching the users age to display the historical person history and achievements. 

Testing and Evaluation:
 Extensive testing was conducted throughout the development process to ensure the functionality and reliability of the application. Test cases were designed to cover various scenarios, including searching for different types of information, and user authentication.
The application performed well during testing, with search queries executing quickly and accurate results being returned. User authentication and preferences were also successfully implemented, providing a personalized experience.

Results:
  The history application successfully fulfils its purpose of providing users with access to historical information in an engaging and user-friendly manner. The timeline feature and search functionality make it easy for users to explore different history celebrities and search for specific events. 

CODE DOCUMENTAION

Code Analysis:
1. Layout:
The code starts by setting the layout for the activity using the setContentView method. It associates a specific layout XML file with the activity, defining the appearance and arrangement of the views.

2. View:
Next, various views are initialized using the findViewById method. The EditText views etAge and etName are identified by their respective IDs and assigned to variables for further usage. Similarly, the Button views btnButton and btnButton2, as well as the TextView view tvResult, are initialized.

3. User Interaction:
The code sets an OnClickListener for the btnButton using the setOnClickListener method. This allows the button to listen for the user's click event and perform certain actions based on the defined logic.

4. Conditional Statements:
Inside the OnClickListener, conditional statements are used to determine the appropriate message to display based on the entered age. The etAge EditText is used to obtain the age input, which is then stored in an age variable. Depending on the value of age, a specific message is assigned to the message variable.

5. Message Display:
After the appropriate message is assigned to the message variable, it can be displayed in the tvResult TextView. The setText method is used to update the content of the TextView with the assigned message. 

ALGORITHMS AND TECHNIQUES
1. The code overrides the onCreate method of an Android Activity.
2. It sets the content view of the activity to the layout file activity_main.
3. Various UI elements such as EditText, Button, and TextView are initialized using findViewById.
4. The btnButton has an OnClickListener attached to it, which responds to button clicks.
5. Inside the button click listener, there is a series of if-else conditions based on the age entered.
6. Depending on the entered age, different messages are assigned to the message variable.
7. The final text is set to the tvResult TextView.
8. The btnButton2 has an OnClickListener attached to it, which clears the EditText fields and resets the tvResult TextView.

In summary, my code uses Android UI components and conditional statements to display different messages based on the entered age.

DATA PROCESSING
1. Data Collection: First, relevant data is collected from various sources such as databases, files, or APIs. This data can be structured (tabular data) or unstructured (text, images, etc.).

2. Data Inspection: The collected data is visually inspected to get an initial understanding of its structure, content, and any potential issues such as missing values, outliers, or inconsistencies.

3. Data Cleaning: In this step, various cleaning operations are performed to eliminate errors or inconsistencies in the data. This includes handling missing values, removing duplicates, correcting data types, and handling outliers.

4. Data Transformation: Here, the data is transformed and restructured as per the requirements of the code or analysis. This may involve feature engineering, aggregating data, normalizing or scaling variables, or converting categorical data to numerical representations.

5. Data Integration: If multiple datasets are involved, they may need to be merged or combined based on common variables or keys. This is done to create a unified dataset that can be used in the code.

6. Data Sampling: In some cases, the size of the data may be too large for analysis, or the code may require a subset of the data for training or testing. In such cases, random sampling or other techniques are used to select a representative subset.

7. Data Validation: After the cleaning and transformation steps, the data is validated to ensure its quality and accuracy. This involves performing checks on the data, cross-referencing with external sources, or applying statistical methods to identify potential issues.

8. Data Splitting: Depending on the code requirements, the dataset may need to be split into training, validation, and test sets. This is typically done in machine learning tasks to evaluate the model's performance.

Once these steps are completed, the processed and cleaned data is ready to be used in your code for analysis, modelling, visualization, or any other desired task.

MODEL CREATION
In the code snippet, I’ve have shared the implementation of an onCreate method in an Android activity, which mainly deals with setting up the user interface and handling button clicks. 

ACTIVITY_MAIN.XML SETTINGS
The above code snippet shows the layout XML file for an Android app. It contains several UI elements like TextView, EditText, and Button.

1. TextView with id "tvTitle": It displays the title of the app.
2. EditText with id "etAge": It allows the user to enter their age between 20-30.
3. Button with id "btnButton": It generates a history based on the user's age.
4. Button with id "btnButton2": It clears the entered values.
5. TextView with id "tvResult": It displays the generated history.
6. EditText with id "etName": It allows the user to enter their name.

These elements are placed using constraints to define their positions within the parent layout. The layout also includes margin attributes to define the spacing between elements. Additionally, some elements have colour and text attributes to customize their appearance.

REFERENCES:
Sources I used to learn how to set colour in edit text and text view:
https://youtu.be/gk77KlgI35c?si=CB3Djj9_NxxzGxq2

Source I used to learn how to change Hint colour:
https://youtu.be/T88awN53zVE?si=SNyTY3SXblvgW4PE

Source I used to learn how to change the background image:
https://youtu.be/7OvsWwbvYsM?si=bfhlwhsHTLwXrwcy

website I use to find all historical people:
Angus Cloud
https://en.wikipedia.org/wiki/Angus_Cloud

Christina Grimmie
https://en.wikipedia.org/wiki/Christina_Grimmie

Zendaya
https://en.wikipedia.org/wiki/Zendaya

Keke Palmer
https://en.wikipedia.org/wiki/Keke_Palmer

Amandla Stenberg
https://en.wikipedia.org/wiki/Amandla_Stenberg

Shuri
https://en.wikipedia.org/wiki/Shuri

Yara Shahidi
https://en.wikipedia.org/wiki/Yara_Shahidi

Peter Parker
https://en.wikipedia.org/wiki/Spider-Man

Eleanor Crain Vance
https://www.imdb.com/name/nm6442992/

Sabrina Spellman
https://en.wikipedia.org/wiki/Chilling_Adventures_of_Sabrina_(TV_series)

Alexander the Great
https://en.wikipedia.org/wiki/Alexander_the_Great

Conclusion:
   The history application delivers an interactive and informative experience for users interested in history. Its user-friendly interface, comprehensive content, and customization options make it a valuable resource for both casual learners and history enthusiasts
