git remote add origin https://github.com/nimrahbanu/my-portfolio.git
~/.ssh/id_rsa_nimrahbanu
ssh-keygen -t rsa -b 4096 -C "nimrah271999@gmail.com"
Enter file in which to save the key (/c/Users/YourName/.ssh/id_rsa): /c/Users/YourName/.ssh/id_rsa_nbaaa
Ceval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa_nbaaa
git remote set-url origin git@github-nimrahbanu:nimrahbanu/my-portfolio.git
