## Professor's repo → your laptop → your private GitHub → Databricks


**To get new class materials (lectures, hw, etc.),from /Users/bryson *in terminal***: 

	cd CSCI443_26S_AdvancedDataScience

> repo folder on local machine
		
	git pull upstream main    

> This pulls from the professor's repo into your local machine. 


---


**Pull the changes from databricks to your local machine**:

	git pull origin main

**Then push it into your private repo, *in terminal***:
    
	git push

> This pushes the new class materials to your private repo.


---


In **Databricks**, open your **Git folder** → click the **main** branch button → click **Pull** to get the latest from your private repo.


> This will update your databricks folder with the new materials from your private repo.


---


When you finish your homework, hit **main** at the top -> **add a commit message** describing what you did (e.g. "completed hw1") -> **Click Commit & Push**


> This will update the file you're done editing in personal repo.


---


To **submit** the homework, **download the raw .ipynb file** you need to submit from the updated personal repo and **upload it to blackboard**.



