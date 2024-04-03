# Servicenow
 - Servicenow script to clean up duplicate product models
 - Javascript & GlideRecord used
 - Issue: This script was created because there were duplicate product models with the same name, but they were associated to CI's and assets
 - Steps:
     - Identity the duplicates
     - Find out which duplicate are present on less CI's
     - Remove the duplicate from the CI records
     - Delete the duplicate
     - Populate the one remaining product model onto the target records
