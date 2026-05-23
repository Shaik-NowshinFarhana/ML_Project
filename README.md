#Machine Learning Project

1.connect with github first and create a repository there.

Run these commands one by one :-
echo "# ML_Project" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Shaik-NowshinFarhana/ML_Project.git    
git push -u origin main


2. Add gitignore files at the repository and pull it at your local machine to make sure all the things are synced perfectly.
use command :-git pull 

3.Create setup.py and requirements.txt
setup.py:- it is used to build the entire ml project as a package.
    code:-    
        from setuptools import find_packages,setup
        setup(
            name='ML_Project',version='0.0.1',author='NowshinFarhana',
            author_email='nowshinfarhanask@gmail.com',packages=find_packages(),
            install_requires=['pandas','numpy','seaborn','matplotlib','scipy']
        )