0x00. AirBnB clone - The console
put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances
create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
echo "# AirBnB_clone" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
