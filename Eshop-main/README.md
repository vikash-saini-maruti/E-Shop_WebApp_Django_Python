# E-Shop
This project involves the creation of an E-Shop Website, a virtual platform where users can browse and purchase a variety of products. The website presents users with a catalog of available items for sale and includes a shopping cart feature for easy online shopping. Once users have selected their desired products, they can proceed to the order confirmation process. The system is developed using Django, a Python web framework. Created by Vikash Saini



Sure, here are the steps rewritten for clarity:

1. Clone the repository into a folder on your computer.
2. Download and install Python from the official website.
3. Open a terminal or command prompt window and navigate to the folder containing the cloned repository.
4. Create a virtual environment by running the following command in the terminal window:
   ```
   python -m venv myenv
   ```
   Replace `myenv` with the name you want to give to your virtual environment.
5. Activate the virtual environment by running the appropriate command based on your operating system:
   - On Windows:
     ```
     myenv\Scripts\activate
     ```
   - On macOS and Linux:
     ```
     source myenv/bin/activate
     ```
6. Once the virtual environment is activated, execute the following command in the terminal window to install all dependencies automatically, If any library installation fails, the script will notify you upon completion.:
   ```
   python repoinstall.py
   ```
   >>OR

    In such cases, you can manually install the required libraries by running:

   pip install -r requirements.txt

   >>Note >>
If any library still gives an error, install it manually by running:
   ```
    pip install examplelibrary
   
   ```
  Replace `examplelibrary` with the name of the library causing the error.
   ```
   ```

These steps should help you set up and install the required dependencies for the repository.


7. Type ``` python manage.py runserver ``` to start a localhost server for the app.
   
9. Admin URL, ID, and password is ( where can be access from admin side like add product punch mark delivered etc ). 
>>
```
default_url/admin/ ( example - http://127.0.0.1:8000/admin/)
ID- vikash
Pass- vikash
```
