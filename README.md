# TikTok Followers Counter
This Python script gets the number of followers for a TikTok account by scraping the web page of the account using BeautifulSoup and requests libraries. The number of followers is then displayed in a GUI created using the tkinter library.

## Dependencies
Python 3.x  
requests==2.26.0  
beautifulsoup4==4.10.0  
tk==0.1.0    
You can install the dependencies by running  
pip install -r requirements.txt.

## Usage
Clone the repository or download the code.  
Install the dependencies using the command `pip install -r requirements.txt`.  
Run the script using the command python `tiktok_followers.py`.  
*If you do not want to know the code and just want to run, double click on `tiktok_followers.exe`*
Enter the TikTok username in the input field and click the "Get Followers" button to display the number of followers.  
*Notes*
The script works only if the TikTok account is public.  
If the TikTok account does not exist or is private, the script will display an error message.  
The GUI window can be closed by clicking the close button or pressing the "Esc" key.  
## License
This project is licensed under the MIT License. Feel free to use and modify the code as per your requirements.
