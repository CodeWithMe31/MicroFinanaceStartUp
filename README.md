# MicroFinanaceStartUp

# GitHub Final Project – Simple Interest Calculator

This repository is a sample open source project created as part of a migration exercise from SVN to Git.

It demonstrates hosting a small script on GitHub along with the supporting documentation needed for community collaboration. 

The project includes a simple **Bash script** to calculate **Simple Interest** given the principal amount, rate of interest, and time period.  
It also follows open source best practices by including:
- A license (Apache 2.0)
- A Code of Conduct
- Contribution Guidelines
- A descriptive README

## Simple Interest Formula
The formula used in this project is:
Simple interest = (Principal x Rate x Time)/100

Where:
- **Principal (p):** The amount of money borrowed or invested.
- **Rate (r):** Annual interest rate (in percentage).
- **Time (t):** Time period in years.

# How to run (Commands)
## clone the repository

**`git clone \repository HTTPS link\`** (replace "\repository HTTPS link\" with repository HTTPS link)

**`cd \repository name\`** (replace "\repository name\" with name of the repository that you want to clone)

## run the bash script

This command will make the script executable:

**`chmod +x simple-interest.sh`**

If you want to run the bash script directly like this:

**`./simple-interest.sh`**

then the file must have execute permission. Without **`chmod +x`**, you will get a "permission denied" error.

If you run the script explicitly with bash, like:

**`bash simple-interest.sh`**

then **`chmod +x`** is not needed, becuase you're directly telling the shell to run it with a bash interpreter.

After running the bash script, it asks the user to input *Principal*, *Rate of interest*, and *Time period* in years, then calculates and displays the simple interest.

