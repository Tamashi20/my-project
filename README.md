# my-project
def hello_world():
  print("Hello, world! This is my first project in Git hub.")

if __name__ == "__main__":
  hello_world()
# Create a new branch
git checkout -b new-branch

# Modify the code file in the new branch
vi hello_world.py

# Add the changes to Git
git add hello_world.py

# Commit the changes
git commit -m "Added a message to the hello_world() function"

# Push the changes to GitHub
git push origin new-branch

# Merge the changes back to the master branch
git checkout master
git merge new-branch

# Push the changes to GitHub
git push origin master
