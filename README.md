Prerequisites:
Python 3.12.6 (https://www.python.org/downloads/)
VS Code (https://code.visualstudio.com/download/)
Pip (https://packaging.python.org/en/latest/tutorials/installing-packages/)
The ZIP file containing all of the code and files for the application.
Required Python libraries:
Streamlit
Pandas
NumPy
Matplotlib
Scikit-learn
Installation and Setup:
1. After ensuring the required applications are installed, download the movie_recommender_system repository to your local machine.
2. Extract the downloaded ZIP file to your preferred location.
3. Open the extracted folder in VS Code.
4. In the terminal, copy, paste, and run this command. This will install all the required libraries.
	pip install streamlit numpy matplotlib scikit-learn pandas
5. Open the Main.ipynb file and click “Run All” at the top of the screen. This will create two required files for the application
6. In the terminal, copy, paste, and run this command. This will launch the application.
	py -m streamlit run app.py
7. After running the command, you can open http://localhost:8501 on a browser of your choice. (e.g. Chrome).
8. After opening the application in your browser, you can select any movie of your choice to get the recommendations for your selected/typed movie. For example, if you select the movie “The Godfather”. You will be recommended movies such as “The Godfather: Part II, Joker, Bomb City” etc.
9. To stop the dashboard after use, head back to the terminal and press ctrl+c. 
10. To produce the visualizations, open the visualizations.ipynb file and again select “Run All”.
