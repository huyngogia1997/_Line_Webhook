# _Line_Webhook

#### # Install Development Environment
1. Install [ngrok](https://dashboard.ngrok.com/get-started/setup) 

2. Run
    ```sh 
    ngrok http [PUBLIC_SERVER_PORT]
    ```

3. Go to Developer Page -> Chatbots -> Messenging API -> Webhook URL 

4. Set `Webhook URL = [https forwarding url]` (when run cmd at step 2) 
    > Note: start server before verify

5. Click **Verify** button

6. Login line messenger and scan chatbot QR Code (Developer Page -> Chatbot -> Messenging API -> QR Code)

7. Type "Hello world" and Enter

