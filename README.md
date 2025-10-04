# eduportal-flask
for education and entertainment purpose 
# EduPortal Flask Web App

This is a **demo educational portal** built with **Flask**, featuring:

- User registration and login
- Admin account for uploading/deleting videos, research papers, and images
- Colorful dashboard with sections: Videos, Research, Images, Sports
- Public users can view content uploaded by the admin
- Hosted live via cloudflared tunnel (Colab demo) or Render deployment

## Admin Account

- Username: `admin`  
- Password: `xxxxxx`

## Installation (Local)

```bash
git clone https://github.com/<your-username>/eduportal-flask.git
cd eduportal-flask
pip install -r requirements.txt
python app.py
