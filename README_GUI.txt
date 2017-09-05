STEPS TO RUN GUI ON WEB BROWSER.

STEP 1: 
Unzip the file kpt_gui_gp4.zip

FOLLOWING FILES WILL GET UNZIPPED
1. book_avg_sent.txt (training data for books)
2. building_test.py
3. demo.py
4. Folder named “static”: containing design.css file
5. Folder named “template”: home.html
6. train_data_gui.txt (training data for sentiment analysis of user text.)

STEP 2: 
Open file building_test.py and edit the following method with variable path.

	def read_file_and_extract_reviews(book):
    		path = “local_path/book_avg_sent.txt"

STEP 3: 
Open file demo.py change the variable named as “local_path”
	local_path = “local_path_of_system_containing_data_file/train_data_gui.txt"

STEP 4: 
Go to the directory (from command line or terminal) where the zip kpt_gui_gp4.zip was unzipped and paste following command.
	“python demo.py” [without quotes.]

Following messages should appear on the screen.


