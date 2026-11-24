# Google Cloud Professional Agentic Architect Certification

**Hands-On Lab Notebooks**

These Jupyter notebooks accompany the LearnGrid study guide for the Google Cloud Professional Agentic Architect certification. Each notebook is one hands-on lab from the book. It explains the concepts, walks you through each step, and contains all the Python code you need.

**Folder Structure**


Appendix-C-Setup	Lab 00: Set Up the Lab Environment	

Chapter-03	Lab 03-01: Ground a Policy Assistant in Enterprise Documents	
Chapter-03	Lab 03-02: Compare Prompting Techniques	
Chapter-03	Lab 03-03: Build a State-Based Returns Flow in Code


Chapter-04	Lab 04-01: Build and Run a Minimal Coding Agent	
Chapter-04	Lab 04-02: Customize the Agent With Rules, Skills, and Hooks	
Chapter-04	Lab 04-03: Find and Patch a Vulnerability With a Subagent	


Chapter-05	Lab 05-01: Compare Models, Thinking Levels, and Routing	
Chapter-05	Lab 05-02: Build an ADK Agent With Tools, Callbacks, and a Schema	
Chapter-05	Lab 05-03: Scope State and Add Long-Term Memory	


Chapter-06	Lab 06-01: Compare Vector, Keyword, and Hybrid Retrieval	
Chapter-06	Lab 06-02: Query a Database Safely With MCP Toolbox	
Chapter-06	Lab 06-03: Build a Custom MCP Server for a SaaS Tool	


Chapter-07	Lab 07-01: Build Sequential, Parallel, and Loop Workflows	
Chapter-07	Lab 07-02: Compare Delegation With Agents as Tools	
Chapter-07	Lab 07-03: Connect Agents Across Teams With A2A	


Chapter-08	Lab 08-01: Evaluate an Agent Against a Golden Dataset	
Chapter-08	Lab 08-02: Score Responses With Custom Autoraters	


Chapter-09	Lab 09-01: Deploy an Agent to Cloud Run and Release a Canary	3
Chapter-09	Lab 09-02: Trace, Log, and Alert on Tool Calls	
Chapter-09	Lab 09-03: Detect and Break a Reasoning Loop	


Chapter-10	Lab 10-01: Screen Prompts, Tool Content, and Replies With Model Armor	
Chapter-10	Lab 10-02: Require Human Approval for High-Risk Actions	
Chapter-10	Lab 10-03: Apply Least Privilege, Propagate Identity, and Audit	3


Run the Chapter 04 labs in order: 
Lab 04-02 continues in the workspace that Lab 04-01 creates. 

In Chapter 09, the cleanup cell of Lab 09-01 deletes the Cloud Run service; if you do Lab 09-02 next, you can clean up both labs at the end.



**Before You Start**

1.	Create a Google Cloud project and link a billing account, as described in Appendix C of the book. This is the only step that may require the Google Cloud console.
2.	Open Lab 00: Set Up the Lab Environment and run it once. It installs the client libraries, signs you in, enables the APIs that every lab uses, and checks that Gemini responds.


**Where to Run the Notebooks**


•	Google Colab (recommended): Go to colab.research.google.com, choose File > Upload notebook, and select the notebook. When you run the authentication cell, sign in with the Google account that owns your lab project.


•	Jupyter, JupyterLab, or VS Code on your own computer: Install Python 3.10 or later and the Google Cloud CLI, run gcloud auth application-default login once, and open the notebook.


•	Colab Enterprise or Vertex AI Workbench: Upload the notebook to your environment in the lab project.


**Tips**


•	Run the cells in order, from top to bottom, with Shift+Enter.


•	Enter your project ID in the configuration cell of each notebook. If you set the GOOGLE_CLOUD_PROJECT and GEMINI_MODEL environment variables (Appendix C), the notebooks use them automatically.


•	Gemini model IDs change over time. If a cell reports that the model is not found, set MODEL to a current Gemini Flash model ID.
•	Run the Clean Up cell at the end of each lab so that you are not charged for resources that you no longer need.

