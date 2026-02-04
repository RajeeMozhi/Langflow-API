## Hosting Langflow on the Web

When we host Langflow on the web, the URL can be shared with anyone. Anyone with access to the URL can use it.

### How to Get the Langflow URL

#### Step 1: Extract the API from Langflow
1. Go to **Langflow → Share → API Access**
2. Copy the URL from the localhost
3. Copy the **Request Body**
4. Copy the **Langflow API Key** from your Profile (top right corner)

#### Step 2: Create a Postman Collection
1. Open Postman and create a new **Collection**
2. Create a **POST** request
3. Paste the copied URL and Request Body from Step 1

#### Step 3: Add the API Key in Postman
1. Go to the **Headers** tab in Postman
2. Add a new key: `x-api-key`
3. Paste the Langflow API Key as the value

#### Step 4: Validate the response in Postman
1. Click **Send**
2. Validate the response
