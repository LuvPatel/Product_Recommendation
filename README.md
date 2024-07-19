# Product_Recommendation

This Project demonstrates the product recommendation system using the SVD model, based on the user order purchases as well as similar user purchase preferences/history. 

Instructions to run the program are as follows: 

## Prerequisites:
- Python
- pip

If the above conditions satisfies, execute the below steps:

#### Clone the repository
```bash
git clone https://github.com/LuvPatel/Product_Recommendation.git
```

#### Change to the project directory
```bash
cd Product_Recommendation
```

#### Create a Virtual Environment
```bash
python -m venv venv
```

#### Activate the Virtual Environment
```bash
venv/Scripts/Activate
```

#### Install dependencies
```bash
pip install -r requirements.txt
```

#### Run the application
```bash
flask run
```

#### Deactivate once done with the program execution
```bash
deactivate
```

### Navigating the program

Once the application is up and running, navigate to 

```bash
http://localhost:5000
```


On the homepage, enter a "user ID" and hit "Get recommendation" button.

To find the similar user to the target user, hit the "Get similar user" button.

