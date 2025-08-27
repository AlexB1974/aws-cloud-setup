#  Technical Journal – AWS Project

This file records the challenges encountered during the project and how they were resolved.

##  Issue 1: GitHub Pages disabled
**Description:** GitHub Pages was blocked because the repository was a fork  
**Solution:** Left the fork network, made the repository public, and re-enabled Pages

---

##  Issue 2: Visibility locked
**Description:** Could not change repository visibility due to fork status  
**Solution:** Confirmed repo name, left fork, and changed visibility in settings

---

##  Issue 3: Language mismatch
**Description:** Original site was in Spanish, needed to be in English  
**Solution:** Translated `index.html` manually and updated greeting to “Hi, my name is Alex!”

---

##  Issue 4: AWS CLI not responding
**Description:** CLI commands failed due to missing credentials  
**Solution:** Re-ran `aws configure`, verified keys, and tested with `aws s3 ls`

---

##  Issue 5: Python script not connecting
**Description:** Boto3 couldn’t access EC2  
**Solution:** Checked IAM permissions, added `AmazonEC2FullAccess`, and retried script

---

##  Lessons Learned
- Always check repository visibility before enabling GitHub Pages
- IAM policies must be precise for each service
- Documenting problems helps avoid them in future setups
