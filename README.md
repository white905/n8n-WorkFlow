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
 5. Fill the n8n's URL (or paste https://oauth.n8n.cloud/oauth2/callback)<br>![image](https://github.com/user-attachments/assets/a662d045-2119-4882-a9e7-729a022c4e42)
 6. Click "Create"
 7. Keep your information in a safe place

#### Add Gmail Account
 1. Go to Audience
 2. Add the gmail you want to connect to n8n

#### Set the Scope
1. Go to Data Access
2. Click "Add or remove scopes"
3. Find Google Drive API and choose the scope (.../auth/drive)<br>![image](https://github.com/user-attachments/assets/8804d77b-a342-4db0-a436-c4cdb91105c5)
4. Update the scope

## n8n Auto-generated Tutorial Documentation
### API Configuration
#### Set Google Gemini Api Account
1. Choose "Create new credential"<br>![image](https://github.com/user-attachments/assets/307c4a02-4f23-446b-a668-70e9af1af331)
2. Paste your API Key created before
3. Save
4. Choose the model (Recommend the latest version of the flash model)

#### Set Google Drive Api
1. Click "Create new credential"
2. Pasted the Client ID and Client Password you get on step "Linked to n8n"

#### Set the Floder
1. Go to your Google Drive and Create a folder you want to save the tutorial
2. Copy the folder's URL
3. Paste the URL in the Parent Floder<br>![image](https://github.com/user-attachments/assets/ce93b28a-1dcd-42c0-9a75-59c1d1da72b0)

### How to use it?
1. Open the Chatbox
2. Enter the topic you want to generate
3. Receive the markdown document in your Google Drive
