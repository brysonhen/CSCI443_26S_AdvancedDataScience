### Professor's repo & your repo → your laptop → your private GitHub → Databricks
	cd CSCI443_26S_AdvancedDataScience
	git pull origin main
	git pull upstream main
	git push
**then pull in databricks**

---
###Step-by-step
**From /Users/bryson *in terminal***: 

	cd CSCI443_26S_AdvancedDataScience

**Pull the changes from databricks to your local machine**:

	git pull origin main

> Pulls the changes made in databricks into your local machine.

**To get new class materials (lectures, hw, etc.):**

	git pull upstream main    

> Pulls from the professor's repo into your local machine. 


---


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



