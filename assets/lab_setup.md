### Lab: Start AutoGen Studio

Autogen will require an API Key. We will use OpenAI so execute this command on the command line:

`export OPENAI_API_KEY="your-key-here"`

To run AutoGen Studio, you need to specify the port it will operate on, using the following command:

`autogenstudio ui --port 8081 --host 0.0.0.0`

This command configures AutoGen Studio to run on port 8081 and be accessible from any machine.

Note: to run this in the background so it doesn’t end when the terminal ends, use this command:

`nohup autogenstudio ui — port 8081 — host 0.0.0.0 &`

#### Access AutoGen Studio

Open your web browser and go to `http://<your-lightsail-instance-public-ip>:8081/`. You should now see the AutoGen Studio interface.