# Development directions

1. Clone this repo: `git clone https://github.com/Stormy0611/next-django-chatgpt`
2. Create a virtual environment: `python -m venv venv`
3. Activate it ☝️: `source venv/bin/activate` or `venv\Scripts\activate` if you're on a Windows
4. Install dependencies: `npm install && cd backend && pip install -r requirements.txt && cd .. && cd frontend && npm install && cd ..`
5. Setup the project `.env` file by taking as example the `.env.example` on the root folder (refer to [configuration](#Configuration) for more details)
6. Setup the frontend app's `frontend/.env` file by taking as example the `frontend/.env.example` file (refer to [configuration](#Configuration) for more details)
7. Start the application: `npm start` (make sure Postgres is up and running)


# django-next
Django-CRUD with Next JS Frontend

TODO:
- Pass roles and adjust UI screens accordingly
- Include refresh token or similar flow since token expires quite fast. 
- Some overall UI improvements on the table to treat the ingredients better. 

The following code was made in less than a day. It's a fast development that compresses a lot of features and tries to balance best practices, so there will be comments about potential improvements.

This is using https://github.com/juanbenitezdev/django-rest-framework-crud as base and following this tutorial for Next Js.

https://www.ansonlowzf.com/create-a-website-with-material-ui-v5-nextjs/#create-a-muinextlink-component

It has been customized to change the business topic and create adoptions to enable communication. 

Usage: 

docker-compose up

Internal README for each backend and frontend are available.
