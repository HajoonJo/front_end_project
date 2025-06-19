# Instructions

## npm install
* go to terminal (crtl + `) and type "install npm", this has to be done manually

## Front End
ensure that you're in the correct directory
1. cd react-with-flask
2. npm run dev  
3. open the browser link, ensure that the port is 5173

## Back End
In a separate terminal (crtl + shift + `)
1. mkdir api
2. cd api
3. python -m venv venv          | if "venv" folder is there, delete it
4. source venv/bin/activate
5. pip install flask python-dotenv
6. npm run api
7. open browser link, change the URL address to 
    http://127.0.0.1:5000/api/time
