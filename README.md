# n8n-WorkFlow
Combine n8n with AI APIs to form a personalized workflow.

## API Configuration
### Gemini API
1. Open the AI studio (https://aistudio.google.com/app/apikey)
2. Click "Create API Key"
3. Click "Create API Key in new project"
4. Get your API Key

### Google Drive API
#### Create New Project
1. Open the Google Cloud (https://cloud.google.com/)
2. Click "Console"
3. Click on the icon in the upper left corner<br>![image](https://github.com/user-attachments/assets/0920c20f-fe2c-4d97-9937-e748cbf7eff8)
4. Click "New Project"
5. Name the new project

#### Create the Google Drive API
1. Click on the menu in the upper left corner
2. Choose "APIs & Services"
3. Click "Enable APIs and Services"<br>![image](https://github.com/user-attachments/assets/0c33f41d-641b-48b9-b45c-ffcac75bab30)
4. Find Google Dirve API and Enable it

#### OAuth authorized n8n
1. Click "OAuth consent screen"
2. Get Started
3. Fill the information<br>![image](https://github.com/user-attachments/assets/89634734-dad1-4cba-afcd-6597e8099d92)
   - Fill your app name and gmail
   - Choose External (For individual user)
   - Fill the gmail you want to be contacted
   - Agree the policy

 #### Linked to n8n
 1. Click "Clients"
 2. Click "Create Clients"<br>![image](https://github.com/user-attachments/assets/feecfcf7-e1a6-4ad1-827c-300ff3523c2a)
 3. Choose "Web application"
 4. Fill the name (like n8n Drive Web Client)
 5. 


1. Click "Credentials"
2. Click "Create Credentials"
3. Choose "OAuth Client ID"
