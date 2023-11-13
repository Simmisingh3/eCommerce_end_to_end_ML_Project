## This is my eCommerce End to End Machine Learning Project.

## Create a README.md file to add steps

### First initialise the git on terminal.

```
git init
```

### To push your repository to github
```
git add .
```
### Create .gitignore file and LICENCE file on github 

### To pull your files from github 

```
git pull
```

## To push your file

```
git push
```
## Commit Comment
```
git commit -m "This is my First commit"
```

# To run init_set.sh file on git bash
```
bash your_file_name.sh
```
### 
1. Write you codes on template file to create all the related file and folders
2. On git bash type 
``` python template.py 
```
3. Write your required libraries and frameworks on Requirements.txt
4. On setup.py write your code to start the setting up of your local library.
5. Write your code on init_setp.sh
5. Activate the environment, On git bash type 
``` 
bash init_setup.sh
```
6. Sometimes you need to activate environment mannually on git bash
```
source activate ./env
```
7. To activate local package, On git bash type

```
python setup.py install
```

# To install the local package that is CustomerReview, there are 2 ways  `main way`
```
python setup.py install
```

## Another way to insatll is to mention -e . in your requirements file and you can run 
```
pip install -r requirements.txt 
```
### ```Data ```
This dataset is having data of customers who buys clothes online. The store offers in-store style and clothing advice sessions. Customers come in to the store, have sessions/meetings with a personal stylist, then they can go home and order either on a mobile app or website for the clothes they want.

The company is trying to decide whether to focus their efforts on their mobile app experience or their website.

Steps:
1. Data Ingestion
2. Data Transformation
3. Model Training
4. Training Pipeline
5. Prediction pipeline
