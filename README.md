Please use the class diagrams below, paying close attention to the relationships between them and the attributes' accessibility.
• You will need to add some attributes or their types that were left out of the class diagrams in order to complete the implementations to meet the quiz's requirements. For example, you must choose what additional attributes to include in the classes in order to establish the relationships (aggregate or composition) shown in the class diagram.
• Aside from that, you'll have to figure out what parameters you'll need to implement the constructors, such as _init_.
•The attributes and methods of the classes in the class diagrams do not include data types, you are required to use type hints to specify the data type for all attributes, local variables, function parameters, and function return types.
If any classes require setter or getter properties, do so.
When implementing these classes in Python, make sure you follow the correct Python syntax or conventions.
The professor who is added to the Department should also be added to one of the Building objects of the Department.
• The method remove_professor(professor_name) should remove the professor from both the Department and Building object.
The method get fulltime_professors() should return a list of full-time professors.
The method get_buildings_by_stories(stories) should return a list of buildings which have the same number of stories as the parameter "stories".
• The method get_professors_by_building (building name) gives a list of professors who belong to the building whose building name is the same as the parameter "building name" in that method.
The method remove_parttime_professors() should remove all the part-time professors who are assigned to this Building object. However, this method should not affect the list of the professors in the Department object.
• The method get_professor_with_highest_salary() should find and return the Professor object who has the highest salary in this Building object.
• Do not use library functions which are related to algorithms such as max() or min() of the list, or other third-party modules like Numpy or Pandas. Also, Python's one-liners are not allowed to be used, such as list comprehensions, lambda functions, list slicing etc.
• Create a main method to test all your classes and their methods thoroughly.
![image](https://user-images.githubusercontent.com/123284377/218912938-1abf9447-dc6f-4fc6-8a64-556be58c529b.png) 
